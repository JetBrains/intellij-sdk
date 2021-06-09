[//]: # (title: GoLand Extension Point List)

<!-- Copyright 2000-2021 JetBrains s.r.o. and other contributors. Use of this source code is governed by the Apache 2.0 license that can be found in the LICENSE file. -->

14 Extension Points (EP) for GoLand
         
See [Extension Point List](extension_point_list.md) for IntelliJ Platform EPs.

<include src="extension_point_list.md" include-id="ep_list_legend"></include>

## GoLand

### goland.xml
goland.xml

| Extension Point | Implementation |
|-----------------|----------------|
| [com.goide.dlv.positionConverterFactory](https://jb.gg/ipe?extensions=com.goide.dlv.positionConverterFactory) | `DlvPositionConverterFactory` | 
| [com.goide.documentation.packageVersionProvider](https://jb.gg/ipe?extensions=com.goide.documentation.packageVersionProvider) | `GoDocumentationPackageVersionProvider` | 
| [com.goide.executorExtension](https://jb.gg/ipe?extensions=com.goide.executorExtension) | `GoExecutorExtension` | 
| [com.goide.externalToolIntegrator](https://jb.gg/ipe?extensions=com.goide.externalToolIntegrator) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | `GoExternalToolIntegrator` | 
| [com.goide.highlighting.errorAnnotatorSuppressor](https://jb.gg/ipe?extensions=com.goide.highlighting.errorAnnotatorSuppressor) | `GoErrorAnnotatorSuppressor` | 
| [com.goide.importPathsProvider](https://jb.gg/ipe?extensions=com.goide.importPathsProvider) | `GoImportPathsProvider` | 
| [com.goide.importResolver](https://jb.gg/ipe?extensions=com.goide.importResolver) | `GoImportResolver` | 
| [com.goide.imports.weigher](https://jb.gg/ipe?extensions=com.goide.imports.weigher) | `GoImportsWeigher` | 
| [com.goide.importsFilter](https://jb.gg/ipe?extensions=com.goide.importsFilter) | `GoImportsFilter` | 
| [com.goide.packageFactory](https://jb.gg/ipe?extensions=com.goide.packageFactory) | `GoPackageFactory` | 
| [com.goide.rootsProvider](https://jb.gg/ipe?extensions=com.goide.rootsProvider) | `GoRootsProvider` | 
| [com.goide.runConfigurationExtension](https://jb.gg/ipe?extensions=com.goide.runConfigurationExtension) | `GoRunConfigurationExtension` | 
| [com.goide.sdkProvider](https://jb.gg/ipe?extensions=com.goide.sdkProvider) | `GoSdkProvider` | 
| [com.goide.support](https://jb.gg/ipe?extensions=com.goide.support) | `GoLangSupport` | 

