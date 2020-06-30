---
title: Dynamic Plugins
---
<!-- Copyright 2000-2020 JetBrains s.r.o. and other contributors. Use of this source code is governed by the Apache 2.0 license that can be found in the LICENSE file. -->

Starting with 2020.1 release, the ability to install, update and uninstall plugins without restarting the IDE is available in the IntelliJ Platform. During plugin development, this also allows avoiding restarts of the [IDE Development Instance](/basics/ide_development_instance.md#enabling-auto-reload) after every code change. 

> **NOTE** If a plugin _requires_ restart (e.g., due to using native libraries) specify `require-restart="true"` for `<idea-plugin>` root tag in `plugin.xml`.

For a plugin to support this, all restrictions listed below must be met. To verify a plugin locally, run _Plugin DevKit | Plugin descriptor | Plugin.xml dynamic plugin verification_ 
inspection on all plugin descriptor files (required `plugin.xml` as well as any additional files).

For plugins hosted on the [JetBrains Plugins Repository](https://plugins.jetbrains.com) the built-in [Plugin Verifier](https://blog.jetbrains.com/platform/2018/07/plugins-repository-now-integrates-with-the-plugin-verification-tool/)
will run these checks automatically. See [Plugin Verifier](/reference_guide/api_changes_list.md#plugin-verifier) for more information on how to run it locally.

During development, [Enabling Auto-Reload](/basics/ide_development_instance.md#enabling-auto-reload) will allow code changes to take effect immediately in the sandbox IDE instance.

### No Use of Components
No Components must be used; existing ones [must be migrated](plugin_components.md) to services, extensions or listeners.

### Action Group Requires ID
All `<group>`s must declare a unique `id`.

### Use Only Dynamic Extensions
All extensions, whether defined in the platform itself or coming from other plugins, must be marked as dynamic (see next paragraph). 

### Mark Extension Points as Dynamic
All extension points provided by the plugin must adhere to specific usage rules and then [be declared](plugin_extension_points.md#dynamic-extension-points) ready for dynamic use explicitly.

### Configurables Depending on Extension Points
Any `Configurable` which depends on dynamic extension points must implement `Configurable.WithEpDependencies`.

### No Use of Service Overrides
Application, project and module services declared with `overrides="true"` are not allowed.

## Plugin Load/Unload Events
Register [`com.intellij.ide.plugins.DynamicPluginListener`](upsource:///platform/platform-impl/src/com/intellij/ide/plugins/DynamicPlugins.kt) [listener](plugin_listeners.md) to receive updates on plugin load/unload events.