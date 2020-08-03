# IntelliJ Platform SDK Code Samples

[![official JetBrains project](https://jb.gg/badges/official.svg)][jb:confluence-on-gh]
[![JetBrains IntelliJ Platform SDK Docs](https://jb.gg/badges/docs.svg)][jb:docs]
[![Twitter Follow](https://img.shields.io/twitter/follow/JBPlatform?style=flat)][jb:twitter]
[![Build](https://github.com/JetBrains/intellij-sdk-docs/workflows/Build/badge.svg)][gh:build]
[![Slack](https://img.shields.io/badge/Slack-%23intellij--platform-blue)][jb:slack]

Learn how to build plugins using IntelliJ Platform SDK for the [JetBrains products][jb:products] by experimenting with
our code samples. These samples show you how features work and help you jumpstart your plugins.

There is also [IntelliJ Platform Plugin Template][gh:template] project available, which is a repository that provides
a pure boilerplate template. Plugin Template makes it easier to create a new plugin project by preconfiguring
the project scaffold and CI using GitHub Actions, linking to the proper documentation pages, and keeping everything
organized.

| Code sample                                                            | Description                                                                                                                                            |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Action Basics](./action_basics)                                       | Action and Action Group patterns implementation, adds entries to the Tools menu.                                                                       |
| [Comparing References Inspection](./comparing_references_inspection)   | Local Inspection Tool, adds entries to `Preferences \| Editor \| Inspections \| Java \| Probable Bugs`.                                                |
| [Conditional Operator Intention](./conditional_operator_intention)     | Intention action, suggests converting a ternary operator into an *if* block and adds entry to `Preferences \| Editor \| Intentions \| SDK Intentions`. |
| [Editor Basics](./editor_basics)                                       | Basic Editor APIs example with editor popup menu with extra actions.                                                                                   |
| [Facet Basics](./facet_basics)                                         | Custom Facet pattern, adds *SDK Facet* to the `Project Structure \| Project Settings \| Facets menu`.                                                  |
| [Framework Basics](./framework_basics)                                 | Basic *SDK Demo Framework* support added to the `File \| New \| Project \| IntelliJ Platform Plugin`                                                   |
| [Inspection Basics](./inspection_basics)                               | Code Inspection entry added to the `Preferences \| Editor \| Inspections \| SDK \| Example Tools`.                                                     |
| [Kotlin Demo](./kotlin_demo)                                           | Kotlin example extending the *Main Menu* with a `Greeting` menu group.                                                                                 |
| [Live Templates](./live_templates)                                     | Live templates for Markdown language, adds an entry to the `Preferences \| Editor \| Live Templates` dialog.                                           |
| [Max Opened Projects](./max_opened_projects)                           | Application services and listeners, shows warning dialog when more than 3 open projects are opened.                                                    |
| [Module](./module)                                                     | *SDK Demo Module* module type added to the `File \| New \| Project...`.                                                                                |
| [Product Specific - PyCharm Sample](./product_specific/pycharm_basics) | Plugin project configuration for the PyCharm IDE.                                                                                                      |
| [Project Model](./project_model)                                       | Interacts with the project model, adds menu items to `Tools` and `Editor Context` menus.                                                               |
| [Project View Pane](./project_view_pane)                               | Project View Pane listing only image files.                                                                                                            |
| [Project Wizard](./project_wizard)                                     | Project Wizard example with demo steps.                                                                                                                |
| [Psi Demo](./psi_demo)                                                 | PSI Navigation features presentation.                                                                                                                  |
| [Run Configuration](./run_configuration)                               | Run configuration implementation with factory, options and UI.                                                                                         |
| [Settings](./settings)                                                 | Custom settings panel, adds a settings panel to the `Settings \| Preferences` panel under `Tools`.                                                     |
| [Simple Language Plugin](./simple_language_plugin)                     | Custom language support, defines a new *Simple language* with syntax highlighting, annotations, code completion, and other features.                   |
| [Theme Basics](./theme_basics)                                         | Sample *UI Theme* plugin with basic interface modifications.                                                                                           |
| [Tool Window](./tool_window)                                           | Custom Tool Window example plugin.                                                                                                                     |
| [Tree Structure Provider](./tree_structure_provider)                   | Tree Structure Provider showing only plain text files.                                                                                                 |

[gh:build]: https://github.com/JetBrains/intellij-sdk-docs/actions?query=workflow%3ABuild
[gh:template]: https://github.com/JetBrains/intellij-platform-plugin-template

[jb:confluence-on-gh]: https://confluence.jetbrains.com/display/ALL/JetBrains+on+GitHub
[jb:docs]: http://www.jetbrains.org/intellij/sdk/docs
[jb:products]: https://www.jetbrains.com/products.html
[jb:slack]: https://plugins.jetbrains.com/slack
[jb:twitter]: https://twitter.com/JBPlatform
