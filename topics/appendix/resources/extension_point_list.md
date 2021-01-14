[//]: # (title: Extension Point List)

1183 Extension Points

_Extension Point_ searches for usages inside existing implementations of open-source IntelliJ Platform plugins via [IntelliJ Platform Explorer](https://plugins.jetbrains.com/intellij-platform-explorer).

_Implementation_ opens declaration of related class. 

### Note Legend

| Icon | Description | Details |
|---|---|---|
| ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | Non-Dynamic Extension Point | Installation/update of plugin requires restart |
| ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | Experimental API | Implementation annotated with `@ApiStatus.Experimental`, API might be altered or removed without prior notice |
| ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | Project-Level Extension Point | Declared with `area="IDEA_PROJECT"` |

## [Analysis.xml](upsource:///platform/analysis-api/resources/META-INF/Analysis.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.codeInsight.containerProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.containerProvider) | [`ContainerProvider`](upsource:///platform/core-api/src/com/intellij/codeInsight/ContainerProvider.java) | 
|  | [com.intellij.codeInsight.signatureHelp](https://jb.gg/ipe?extensions=com.intellij.codeInsight.signatureHelp) | [`SignatureHelpProvider`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/signatureHelp/SignatureHelpProvider.java) | 
|  | [com.intellij.codeInspection.InspectionExtension](https://jb.gg/ipe?extensions=com.intellij.codeInspection.InspectionExtension) | [`InspectionExtensionsFactory`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/lang/InspectionExtensionsFactory.java) | 
|  | [com.intellij.completion.contributor](https://jb.gg/ipe?extensions=com.intellij.completion.contributor) | [`CompletionContributor`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/completion/CompletionContributor.java) | 
|  | [com.intellij.completion.skip](https://jb.gg/ipe?extensions=com.intellij.completion.skip) | [`CompletionPreselectSkipper`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/completion/CompletionPreselectSkipper.java) | 
|  | [com.intellij.documentationProvider](https://jb.gg/ipe?extensions=com.intellij.documentationProvider) | [`DocumentationProvider`](upsource:///platform/analysis-api/src/com/intellij/lang/documentation/DocumentationProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.fileContextProvider](https://jb.gg/ipe?extensions=com.intellij.fileContextProvider) | [`FileContextProvider`](upsource:///platform/core-api/src/com/intellij/psi/FileContextProvider.java) | 
|  | [com.intellij.fileLookupInfoProvider](https://jb.gg/ipe?extensions=com.intellij.fileLookupInfoProvider) | [`FileLookupInfoProvider`](upsource:///platform/analysis-api/src/com/intellij/psi/file/FileLookupInfoProvider.java) | 
|  | [com.intellij.globalInspection](https://jb.gg/ipe?extensions=com.intellij.globalInspection) | [`GlobalInspectionTool`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/GlobalInspectionTool.java) | 
|  | [com.intellij.gotoDeclarationHandler](https://jb.gg/ipe?extensions=com.intellij.gotoDeclarationHandler) | [`GotoDeclarationHandler`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/navigation/actions/GotoDeclarationHandler.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.highlightErrorFilter](https://jb.gg/ipe?extensions=com.intellij.highlightErrorFilter) | [`HighlightErrorFilter`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/highlighting/HighlightErrorFilter.java) | 
|  | [com.intellij.inspectionToolProvider](https://jb.gg/ipe?extensions=com.intellij.inspectionToolProvider) | [`InspectionToolProvider`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/InspectionToolProvider.java) | 
|  | [com.intellij.inspectionsReportConverter](https://jb.gg/ipe?extensions=com.intellij.inspectionsReportConverter) | [`InspectionsReportConverter`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/InspectionsReportConverter.java) | 
|  | [com.intellij.intentionAction](https://jb.gg/ipe?extensions=com.intellij.intentionAction) | [`IntentionAction`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/intention/IntentionAction.java) | 
|  | [com.intellij.lang.documentationProvider](https://jb.gg/ipe?extensions=com.intellij.lang.documentationProvider) | [`DocumentationProvider`](upsource:///platform/analysis-api/src/com/intellij/lang/documentation/DocumentationProvider.java) | 
|  | [com.intellij.lang.inspectionSuppressor](https://jb.gg/ipe?extensions=com.intellij.lang.inspectionSuppressor) | [`InspectionSuppressor`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/InspectionSuppressor.java) | 
|  | [com.intellij.languageInjector](https://jb.gg/ipe?extensions=com.intellij.languageInjector) | [`LanguageInjector`](upsource:///platform/analysis-api/src/com/intellij/psi/LanguageInjector.java) | 
|  | [com.intellij.liveTemplateContext](https://jb.gg/ipe?extensions=com.intellij.liveTemplateContext) | [`TemplateContextType`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/template/TemplateContextType.java) | 
|  | [com.intellij.liveTemplateMacro](https://jb.gg/ipe?extensions=com.intellij.liveTemplateMacro) | [`Macro`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/template/Macro.java) | 
|  | [com.intellij.localInspection](https://jb.gg/ipe?extensions=com.intellij.localInspection) | [`LocalInspectionTool`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/LocalInspectionTool.java) | 
|  | [com.intellij.weigher](https://jb.gg/ipe?extensions=com.intellij.weigher) | [`Weigher`](upsource:///platform/analysis-api/src/com/intellij/psi/Weigher.java) | 

## [AnalysisImpl.xml](upsource:///platform/analysis-impl/resources/META-INF/AnalysisImpl.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.completionData](https://jb.gg/ipe?extensions=com.intellij.completionData) | [~~`CompletionData`~~](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/completion/CompletionData.java) | 
|  | [com.intellij.elementLookupRenderer](https://jb.gg/ipe?extensions=com.intellij.elementLookupRenderer) | [~~`ElementLookupRenderer`~~](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/lookup/impl/ElementLookupRenderer.java) | 
|  | [com.intellij.liveTemplateOptionalProcessor](https://jb.gg/ipe?extensions=com.intellij.liveTemplateOptionalProcessor) | [`TemplateOptionalProcessor`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/template/impl/TemplateOptionalProcessor.java) | 
|  | [com.intellij.liveTemplatePreprocessor](https://jb.gg/ipe?extensions=com.intellij.liveTemplatePreprocessor) | [`TemplatePreprocessor`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/template/impl/TemplatePreprocessor.java) | 
|  | [com.intellij.outerLanguageRangePatcher](https://jb.gg/ipe?extensions=com.intellij.outerLanguageRangePatcher) | [`OuterLanguageRangePatcher`](upsource:///platform/analysis-impl/src/com/intellij/psi/templateLanguages/TemplateDataElementType.java) | 
|  | [com.intellij.psi.fileReferenceHelper](https://jb.gg/ipe?extensions=com.intellij.psi.fileReferenceHelper) | [`FileReferenceHelper`](upsource:///platform/analysis-impl/src/com/intellij/psi/impl/source/resolve/reference/impl/providers/FileReferenceHelper.java) | 
|  | [com.intellij.resolveScopeEnlarger](https://jb.gg/ipe?extensions=com.intellij.resolveScopeEnlarger) | [`ResolveScopeEnlarger`](upsource:///platform/analysis-impl/src/com/intellij/psi/ResolveScopeEnlarger.java) | 
|  | [com.intellij.resolveScopeProvider](https://jb.gg/ipe?extensions=com.intellij.resolveScopeProvider) | [`ResolveScopeProvider`](upsource:///platform/analysis-impl/src/com/intellij/psi/ResolveScopeProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.severitiesProvider](https://jb.gg/ipe?extensions=com.intellij.severitiesProvider) | [`SeveritiesProvider`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/SeveritiesProvider.java) | 
|  | [com.intellij.useScopeEnlarger](https://jb.gg/ipe?extensions=com.intellij.useScopeEnlarger) | [`UseScopeEnlarger`](upsource:///platform/indexing-api/src/com/intellij/psi/search/UseScopeEnlarger.java) | 
|  | [com.intellij.useScopeOptimizer](https://jb.gg/ipe?extensions=com.intellij.useScopeOptimizer) | [`ScopeOptimizer`](upsource:///platform/indexing-api/src/com/intellij/psi/search/ScopeOptimizer.java) | 

## [android-adb.xml](upsource:///android/android-adb/src/META-INF/android-adb.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.explorer.fileHandler](https://jb.gg/ipe?extensions=com.android.tools.idea.explorer.fileHandler) | [`FileHandler`](upsource:///android/android-adb/src/com/android/tools/idea/deviceExplorer/FileHandler.java) | 

## [android-kotlin-extensions-common.xml](upsource:///android/android-kotlin/android-extensions-idea-common/src/META-INF/android-kotlin-extensions-common.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.jetbrains.kotlin.android.model.androidModuleInfoProvider](https://jb.gg/ipe?extensions=org.jetbrains.kotlin.android.model.androidModuleInfoProvider) | [`AndroidModuleInfoProvider`](upsource:///android/android-kotlin/android-extensions-idea-common/src/org/jetbrains/kotlin/android/model/AndroidModuleInfoProvider.kt) | 

## [android-kotlin.xml](upsource:///android/android/src/META-INF/android-kotlin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [org.jetbrains.kotlin.androidDexer](https://jb.gg/ipe?extensions=org.jetbrains.kotlin.androidDexer) | `AndroidDexer` | 

## [android-lang.xml](upsource:///android/android-lang/src/META-INF/android-lang.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.lang.androidSql.contextProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.lang.androidSql.contextProvider) | [`Provider`](upsource:///android/android-lang/src/com/android/tools/idea/lang/androidSql/AndroidSqlContext.kt) | 

## [android-plugin.xml](upsource:///android/android/src/META-INF/android-plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.captureType](https://jb.gg/ipe?extensions=com.android.captureType) | [`CaptureType`](upsource:///android/android/src/com/android/tools/idea/profiling/capture/CaptureType.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.customProjectTypeImporter](https://jb.gg/ipe?extensions=com.android.customProjectTypeImporter) | [`CustomProjectTypeImporter`](upsource:///android/android/src/com/android/tools/idea/project/CustomProjectTypeImporter.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.gradle.sync.postSyncModuleSetupStep](https://jb.gg/ipe?extensions=com.android.gradle.sync.postSyncModuleSetupStep) | [`ModuleSetupStep`](upsource:///android/android/src/com/android/tools/idea/gradle/project/sync/setup/post/ModuleSetupStep.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.gradle.sync.postSyncProjectCleanupStep](https://jb.gg/ipe?extensions=com.android.gradle.sync.postSyncProjectCleanupStep) | [`ProjectCleanupStep`](upsource:///android/android/src/com/android/tools/idea/gradle/project/sync/setup/post/ProjectCleanupStep.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.gradle.sync.postSyncProjectSetupStep](https://jb.gg/ipe?extensions=com.android.gradle.sync.postSyncProjectSetupStep) | [`ProjectSetupStep`](upsource:///android/android/src/com/android/tools/idea/gradle/project/sync/setup/post/ProjectSetupStep.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.gradle.sync.syncErrorHandler](https://jb.gg/ipe?extensions=com.android.gradle.sync.syncErrorHandler) | [`SyncErrorHandler`](upsource:///android/android/src/com/android/tools/idea/gradle/project/sync/errors/SyncErrorHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.ide.androidConfigurableContributor](https://jb.gg/ipe?extensions=com.android.ide.androidConfigurableContributor) | [`AndroidConfigurableContributor`](upsource:///android/android/src/com/android/tools/idea/structure/dialog/AndroidConfigurableContributor.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.ide.developerServiceBuildSystemOperations](https://jb.gg/ipe?extensions=com.android.ide.developerServiceBuildSystemOperations) | [`DeveloperServiceBuildSystemOperations`](upsource:///android/android/src/com/android/tools/idea/structure/services/DeveloperServiceBuildSystemOperations.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.ide.moduleStructureConfigurableContributor](https://jb.gg/ipe?extensions=com.android.ide.moduleStructureConfigurableContributor) | [`ModuleStructureConfigurableContributor`](upsource:///android/android/src/com/android/tools/idea/structure/dialog/ModuleStructureConfigurableContributor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.ide.projectStructureItemsContributor](https://jb.gg/ipe?extensions=com.android.ide.projectStructureItemsContributor) | [`ProjectStructureItemsContributor`](upsource:///android/android/src/com/android/tools/idea/structure/dialog/ProjectStructureItemsContributor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.ide.sdkEventListener](https://jb.gg/ipe?extensions=com.android.ide.sdkEventListener) | [`AndroidSdkEventListener`](upsource:///android/android/src/com/android/tools/idea/sdk/IdeSdks.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.logcat.filterProvider](https://jb.gg/ipe?extensions=com.android.logcat.filterProvider) | [`LogcatFilterProvider`](upsource:///android/android/src/com/android/tools/idea/logcat/LogcatFilterProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.moduleDescriptionProvider](https://jb.gg/ipe?extensions=com.android.moduleDescriptionProvider) | [`ModuleDescriptionProvider`](upsource:///android/android/src/com/android/tools/idea/npw/module/ModuleDescriptionProvider.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.rendering.renderErrorContributor](https://jb.gg/ipe?extensions=com.android.rendering.renderErrorContributor) | [`Provider`](upsource:///android/android/src/com/android/tools/idea/rendering/RenderErrorContributor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.rendering.renderSecurityManagerOverrides](https://jb.gg/ipe?extensions=com.android.rendering.renderSecurityManagerOverrides) | [`RenderSecurityManagerOverrides`](upsource:///android/android/src/com/android/tools/idea/rendering/RenderSecurityManagerOverrides.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.run.androidDebugger](https://jb.gg/ipe?extensions=com.android.run.androidDebugger) | [`AndroidDebugger`](upsource:///android/android/src/com/android/tools/idea/run/editor/AndroidDebugger.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.run.androidLaunchTaskContributor](https://jb.gg/ipe?extensions=com.android.run.androidLaunchTaskContributor) | [`AndroidLaunchTaskContributor`](upsource:///android/android/src/com/android/tools/idea/run/AndroidLaunchTaskContributor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.run.deployTargetProvider](https://jb.gg/ipe?extensions=com.android.run.deployTargetProvider) | [`DeployTargetProvider`](upsource:///android/android/src/com/android/tools/idea/run/editor/DeployTargetProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.run.deviceNameRenderer](https://jb.gg/ipe?extensions=com.android.run.deviceNameRenderer) | [`DeviceNameRendererEx`](upsource:///android/android/src/com/android/tools/idea/ddms/DeviceNameRendererEx.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.gradleModelProvider](https://jb.gg/ipe?extensions=com.android.tools.gradleModelProvider) | [`GradleModelProvider`](upsource:///plugins/gradle-dsl/src/com/android/tools/idea/gradle/dsl/api/GradleModelProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.databinding.layoutBindingSupport](https://jb.gg/ipe?extensions=com.android.tools.idea.databinding.layoutBindingSupport) | [`LayoutBindingSupport`](upsource:///android/android/src/com/android/tools/idea/databinding/LayoutBindingSupport.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.explorer.fileOpener](https://jb.gg/ipe?extensions=com.android.tools.idea.explorer.fileOpener) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.lang.databinding.dataBindingCompletionSupport](https://jb.gg/ipe?extensions=com.android.tools.idea.lang.databinding.dataBindingCompletionSupport) | [`DataBindingCompletionSupport`](upsource:///android/android/src/com/android/tools/idea/lang/databinding/DataBindingCompletionSupport.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.lang.databinding.dataBindingExpressionSupport](https://jb.gg/ipe?extensions=com.android.tools.idea.lang.databinding.dataBindingExpressionSupport) | [`DataBindingExpressionSupport`](upsource:///android/android/src/com/android/tools/idea/lang/databinding/DataBindingExpressionSupport.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.structure.services.developerServiceCreators](https://jb.gg/ipe?extensions=com.android.tools.idea.structure.services.developerServiceCreators) | [`DeveloperServiceCreators`](upsource:///android/android/src/com/android/tools/idea/structure/services/DeveloperServiceCreators.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.ui.guiTestingStatusProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.ui.guiTestingStatusProvider) | [`GuiTestingStatusProvider`](upsource:///android/android/src/com/android/tools/idea/ui/GuiTestingStatusProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.wizard.template.wizardTemplateProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.wizard.template.wizardTemplateProvider) | `WizardTemplateProvider` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.jetbrains.android.actions.newResourceCreationHandler](https://jb.gg/ipe?extensions=org.jetbrains.android.actions.newResourceCreationHandler) | [`NewResourceCreationHandler`](upsource:///android/android/src/org/jetbrains/android/actions/NewResourceCreationHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.jetbrains.android.mavenProvider](https://jb.gg/ipe?extensions=org.jetbrains.android.mavenProvider) | [`AndroidMavenProvider`](upsource:///android/android/src/org/jetbrains/android/maven/AndroidMavenProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [org.jetbrains.android.uipreview.viewLoaderExtension](https://jb.gg/ipe?extensions=org.jetbrains.android.uipreview.viewLoaderExtension) | [`ViewLoaderExtension`](upsource:///android/android/src/org/jetbrains/android/uipreview/ViewLoaderExtension.java) | 

## [AndroidStudioPlugin.xml](upsource:///android/adt-branding/src/META-INF/AndroidStudioPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.androidStudioInitializer](https://jb.gg/ipe?extensions=com.intellij.androidStudioInitializer) | `Runnable` | 

## [AntSupport](upsource:///plugins/ant/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [AntSupport.AntMessageCustomizer](https://jb.gg/ipe?extensions=AntSupport.AntMessageCustomizer) | [`AntMessageCustomizer`](upsource:///plugins/ant/src/com/intellij/lang/ant/config/execution/AntMessageCustomizer.java) | 

## [assistant.xml](upsource:///android/assistant/src/META-INF/assistant.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.assistant.actionHandler](https://jb.gg/ipe?extensions=com.android.tools.idea.assistant.actionHandler) | [`AssistActionHandler`](upsource:///android/assistant/src/com/android/tools/idea/assistant/AssistActionHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.assistant.actionStateManager](https://jb.gg/ipe?extensions=com.android.tools.idea.assistant.actionStateManager) | [`AssistActionStateManager`](upsource:///android/assistant/src/com/android/tools/idea/assistant/AssistActionStateManager.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.assistant.assistantBundleCreator](https://jb.gg/ipe?extensions=com.android.tools.idea.assistant.assistantBundleCreator) | [`AssistantBundleCreator`](upsource:///android/assistant/src/com/android/tools/idea/assistant/AssistantBundleCreator.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.assistant.panelFactory](https://jb.gg/ipe?extensions=com.android.tools.idea.assistant.panelFactory) | [`PanelFactory`](upsource:///android/assistant/src/com/android/tools/idea/assistant/PanelFactory.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.assistant.scrollHandler](https://jb.gg/ipe?extensions=com.android.tools.idea.assistant.scrollHandler) | [`ScrollHandler`](upsource:///android/assistant/src/com/android/tools/idea/assistant/ScrollHandler.java) | 

## [builtInServer.xml](upsource:///platform/built-in-server/resources/META-INF/builtInServer.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.httpRequestHandler](https://jb.gg/ipe?extensions=com.intellij.httpRequestHandler) | [`HttpRequestHandler`](upsource:///platform/platform-util-io/src/org/jetbrains/ide/HttpRequestHandler.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.jetbrains.binaryRequestHandler](https://jb.gg/ipe?extensions=org.jetbrains.binaryRequestHandler) | [`BinaryRequestHandler`](upsource:///platform/platform-util-io/src/org/jetbrains/ide/BinaryRequestHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.jetbrains.customPortServerManager](https://jb.gg/ipe?extensions=org.jetbrains.customPortServerManager) | [`CustomPortServerManager`](upsource:///platform/built-in-server-api/src/org/jetbrains/ide/CustomPortServerManager.kt) | 
|  | [org.jetbrains.jsonRpcDomain](https://jb.gg/ipe?extensions=org.jetbrains.jsonRpcDomain) | `Object` | 
|  | [org.jetbrains.webServerFileHandler](https://jb.gg/ipe?extensions=org.jetbrains.webServerFileHandler) | [`WebServerFileHandler`](upsource:///platform/built-in-server/src/org/jetbrains/builtInWebServer/WebServerFileHandler.kt) | 
|  | [org.jetbrains.webServerPathHandler](https://jb.gg/ipe?extensions=org.jetbrains.webServerPathHandler) | [`WebServerPathHandler`](upsource:///platform/built-in-server/src/org/jetbrains/builtInWebServer/WebServerPathHandler.kt) | 
|  | [org.jetbrains.webServerRootsProvider](https://jb.gg/ipe?extensions=org.jetbrains.webServerRootsProvider) | [`WebServerRootsProvider`](upsource:///platform/built-in-server-api/src/org/jetbrains/builtInWebServer/WebServerRootsProvider.kt) | 

## [ByteCodeViewer](upsource:///plugins/ByteCodeViewer/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [ByteCodeViewer.classSearcher](https://jb.gg/ipe?extensions=ByteCodeViewer.classSearcher) | [`ClassSearcher`](upsource:///plugins/ByteCodeViewer/src/com/intellij/byteCodeViewer/ClassSearcher.java) | 

## [com.intellij.copyright](upsource:///plugins/copyright/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.copyright.updater](https://jb.gg/ipe?extensions=com.intellij.copyright.updater) | [`UpdateCopyrightsProvider`](upsource:///plugins/copyright/src/com/maddyhome/idea/copyright/psi/UpdateCopyrightsProvider.java) | 
|  | [com.intellij.copyright.variablesProvider](https://jb.gg/ipe?extensions=com.intellij.copyright.variablesProvider) | [`CopyrightVariablesProvider`](upsource:///plugins/copyright/src/com/maddyhome/idea/copyright/pattern/CopyrightVariablesProvider.java) | 

## [com.intellij.gradle](upsource:///plugins/gradle/plugin-resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.plugins.gradle.executionEnvironmentProvider](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.executionEnvironmentProvider) | [`GradleExecutionEnvironmentProvider`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/execution/build/GradleExecutionEnvironmentProvider.java) | 
|  | [org.jetbrains.plugins.gradle.importCustomizer](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.importCustomizer) | [`GradleImportCustomizer`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/service/project/GradleImportCustomizer.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.jetbrains.plugins.gradle.issueChecker](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.issueChecker) | [`GradleIssueChecker`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/issue/GradleIssueChecker.kt) | 
|  | [org.jetbrains.plugins.gradle.orderEnumerationHandlerFactory](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.orderEnumerationHandlerFactory) | [`FactoryImpl`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/execution/GradleOrderEnumeratorHandler.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.jetbrains.plugins.gradle.projectModelContributor](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.projectModelContributor) | [`ProjectModelContributor`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/service/project/ProjectModelContributor.java) | 
|  | [org.jetbrains.plugins.gradle.projectResolve](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.projectResolve) | [`GradleProjectResolverExtension`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/service/project/GradleProjectResolverExtension.java) | 
|  | [org.jetbrains.plugins.gradle.settingsControlProvider](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.settingsControlProvider) | [`GradleSettingsControlProvider`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/service/settings/GradleSettingsControlProvider.java) | 
|  | [org.jetbrains.plugins.gradle.taskManager](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.taskManager) | [`GradleTaskManagerExtension`](upsource:///plugins/gradle/src/org/jetbrains/plugins/gradle/service/task/GradleTaskManagerExtension.java) | 

## [com.intellij.java-i18n](upsource:///plugins/java-i18n/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.java-i18n.i18nizeHandlerProvider](https://jb.gg/ipe?extensions=com.intellij.java-i18n.i18nizeHandlerProvider) | [`I18nizeHandlerProvider`](upsource:///plugins/java-i18n/src/com/intellij/codeInspection/i18n/I18nizeHandlerProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.java-i18n.resourceBundleManager](https://jb.gg/ipe?extensions=com.intellij.java-i18n.resourceBundleManager) | [`ResourceBundleManager`](upsource:///plugins/java-i18n/src/com/intellij/lang/properties/psi/ResourceBundleManager.java) | 

## [com.intellij.platform.images](upsource:///images/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.images.themeFilter](https://jb.gg/ipe?extensions=com.intellij.images.themeFilter) | [`ThemeFilter`](upsource:///images/src/org/intellij/images/thumbnail/actions/ThemeFilter.java) | 

## [com.intellij.properties](upsource:///plugins/properties/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.properties.alphaUnsortedInspectionSuppressor](https://jb.gg/ipe?extensions=com.intellij.properties.alphaUnsortedInspectionSuppressor) | [`AlphaUnsortedPropertiesFileInspectionSuppressor`](upsource:///plugins/properties/properties-psi-impl/src/com/intellij/codeInspection/unsorted/AlphaUnsortedPropertiesFileInspectionSuppressor.java) | 
|  | [com.intellij.properties.duplicatePropertyKeyAnnotationSuppressor](https://jb.gg/ipe?extensions=com.intellij.properties.duplicatePropertyKeyAnnotationSuppressor) | [`DuplicatePropertyKeyAnnotationSuppressor`](upsource:///plugins/properties/properties-psi-impl/src/com/intellij/lang/properties/DuplicatePropertyKeyAnnotationSuppressor.java) | 
|  | [com.intellij.properties.implicitPropertyUsageProvider](https://jb.gg/ipe?extensions=com.intellij.properties.implicitPropertyUsageProvider) | [`ImplicitPropertyUsageProvider`](upsource:///plugins/properties/properties-psi-impl/src/com/intellij/codeInspection/unused/ImplicitPropertyUsageProvider.java) | 

## [com.intellij.stats.completion](upsource:///plugins/stats-collector/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.stats.completion.policy](https://jb.gg/ipe?extensions=com.intellij.stats.completion.policy) | [`CompletionStatsPolicy`](upsource:///plugins/stats-collector/src/com/intellij/stats/completion/CompletionStatsPolicy.kt) | 

## [com.intellij.tasks](upsource:///plugins/tasks/tasks-core/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.tasks.commitPlaceholderProvider](https://jb.gg/ipe?extensions=com.intellij.tasks.commitPlaceholderProvider) | [`CommitPlaceholderProvider`](upsource:///platform/tasks-platform-api/src/com/intellij/tasks/CommitPlaceholderProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.tasks.dialogPanelProvider](https://jb.gg/ipe?extensions=com.intellij.tasks.dialogPanelProvider) | [`TaskDialogPanelProvider`](upsource:///plugins/tasks/tasks-api/src/com/intellij/tasks/ui/TaskDialogPanelProvider.java) | 
|  | [com.intellij.tasks.repositoryType](https://jb.gg/ipe?extensions=com.intellij.tasks.repositoryType) | [`TaskRepositoryType`](upsource:///platform/tasks-platform-api/src/com/intellij/tasks/TaskRepositoryType.java) | 

## [com.intellij.testGuiFramework](upsource:///platform/testGuiFramework/res/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.generatedCodeReceiver](https://jb.gg/ipe?extensions=com.intellij.generatedCodeReceiver) | [`GeneratedCodeReceiver`](upsource:///platform/testGuiFramework/src/com/intellij/testGuiFramework/recorder/GeneratedCodeReceiver.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.guiRecorderListener](https://jb.gg/ipe?extensions=com.intellij.guiRecorderListener) | [`GuiRecorderListener`](upsource:///platform/testGuiFramework/src/com/intellij/testGuiFramework/recorder/GuiRecorderListener.java) | 

## [com.intellij.uiDesigner](upsource:///plugins/ui-designer/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.paletteItemProvider](https://jb.gg/ipe?extensions=com.intellij.paletteItemProvider) | [`PaletteItemProvider`](upsource:///plugins/ui-designer/src/com/intellij/ide/palette/PaletteItemProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.uiDesigner.formInspectionTool](https://jb.gg/ipe?extensions=com.intellij.uiDesigner.formInspectionTool) | [`FormInspectionTool`](upsource:///plugins/ui-designer/src/com/intellij/uiDesigner/inspections/FormInspectionTool.java) | 

## [CompletionExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/CompletionExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.codeInsight.wordCompletionFilter](https://jb.gg/ipe?extensions=com.intellij.codeInsight.wordCompletionFilter) | [`WordCompletionElementFilter`](upsource:///platform/lang-api/src/com/intellij/lang/WordCompletionElementFilter.java) | 
|  | [com.intellij.completion.confidence](https://jb.gg/ipe?extensions=com.intellij.completion.confidence) | [`CompletionConfidence`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/completion/CompletionConfidence.java) | 
|  | [com.intellij.completion.ml.contextFeatures](https://jb.gg/ipe?extensions=com.intellij.completion.ml.contextFeatures) | [`ContextFeatureProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/completion/ml/ContextFeatureProvider.java) | 
|  | [com.intellij.completion.ml.elementFeatures](https://jb.gg/ipe?extensions=com.intellij.completion.ml.elementFeatures) | [`ElementFeatureProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/completion/ml/ElementFeatureProvider.java) | 
|  | [com.intellij.completion.ml.model](https://jb.gg/ipe?extensions=com.intellij.completion.ml.model) | [`RankingModelProvider`](upsource:///platform/platform-impl/src/com/intellij/internal/ml/completion/RankingModelProvider.java) | 
|  | [com.intellij.completion.plainTextSymbol](https://jb.gg/ipe?extensions=com.intellij.completion.plainTextSymbol) | [`PlainTextSymbolCompletionContributor`](upsource:///platform/lang-api/src/com/intellij/codeInsight/completion/PlainTextSymbolCompletionContributor.java) | 
|  | [com.intellij.completion.preselectionBehaviourProvider](https://jb.gg/ipe?extensions=com.intellij.completion.preselectionBehaviourProvider) | [`CompletionPreselectionBehaviourProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/completion/CompletionPreselectionBehaviourProvider.java) | 
|  | [com.intellij.createDirectoryCompletionContributor](https://jb.gg/ipe?extensions=com.intellij.createDirectoryCompletionContributor) | [`CreateDirectoryCompletionContributor`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/CreateDirectoryCompletionContributor.java) | 
|  | [com.intellij.lookup.actionProvider](https://jb.gg/ipe?extensions=com.intellij.lookup.actionProvider) | [`LookupActionProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/lookup/LookupActionProvider.java) | 
|  | [com.intellij.lookup.charFilter](https://jb.gg/ipe?extensions=com.intellij.lookup.charFilter) | [`CharFilter`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/lookup/CharFilter.java) | 
|  | [com.intellij.lookup.usageDetails](https://jb.gg/ipe?extensions=com.intellij.lookup.usageDetails) | [`LookupUsageDescriptor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/lookup/impl/LookupUsageDescriptor.java) | 
|  | [com.intellij.templateParameterTraversalPolicy](https://jb.gg/ipe?extensions=com.intellij.templateParameterTraversalPolicy) | [`TemplateParameterTraversalPolicy`](upsource:///platform/lang-api/src/com/intellij/codeInsight/completion/TemplateParameterTraversalPolicy.java) | 

## [compose-designer.xml](upsource:///android/compose-designer/src/META-INF/compose-designer.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.compose.preview.composeEditorNotificationProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.compose.preview.composeEditorNotificationProvider) | [`Provider`](upsource:///platform/platform-api/src/com/intellij/ui/EditorNotifications.java) | 

## [Core.xml](upsource:///platform/core-api/resources/META-INF/Core.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.applicationService](https://jb.gg/ipe?extensions=com.intellij.applicationService) | `n/a` | 
|  | [com.intellij.backgroundPostStartupActivity](https://jb.gg/ipe?extensions=com.intellij.backgroundPostStartupActivity) | [`StartupActivity`](upsource:///platform/core-api/src/com/intellij/openapi/startup/StartupActivity.java) | 
|  | [com.intellij.editorFactoryDocumentListener](https://jb.gg/ipe?extensions=com.intellij.editorFactoryDocumentListener) | [`DocumentListener`](upsource:///platform/core-api/src/com/intellij/openapi/editor/event/DocumentListener.java) | 
|  | [com.intellij.fileTypeDetector](https://jb.gg/ipe?extensions=com.intellij.fileTypeDetector) | [`FileTypeDetector`](upsource:///platform/core-api/src/com/intellij/openapi/fileTypes/FileTypeRegistry.java) | 
|  | [com.intellij.lang.elementManipulator](https://jb.gg/ipe?extensions=com.intellij.lang.elementManipulator) | [`ElementManipulator`](upsource:///platform/core-api/src/com/intellij/psi/ElementManipulator.java) | 
|  | [com.intellij.lang.parserDefinition](https://jb.gg/ipe?extensions=com.intellij.lang.parserDefinition) | [`ParserDefinition`](upsource:///platform/core-api/src/com/intellij/lang/ParserDefinition.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.languageBundle](https://jb.gg/ipe?extensions=com.intellij.languageBundle) | `n/a` | 
|  | [com.intellij.metaLanguage](https://jb.gg/ipe?extensions=com.intellij.metaLanguage) | [`MetaLanguage`](upsource:///platform/core-api/src/com/intellij/lang/MetaLanguage.java) | 
|  | [com.intellij.moduleService](https://jb.gg/ipe?extensions=com.intellij.moduleService) | `n/a` | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.multiHostInjector](https://jb.gg/ipe?extensions=com.intellij.multiHostInjector) | [`MultiHostInjector`](upsource:///platform/core-api/src/com/intellij/lang/injection/MultiHostInjector.java) | 
|  | [com.intellij.pom.declarationSearcher](https://jb.gg/ipe?extensions=com.intellij.pom.declarationSearcher) | [`PomDeclarationSearcher`](upsource:///platform/core-api/src/com/intellij/pom/PomDeclarationSearcher.java) | 
|  | [com.intellij.postStartupActivity](https://jb.gg/ipe?extensions=com.intellij.postStartupActivity) | [`StartupActivity`](upsource:///platform/core-api/src/com/intellij/openapi/startup/StartupActivity.java) | 
|  | [com.intellij.projectService](https://jb.gg/ipe?extensions=com.intellij.projectService) | `n/a` | 
|  | [com.intellij.requiredForSmartModeStartupActivity](https://jb.gg/ipe?extensions=com.intellij.requiredForSmartModeStartupActivity) | [`RequiredForSmartMode`](upsource:///platform/core-api/src/com/intellij/openapi/startup/StartupActivity.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.startupActivity](https://jb.gg/ipe?extensions=com.intellij.startupActivity) | [`StartupActivity`](upsource:///platform/core-api/src/com/intellij/openapi/startup/StartupActivity.java) | 
|  | [com.intellij.stubElementTypeHolder](https://jb.gg/ipe?extensions=com.intellij.stubElementTypeHolder) | `n/a` | 
|  | [com.intellij.vfs.asyncListener](https://jb.gg/ipe?extensions=com.intellij.vfs.asyncListener) | [`AsyncFileListener`](upsource:///platform/core-api/src/com/intellij/openapi/vfs/AsyncFileListener.java) | 
|  | [com.intellij.virtualFileManagerListener](https://jb.gg/ipe?extensions=com.intellij.virtualFileManagerListener) | [`VirtualFileManagerListener`](upsource:///platform/core-api/src/com/intellij/openapi/vfs/VirtualFileManagerListener.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.writingAccessProvider](https://jb.gg/ipe?extensions=com.intellij.writingAccessProvider) | [`WritingAccessProvider`](upsource:///platform/core-api/src/com/intellij/openapi/vfs/WritingAccessProvider.java) | 

## [CoreImpl.xml](upsource:///platform/core-impl/resources/META-INF/CoreImpl.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.controlFlowProvider](https://jb.gg/ipe?extensions=com.intellij.controlFlowProvider) | [`ControlFlowProvider`](upsource:///platform/core-impl/src/com/intellij/codeInsight/controlflow/ControlFlowProvider.java) | 
|  | [com.intellij.lang.ast.factory](https://jb.gg/ipe?extensions=com.intellij.lang.ast.factory) | [`ASTFactory`](upsource:///platform/core-impl/src/com/intellij/lang/ASTFactory.java) | 
|  | [com.intellij.lang.tokenSeparatorGenerator](https://jb.gg/ipe?extensions=com.intellij.lang.tokenSeparatorGenerator) | [`TokenSeparatorGenerator`](upsource:///platform/core-api/src/com/intellij/lang/TokenSeparatorGenerator.java) | 
|  | [com.intellij.psi.implicitReferenceProvider](https://jb.gg/ipe?extensions=com.intellij.psi.implicitReferenceProvider) | [`ImplicitReferenceProvider`](upsource:///platform/core-api/src/com/intellij/model/psi/ImplicitReferenceProvider.java) | 
|  | [com.intellij.psi.referenceContributor](https://jb.gg/ipe?extensions=com.intellij.psi.referenceContributor) | [`PsiReferenceContributor`](upsource:///platform/core-api/src/com/intellij/psi/PsiReferenceContributor.java) | 
|  | [com.intellij.psi.symbolReferenceProvider](https://jb.gg/ipe?extensions=com.intellij.psi.symbolReferenceProvider) | [`PsiSymbolReferenceProvider`](upsource:///platform/core-api/src/com/intellij/model/psi/PsiSymbolReferenceProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.psi.treeChangeListener](https://jb.gg/ipe?extensions=com.intellij.psi.treeChangeListener) | [`PsiTreeChangeListener`](upsource:///platform/core-api/src/com/intellij/psi/PsiTreeChangeListener.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.psi.treeChangePreprocessor](https://jb.gg/ipe?extensions=com.intellij.psi.treeChangePreprocessor) | [`PsiTreeChangePreprocessor`](upsource:///platform/core-impl/src/com/intellij/psi/impl/PsiTreeChangePreprocessor.java) | 
|  | [com.intellij.smartPointer.anchorProvider](https://jb.gg/ipe?extensions=com.intellij.smartPointer.anchorProvider) | [`SmartPointerAnchorProvider`](upsource:///platform/core-impl/src/com/intellij/psi/impl/smartPointers/SmartPointerAnchorProvider.java) | 
|  | [com.intellij.treeCopyHandler](https://jb.gg/ipe?extensions=com.intellij.treeCopyHandler) | [`TreeCopyHandler`](upsource:///platform/core-impl/src/com/intellij/psi/impl/source/tree/TreeCopyHandler.java) | 
|  | [com.intellij.virtualFileSystem](https://jb.gg/ipe?extensions=com.intellij.virtualFileSystem) | [`VirtualFileSystem`](upsource:///platform/core-api/src/com/intellij/openapi/vfs/VirtualFileSystem.java) | 

## [Coverage](upsource:///plugins/coverage/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.javaCoverageEngineExtension](https://jb.gg/ipe?extensions=com.intellij.javaCoverageEngineExtension) | [`JavaCoverageEngineExtension`](upsource:///plugins/coverage/src/com/intellij/coverage/JavaCoverageEngineExtension.java) | 

## [coverage-common-plugin.xml](upsource:///plugins/coverage-common/src/META-INF/coverage-common-plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.coverageEngine](https://jb.gg/ipe?extensions=com.intellij.coverageEngine) | [`CoverageEngine`](upsource:///plugins/coverage-common/src/com/intellij/coverage/CoverageEngine.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.coverageOptions](https://jb.gg/ipe?extensions=com.intellij.coverageOptions) | [`CoverageOptions`](upsource:///plugins/coverage-common/src/com/intellij/coverage/CoverageOptions.java) | 
|  | [com.intellij.coverageRunner](https://jb.gg/ipe?extensions=com.intellij.coverageRunner) | [`CoverageRunner`](upsource:///plugins/coverage-common/src/com/intellij/coverage/CoverageRunner.java) | 

## [customview.xml](upsource:///android/designer/customview/src/META-INF/customview.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.customview.preview.<br/>customViewEditorNotificationProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.customview.preview.customViewEditorNotificationProvider) | [`Provider`](upsource:///platform/platform-api/src/com/intellij/ui/EditorNotifications.java) | 

## [designer.xml](upsource:///android/designer/src/META-INF/designer.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.uibuilder.editor.multirepresentation.<br/>sourcecode.sourceCodePreviewRepresentationProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.uibuilder.editor.multirepresentation.sourcecode.sourceCodePreviewRepresentationProvider) | [`PreviewRepresentationProvider`](upsource:///android/designer/src/com/android/tools/idea/uibuilder/editor/multirepresentation/PreviewRepresentationProvider.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.android.tools.idea.uibuilder.handlers.viewHandlerProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.uibuilder.handlers.viewHandlerProvider) | [`ViewHandlerProvider`](upsource:///android/designer/src/com/android/tools/idea/uibuilder/handlers/ViewHandlerProvider.kt) | 

## [DesignerCorePlugin.xml](upsource:///plugins/ui-designer-core/src/META-INF/DesignerCorePlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [Designer.customizations](https://jb.gg/ipe?extensions=Designer.customizations) | [`DesignerCustomizations`](upsource:///plugins/ui-designer-core/src/com/intellij/designer/DesignerCustomizations.java) | 

## [DevKit](upsource:///plugins/devkit/devkit-core/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [DevKit.lang.goodCodeRedVisitor](https://jb.gg/ipe?extensions=DevKit.lang.goodCodeRedVisitor) | [`GoodCodeRedVisitor`](upsource:///plugins/devkit/devkit-core/src/inspections/internal/GoodCodeRedVisitor.java) | 

## [DomPlugin.xml](upsource:///xml/dom-impl/src/META-INF/DomPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.dom.converter](https://jb.gg/ipe?extensions=com.intellij.dom.converter) | `n/a` | 
|  | [com.intellij.dom.customAnnotationChecker](https://jb.gg/ipe?extensions=com.intellij.dom.customAnnotationChecker) | [`DomCustomAnnotationChecker`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/highlighting/DomCustomAnnotationChecker.java) | 
|  | [com.intellij.dom.extender](https://jb.gg/ipe?extensions=com.intellij.dom.extender) | [`DomExtender`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/reflect/DomExtender.java) | 
|  | [com.intellij.dom.fileDescription](https://jb.gg/ipe?extensions=com.intellij.dom.fileDescription) | [`DomFileDescription`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/DomFileDescription.java) | 
|  | [com.intellij.dom.fileMetaData](https://jb.gg/ipe?extensions=com.intellij.dom.fileMetaData) | [`DomFileDescription`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/DomFileDescription.java) | 
|  | [com.intellij.dom.implementation](https://jb.gg/ipe?extensions=com.intellij.dom.implementation) | [`DomElement`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/DomElement.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.dom.uiControlsProvider](https://jb.gg/ipe?extensions=com.intellij.dom.uiControlsProvider) | [`Consumer`](upsource:///platform/util-rt/src/com/intellij/util/Consumer.java) | 
|  | [com.intellij.moduleContextProvider](https://jb.gg/ipe?extensions=com.intellij.moduleContextProvider) | [`ModuleContextProvider`](upsource:///xml/dom-openapi/src/com/intellij/util/xml/ModuleContextProvider.java) | 

## [dvcs.xml](upsource:///platform/dvcs-impl/src/META-INF/dvcs.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.cherryPicker](https://jb.gg/ipe?extensions=com.intellij.cherryPicker) | [`VcsCherryPicker`](upsource:///platform/dvcs-api/src/com/intellij/dvcs/cherrypick/VcsCherryPicker.java) | 
|  | [com.intellij.clonePathProvider](https://jb.gg/ipe?extensions=com.intellij.clonePathProvider) | [`ClonePathProvider`](upsource:///platform/dvcs-impl/src/com/intellij/dvcs/repo/ClonePathProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.prePushHandler](https://jb.gg/ipe?extensions=com.intellij.prePushHandler) | [`PrePushHandler`](upsource:///platform/dvcs-impl/src/com/intellij/dvcs/push/PrePushHandler.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.pushSupport](https://jb.gg/ipe?extensions=com.intellij.pushSupport) | [`PushSupport`](upsource:///platform/dvcs-api/src/com/intellij/dvcs/push/PushSupport.java) | 
|  | [com.intellij.vcsRepositoryCreator](https://jb.gg/ipe?extensions=com.intellij.vcsRepositoryCreator) | [`VcsRepositoryCreator`](upsource:///platform/dvcs-impl/src/com/intellij/dvcs/repo/VcsRepositoryCreator.java) | 

## [Editor.xml](upsource:///platform/editor-ui-api/resources/META-INF/Editor.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.editorFactoryListener](https://jb.gg/ipe?extensions=com.intellij.editorFactoryListener) | [`EditorFactoryListener`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/event/EditorFactoryListener.java) | 
|  | [com.intellij.syntaxHighlighter](https://jb.gg/ipe?extensions=com.intellij.syntaxHighlighter) | [`SyntaxHighlighter`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/fileTypes/SyntaxHighlighter.java) | 

## [EditorExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/EditorExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.backspaceHandlerDelegate](https://jb.gg/ipe?extensions=com.intellij.backspaceHandlerDelegate) | [`BackspaceHandlerDelegate`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/BackspaceHandlerDelegate.java) | 
|  | [com.intellij.basicWordSelectionFilter](https://jb.gg/ipe?extensions=com.intellij.basicWordSelectionFilter) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.bidiRegionsSeparator](https://jb.gg/ipe?extensions=com.intellij.bidiRegionsSeparator) | [`BidiRegionsSeparator`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/bidi/BidiRegionsSeparator.java) | 
|  | [com.intellij.codeBlockProvider](https://jb.gg/ipe?extensions=com.intellij.codeBlockProvider) | [`CodeBlockProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/CodeBlockProvider.java) | 
|  | [com.intellij.codeInsight.fillParagraph](https://jb.gg/ipe?extensions=com.intellij.codeInsight.fillParagraph) | [`ParagraphFillHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/fillParagraph/ParagraphFillHandler.java) | 
|  | [com.intellij.commentCompleteHandler](https://jb.gg/ipe?extensions=com.intellij.commentCompleteHandler) | [`CommentCompleteHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/CommentCompleteHandler.java) | 
|  | [com.intellij.copyPastePostProcessor](https://jb.gg/ipe?extensions=com.intellij.copyPastePostProcessor) | [`CopyPastePostProcessor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/CopyPastePostProcessor.java) | 
|  | [com.intellij.copyPastePreProcessor](https://jb.gg/ipe?extensions=com.intellij.copyPastePreProcessor) | [`CopyPastePreProcessor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/CopyPastePreProcessor.java) | 
|  | [com.intellij.customPasteProvider](https://jb.gg/ipe?extensions=com.intellij.customPasteProvider) | [`PasteProvider`](upsource:///platform/platform-api/src/com/intellij/ide/PasteProvider.java) | 
|  | [com.intellij.editor.backspaceModeOverride](https://jb.gg/ipe?extensions=com.intellij.editor.backspaceModeOverride) | [`BackspaceModeOverride`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/BackspaceModeOverride.java) | 
|  | [com.intellij.enterBetweenBracesDelegate](https://jb.gg/ipe?extensions=com.intellij.enterBetweenBracesDelegate) | [`EnterBetweenBracesDelegate`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/enter/EnterBetweenBracesDelegate.java) | 
|  | [com.intellij.enterHandlerDelegate](https://jb.gg/ipe?extensions=com.intellij.enterHandlerDelegate) | [`EnterHandlerDelegate`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/enter/EnterHandlerDelegate.java) | 
|  | [com.intellij.extendWordSelectionHandler](https://jb.gg/ipe?extensions=com.intellij.extendWordSelectionHandler) | [`ExtendWordSelectionHandler`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/ExtendWordSelectionHandler.java) | 
|  | [com.intellij.flipCommaIntention.flipper](https://jb.gg/ipe?extensions=com.intellij.flipCommaIntention.flipper) | [`Flipper`](upsource:///platform/lang-impl/src/com/intellij/openapi/editor/actions/FlipCommaIntention.java) | 
|  | [com.intellij.generalEditorOptionsExtension](https://jb.gg/ipe?extensions=com.intellij.generalEditorOptionsExtension) | [`UnnamedConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/UnnamedConfigurable.java) | 
|  | [com.intellij.joinLinesHandler](https://jb.gg/ipe?extensions=com.intellij.joinLinesHandler) | [`JoinLinesHandlerDelegate`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/JoinLinesHandlerDelegate.java) | 
|  | [com.intellij.lang.emacs](https://jb.gg/ipe?extensions=com.intellij.lang.emacs) | [`EmacsProcessingHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/emacs/EmacsProcessingHandler.java) | 
|  | [com.intellij.lang.quoteHandler](https://jb.gg/ipe?extensions=com.intellij.lang.quoteHandler) | [`QuoteHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/QuoteHandler.java) | 
|  | [com.intellij.lang.smartEnterProcessor](https://jb.gg/ipe?extensions=com.intellij.lang.smartEnterProcessor) | [`SmartEnterProcessor`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/smartEnter/SmartEnterProcessor.java) | 
|  | [com.intellij.moveLeftRightHandler](https://jb.gg/ipe?extensions=com.intellij.moveLeftRightHandler) | [`MoveElementLeftRightHandler`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/moveLeftRight/MoveElementLeftRightHandler.java) | 
|  | [com.intellij.preserveIndentOnPaste](https://jb.gg/ipe?extensions=com.intellij.preserveIndentOnPaste) | `n/a` | 
|  | [com.intellij.quoteHandler](https://jb.gg/ipe?extensions=com.intellij.quoteHandler) | [`QuoteHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/QuoteHandler.java) | 
|  | [com.intellij.selectionDequotingFilter](https://jb.gg/ipe?extensions=com.intellij.selectionDequotingFilter) | [~~`DequotingFilter`~~](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/SelectionQuotingTypedHandler.java) | 
|  | [com.intellij.selectionUnquotingFilter](https://jb.gg/ipe?extensions=com.intellij.selectionUnquotingFilter) | [`UnquotingFilter`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/editorActions/SelectionQuotingTypedHandler.java) | 
|  | [com.intellij.statementUpDownMover](https://jb.gg/ipe?extensions=com.intellij.statementUpDownMover) | [`StatementUpDownMover`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/moveUpDown/StatementUpDownMover.java) | 
|  | [com.intellij.typedHandler](https://jb.gg/ipe?extensions=com.intellij.typedHandler) | [`TypedHandlerDelegate`](upsource:///platform/lang-api/src/com/intellij/codeInsight/editorActions/TypedHandlerDelegate.java) | 
|  | [com.intellij.wordBoundaryFilter](https://jb.gg/ipe?extensions=com.intellij.wordBoundaryFilter) | [`WordBoundaryFilter`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/actions/WordBoundaryFilter.java) | 

## [ExternalSystemExtensionPoints.xml](upsource:///platform/external-system-impl/resources/META-INF/ExternalSystemExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalExecutionAware](https://jb.gg/ipe?extensions=com.intellij.externalExecutionAware) | [`ExternalSystemExecutionAware`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/execution/ExternalSystemExecutionAware.kt) | 
|  | [com.intellij.externalIconProvider](https://jb.gg/ipe?extensions=com.intellij.externalIconProvider) | [`ExternalSystemIconProvider`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/ui/ExternalSystemIconProvider.kt) | 
|  | [com.intellij.externalProjectDataService](https://jb.gg/ipe?extensions=com.intellij.externalProjectDataService) | [`ProjectDataService`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/manage/ProjectDataService.java) | 
|  | [com.intellij.externalProjectStructureCustomizer](https://jb.gg/ipe?extensions=com.intellij.externalProjectStructureCustomizer) | [`ExternalProjectStructureCustomizer`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/importing/ExternalProjectStructureCustomizer.java) | 
|  | [com.intellij.externalProjectWatcherContributor](https://jb.gg/ipe?extensions=com.intellij.externalProjectWatcherContributor) | [`Contributor`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/project/autoimport/ExternalSystemProjectsWatcherImpl.java) | 
|  | [com.intellij.externalSystem.beforeRunTaskImporter](https://jb.gg/ipe?extensions=com.intellij.externalSystem.beforeRunTaskImporter) | [`BeforeRunTaskImporter`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/settings/BeforeRunTaskImporter.java) | 
|  | [com.intellij.externalSystem.debuggerBackend](https://jb.gg/ipe?extensions=com.intellij.externalSystem.debuggerBackend) | [`DebuggerBackendExtension`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/debugger/DebuggerBackendExtension.java) | 
|  | [com.intellij.externalSystem.facetConfigurationImporter](https://jb.gg/ipe?extensions=com.intellij.externalSystem.facetConfigurationImporter) | [`FacetConfigurationImporter`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/settings/FacetConfigurationImporter.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystem.modifiableModelsProvider](https://jb.gg/ipe?extensions=com.intellij.externalSystem.modifiableModelsProvider) | [`ModifiableModelsProviderExtension`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/ModifiableModelsProviderExtension.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystem.moduleDataServiceExtension](https://jb.gg/ipe?extensions=com.intellij.externalSystem.moduleDataServiceExtension) | [`ModuleDataServiceExtension`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/project/manage/ModuleDataServiceExtension.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystem.runConfigurationExtension](https://jb.gg/ipe?extensions=com.intellij.externalSystem.runConfigurationExtension) | [`ExternalSystemRunConfigurationExtension`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/execution/ExternalSystemRunConfigurationExtension.java) | 
|  | [com.intellij.externalSystem.runConfigurationImporter](https://jb.gg/ipe?extensions=com.intellij.externalSystem.runConfigurationImporter) | [`RunConfigurationImporter`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/settings/RunConfigurationImporter.java) | 
|  | [com.intellij.externalSystemConfigLocator](https://jb.gg/ipe?extensions=com.intellij.externalSystemConfigLocator) | [`ExternalSystemConfigLocator`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/settings/ExternalSystemConfigLocator.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystemConfigurationHandler](https://jb.gg/ipe?extensions=com.intellij.externalSystemConfigurationHandler) | [`ConfigurationHandler`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/service/project/settings/ConfigurationHandler.java) | 
|  | [com.intellij.externalSystemExecutionConsoleManager](https://jb.gg/ipe?extensions=com.intellij.externalSystemExecutionConsoleManager) | [`ExternalSystemExecutionConsoleManager`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/execution/ExternalSystemExecutionConsoleManager.java) | 
|  | [com.intellij.externalSystemKeymapProvider](https://jb.gg/ipe?extensions=com.intellij.externalSystemKeymapProvider) | [`ActionsProvider`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/project/manage/ExternalSystemKeymapExtension.java) | 
|  | [com.intellij.externalSystemManager](https://jb.gg/ipe?extensions=com.intellij.externalSystemManager) | [`ExternalSystemManager`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/ExternalSystemManager.java) | 
|  | [com.intellij.externalSystemNotificationExtension](https://jb.gg/ipe?extensions=com.intellij.externalSystemNotificationExtension) | [`ExternalSystemNotificationExtension`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/notification/ExternalSystemNotificationExtension.java) | 
|  | [com.intellij.externalSystemOutputDispatcher](https://jb.gg/ipe?extensions=com.intellij.externalSystemOutputDispatcher) | [`ExternalSystemOutputDispatcherFactory`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/execution/ExternalSystemEventDispatcher.kt) | 
|  | [com.intellij.externalSystemOutputParserProvider](https://jb.gg/ipe?extensions=com.intellij.externalSystemOutputParserProvider) | [`ExternalSystemOutputParserProvider`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/execution/ExternalSystemOutputParserProvider.java) | 
|  | [com.intellij.externalSystemSettingsListener](https://jb.gg/ipe?extensions=com.intellij.externalSystemSettingsListener) | [`ExternalSystemSettingsListenerEx`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/settings/ExternalSystemSettingsListenerEx.kt) | 
|  | [com.intellij.externalSystemTaskNotificationListener](https://jb.gg/ipe?extensions=com.intellij.externalSystemTaskNotificationListener) | [`ExternalSystemTaskNotificationListener`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/model/task/ExternalSystemTaskNotificationListener.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystemUnlinkedProjectAware](https://jb.gg/ipe?extensions=com.intellij.externalSystemUnlinkedProjectAware) | [`ExternalSystemUnlinkedProjectAware`](upsource:///platform/external-system-api/src/com/intellij/openapi/externalSystem/autolink/ExternalSystemUnlinkedProjectAware.kt) | 
|  | [com.intellij.externalSystemViewContributor](https://jb.gg/ipe?extensions=com.intellij.externalSystemViewContributor) | [`ExternalSystemViewContributor`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/view/ExternalSystemViewContributor.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalSystemWorkspaceContributor](https://jb.gg/ipe?extensions=com.intellij.externalSystemWorkspaceContributor) | [`Contributor`](upsource:///platform/external-system-impl/src/com/intellij/openapi/externalSystem/service/project/ExternalProjectsWorkspaceImpl.java) | 

## [FormatterExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/FormatterExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.codeStyleSettingsModifier](https://jb.gg/ipe?extensions=com.intellij.codeStyleSettingsModifier) | [`CodeStyleSettingsModifier`](upsource:///platform/code-style-api/src/com/intellij/psi/codeStyle/modifier/CodeStyleSettingsModifier.java) | 
|  | [com.intellij.disabledIndentRangesProvider](https://jb.gg/ipe?extensions=com.intellij.disabledIndentRangesProvider) | [`DisabledIndentRangesProvider`](upsource:///platform/code-style-impl/src/com/intellij/psi/impl/source/DisabledIndentRangesProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.externalFormatProcessor](https://jb.gg/ipe?extensions=com.intellij.externalFormatProcessor) | [`ExternalFormatProcessor`](upsource:///platform/code-style-impl/src/com/intellij/psi/codeStyle/ExternalFormatProcessor.java) | 
|  | [com.intellij.fileCodeStyleProvider](https://jb.gg/ipe?extensions=com.intellij.fileCodeStyleProvider) | [`FileCodeStyleProvider`](upsource:///platform/code-style-api/src/com/intellij/psi/codeStyle/FileCodeStyleProvider.java) | 
|  | [com.intellij.fileIndentOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.fileIndentOptionsProvider) | [`FileIndentOptionsProvider`](upsource:///platform/code-style-api/src/com/intellij/psi/codeStyle/FileIndentOptionsProvider.java) | 
|  | [com.intellij.fileTypeIndentOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.fileTypeIndentOptionsProvider) | [`FileTypeIndentOptionsProvider`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/FileTypeIndentOptionsProvider.java) | 
|  | [com.intellij.lang.formatter](https://jb.gg/ipe?extensions=com.intellij.lang.formatter) | [`FormattingModelBuilder`](upsource:///platform/code-style-api/src/com/intellij/formatting/FormattingModelBuilder.java) | 
|  | [com.intellij.lang.formatter.newLineIndentMarkerProvider](https://jb.gg/ipe?extensions=com.intellij.lang.formatter.newLineIndentMarkerProvider) | [`NewLineIndentMarkerProvider`](upsource:///platform/code-style-impl/src/com/intellij/psi/impl/source/codeStyle/NewLineIndentMarkerProvider.java) | 
|  | [com.intellij.lang.formatter.restriction](https://jb.gg/ipe?extensions=com.intellij.lang.formatter.restriction) | [`LanguageFormattingRestriction`](upsource:///platform/code-style-api/src/com/intellij/lang/LanguageFormattingRestriction.java) | 
|  | [com.intellij.lang.formatting.extractor](https://jb.gg/ipe?extensions=com.intellij.lang.formatting.extractor) | [`LangCodeStyleExtractor`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/extractor/differ/LangCodeStyleExtractor.java) | 
|  | [com.intellij.lang.importOptimizer](https://jb.gg/ipe?extensions=com.intellij.lang.importOptimizer) | [`ImportOptimizer`](upsource:///platform/lang-api/src/com/intellij/lang/ImportOptimizer.java) | 
|  | [com.intellij.lang.indentStrategy](https://jb.gg/ipe?extensions=com.intellij.lang.indentStrategy) | [`IndentStrategy`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/IndentStrategy.java) | 
|  | [com.intellij.lang.lineWrapStrategy](https://jb.gg/ipe?extensions=com.intellij.lang.lineWrapStrategy) | [`LineWrapPositionStrategy`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/LineWrapPositionStrategy.java) | 
|  | [com.intellij.lang.rearranger](https://jb.gg/ipe?extensions=com.intellij.lang.rearranger) | [`Rearranger`](upsource:///platform/code-style-api/src/com/intellij/psi/codeStyle/arrangement/Rearranger.java) | 
|  | [com.intellij.lang.whiteSpaceFormattingStrategy](https://jb.gg/ipe?extensions=com.intellij.lang.whiteSpaceFormattingStrategy) | [`WhiteSpaceFormattingStrategy`](upsource:///platform/code-style-impl/src/com/intellij/psi/formatter/WhiteSpaceFormattingStrategy.java) | 
|  | [com.intellij.langCodeStyleSettingsProvider](https://jb.gg/ipe?extensions=com.intellij.langCodeStyleSettingsProvider) | [`LanguageCodeStyleSettingsProvider`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/LanguageCodeStyleSettingsProvider.java) | 
|  | [com.intellij.lineIndentProvider](https://jb.gg/ipe?extensions=com.intellij.lineIndentProvider) | [`LineIndentProvider`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/lineIndent/LineIndentProvider.java) | 
|  | [com.intellij.postFormatProcessor](https://jb.gg/ipe?extensions=com.intellij.postFormatProcessor) | [`PostFormatProcessor`](upsource:///platform/code-style-impl/src/com/intellij/psi/impl/source/codeStyle/PostFormatProcessor.java) | 
|  | [com.intellij.preFormatProcessor](https://jb.gg/ipe?extensions=com.intellij.preFormatProcessor) | [`PreFormatProcessor`](upsource:///platform/code-style-impl/src/com/intellij/psi/impl/source/codeStyle/PreFormatProcessor.java) | 
|  | [com.intellij.predefinedCodeStyle](https://jb.gg/ipe?extensions=com.intellij.predefinedCodeStyle) | [`PredefinedCodeStyle`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/PredefinedCodeStyle.java) | 
|  | [com.intellij.rearranger.ui](https://jb.gg/ipe?extensions=com.intellij.rearranger.ui) | [`Factory`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/arrangement/std/ArrangementUiComponent.java) | 

## [Git4Idea](upsource:///plugins/git4idea/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [Git4Idea.GitCheckinExplicitMovementProvider](https://jb.gg/ipe?extensions=Git4Idea.GitCheckinExplicitMovementProvider) | [`GitCheckinExplicitMovementProvider`](upsource:///plugins/git4idea/src/git4idea/checkin/GitCheckinExplicitMovementProvider.java) | 
|  | [Git4Idea.GitHttpAuthDataProvider](https://jb.gg/ipe?extensions=Git4Idea.GitHttpAuthDataProvider) | [`GitHttpAuthDataProvider`](upsource:///plugins/git4idea/src/git4idea/remote/GitHttpAuthDataProvider.java) | 
|  | [Git4Idea.gitFetchHandler](https://jb.gg/ipe?extensions=Git4Idea.gitFetchHandler) | [`GitFetchHandler`](upsource:///plugins/git4idea/src/git4idea/fetch/GitFetchHandler.kt) | 
|  | [Git4Idea.gitProtectedBranchProvider](https://jb.gg/ipe?extensions=Git4Idea.gitProtectedBranchProvider) | [`GitProtectedBranchProvider`](upsource:///plugins/git4idea/src/git4idea/config/GitProtectedBranchProvider.kt) | 
|  | [Git4Idea.gitRepositoryHostingService](https://jb.gg/ipe?extensions=Git4Idea.gitRepositoryHostingService) | [`GitRepositoryHostingService`](upsource:///plugins/git4idea/src/git4idea/remote/GitRepositoryHostingService.java) | 

## [google-app-engine-plugin.xml](upsource:///plugins/google-app-engine/resources/META-INF/google-app-engine-plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.appengine.forbiddenCodeHandler](https://jb.gg/ipe?extensions=com.intellij.appengine.forbiddenCodeHandler) | [`AppEngineForbiddenCodeHandler`](upsource:///plugins/google-app-engine/source/com/intellij/appengine/inspections/AppEngineForbiddenCodeHandler.java) | 

## [gradle-groovy-integration.xml](upsource:///plugins/gradle/java/resources/META-INF/gradle-groovy-integration.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.plugins.gradle.pluginDescriptions](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.pluginDescriptions) | [`GradlePluginDescriptionsExtension`](upsource:///plugins/gradle/java/src/codeInsight/GradlePluginDescriptionsExtension.java) | 
|  | [org.jetbrains.plugins.gradle.resolve.contributor](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.resolve.contributor) | [`GradleMethodContextContributor`](upsource:///plugins/gradle/java/src/service/resolve/GradleMethodContextContributor.java) | 

## [Indexing.xml](upsource:///platform/indexing-api/resources/META-INF/Indexing.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.definitionsSearch](https://jb.gg/ipe?extensions=com.intellij.definitionsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.fileBasedIndex](https://jb.gg/ipe?extensions=com.intellij.fileBasedIndex) | [`FileBasedIndexExtension`](upsource:///platform/indexing-api/src/com/intellij/util/indexing/FileBasedIndexExtension.java) | 
|  | [com.intellij.fileBasedIndexInfrastructureExtension](https://jb.gg/ipe?extensions=com.intellij.fileBasedIndexInfrastructureExtension) | [`FileBasedIndexInfrastructureExtension`](upsource:///platform/lang-impl/src/com/intellij/util/indexing/FileBasedIndexInfrastructureExtension.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.findModelExtension](https://jb.gg/ipe?extensions=com.intellij.findModelExtension) | [`FindModelExtension`](upsource:///platform/indexing-api/src/com/intellij/find/FindModelExtension.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.indexableFilesContributor](https://jb.gg/ipe?extensions=com.intellij.indexableFilesContributor) | [`IndexableFilesContributor`](upsource:///platform/indexing-api/src/com/intellij/util/indexing/roots/IndexableFilesContributor.java) | 
|  | [com.intellij.indexedRootsProvider](https://jb.gg/ipe?extensions=com.intellij.indexedRootsProvider) | [`IndexableSetContributor`](upsource:///platform/indexing-api/src/com/intellij/util/indexing/IndexableSetContributor.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.indexingFlavor](https://jb.gg/ipe?extensions=com.intellij.indexingFlavor) | [`FileIndexingFlavorProvider`](upsource:///platform/core-api/src/com/intellij/util/indexing/flavor/FileIndexingFlavorProvider.java) | 
|  | [com.intellij.projectIndexingHistoryListener](https://jb.gg/ipe?extensions=com.intellij.projectIndexingHistoryListener) | [`ProjectIndexingHistoryListener`](upsource:///platform/lang-impl/src/com/intellij/util/indexing/diagnostic/IndexDiagnosticDumper.kt) | 
|  | [com.intellij.referencesSearch](https://jb.gg/ipe?extensions=com.intellij.referencesSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.stubIndex](https://jb.gg/ipe?extensions=com.intellij.stubIndex) | [`StubIndexExtension`](upsource:///platform/indexing-api/src/com/intellij/psi/stubs/StubIndexExtension.java) | 

## [Inspect.xml](upsource:///platform/inspect/resources/META-INF/Inspect.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.inspectResultsConsumer](https://jb.gg/ipe?extensions=com.intellij.inspectResultsConsumer) | [`InspectResultsConsumer`](upsource:///platform/inspect/src/com/intellij/codeInspection/InspectResultsConsumer.java) | 

## [InspectionGadgets.xml](upsource:///plugins/InspectionGadgets/src/META-INF/InspectionGadgets.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.implicit.resource.closer](https://jb.gg/ipe?extensions=com.intellij.implicit.resource.closer) | [`ImplicitResourceCloser`](upsource:///plugins/InspectionGadgets/InspectionGadgetsAnalysis/src/com/intellij/codeInspection/resources/ImplicitResourceCloser.java) | 
|  | [com.intellij.naming.convention.class](https://jb.gg/ipe?extensions=com.intellij.naming.convention.class) | [`NamingConvention`](upsource:///platform/lang-impl/src/com/intellij/codeInspection/naming/NamingConvention.java) | 
|  | [com.intellij.naming.convention.field](https://jb.gg/ipe?extensions=com.intellij.naming.convention.field) | [`NamingConvention`](upsource:///platform/lang-impl/src/com/intellij/codeInspection/naming/NamingConvention.java) | 
|  | [com.intellij.naming.convention.method](https://jb.gg/ipe?extensions=com.intellij.naming.convention.method) | [`NamingConvention`](upsource:///platform/lang-impl/src/com/intellij/codeInspection/naming/NamingConvention.java) | 

## [JavaAnalysisPlugin.xml](upsource:///java/java-analysis-impl/src/META-INF/JavaAnalysisPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.allowedApiFilter](https://jb.gg/ipe?extensions=com.intellij.allowedApiFilter) | [`AllowedApiFilterExtension`](upsource:///java/java-analysis-impl/src/com/intellij/psi/impl/AllowedApiFilterExtension.java) | 
|  | [com.intellij.canBeFinal](https://jb.gg/ipe?extensions=com.intellij.canBeFinal) | [`CanBeFinalHandler`](upsource:///java/java-analysis-impl/src/com/intellij/codeInspection/canBeFinal/CanBeFinalHandler.java) | 
|  | [com.intellij.codeInsight.changeVariableTypeQuickFixProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.changeVariableTypeQuickFixProvider) | [`ChangeVariableTypeQuickFixProvider`](upsource:///java/java-analysis-api/src/com/intellij/codeInsight/quickfix/ChangeVariableTypeQuickFixProvider.java) | 
|  | [com.intellij.codeInsight.implicitSubclassProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.implicitSubclassProvider) | [`ImplicitSubclassProvider`](upsource:///java/java-analysis-impl/src/com/intellij/codeInspection/inheritance/ImplicitSubclassProvider.kt) | 
|  | [com.intellij.deadCode](https://jb.gg/ipe?extensions=com.intellij.deadCode) | [`EntryPoint`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/reference/EntryPoint.java) | 
|  | [com.intellij.java.error.fix](https://jb.gg/ipe?extensions=com.intellij.java.error.fix) | [`IntentionAction`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/intention/IntentionAction.java) | 
|  | [com.intellij.lang.jvm.actions.jvmElementActionsFactory](https://jb.gg/ipe?extensions=com.intellij.lang.jvm.actions.jvmElementActionsFactory) | [`JvmElementActionsFactory`](upsource:///java/java-analysis-api/src/com/intellij/lang/jvm/actions/JvmElementActionsFactory.kt) | 
|  | [com.intellij.visibility](https://jb.gg/ipe?extensions=com.intellij.visibility) | [`VisibilityExtension`](upsource:///platform/analysis-impl/src/com/intellij/codeInspection/visibility/VisibilityExtension.java) | 

## [JavaIndexingPlugin.xml](upsource:///java/java-indexing-impl/src/META-INF/JavaIndexingPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.allClassesSearch](https://jb.gg/ipe?extensions=com.intellij.allClassesSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.allOverridingMethodsSearch](https://jb.gg/ipe?extensions=com.intellij.allOverridingMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.annotatedElementsSearch](https://jb.gg/ipe?extensions=com.intellij.annotatedElementsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.annotatedPackagesSearch](https://jb.gg/ipe?extensions=com.intellij.annotatedPackagesSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.classInheritorsSearch](https://jb.gg/ipe?extensions=com.intellij.classInheritorsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.classesWithAnnotatedMembersSearch](https://jb.gg/ipe?extensions=com.intellij.classesWithAnnotatedMembersSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.customPropertyScopeProvider](https://jb.gg/ipe?extensions=com.intellij.customPropertyScopeProvider) | [`CustomPropertyScopeProvider`](upsource:///java/java-indexing-impl/src/com/intellij/psi/impl/search/CustomPropertyScopeProvider.java) | 
|  | [com.intellij.directClassInheritorsSearch](https://jb.gg/ipe?extensions=com.intellij.directClassInheritorsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.functionalExpressionSearch](https://jb.gg/ipe?extensions=com.intellij.functionalExpressionSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.implicitToStringSearch](https://jb.gg/ipe?extensions=com.intellij.implicitToStringSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.java.shortNamesCache](https://jb.gg/ipe?extensions=com.intellij.java.shortNamesCache) | [`PsiShortNamesCache`](upsource:///java/java-indexing-api/src/com/intellij/psi/search/PsiShortNamesCache.java) | 
|  | [com.intellij.methodReferencesSearch](https://jb.gg/ipe?extensions=com.intellij.methodReferencesSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.overridingMethodsSearch](https://jb.gg/ipe?extensions=com.intellij.overridingMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 

## [JavaPlugin.xml](upsource:///java/java-impl/src/META-INF/JavaPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.OrderRootTypeUI](https://jb.gg/ipe?extensions=com.intellij.OrderRootTypeUI) | [`OrderRootTypeUIFactory`](upsource:///platform/lang-api/src/com/intellij/openapi/roots/ui/OrderRootTypeUIFactory.java) | 
|  | [com.intellij.attachSourcesProvider](https://jb.gg/ipe?extensions=com.intellij.attachSourcesProvider) | [`AttachSourcesProvider`](upsource:///java/openapi/src/com/intellij/codeInsight/AttachSourcesProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.buildProcess.parametersProvider](https://jb.gg/ipe?extensions=com.intellij.buildProcess.parametersProvider) | [`BuildProcessParametersProvider`](upsource:///java/compiler/impl/src/com/intellij/compiler/server/BuildProcessParametersProvider.java) | 
|  | [com.intellij.canBeEmpty](https://jb.gg/ipe?extensions=com.intellij.canBeEmpty) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.codeInsight.createFieldFromUsageHelper](https://jb.gg/ipe?extensions=com.intellij.codeInsight.createFieldFromUsageHelper) | [`CreateFieldFromUsageHelper`](upsource:///java/java-impl/src/com/intellij/codeInsight/daemon/impl/quickfix/CreateFieldFromUsageHelper.java) | 
|  | [com.intellij.codeInsight.externalLibraryResolver](https://jb.gg/ipe?extensions=com.intellij.codeInsight.externalLibraryResolver) | [`ExternalLibraryResolver`](upsource:///java/java-impl/src/com/intellij/codeInsight/daemon/quickFix/ExternalLibraryResolver.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compilableFileTypesProvider](https://jb.gg/ipe?extensions=com.intellij.compilableFileTypesProvider) | [`CompilableFileTypesProvider`](upsource:///java/compiler/openapi/src/com/intellij/openapi/compiler/CompilableFileTypesProvider.java) | 
|  | [com.intellij.compileServer.plugin](https://jb.gg/ipe?extensions=com.intellij.compileServer.plugin) | `n/a` | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compiler](https://jb.gg/ipe?extensions=com.intellij.compiler) | [~~`Compiler`~~](upsource:///java/compiler/openapi/src/com/intellij/openapi/compiler/Compiler.java) | 
|  | [com.intellij.compiler.buildTargetScopeProvider](https://jb.gg/ipe?extensions=com.intellij.compiler.buildTargetScopeProvider) | [`BuildTargetScopeProvider`](upsource:///java/compiler/impl/src/com/intellij/compiler/impl/BuildTargetScopeProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compiler.inspectionValidator](https://jb.gg/ipe?extensions=com.intellij.compiler.inspectionValidator) | [`InspectionValidator`](upsource:///java/compiler/openapi/src/com/intellij/openapi/compiler/util/InspectionValidator.java) | 
|  | [com.intellij.compiler.optionsManager](https://jb.gg/ipe?extensions=com.intellij.compiler.optionsManager) | [`CompilerOptionsFilter`](upsource:///java/compiler/impl/src/com/intellij/compiler/options/CompilerOptionsFilter.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compiler.task](https://jb.gg/ipe?extensions=com.intellij.compiler.task) | [`CompileTask`](upsource:///java/compiler/openapi/src/com/intellij/openapi/compiler/CompileTask.java) | 
|  | [com.intellij.compiler.updateResourcesBuildContributor](https://jb.gg/ipe?extensions=com.intellij.compiler.updateResourcesBuildContributor) | [`UpdateResourcesBuildContributor`](upsource:///java/compiler/impl/src/com/intellij/compiler/impl/UpdateResourcesBuildContributor.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compilerFactory](https://jb.gg/ipe?extensions=com.intellij.compilerFactory) | [~~`CompilerFactory`~~](upsource:///java/compiler/openapi/src/com/intellij/openapi/compiler/CompilerFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.compilerSettingsFactory](https://jb.gg/ipe?extensions=com.intellij.compilerSettingsFactory) | [~~`CompilerSettingsFactory`~~](upsource:///java/compiler/openapi/src/com/intellij/compiler/CompilerSettingsFactory.java) | 
|  | [com.intellij.configuration.ModuleStructureExtension](https://jb.gg/ipe?extensions=com.intellij.configuration.ModuleStructureExtension) | [`ModuleStructureExtension`](upsource:///java/idea-ui/src/com/intellij/openapi/roots/ui/configuration/projectRoot/ModuleStructureExtension.java) | 
|  | [com.intellij.constructorBodyGenerator](https://jb.gg/ipe?extensions=com.intellij.constructorBodyGenerator) | [`ConstructorBodyGenerator`](upsource:///java/java-impl/src/com/intellij/codeInsight/generation/ConstructorBodyGenerator.java) | 
|  | [com.intellij.conversion.rule](https://jb.gg/ipe?extensions=com.intellij.conversion.rule) | [`TypeConversionRule`](upsource:///java/java-impl/src/com/intellij/refactoring/typeMigration/rules/TypeConversionRule.java) | 
|  | [com.intellij.debugger.asyncStackTraceProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.asyncStackTraceProvider) | [`AsyncStackTraceProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/engine/AsyncStackTraceProvider.java) | 
|  | [com.intellij.debugger.codeFragmentFactory](https://jb.gg/ipe?extensions=com.intellij.debugger.codeFragmentFactory) | [`CodeFragmentFactory`](upsource:///java/debugger/openapi/src/com/intellij/debugger/engine/evaluation/CodeFragmentFactory.java) | 
|  | [com.intellij.debugger.compoundRendererProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.compoundRendererProvider) | [`CompoundRendererProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/ui/tree/render/CompoundRendererProvider.java) | 
|  | [com.intellij.debugger.extraSteppingFilter](https://jb.gg/ipe?extensions=com.intellij.debugger.extraSteppingFilter) | [`ExtraSteppingFilter`](upsource:///java/debugger/impl/src/com/intellij/debugger/engine/ExtraSteppingFilter.java) | 
|  | [com.intellij.debugger.frameExtraVarsProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.frameExtraVarsProvider) | [`FrameExtraVariablesProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/engine/FrameExtraVariablesProvider.java) | 
|  | [com.intellij.debugger.javaBreakpointHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.debugger.javaBreakpointHandlerFactory) | [`JavaBreakpointHandlerFactory`](upsource:///java/debugger/impl/src/com/intellij/debugger/engine/JavaBreakpointHandlerFactory.java) | 
|  | [com.intellij.debugger.javaDebugAware](https://jb.gg/ipe?extensions=com.intellij.debugger.javaDebugAware) | [`JavaDebugAware`](upsource:///java/debugger/openapi/src/com/intellij/debugger/engine/JavaDebugAware.java) | 
|  | [com.intellij.debugger.jvmSmartStepIntoHandler](https://jb.gg/ipe?extensions=com.intellij.debugger.jvmSmartStepIntoHandler) | [`JvmSmartStepIntoHandler`](upsource:///java/debugger/impl/src/com/intellij/debugger/actions/JvmSmartStepIntoHandler.java) | 
|  | [com.intellij.debugger.jvmSteppingCommandProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.jvmSteppingCommandProvider) | [`JvmSteppingCommandProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/impl/JvmSteppingCommandProvider.java) | 
|  | [com.intellij.debugger.nodeNameAdjuster](https://jb.gg/ipe?extensions=com.intellij.debugger.nodeNameAdjuster) | [`NodeDescriptorNameAdjuster`](upsource:///java/debugger/openapi/src/com/intellij/debugger/ui/tree/NodeDescriptorNameAdjuster.java) | 
|  | [com.intellij.debugger.nodeRenderer](https://jb.gg/ipe?extensions=com.intellij.debugger.nodeRenderer) | [`NodeRenderer`](upsource:///java/debugger/impl/src/com/intellij/debugger/ui/tree/render/NodeRenderer.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.debugger.positionManagerFactory](https://jb.gg/ipe?extensions=com.intellij.debugger.positionManagerFactory) | [`PositionManagerFactory`](upsource:///java/debugger/openapi/src/com/intellij/debugger/PositionManagerFactory.java) | 
|  | [com.intellij.debugger.simplePropertyGetterProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.simplePropertyGetterProvider) | [`SimplePropertyGetterProvider`](upsource:///java/debugger/openapi/src/com/intellij/debugger/engine/SimplePropertyGetterProvider.java) | 
|  | [com.intellij.debugger.sourcePositionHighlighter](https://jb.gg/ipe?extensions=com.intellij.debugger.sourcePositionHighlighter) | [`SourcePositionHighlighter`](upsource:///java/debugger/openapi/src/com/intellij/debugger/engine/SourcePositionHighlighter.java) | 
|  | [com.intellij.debugger.sourcePositionProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.sourcePositionProvider) | [`SourcePositionProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/engine/SourcePositionProvider.java) | 
|  | [com.intellij.debugger.syntheticProvider](https://jb.gg/ipe?extensions=com.intellij.debugger.syntheticProvider) | [`SyntheticTypeComponentProvider`](upsource:///java/debugger/openapi/src/com/intellij/debugger/engine/SyntheticTypeComponentProvider.java) | 
|  | [com.intellij.debuggerClassFilterProvider](https://jb.gg/ipe?extensions=com.intellij.debuggerClassFilterProvider) | [`DebuggerClassFilterProvider`](upsource:///java/openapi/src/com/intellij/ui/classFilter/DebuggerClassFilterProvider.java) | 
|  | [com.intellij.debuggerEditorTextProvider](https://jb.gg/ipe?extensions=com.intellij.debuggerEditorTextProvider) | [`EditorTextProvider`](upsource:///java/debugger/impl/src/com/intellij/debugger/impl/EditorTextProvider.java) | 
|  | [com.intellij.documentationDelegateProvider](https://jb.gg/ipe?extensions=com.intellij.documentationDelegateProvider) | [`DocumentationDelegateProvider`](upsource:///java/java-impl/src/com/intellij/codeInsight/javadoc/DocumentationDelegateProvider.java) | 
|  | [com.intellij.encapsulateFields.Helper](https://jb.gg/ipe?extensions=com.intellij.encapsulateFields.Helper) | [`EncapsulateFieldHelper`](upsource:///java/openapi/src/com/intellij/refactoring/encapsulateFields/EncapsulateFieldHelper.java) | 
|  | [com.intellij.exceptionFilter](https://jb.gg/ipe?extensions=com.intellij.exceptionFilter) | [`ExceptionFilterFactory`](upsource:///java/execution/openapi/src/com/intellij/execution/filters/ExceptionFilterFactory.java) | 
|  | [com.intellij.externalAnnotationsArtifactsResolver](https://jb.gg/ipe?extensions=com.intellij.externalAnnotationsArtifactsResolver) | [`ExternalAnnotationsArtifactsResolver`](upsource:///java/java-impl/src/com/intellij/codeInsight/ExternalAnnotationsArtifactsResolver.java) | 
|  | [com.intellij.framework.type](https://jb.gg/ipe?extensions=com.intellij.framework.type) | [`FrameworkTypeEx`](upsource:///java/idea-ui/src/com/intellij/framework/FrameworkTypeEx.java) | 
|  | [com.intellij.frameworkSupport](https://jb.gg/ipe?extensions=com.intellij.frameworkSupport) | [`FrameworkSupportProvider`](upsource:///platform/lang-api/src/com/intellij/ide/util/frameworkSupport/FrameworkSupportProvider.java) | 
|  | [com.intellij.frameworkSupportCommunicator](https://jb.gg/ipe?extensions=com.intellij.frameworkSupportCommunicator) | [`FrameworkSupportCommunicator`](upsource:///java/idea-ui/src/com/intellij/ide/util/newProjectWizard/impl/FrameworkSupportCommunicator.java) | 
|  | [com.intellij.generateAccessorProvider](https://jb.gg/ipe?extensions=com.intellij.generateAccessorProvider) | [`NotNullFunction`](upsource:///platform/util-rt/src/com/intellij/util/NotNullFunction.java) | 
|  | [com.intellij.generation.toStringClassFilter](https://jb.gg/ipe?extensions=com.intellij.generation.toStringClassFilter) | [`GenerateToStringClassFilter`](upsource:///plugins/generate-tostring/src/org/jetbrains/generate/tostring/GenerateToStringClassFilter.java) | 
|  | [com.intellij.getterSetterProvider](https://jb.gg/ipe?extensions=com.intellij.getterSetterProvider) | [`GetterSetterPrototypeProvider`](upsource:///java/java-impl/src/com/intellij/codeInsight/generation/GetterSetterPrototypeProvider.java) | 
|  | [com.intellij.hierarchy.referenceProcessor](https://jb.gg/ipe?extensions=com.intellij.hierarchy.referenceProcessor) | [`CallReferenceProcessor`](upsource:///java/openapi/src/com/intellij/ide/hierarchy/call/CallReferenceProcessor.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.java.compiler](https://jb.gg/ipe?extensions=com.intellij.java.compiler) | [`BackendCompiler`](upsource:///java/compiler/impl/src/com/intellij/compiler/impl/javaCompiler/BackendCompiler.java) | 
|  | [com.intellij.java.externalAnnotation](https://jb.gg/ipe?extensions=com.intellij.java.externalAnnotation) | [`AnnotationProvider`](upsource:///java/java-impl/src/com/intellij/codeInsight/externalAnnotation/AnnotationProvider.java) | 
|  | [com.intellij.java.externalAnnotation.locationProvider](https://jb.gg/ipe?extensions=com.intellij.java.externalAnnotation.locationProvider) | [`AnnotationsLocationProvider`](upsource:///java/java-impl/src/com/intellij/codeInsight/externalAnnotation/location/AnnotationsLocationProvider.java) | 
|  | [com.intellij.java.inspection.bulkMethodInfo](https://jb.gg/ipe?extensions=com.intellij.java.inspection.bulkMethodInfo) | [`BulkMethodInfoProvider`](upsource:///java/java-impl/src/com/intellij/codeInspection/bulkOperation/BulkMethodInfoProvider.java) | 
|  | [com.intellij.java.programPatcher](https://jb.gg/ipe?extensions=com.intellij.java.programPatcher) | [`JavaProgramPatcher`](upsource:///java/execution/openapi/src/com/intellij/execution/runners/JavaProgramPatcher.java) | 
|  | [com.intellij.java.refactoring.chainCallExtractor](https://jb.gg/ipe?extensions=com.intellij.java.refactoring.chainCallExtractor) | [`ChainCallExtractor`](upsource:///java/java-impl/src/com/intellij/refactoring/chainCall/ChainCallExtractor.java) | 
|  | [com.intellij.javaDocNotNecessary](https://jb.gg/ipe?extensions=com.intellij.javaDocNotNecessary) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.javaExpressionSurrounder](https://jb.gg/ipe?extensions=com.intellij.javaExpressionSurrounder) | [`JavaExpressionSurrounder`](upsource:///java/openapi/src/com/intellij/codeInsight/generation/surroundWith/JavaExpressionSurrounder.java) | 
|  | [com.intellij.jreProvider](https://jb.gg/ipe?extensions=com.intellij.jreProvider) | [`JreProvider`](upsource:///java/execution/impl/src/com/intellij/execution/ui/JreProvider.java) | 
|  | [com.intellij.junitPatcher](https://jb.gg/ipe?extensions=com.intellij.junitPatcher) | [`JUnitPatcher`](upsource:///java/execution/openapi/src/com/intellij/execution/JUnitPatcher.java) | 
|  | [com.intellij.junitRecognizer](https://jb.gg/ipe?extensions=com.intellij.junitRecognizer) | [`JUnitRecognizer`](upsource:///java/execution/openapi/src/com/intellij/execution/JUnitRecognizer.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.jvm.exceptionFilter](https://jb.gg/ipe?extensions=com.intellij.jvm.exceptionFilter) | [`JvmExceptionOccurrenceFilter`](upsource:///java/execution/openapi/src/com/intellij/execution/filters/JvmExceptionOccurrenceFilter.java) | 
|  | [com.intellij.languageCompilerRefAdapter](https://jb.gg/ipe?extensions=com.intellij.languageCompilerRefAdapter) | [`LanguageCompilerRefAdapter`](upsource:///java/compiler/impl/src/com/intellij/compiler/backwardRefs/LanguageCompilerRefAdapter.java) | 
|  | [com.intellij.library.dependencyScopeSuggester](https://jb.gg/ipe?extensions=com.intellij.library.dependencyScopeSuggester) | [`LibraryDependencyScopeSuggester`](upsource:///java/java-impl/src/com/intellij/openapi/roots/LibraryDependencyScopeSuggester.java) | 
|  | [com.intellij.library.javaSourceRootDetector](https://jb.gg/ipe?extensions=com.intellij.library.javaSourceRootDetector) | [`RootDetector`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/libraries/ui/RootDetector.java) | 
|  | [com.intellij.methodImplementor](https://jb.gg/ipe?extensions=com.intellij.methodImplementor) | [`MethodImplementor`](upsource:///java/openapi/src/com/intellij/codeInsight/MethodImplementor.java) | 
|  | [com.intellij.moduleConfigurable](https://jb.gg/ipe?extensions=com.intellij.moduleConfigurable) | [`ModuleConfigurable`](upsource:///java/idea-ui/src/com/intellij/openapi/roots/ui/configuration/projectRoot/ModuleConfigurable.java) | 
|  | [com.intellij.overrideImplementsAnnotationsHandler](https://jb.gg/ipe?extensions=com.intellij.overrideImplementsAnnotationsHandler) | [`OverrideImplementsAnnotationsHandler`](upsource:///java/java-impl/src/com/intellij/codeInsight/generation/OverrideImplementsAnnotationsHandler.java) | 
|  | [com.intellij.packaging.artifactPropertiesProvider](https://jb.gg/ipe?extensions=com.intellij.packaging.artifactPropertiesProvider) | [`ArtifactPropertiesProvider`](upsource:///java/compiler/openapi/src/com/intellij/packaging/artifacts/ArtifactPropertiesProvider.java) | 
|  | [com.intellij.packaging.artifactType](https://jb.gg/ipe?extensions=com.intellij.packaging.artifactType) | [`ArtifactType`](upsource:///java/compiler/openapi/src/com/intellij/packaging/artifacts/ArtifactType.java) | 
|  | [com.intellij.packaging.elementType](https://jb.gg/ipe?extensions=com.intellij.packaging.elementType) | [`PackagingElementType`](upsource:///java/compiler/openapi/src/com/intellij/packaging/elements/PackagingElementType.java) | 
|  | [com.intellij.packaging.sourceItemFilter](https://jb.gg/ipe?extensions=com.intellij.packaging.sourceItemFilter) | [`PackagingSourceItemFilter`](upsource:///java/compiler/openapi/src/com/intellij/packaging/ui/PackagingSourceItemFilter.java) | 
|  | [com.intellij.packaging.sourceItemProvider](https://jb.gg/ipe?extensions=com.intellij.packaging.sourceItemProvider) | [`PackagingSourceItemsProvider`](upsource:///java/compiler/openapi/src/com/intellij/packaging/ui/PackagingSourceItemsProvider.java) | 
|  | [com.intellij.predefinedMigrationMapProvider](https://jb.gg/ipe?extensions=com.intellij.predefinedMigrationMapProvider) | [`PredefinedMigrationProvider`](upsource:///java/java-impl/src/com/intellij/refactoring/migration/PredefinedMigrationProvider.java) | 
|  | [com.intellij.projectImportBuilder](https://jb.gg/ipe?extensions=com.intellij.projectImportBuilder) | [`ProjectImportBuilder`](upsource:///java/idea-ui/src/com/intellij/projectImport/ProjectImportBuilder.java) | 
|  | [com.intellij.projectImportProvider](https://jb.gg/ipe?extensions=com.intellij.projectImportProvider) | [`ProjectImportProvider`](upsource:///java/idea-ui/src/com/intellij/projectImport/ProjectImportProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectModelModifier](https://jb.gg/ipe?extensions=com.intellij.projectModelModifier) | [`JavaProjectModelModifier`](upsource:///java/java-impl/src/com/intellij/openapi/roots/JavaProjectModelModifier.java) | 
|  | [com.intellij.projectStructureConfigurableFilter](https://jb.gg/ipe?extensions=com.intellij.projectStructureConfigurableFilter) | [`ProjectStructureConfigurableFilter`](upsource:///java/idea-ui/src/com/intellij/openapi/roots/ui/configuration/ProjectStructureConfigurableFilter.java) | 
|  | [com.intellij.projectStructureDetector](https://jb.gg/ipe?extensions=com.intellij.projectStructureDetector) | [`ProjectStructureDetector`](upsource:///java/idea-ui/src/com/intellij/ide/util/projectWizard/importSources/ProjectStructureDetector.java) | 
|  | [com.intellij.projectStructureValidator](https://jb.gg/ipe?extensions=com.intellij.projectStructureValidator) | [`ProjectStructureValidator`](upsource:///java/idea-ui/src/com/intellij/openapi/roots/ui/configuration/projectRoot/daemon/ProjectStructureValidator.java) | 
|  | [com.intellij.projectWizard.projectCategory](https://jb.gg/ipe?extensions=com.intellij.projectWizard.projectCategory) | [`ProjectCategory`](upsource:///java/idea-ui/src/com/intellij/ide/projectWizard/ProjectCategory.java) | 
|  | [com.intellij.refactoring.introduceParameterMethodUsagesProcessor](https://jb.gg/ipe?extensions=com.intellij.refactoring.introduceParameterMethodUsagesProcessor) | [`IntroduceParameterMethodUsagesProcessor`](upsource:///java/java-impl/src/com/intellij/refactoring/introduceParameter/IntroduceParameterMethodUsagesProcessor.java) | 
|  | [com.intellij.refactoring.moveAllClassesInFileHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveAllClassesInFileHandler) | [`MoveAllClassesInFileHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveClassesOrPackages/MoveAllClassesInFileHandler.java) | 
|  | [com.intellij.refactoring.moveClassHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveClassHandler) | [`MoveClassHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveClassesOrPackages/MoveClassHandler.java) | 
|  | [com.intellij.refactoring.moveClassToInnerHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveClassToInnerHandler) | [`MoveClassToInnerHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveClassesOrPackages/MoveClassToInnerHandler.java) | 
|  | [com.intellij.refactoring.moveInnerClassUsagesHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveInnerClassUsagesHandler) | [`MoveInnerClassUsagesHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveInner/MoveInnerClassUsagesHandler.java) | 
|  | [com.intellij.refactoring.moveInnerHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveInnerHandler) | [`MoveInnerHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveInner/MoveInnerHandler.java) | 
|  | [com.intellij.refactoring.moveMemberHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveMemberHandler) | [`MoveMemberHandler`](upsource:///java/java-impl/src/com/intellij/refactoring/move/moveMembers/MoveMemberHandler.java) | 
|  | [com.intellij.refactoring.overrideMethodProcessor](https://jb.gg/ipe?extensions=com.intellij.refactoring.overrideMethodProcessor) | [`OverrideMethodsProcessor`](upsource:///java/java-impl/src/com/intellij/refactoring/OverrideMethodsProcessor.java) | 
|  | [com.intellij.refactoring.pullUpHelperFactory](https://jb.gg/ipe?extensions=com.intellij.refactoring.pullUpHelperFactory) | [`PullUpHelperFactory`](upsource:///java/openapi/src/com/intellij/refactoring/memberPullUp/PullUpHelperFactory.java) | 
|  | [com.intellij.refactoring.safeDelete.JavaSafeDeleteDelegate](https://jb.gg/ipe?extensions=com.intellij.refactoring.safeDelete.JavaSafeDeleteDelegate) | [`JavaSafeDeleteDelegate`](upsource:///java/openapi/src/com/intellij/refactoring/safeDelete/JavaSafeDeleteDelegate.java) | 
|  | [com.intellij.repositoryLibrary](https://jb.gg/ipe?extensions=com.intellij.repositoryLibrary) | `n/a` | 
|  | [com.intellij.runConfigurationExtension](https://jb.gg/ipe?extensions=com.intellij.runConfigurationExtension) | [`RunConfigurationExtension`](upsource:///java/execution/impl/src/com/intellij/execution/RunConfigurationExtension.java) | 
|  | [com.intellij.safeDelete.importSearcher](https://jb.gg/ipe?extensions=com.intellij.safeDelete.importSearcher) | [`ImportSearcher`](upsource:///java/java-impl/src/com/intellij/refactoring/safeDelete/ImportSearcher.java) | 
|  | [com.intellij.sdkEditorAdditionalOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.sdkEditorAdditionalOptionsProvider) | [`SdkEditorAdditionalOptionsProvider`](upsource:///java/idea-ui/src/com/intellij/openapi/SdkEditorAdditionalOptionsProvider.java) | 
|  | [com.intellij.testGenerator](https://jb.gg/ipe?extensions=com.intellij.testGenerator) | [`TestGenerator`](upsource:///java/java-impl/src/com/intellij/testIntegration/createTest/TestGenerator.java) | 
|  | [com.intellij.unscrambleSupport](https://jb.gg/ipe?extensions=com.intellij.unscrambleSupport) | [`UnscrambleSupport`](upsource:///java/openapi/src/com/intellij/unscramble/UnscrambleSupport.java) | 
|  | [com.intellij.unusedDeclarationFixProvider](https://jb.gg/ipe?extensions=com.intellij.unusedDeclarationFixProvider) | [`UnusedDeclarationFixProvider`](upsource:///java/java-analysis-api/src/com/intellij/codeInspection/reference/UnusedDeclarationFixProvider.java) | 
|  | [com.intellij.variableTypeCalculator](https://jb.gg/ipe?extensions=com.intellij.variableTypeCalculator) | [`VariableTypeCalculator`](upsource:///java/java-impl/src/com/intellij/codeInsight/template/macro/VariableTypeCalculator.java) | 

## [JavaPsiPlugin.xml](upsource:///java/java-psi-impl/src/META-INF/JavaPsiPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.annotationSupport](https://jb.gg/ipe?extensions=com.intellij.annotationSupport) | [`PsiAnnotationSupport`](upsource:///java/java-psi-api/src/com/intellij/psi/PsiAnnotationSupport.java) | 
|  | [com.intellij.classTypePointerFactory](https://jb.gg/ipe?extensions=com.intellij.classTypePointerFactory) | [`ClassTypePointerFactory`](upsource:///java/java-psi-api/src/com/intellij/psi/ClassTypePointerFactory.java) | 
|  | [com.intellij.codeStyle.ReferenceAdjuster](https://jb.gg/ipe?extensions=com.intellij.codeStyle.ReferenceAdjuster) | [`ReferenceAdjuster`](upsource:///java/java-psi-api/src/com/intellij/psi/codeStyle/ReferenceAdjuster.java) | 
|  | [com.intellij.constantExpressionEvaluator](https://jb.gg/ipe?extensions=com.intellij.constantExpressionEvaluator) | [`ConstantExpressionEvaluator`](upsource:///java/java-psi-impl/src/com/intellij/psi/impl/ConstantExpressionEvaluator.java) | 
|  | [com.intellij.custom.exception.handler](https://jb.gg/ipe?extensions=com.intellij.custom.exception.handler) | [`CustomExceptionHandler`](upsource:///java/java-psi-impl/src/com/intellij/codeInsight/CustomExceptionHandler.java) | 
|  | [com.intellij.customJavadocTagProvider](https://jb.gg/ipe?extensions=com.intellij.customJavadocTagProvider) | [`CustomJavadocTagProvider`](upsource:///java/java-psi-api/src/com/intellij/psi/javadoc/CustomJavadocTagProvider.java) | 
|  | [com.intellij.deepestSuperMethodsSearch](https://jb.gg/ipe?extensions=com.intellij.deepestSuperMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.expressionConverter](https://jb.gg/ipe?extensions=com.intellij.expressionConverter) | [`ExpressionConverter`](upsource:///java/java-psi-impl/src/com/intellij/psi/impl/ExpressionConverter.java) | 
|  | [com.intellij.generation.topLevelFactory](https://jb.gg/ipe?extensions=com.intellij.generation.topLevelFactory) | [`JVMElementFactoryProvider`](upsource:///java/java-psi-api/src/com/intellij/psi/JVMElementFactoryProvider.java) | 
|  | [com.intellij.importFilter](https://jb.gg/ipe?extensions=com.intellij.importFilter) | [`ImportFilter`](upsource:///java/java-psi-api/src/com/intellij/codeInsight/ImportFilter.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.java.elementFinder](https://jb.gg/ipe?extensions=com.intellij.java.elementFinder) | [`PsiElementFinder`](upsource:///java/java-psi-api/src/com/intellij/psi/PsiElementFinder.java) | 
|  | [com.intellij.java.languageFeatureProvider](https://jb.gg/ipe?extensions=com.intellij.java.languageFeatureProvider) | [`LanguageFeatureProvider`](upsource:///java/java-psi-api/src/com/intellij/pom/java/LanguageFeatureProvider.java) | 
|  | [com.intellij.javaCompilerConfigurationProxy](https://jb.gg/ipe?extensions=com.intellij.javaCompilerConfigurationProxy) | [`JavaCompilerConfigurationProxy`](upsource:///java/java-psi-api/src/com/intellij/psi/JavaCompilerConfigurationProxy.java) | 
|  | [com.intellij.javaMainMethodProvider](https://jb.gg/ipe?extensions=com.intellij.javaMainMethodProvider) | [`JavaMainMethodProvider`](upsource:///java/java-psi-api/src/com/intellij/codeInsight/runner/JavaMainMethodProvider.java) | 
|  | [com.intellij.javaModuleSystem](https://jb.gg/ipe?extensions=com.intellij.javaModuleSystem) | [`JavaModuleSystem`](upsource:///java/java-psi-api/src/com/intellij/psi/JavaModuleSystem.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.javadocTagInfo](https://jb.gg/ipe?extensions=com.intellij.javadocTagInfo) | [`JavadocTagInfo`](upsource:///java/java-psi-api/src/com/intellij/psi/javadoc/JavadocTagInfo.java) | 
|  | [com.intellij.jvm.declarationSearcher](https://jb.gg/ipe?extensions=com.intellij.jvm.declarationSearcher) | [`JvmDeclarationSearcher`](upsource:///java/java-psi-api/src/com/intellij/lang/jvm/source/JvmDeclarationSearcher.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.jvm.elementProvider](https://jb.gg/ipe?extensions=com.intellij.jvm.elementProvider) | [`JvmElementProvider`](upsource:///java/java-psi-api/src/com/intellij/lang/jvm/facade/JvmElementProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.lang.inferredAnnotationProvider](https://jb.gg/ipe?extensions=com.intellij.lang.inferredAnnotationProvider) | [`InferredAnnotationProvider`](upsource:///java/java-psi-api/src/com/intellij/codeInsight/InferredAnnotationProvider.java) | 
|  | [com.intellij.lang.psiAugmentProvider](https://jb.gg/ipe?extensions=com.intellij.lang.psiAugmentProvider) | [`PsiAugmentProvider`](upsource:///java/java-psi-api/src/com/intellij/psi/augment/PsiAugmentProvider.java) | 
|  | [com.intellij.lang.psiTypeAnnotationModifier](https://jb.gg/ipe?extensions=com.intellij.lang.psiTypeAnnotationModifier) | [~~`TypeAnnotationModifier`~~](upsource:///java/java-psi-api/src/com/intellij/psi/augment/TypeAnnotationModifier.java) | 
|  | [com.intellij.psi.classFileDecompiler](https://jb.gg/ipe?extensions=com.intellij.psi.classFileDecompiler) | [`Decompiler`](upsource:///java/java-psi-api/src/com/intellij/psi/compiled/ClassFileDecompilers.java) | 
|  | [com.intellij.psi.clsCustomNavigationPolicy](https://jb.gg/ipe?extensions=com.intellij.psi.clsCustomNavigationPolicy) | [`ClsCustomNavigationPolicy`](upsource:///java/java-psi-impl/src/com/intellij/psi/impl/compiled/ClsCustomNavigationPolicy.java) | 
|  | [com.intellij.superMethodsSearch](https://jb.gg/ipe?extensions=com.intellij.superMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [com.intellij.testFramework](https://jb.gg/ipe?extensions=com.intellij.testFramework) | [`TestFramework`](upsource:///platform/core-api/src/com/intellij/testIntegration/TestFramework.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.jetbrains.uast.analysis.uastAnalysisPlugin](https://jb.gg/ipe?extensions=org.jetbrains.uast.analysis.uastAnalysisPlugin) | [`UastAnalysisPlugin`](upsource:///uast/uast-common/src/org/jetbrains/uast/analysis/UastAnalysisPlugin.kt) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.jetbrains.uast.generate.uastCodeGenerationPlugin](https://jb.gg/ipe?extensions=org.jetbrains.uast.generate.uastCodeGenerationPlugin) | [`UastCodeGenerationPlugin`](upsource:///uast/uast-common/src/org/jetbrains/uast/generate/UastCodeGenerationPlugin.kt) | 
|  | [org.jetbrains.uast.uastLanguagePlugin](https://jb.gg/ipe?extensions=org.jetbrains.uast.uastLanguagePlugin) | [`UastLanguagePlugin`](upsource:///uast/uast-common/src/org/jetbrains/uast/UastLanguagePlugin.kt) | 

## [JsonPlugin.xml](upsource:///platform/platform-resources/src/META-INF/JsonPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [JavaScript.JsonSchema.ProviderFactory](https://jb.gg/ipe?extensions=JavaScript.JsonSchema.ProviderFactory) | [`JsonSchemaProviderFactory`](upsource:///json/src/com/jetbrains/jsonSchema/extension/JsonSchemaProviderFactory.java) | 
|  | [com.intellij.json.catalog.exclusion](https://jb.gg/ipe?extensions=com.intellij.json.catalog.exclusion) | [`JsonSchemaCatalogExclusion`](upsource:///json/src/com/jetbrains/jsonSchema/remote/JsonSchemaCatalogExclusion.java) | 
|  | [com.intellij.json.customStructureViewFactory](https://jb.gg/ipe?extensions=com.intellij.json.customStructureViewFactory) | [`JsonCustomStructureViewFactory`](upsource:///json/src/com/intellij/json/structureView/JsonCustomStructureViewFactory.java) | 
|  | [com.intellij.json.jsonLikePsiWalkerFactory](https://jb.gg/ipe?extensions=com.intellij.json.jsonLikePsiWalkerFactory) | [`JsonLikePsiWalkerFactory`](upsource:///json/src/com/jetbrains/jsonSchema/extension/JsonLikePsiWalkerFactory.java) | 
|  | [com.intellij.json.jsonLiteralChecker](https://jb.gg/ipe?extensions=com.intellij.json.jsonLiteralChecker) | [`JsonLiteralChecker`](upsource:///json/src/com/intellij/json/codeinsight/JsonLiteralChecker.java) | 
|  | [com.intellij.json.jsonSchemaEnabler](https://jb.gg/ipe?extensions=com.intellij.json.jsonSchemaEnabler) | [`JsonSchemaEnabler`](upsource:///json/src/com/jetbrains/jsonSchema/extension/JsonSchemaEnabler.java) | 
|  | [com.intellij.json.jsonStandardComplianceProvider](https://jb.gg/ipe?extensions=com.intellij.json.jsonStandardComplianceProvider) | [`JsonStandardComplianceProvider`](upsource:///json/src/com/intellij/json/codeinsight/JsonStandardComplianceProvider.java) | 
|  | [com.intellij.json.jsonWidgetSuppressor](https://jb.gg/ipe?extensions=com.intellij.json.jsonWidgetSuppressor) | [`JsonWidgetSuppressor`](upsource:///json/src/com/jetbrains/jsonSchema/extension/JsonWidgetSuppressor.java) | 

## [JUnit](upsource:///plugins/junit/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.junitListener](https://jb.gg/ipe?extensions=com.intellij.junitListener) | [`IDEAJUnitListener`](upsource:///java/java-runtime/src/com/intellij/rt/execution/junit/IDEAJUnitListener.java) | 
|  | [com.intellij.testDiscoveryProducer](https://jb.gg/ipe?extensions=com.intellij.testDiscoveryProducer) | [`TestDiscoveryProducer`](upsource:///java/execution/impl/src/com/intellij/execution/testDiscovery/TestDiscoveryProducer.java) | 

## [LangExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/LangExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.aliasingPsiTargetMapper](https://jb.gg/ipe?extensions=com.intellij.aliasingPsiTargetMapper) | [`AliasingPsiTargetMapper`](upsource:///platform/core-api/src/com/intellij/psi/targets/AliasingPsiTargetMapper.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.analyzeStacktraceFilter](https://jb.gg/ipe?extensions=com.intellij.analyzeStacktraceFilter) | [`Filter`](upsource:///platform/lang-api/src/com/intellij/execution/filters/Filter.java) | 
|  | [com.intellij.anchorReferenceProvider](https://jb.gg/ipe?extensions=com.intellij.anchorReferenceProvider) | [`PathReferenceProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/paths/PathReferenceProvider.java) | 
|  | [com.intellij.annotator](https://jb.gg/ipe?extensions=com.intellij.annotator) | [`Annotator`](upsource:///platform/analysis-api/src/com/intellij/lang/annotation/Annotator.java) | 
|  | [com.intellij.anonymousElementProvider](https://jb.gg/ipe?extensions=com.intellij.anonymousElementProvider) | [`AnonymousElementProvider`](upsource:///platform/editor-ui-api/src/com/intellij/navigation/AnonymousElementProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.autoImportOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.autoImportOptionsProvider) | [`AutoImportOptionsProvider`](upsource:///platform/lang-impl/src/com/intellij/application/options/editor/AutoImportOptionsProvider.java) | 
|  | [com.intellij.braceMatcher](https://jb.gg/ipe?extensions=com.intellij.braceMatcher) | [`BraceMatcher`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/highlighting/BraceMatcher.java) | 
|  | [com.intellij.breadcrumbsInfoProvider](https://jb.gg/ipe?extensions=com.intellij.breadcrumbsInfoProvider) | [`BreadcrumbsProvider`](upsource:///platform/editor-ui-api/src/com/intellij/ui/breadcrumbs/BreadcrumbsProvider.java) | 
|  | [com.intellij.cacheBuilder](https://jb.gg/ipe?extensions=com.intellij.cacheBuilder) | [`WordsScanner`](upsource:///platform/indexing-api/src/com/intellij/lang/cacheBuilder/WordsScanner.java) | 
|  | [com.intellij.callHierarchyProvider](https://jb.gg/ipe?extensions=com.intellij.callHierarchyProvider) | [`HierarchyProvider`](upsource:///platform/lang-api/src/com/intellij/ide/hierarchy/HierarchyProvider.java) | 
|  | [com.intellij.cantBeStatic](https://jb.gg/ipe?extensions=com.intellij.cantBeStatic) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.codeBlockSupportHandler](https://jb.gg/ipe?extensions=com.intellij.codeBlockSupportHandler) | [`CodeBlockSupportHandler`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/highlighting/CodeBlockSupportHandler.java) | 
|  | [com.intellij.codeCompletionConfigurable](https://jb.gg/ipe?extensions=com.intellij.codeCompletionConfigurable) | [`UnnamedConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/UnnamedConfigurable.java) | 
|  | [com.intellij.codeFoldingOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.codeFoldingOptionsProvider) | [`CodeFoldingOptionsProvider`](upsource:///platform/lang-impl/src/com/intellij/application/options/editor/CodeFoldingOptionsProvider.java) | 
|  | [com.intellij.codeInsight.delegateMethods](https://jb.gg/ipe?extensions=com.intellij.codeInsight.delegateMethods) | [`LanguageCodeInsightActionHandler`](upsource:///platform/lang-api/src/com/intellij/lang/LanguageCodeInsightActionHandler.java) | 
|  | [com.intellij.codeInsight.gotoSuper](https://jb.gg/ipe?extensions=com.intellij.codeInsight.gotoSuper) | [`CodeInsightActionHandler`](upsource:///platform/lang-api/src/com/intellij/codeInsight/CodeInsightActionHandler.java) | 
|  | [com.intellij.codeInsight.implementMethod](https://jb.gg/ipe?extensions=com.intellij.codeInsight.implementMethod) | [`LanguageCodeInsightActionHandler`](upsource:///platform/lang-api/src/com/intellij/lang/LanguageCodeInsightActionHandler.java) | 
|  | [com.intellij.codeInsight.inlayProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.inlayProvider) | [`InlayHintsProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hints/InlayHintsProvider.kt) | 
|  | [com.intellij.codeInsight.inlayProviderFactory](https://jb.gg/ipe?extensions=com.intellij.codeInsight.inlayProviderFactory) | [`InlayHintsProviderFactory`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hints/InlayHintsProviderFactory.kt) | 
|  | [com.intellij.codeInsight.lineMarkerProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.lineMarkerProvider) | [`LineMarkerProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/daemon/LineMarkerProvider.java) | 
|  | [com.intellij.codeInsight.overrideMethod](https://jb.gg/ipe?extensions=com.intellij.codeInsight.overrideMethod) | [`LanguageCodeInsightActionHandler`](upsource:///platform/lang-api/src/com/intellij/lang/LanguageCodeInsightActionHandler.java) | 
|  | [com.intellij.codeInsight.parameterInfo](https://jb.gg/ipe?extensions=com.intellij.codeInsight.parameterInfo) | [`ParameterInfoHandler`](upsource:///platform/lang-api/src/com/intellij/lang/parameterInfo/ParameterInfoHandler.java) | 
|  | [com.intellij.codeInsight.parameterInfo.controller.provider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.parameterInfo.controller.provider) | [`ParameterInfoControllerProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/hint/ParameterInfoControllerProvider.java) | 
|  | [com.intellij.codeInsight.parameterInfo.listener](https://jb.gg/ipe?extensions=com.intellij.codeInsight.parameterInfo.listener) | [`ParameterInfoListener`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/hint/ParameterInfoListener.java) | 
|  | [com.intellij.codeInsight.parameterNameHints](https://jb.gg/ipe?extensions=com.intellij.codeInsight.parameterNameHints) | [`InlayParameterHintsProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hints/InlayParameterHintsProvider.java) | 
|  | [com.intellij.codeInsight.surroundWithRangeAdjuster](https://jb.gg/ipe?extensions=com.intellij.codeInsight.surroundWithRangeAdjuster) | [`SurroundWithRangeAdjuster`](upsource:///platform/lang-api/src/com/intellij/codeInsight/generation/surroundWith/SurroundWithRangeAdjuster.java) | 
|  | [com.intellij.codeInsight.typeInfo](https://jb.gg/ipe?extensions=com.intellij.codeInsight.typeInfo) | [`ExpressionTypeProvider`](upsource:///platform/lang-api/src/com/intellij/lang/ExpressionTypeProvider.java) | 
|  | [com.intellij.codeInsight.unresolvedReferenceQuickFixProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.unresolvedReferenceQuickFixProvider) | [`UnresolvedReferenceQuickFixProvider`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/quickfix/UnresolvedReferenceQuickFixProvider.java) | 
|  | [com.intellij.codeStyleSettingsProvider](https://jb.gg/ipe?extensions=com.intellij.codeStyleSettingsProvider) | [`CodeStyleSettingsProvider`](upsource:///platform/lang-api/src/com/intellij/psi/codeStyle/CodeStyleSettingsProvider.java) | 
|  | [com.intellij.codeUsageScopeOptimizer](https://jb.gg/ipe?extensions=com.intellij.codeUsageScopeOptimizer) | [`ScopeOptimizer`](upsource:///platform/indexing-api/src/com/intellij/psi/search/ScopeOptimizer.java) | 
|  | [com.intellij.colorAndFontDescriptorProvider](https://jb.gg/ipe?extensions=com.intellij.colorAndFontDescriptorProvider) | [`ColorAndFontDescriptorsProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/options/colors/ColorAndFontDescriptorsProvider.java) | 
|  | [com.intellij.colorAndFontPanelFactory](https://jb.gg/ipe?extensions=com.intellij.colorAndFontPanelFactory) | [`ColorAndFontPanelFactory`](upsource:///platform/platform-impl/src/com/intellij/application/options/colors/ColorAndFontPanelFactory.java) | 
|  | [com.intellij.colorProvider](https://jb.gg/ipe?extensions=com.intellij.colorProvider) | [`ElementColorProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/editor/ElementColorProvider.java) | 
|  | [com.intellij.colorSettingsPage](https://jb.gg/ipe?extensions=com.intellij.colorSettingsPage) | [`ColorSettingsPage`](upsource:///platform/platform-api/src/com/intellij/openapi/options/colors/ColorSettingsPage.java) | 
|  | [com.intellij.commandLineInspectionProjectConfigurator](https://jb.gg/ipe?extensions=com.intellij.commandLineInspectionProjectConfigurator) | [`CommandLineInspectionProjectConfigurator`](upsource:///platform/platform-impl/src/com/intellij/ide/CommandLineInspectionProjectConfigurator.java) | 
|  | [com.intellij.commentTokenSetProvider](https://jb.gg/ipe?extensions=com.intellij.commentTokenSetProvider) | [`CommentTokenSetProvider`](upsource:///platform/core-impl/src/com/intellij/psi/impl/cache/CommentTokenSetProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.concatenationAwareInjector](https://jb.gg/ipe?extensions=com.intellij.concatenationAwareInjector) | [`ConcatenationAwareInjector`](upsource:///platform/lang-api/src/com/intellij/lang/injection/ConcatenationAwareInjector.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.configurationProducer](https://jb.gg/ipe?extensions=com.intellij.configurationProducer) | [~~`RuntimeConfigurationProducer`~~](upsource:///platform/lang-api/src/com/intellij/execution/junit/RuntimeConfigurationProducer.java) | 
|  | [com.intellij.configurationType](https://jb.gg/ipe?extensions=com.intellij.configurationType) | [`ConfigurationType`](upsource:///platform/lang-api/src/com/intellij/execution/configurations/ConfigurationType.java) | 
|  | [com.intellij.console.folding](https://jb.gg/ipe?extensions=com.intellij.console.folding) | [`ConsoleFolding`](upsource:///platform/execution-impl/src/com/intellij/execution/ConsoleFolding.java) | 
|  | [com.intellij.consoleActionsPostProcessor](https://jb.gg/ipe?extensions=com.intellij.consoleActionsPostProcessor) | [`ConsoleActionsPostProcessor`](upsource:///platform/lang-api/src/com/intellij/execution/actions/ConsoleActionsPostProcessor.java) | 
|  | [com.intellij.consoleFilterProvider](https://jb.gg/ipe?extensions=com.intellij.consoleFilterProvider) | [`ConsoleFilterProvider`](upsource:///platform/lang-api/src/com/intellij/execution/filters/ConsoleFilterProvider.java) | 
|  | [com.intellij.consoleHistoryModelProvider](https://jb.gg/ipe?extensions=com.intellij.consoleHistoryModelProvider) | [`ConsoleHistoryModelProvider`](upsource:///platform/lang-impl/src/com/intellij/execution/console/ConsoleHistoryModelProvider.java) | 
|  | [com.intellij.consoleInputFilterProvider](https://jb.gg/ipe?extensions=com.intellij.consoleInputFilterProvider) | [`ConsoleInputFilterProvider`](upsource:///platform/lang-api/src/com/intellij/execution/filters/ConsoleInputFilterProvider.java) | 
|  | [com.intellij.createFromTemplateActionReplacer](https://jb.gg/ipe?extensions=com.intellij.createFromTemplateActionReplacer) | [`CreateFromTemplateActionReplacer`](upsource:///platform/lang-impl/src/com/intellij/ide/fileTemplates/CreateFromTemplateActionReplacer.java) | 
|  | [com.intellij.createFromTemplateHandler](https://jb.gg/ipe?extensions=com.intellij.createFromTemplateHandler) | [`CreateFromTemplateHandler`](upsource:///platform/lang-impl/src/com/intellij/ide/fileTemplates/CreateFromTemplateHandler.java) | 
|  | [com.intellij.customFoldingProvider](https://jb.gg/ipe?extensions=com.intellij.customFoldingProvider) | [`CustomFoldingProvider`](upsource:///platform/core-api/src/com/intellij/lang/folding/CustomFoldingProvider.java) | 
|  | [com.intellij.customLiveTemplate](https://jb.gg/ipe?extensions=com.intellij.customLiveTemplate) | [`CustomLiveTemplate`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/template/CustomLiveTemplate.java) | 
|  | [com.intellij.customScopesFilter](https://jb.gg/ipe?extensions=com.intellij.customScopesFilter) | [`CustomScopesFilter`](upsource:///platform/analysis-api/src/com/intellij/psi/search/scope/packageSet/CustomScopesFilter.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.customScopesProvider](https://jb.gg/ipe?extensions=com.intellij.customScopesProvider) | [`CustomScopesProvider`](upsource:///platform/analysis-api/src/com/intellij/psi/search/scope/packageSet/CustomScopesProvider.java) | 
|  | [com.intellij.customUsageSearcher](https://jb.gg/ipe?extensions=com.intellij.customUsageSearcher) | [`CustomUsageSearcher`](upsource:///platform/lang-impl/src/com/intellij/find/findUsages/CustomUsageSearcher.java) | 
|  | [com.intellij.daemon.changeLocalityDetector](https://jb.gg/ipe?extensions=com.intellij.daemon.changeLocalityDetector) | [`ChangeLocalityDetector`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/daemon/ChangeLocalityDetector.java) | 
|  | [com.intellij.daemon.externalAnnotatorsFilter](https://jb.gg/ipe?extensions=com.intellij.daemon.externalAnnotatorsFilter) | [`ExternalAnnotatorsFilter`](upsource:///platform/analysis-api/src/com/intellij/lang/ExternalAnnotatorsFilter.java) | 
|  | [com.intellij.daemon.highlightInfoFilter](https://jb.gg/ipe?extensions=com.intellij.daemon.highlightInfoFilter) | [`HighlightInfoFilter`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/HighlightInfoFilter.java) | 
|  | [com.intellij.daemon.intentionActionFilter](https://jb.gg/ipe?extensions=com.intellij.daemon.intentionActionFilter) | [`IntentionActionFilter`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/IntentionActionFilter.java) | 
|  | [com.intellij.daemon.tooltipActionProvider](https://jb.gg/ipe?extensions=com.intellij.daemon.tooltipActionProvider) | [`TooltipActionProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/impl/tooltips/TooltipActionProvider.java) | 
|  | [com.intellij.declarationRangeHandler](https://jb.gg/ipe?extensions=com.intellij.declarationRangeHandler) | [`DeclarationRangeHandler`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hint/DeclarationRangeHandler.java) | 
|  | [com.intellij.defaultHighlightingSettingProvider](https://jb.gg/ipe?extensions=com.intellij.defaultHighlightingSettingProvider) | [`DefaultHighlightingSettingProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/daemon/impl/analysis/DefaultHighlightingSettingProvider.java) | 
|  | [com.intellij.defaultLiveTemplates](https://jb.gg/ipe?extensions=com.intellij.defaultLiveTemplates) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.defaultLiveTemplatesProvider](https://jb.gg/ipe?extensions=com.intellij.defaultLiveTemplatesProvider) | [~~`DefaultLiveTemplatesProvider`~~](upsource:///platform/lang-impl/src/com/intellij/codeInsight/template/impl/DefaultLiveTemplatesProvider.java) | 
|  | [com.intellij.defaultTemplatePropertiesProvider](https://jb.gg/ipe?extensions=com.intellij.defaultTemplatePropertiesProvider) | [`DefaultTemplatePropertiesProvider`](upsource:///platform/lang-api/src/com/intellij/ide/fileTemplates/DefaultTemplatePropertiesProvider.java) | 
|  | [com.intellij.definitionsScopedSearch](https://jb.gg/ipe?extensions=com.intellij.definitionsScopedSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.diffPreviewProvider](https://jb.gg/ipe?extensions=com.intellij.diffPreviewProvider) | [`DiffPreviewProvider`](upsource:///platform/diff-api/src/com/intellij/openapi/diff/impl/settings/DiffPreviewProvider.java) | 
|  | [com.intellij.dynamicContextProvider](https://jb.gg/ipe?extensions=com.intellij.dynamicContextProvider) | [`DynamicContextProvider`](upsource:///platform/lang-impl/src/com/intellij/openapi/paths/DynamicContextProvider.java) | 
|  | [com.intellij.editorAppearanceConfigurable](https://jb.gg/ipe?extensions=com.intellij.editorAppearanceConfigurable) | [`UnnamedConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/UnnamedConfigurable.java) | 
|  | [com.intellij.editorOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.editorOptionsProvider) | [`EditorOptionsProvider`](upsource:///platform/platform-impl/src/com/intellij/application/options/editor/EditorOptionsProvider.java) | 
|  | [com.intellij.editorSmartKeysConfigurable](https://jb.gg/ipe?extensions=com.intellij.editorSmartKeysConfigurable) | [`UnnamedConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/UnnamedConfigurable.java) | 
|  | [com.intellij.elementDescriptionProvider](https://jb.gg/ipe?extensions=com.intellij.elementDescriptionProvider) | [`ElementDescriptionProvider`](upsource:///platform/core-api/src/com/intellij/psi/ElementDescriptionProvider.java) | 
|  | [com.intellij.elementPreviewProvider](https://jb.gg/ipe?extensions=com.intellij.elementPreviewProvider) | [`ElementPreviewProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/preview/ElementPreviewProvider.java) | 
|  | [com.intellij.elementSignatureProvider](https://jb.gg/ipe?extensions=com.intellij.elementSignatureProvider) | [`ElementSignatureProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/folding/impl/ElementSignatureProvider.java) | 
|  | [com.intellij.elementsToHighlightFilter](https://jb.gg/ipe?extensions=com.intellij.elementsToHighlightFilter) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.errorOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.errorOptionsProvider) | [`ErrorOptionsProvider`](upsource:///platform/lang-impl/src/com/intellij/profile/codeInspection/ui/ErrorOptionsProvider.java) | 
|  | [com.intellij.errorQuickFixProvider](https://jb.gg/ipe?extensions=com.intellij.errorQuickFixProvider) | [`ErrorQuickFixProvider`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/analysis/ErrorQuickFixProvider.java) | 
|  | [com.intellij.executionTargetLanguageRuntimeType](https://jb.gg/ipe?extensions=com.intellij.executionTargetLanguageRuntimeType) | [`LanguageRuntimeType`](upsource:///platform/lang-api/src/com/intellij/execution/target/LanguageRuntimeType.kt) | 
|  | [com.intellij.executionTargetProvider](https://jb.gg/ipe?extensions=com.intellij.executionTargetProvider) | [`ExecutionTargetProvider`](upsource:///platform/lang-api/src/com/intellij/execution/ExecutionTargetProvider.java) | 
|  | [com.intellij.executionTargetType](https://jb.gg/ipe?extensions=com.intellij.executionTargetType) | [`TargetEnvironmentType`](upsource:///platform/lang-api/src/com/intellij/execution/target/TargetEnvironmentType.kt) | 
|  | [com.intellij.executor](https://jb.gg/ipe?extensions=com.intellij.executor) | [`Executor`](upsource:///platform/lang-api/src/com/intellij/execution/Executor.java) | 
|  | [com.intellij.externalAnnotator](https://jb.gg/ipe?extensions=com.intellij.externalAnnotator) | [`ExternalAnnotator`](upsource:///platform/analysis-api/src/com/intellij/lang/annotation/ExternalAnnotator.java) | 
|  | [com.intellij.facet.toolWindow](https://jb.gg/ipe?extensions=com.intellij.facet.toolWindow) | [`ToolWindowFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/ToolWindowFactory.java) | 
|  | [com.intellij.facetType](https://jb.gg/ipe?extensions=com.intellij.facetType) | [`FacetType`](upsource:///platform/lang-api/src/com/intellij/facet/FacetType.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.favoriteNodeProvider](https://jb.gg/ipe?extensions=com.intellij.favoriteNodeProvider) | [`FavoriteNodeProvider`](upsource:///platform/lang-api/src/com/intellij/ide/favoritesTreeView/FavoriteNodeProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.favoritesListProvider](https://jb.gg/ipe?extensions=com.intellij.favoritesListProvider) | [`FavoritesListProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/favoritesTreeView/FavoritesListProvider.java) | 
|  | [com.intellij.filePasteProvider](https://jb.gg/ipe?extensions=com.intellij.filePasteProvider) | [`PasteProvider`](upsource:///platform/platform-api/src/com/intellij/ide/PasteProvider.java) | 
|  | [com.intellij.fileStructureGroupRuleProvider](https://jb.gg/ipe?extensions=com.intellij.fileStructureGroupRuleProvider) | [`FileStructureGroupRuleProvider`](upsource:///platform/usageView/src/com/intellij/usages/impl/FileStructureGroupRuleProvider.java) | 
|  | [com.intellij.fileTemplateGroup](https://jb.gg/ipe?extensions=com.intellij.fileTemplateGroup) | [`FileTemplateGroupDescriptorFactory`](upsource:///platform/lang-api/src/com/intellij/ide/fileTemplates/FileTemplateGroupDescriptorFactory.java) | 
|  | [com.intellij.fileType.fileViewProviderFactory](https://jb.gg/ipe?extensions=com.intellij.fileType.fileViewProviderFactory) | [`FileViewProviderFactory`](upsource:///platform/core-api/src/com/intellij/psi/FileViewProviderFactory.java) | 
|  | [com.intellij.fileTypeStatisticProvider](https://jb.gg/ipe?extensions=com.intellij.fileTypeStatisticProvider) | [`FileTypeStatisticProvider`](upsource:///platform/platform-impl/src/com/intellij/internal/statistic/fileTypes/FileTypeStatisticProvider.java) | 
|  | [com.intellij.filetype.prebuiltStubsProvider](https://jb.gg/ipe?extensions=com.intellij.filetype.prebuiltStubsProvider) | [`PrebuiltStubsProvider`](upsource:///platform/indexing-impl/src/com/intellij/psi/stubs/PrebuiltStubs.kt) | 
|  | [com.intellij.filetype.stubBuilder](https://jb.gg/ipe?extensions=com.intellij.filetype.stubBuilder) | [`BinaryFileStubBuilder`](upsource:///platform/core-api/src/com/intellij/psi/stubs/BinaryFileStubBuilder.java) | 
|  | [com.intellij.findInProjectExtension](https://jb.gg/ipe?extensions=com.intellij.findInProjectExtension) | [`FindInProjectExtension`](upsource:///platform/lang-impl/src/com/intellij/find/impl/FindInProjectExtension.kt) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.findInProjectSearchEngine](https://jb.gg/ipe?extensions=com.intellij.findInProjectSearchEngine) | [`FindInProjectSearchEngine`](upsource:///platform/lang-api/src/com/intellij/find/FindInProjectSearchEngine.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.findUsagesHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.findUsagesHandlerFactory) | [`FindUsagesHandlerFactory`](upsource:///platform/lang-impl/src/com/intellij/find/findUsages/FindUsagesHandlerFactory.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.focusModeProvider](https://jb.gg/ipe?extensions=com.intellij.focusModeProvider) | [`FocusModeProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/impl/focusMode/FocusModeProvider.java) | 
|  | [com.intellij.framework.detector](https://jb.gg/ipe?extensions=com.intellij.framework.detector) | [`FrameworkDetector`](upsource:///platform/lang-api/src/com/intellij/framework/detection/FrameworkDetector.java) | 
|  | [com.intellij.generalCodeStyleOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.generalCodeStyleOptionsProvider) | [`GeneralCodeStyleOptionsProvider`](upsource:///platform/lang-impl/src/com/intellij/application/options/GeneralCodeStyleOptionsProvider.java) | 
|  | [com.intellij.generatedSourcesFilter](https://jb.gg/ipe?extensions=com.intellij.generatedSourcesFilter) | [`GeneratedSourcesFilter`](upsource:///platform/analysis-api/src/com/intellij/openapi/roots/GeneratedSourcesFilter.java) | 
|  | [com.intellij.globalIndexFilter](https://jb.gg/ipe?extensions=com.intellij.globalIndexFilter) | [`GlobalIndexFilter`](upsource:///platform/lang-impl/src/com/intellij/util/indexing/GlobalIndexFilter.java) | 
|  | [com.intellij.goto.nonProjectScopeDisabler](https://jb.gg/ipe?extensions=com.intellij.goto.nonProjectScopeDisabler) | `n/a` | 
|  | [com.intellij.gotoActionAliasMatcher](https://jb.gg/ipe?extensions=com.intellij.gotoActionAliasMatcher) | [`GotoActionAliasMatcher`](upsource:///platform/lang-impl/src/com/intellij/ide/util/gotoByName/GotoActionAliasMatcher.java) | 
|  | [com.intellij.gotoClassContributor](https://jb.gg/ipe?extensions=com.intellij.gotoClassContributor) | [`ChooseByNameContributor`](upsource:///platform/lang-api/src/com/intellij/navigation/ChooseByNameContributor.java) | 
|  | [com.intellij.gotoFileContributor](https://jb.gg/ipe?extensions=com.intellij.gotoFileContributor) | [`ChooseByNameContributor`](upsource:///platform/lang-api/src/com/intellij/navigation/ChooseByNameContributor.java) | 
|  | [com.intellij.gotoFileCustomizer](https://jb.gg/ipe?extensions=com.intellij.gotoFileCustomizer) | [`GotoFileCustomizer`](upsource:///platform/lang-impl/src/com/intellij/ide/util/gotoByName/GotoFileCustomizer.java) | 
|  | [com.intellij.gotoRelatedProvider](https://jb.gg/ipe?extensions=com.intellij.gotoRelatedProvider) | [`GotoRelatedProvider`](upsource:///platform/lang-api/src/com/intellij/navigation/GotoRelatedProvider.java) | 
|  | [com.intellij.gotoSymbolContributor](https://jb.gg/ipe?extensions=com.intellij.gotoSymbolContributor) | [`ChooseByNameContributor`](upsource:///platform/lang-api/src/com/intellij/navigation/ChooseByNameContributor.java) | 
|  | [com.intellij.gotoTargetRendererProvider](https://jb.gg/ipe?extensions=com.intellij.gotoTargetRendererProvider) | [`GotoTargetRendererProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/navigation/GotoTargetRendererProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.hectorComponentProvider](https://jb.gg/ipe?extensions=com.intellij.hectorComponentProvider) | [`HectorComponentPanelsProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/editor/HectorComponentPanelsProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.highlightInfoPostFilter](https://jb.gg/ipe?extensions=com.intellij.highlightInfoPostFilter) | [`HighlightInfoPostFilter`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/HighlightInfoPostFilter.java) | 
|  | [com.intellij.highlightRangeExtension](https://jb.gg/ipe?extensions=com.intellij.highlightRangeExtension) | [`HighlightRangeExtension`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/HighlightRangeExtension.java) | 
|  | [com.intellij.highlightUsagesHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.highlightUsagesHandlerFactory) | [`HighlightUsagesHandlerFactory`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/highlighting/HighlightUsagesHandlerFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.highlightVisitor](https://jb.gg/ipe?extensions=com.intellij.highlightVisitor) | [`HighlightVisitor`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/impl/HighlightVisitor.java) | 
|  | [com.intellij.highlightingPassFactory](https://jb.gg/ipe?extensions=com.intellij.highlightingPassFactory) | [`TextEditorHighlightingPassFactoryRegistrar`](upsource:///platform/analysis-impl/src/com/intellij/codeHighlighting/TextEditorHighlightingPassFactoryRegistrar.java) | 
|  | [com.intellij.iconProvider](https://jb.gg/ipe?extensions=com.intellij.iconProvider) | [`IconProvider`](upsource:///platform/core-api/src/com/intellij/ide/IconProvider.java) | 
|  | [com.intellij.idIndexer](https://jb.gg/ipe?extensions=com.intellij.idIndexer) | [`IdIndexer`](upsource:///platform/indexing-impl/src/com/intellij/psi/impl/cache/impl/id/IdIndexer.java) | 
|  | [com.intellij.implementationViewDocumentFactory](https://jb.gg/ipe?extensions=com.intellij.implementationViewDocumentFactory) | [`ImplementationViewDocumentFactory`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/hint/ImplementationViewDocumentFactory.kt) | 
|  | [com.intellij.implementationViewSessionFactory](https://jb.gg/ipe?extensions=com.intellij.implementationViewSessionFactory) | [`ImplementationViewSessionFactory`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/hint/ImplementationViewSession.kt) | 
|  | [com.intellij.implicitUsageProvider](https://jb.gg/ipe?extensions=com.intellij.implicitUsageProvider) | [`ImplicitUsageProvider`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/daemon/ImplicitUsageProvider.java) | 
|  | [com.intellij.importFilteringRule](https://jb.gg/ipe?extensions=com.intellij.importFilteringRule) | [`ImportFilteringRule`](upsource:///platform/usageView/src/com/intellij/usages/rules/ImportFilteringRule.java) | 
|  | [com.intellij.include.provider](https://jb.gg/ipe?extensions=com.intellij.include.provider) | [`FileIncludeProvider`](upsource:///platform/lang-impl/src/com/intellij/psi/impl/include/FileIncludeProvider.java) | 
|  | [com.intellij.indexPatternBuilder](https://jb.gg/ipe?extensions=com.intellij.indexPatternBuilder) | [`IndexPatternBuilder`](upsource:///platform/indexing-impl/src/com/intellij/psi/impl/search/IndexPatternBuilder.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.indexPatternProvider](https://jb.gg/ipe?extensions=com.intellij.indexPatternProvider) | [`IndexPatternProvider`](upsource:///platform/indexing-api/src/com/intellij/psi/search/IndexPatternProvider.java) | 
|  | [com.intellij.indexPatternSearch](https://jb.gg/ipe?extensions=com.intellij.indexPatternSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.indexableFilesFilter](https://jb.gg/ipe?extensions=com.intellij.indexableFilesFilter) | [`IndexableFilesFilter`](upsource:///platform/lang-impl/src/com/intellij/util/indexing/IndexableFilesFilter.java) | 
|  | [com.intellij.inspectionElementsMerger](https://jb.gg/ipe?extensions=com.intellij.inspectionElementsMerger) | [`InspectionElementsMerger`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/ex/InspectionElementsMerger.java) | 
|  | [com.intellij.inspectionProfileActionProvider](https://jb.gg/ipe?extensions=com.intellij.inspectionProfileActionProvider) | [`InspectionProfileActionProvider`](upsource:///platform/lang-impl/src/com/intellij/profile/codeInspection/ui/InspectionProfileActionProvider.java) | 
|  | [com.intellij.intentionMenuContributor](https://jb.gg/ipe?extensions=com.intellij.intentionMenuContributor) | [`IntentionMenuContributor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/impl/IntentionMenuContributor.java) | 
|  | [com.intellij.internalFileTemplate](https://jb.gg/ipe?extensions=com.intellij.internalFileTemplate) | `n/a` | 
|  | [com.intellij.lang.braceMatcher](https://jb.gg/ipe?extensions=com.intellij.lang.braceMatcher) | [`PairedBraceMatcher`](upsource:///platform/analysis-api/src/com/intellij/lang/PairedBraceMatcher.java) | 
|  | [com.intellij.lang.codeReferenceSearcher](https://jb.gg/ipe?extensions=com.intellij.lang.codeReferenceSearcher) | [`CodeReferenceSearcher`](upsource:///platform/indexing-api/src/com/intellij/model/search/CodeReferenceSearcher.java) | 
|  | [com.intellij.lang.commenter](https://jb.gg/ipe?extensions=com.intellij.lang.commenter) | [`Commenter`](upsource:///platform/core-api/src/com/intellij/lang/Commenter.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.lang.directNavigationProvider](https://jb.gg/ipe?extensions=com.intellij.lang.directNavigationProvider) | [`DirectNavigationProvider`](upsource:///platform/core-api/src/com/intellij/navigation/DirectNavigationProvider.java) | 
|  | [com.intellij.lang.documentationFixer](https://jb.gg/ipe?extensions=com.intellij.lang.documentationFixer) | [`DocCommentFixer`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/documentation/DocCommentFixer.java) | 
|  | [com.intellij.lang.documentationToolWindowManager](https://jb.gg/ipe?extensions=com.intellij.lang.documentationToolWindowManager) | [`DocToolWindowManager`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/documentation/DocToolWindowManager.java) | 
|  | [com.intellij.lang.fileViewProviderFactory](https://jb.gg/ipe?extensions=com.intellij.lang.fileViewProviderFactory) | [`FileViewProviderFactory`](upsource:///platform/core-api/src/com/intellij/psi/FileViewProviderFactory.java) | 
|  | [com.intellij.lang.findUsagesProvider](https://jb.gg/ipe?extensions=com.intellij.lang.findUsagesProvider) | [`FindUsagesProvider`](upsource:///platform/indexing-api/src/com/intellij/lang/findUsages/FindUsagesProvider.java) | 
|  | [com.intellij.lang.foldingBuilder](https://jb.gg/ipe?extensions=com.intellij.lang.foldingBuilder) | [`FoldingBuilder`](upsource:///platform/core-api/src/com/intellij/lang/folding/FoldingBuilder.java) | 
|  | [com.intellij.lang.implementationTextProcessor](https://jb.gg/ipe?extensions=com.intellij.lang.implementationTextProcessor) | [`ImplementationTextProcessor`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hint/ImplementationTextProcessor.java) | 
|  | [com.intellij.lang.implementationTextSelectioner](https://jb.gg/ipe?extensions=com.intellij.lang.implementationTextSelectioner) | [`ImplementationTextSelectioner`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hint/ImplementationTextSelectioner.java) | 
|  | [com.intellij.lang.psiElementExternalizer](https://jb.gg/ipe?extensions=com.intellij.lang.psiElementExternalizer) | [`PsiElementExternalizer`](upsource:///platform/lang-api/src/com/intellij/lang/PsiElementExternalizer.java) | 
|  | [com.intellij.lang.psiStructureViewFactory](https://jb.gg/ipe?extensions=com.intellij.lang.psiStructureViewFactory) | [`PsiStructureViewFactory`](upsource:///platform/editor-ui-api/src/com/intellij/lang/PsiStructureViewFactory.java) | 
|  | [com.intellij.lang.sliceProvider](https://jb.gg/ipe?extensions=com.intellij.lang.sliceProvider) | [`SliceLanguageSupportProvider`](upsource:///platform/lang-impl/src/com/intellij/slicer/SliceLanguageSupportProvider.java) | 
|  | [com.intellij.lang.structureViewExtension](https://jb.gg/ipe?extensions=com.intellij.lang.structureViewExtension) | [`StructureViewExtension`](upsource:///platform/structure-view-impl/src/com/intellij/ide/structureView/StructureViewExtension.java) | 
|  | [com.intellij.lang.substitutor](https://jb.gg/ipe?extensions=com.intellij.lang.substitutor) | [`LanguageSubstitutor`](upsource:///platform/core-api/src/com/intellij/psi/LanguageSubstitutor.java) | 
|  | [com.intellij.lang.surroundDescriptor](https://jb.gg/ipe?extensions=com.intellij.lang.surroundDescriptor) | [`SurroundDescriptor`](upsource:///platform/lang-api/src/com/intellij/lang/surroundWith/SurroundDescriptor.java) | 
|  | [com.intellij.lang.symbolSearchTarget](https://jb.gg/ipe?extensions=com.intellij.lang.symbolSearchTarget) | [`SymbolSearchTargetFactory`](upsource:///platform/lang-impl/src/com/intellij/find/usages/symbol/SymbolSearchTargetFactory.java) | 
|  | [com.intellij.lang.syntaxHighlighter](https://jb.gg/ipe?extensions=com.intellij.lang.syntaxHighlighter) | [`SyntaxHighlighter`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/fileTypes/SyntaxHighlighter.java) | 
|  | [com.intellij.lang.treePatcher](https://jb.gg/ipe?extensions=com.intellij.lang.treePatcher) | [`TreePatcher`](upsource:///platform/core-impl/src/com/intellij/psi/templateLanguages/TreePatcher.java) | 
|  | [com.intellij.lang.unwrapDescriptor](https://jb.gg/ipe?extensions=com.intellij.lang.unwrapDescriptor) | [`UnwrapDescriptor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/unwrap/UnwrapDescriptor.java) | 
|  | [com.intellij.library.presentationProvider](https://jb.gg/ipe?extensions=com.intellij.library.presentationProvider) | [`LibraryPresentationProvider`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/libraries/LibraryPresentationProvider.java) | 
|  | [com.intellij.library.type](https://jb.gg/ipe?extensions=com.intellij.library.type) | [`LibraryType`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/libraries/LibraryType.java) | 
|  | [com.intellij.librarySettingsProvider](https://jb.gg/ipe?extensions=com.intellij.librarySettingsProvider) | [`LibrarySettingsProvider`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/ui/configuration/LibrarySettingsProvider.java) | 
|  | [com.intellij.liveTemplateSubstitutor](https://jb.gg/ipe?extensions=com.intellij.liveTemplateSubstitutor) | [`TemplateSubstitutor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/template/TemplateSubstitutor.java) | 
|  | [com.intellij.longLineInspectionPolicy](https://jb.gg/ipe?extensions=com.intellij.longLineInspectionPolicy) | [`LongLineInspectionPolicy`](upsource:///platform/lang-impl/src/com/intellij/codeInspection/longLine/LongLineInspectionPolicy.java) | 
|  | [com.intellij.macro](https://jb.gg/ipe?extensions=com.intellij.macro) | [`Macro`](upsource:///platform/execution-impl/src/com/intellij/ide/macro/Macro.java) | 
|  | [com.intellij.macroFilter](https://jb.gg/ipe?extensions=com.intellij.macroFilter) | [`MacroFilter`](upsource:///platform/execution-impl/src/com/intellij/ide/macro/MacroFilter.java) | 
|  | [com.intellij.metaDataContributor](https://jb.gg/ipe?extensions=com.intellij.metaDataContributor) | [`MetaDataContributor`](upsource:///platform/core-api/src/com/intellij/psi/meta/MetaDataContributor.java) | 
|  | [com.intellij.methodHierarchyProvider](https://jb.gg/ipe?extensions=com.intellij.methodHierarchyProvider) | [`HierarchyProvider`](upsource:///platform/lang-api/src/com/intellij/ide/hierarchy/HierarchyProvider.java) | 
|  | [com.intellij.methodNavigationOffsetProvider](https://jb.gg/ipe?extensions=com.intellij.methodNavigationOffsetProvider) | [`MethodNavigationOffsetProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/navigation/MethodNavigationOffsetProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.modelScopeItemPresenter](https://jb.gg/ipe?extensions=com.intellij.modelScopeItemPresenter) | [`ModelScopeItemPresenter`](upsource:///platform/lang-impl/src/com/intellij/analysis/dialog/ModelScopeItemPresenter.java) | 
|  | [com.intellij.module.workingDirectoryProvider](https://jb.gg/ipe?extensions=com.intellij.module.workingDirectoryProvider) | [`WorkingDirectoryProvider`](upsource:///platform/execution-impl/src/com/intellij/openapi/module/WorkingDirectoryProvider.java) | 
|  | [com.intellij.moduleBuilder](https://jb.gg/ipe?extensions=com.intellij.moduleBuilder) | [`ModuleBuilder`](upsource:///platform/lang-api/src/com/intellij/ide/util/projectWizard/ModuleBuilder.java) | 
|  | [com.intellij.moduleConfigurationEditorProvider](https://jb.gg/ipe?extensions=com.intellij.moduleConfigurationEditorProvider) | [`ModuleConfigurationEditorProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/roots/ui/configuration/ModuleConfigurationEditorProvider.java) | 
|  | [com.intellij.moduleRendererFactory](https://jb.gg/ipe?extensions=com.intellij.moduleRendererFactory) | [`ModuleRendererFactory`](upsource:///platform/lang-impl/src/com/intellij/ide/util/ModuleRendererFactory.java) | 
|  | [com.intellij.moduleType](https://jb.gg/ipe?extensions=com.intellij.moduleType) | [`ModuleType`](upsource:///platform/lang-api/src/com/intellij/openapi/module/ModuleType.java) | 
|  | [com.intellij.multiLangCommenter](https://jb.gg/ipe?extensions=com.intellij.multiLangCommenter) | [`MultipleLangCommentProvider`](upsource:///platform/lang-impl/src/com/intellij/psi/templateLanguages/MultipleLangCommentProvider.java) | 
|  | [com.intellij.multipleRunLocationsProvider](https://jb.gg/ipe?extensions=com.intellij.multipleRunLocationsProvider) | [`MultipleRunLocationsProvider`](upsource:///platform/lang-api/src/com/intellij/execution/actions/MultipleRunLocationsProvider.kt) | 
|  | [com.intellij.navbar](https://jb.gg/ipe?extensions=com.intellij.navbar) | [`NavBarModelExtension`](upsource:///platform/lang-impl/src/com/intellij/ide/navigationToolbar/NavBarModelExtension.java) | 
|  | [com.intellij.optionsApplicabilityFilter](https://jb.gg/ipe?extensions=com.intellij.optionsApplicabilityFilter) | [`OptionsApplicabilityFilter`](upsource:///platform/lang-impl/src/com/intellij/application/options/OptionsApplicabilityFilter.java) | 
|  | [com.intellij.outOfSourcesChecker](https://jb.gg/ipe?extensions=com.intellij.outOfSourcesChecker) | [`OutOfSourcesChecker`](upsource:///platform/lang-api/src/com/intellij/openapi/projectRoots/OutOfSourcesChecker.java) | 
|  | [com.intellij.packageDependencies.visitor](https://jb.gg/ipe?extensions=com.intellij.packageDependencies.visitor) | [`DependencyVisitorFactory`](upsource:///platform/analysis-impl/src/com/intellij/packageDependencies/DependencyVisitorFactory.java) | 
|  | [com.intellij.pathReferenceProvider](https://jb.gg/ipe?extensions=com.intellij.pathReferenceProvider) | [`PathReferenceProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/paths/PathReferenceProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.patternDialectProvider](https://jb.gg/ipe?extensions=com.intellij.patternDialectProvider) | [`PatternDialectProvider`](upsource:///platform/lang-impl/src/com/intellij/packageDependencies/ui/PatternDialectProvider.java) | 
|  | [com.intellij.patternProvider](https://jb.gg/ipe?extensions=com.intellij.patternProvider) | [`PatternProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/generation/PatternProvider.java) | 
|  | [com.intellij.patterns.patternClass](https://jb.gg/ipe?extensions=com.intellij.patterns.patternClass) | `Object` | 
|  | [com.intellij.presentationProvider](https://jb.gg/ipe?extensions=com.intellij.presentationProvider) | [`PresentationProvider`](upsource:///platform/platform-api/src/com/intellij/ide/presentation/PresentationProvider.java) | 
|  | [com.intellij.previewHintProvider](https://jb.gg/ipe?extensions=com.intellij.previewHintProvider) | [`PreviewHintProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/preview/PreviewHintProvider.java) | 
|  | [com.intellij.printHandler](https://jb.gg/ipe?extensions=com.intellij.printHandler) | [`PrintActionHandler`](upsource:///platform/lang-api/src/com/intellij/ide/actions/PrintActionHandler.java) | 
|  | [com.intellij.printOption](https://jb.gg/ipe?extensions=com.intellij.printOption) | [`PrintOption`](upsource:///platform/lang-impl/src/com/intellij/codeEditor/printing/PrintOption.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.problemFileHighlightFilter](https://jb.gg/ipe?extensions=com.intellij.problemFileHighlightFilter) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 
|  | [com.intellij.problemHighlightFilter](https://jb.gg/ipe?extensions=com.intellij.problemHighlightFilter) | [`ProblemHighlightFilter`](upsource:///platform/analysis-api/src/com/intellij/codeInsight/daemon/ProblemHighlightFilter.java) | 
|  | [com.intellij.programRunner](https://jb.gg/ipe?extensions=com.intellij.programRunner) | [`ProgramRunner`](upsource:///platform/lang-api/src/com/intellij/execution/runners/ProgramRunner.java) | 
|  | [com.intellij.project.converterProvider](https://jb.gg/ipe?extensions=com.intellij.project.converterProvider) | [`ConverterProvider`](upsource:///platform/lang-impl/src/com/intellij/conversion/ConverterProvider.java) | 
|  | [com.intellij.projectFacetListener](https://jb.gg/ipe?extensions=com.intellij.projectFacetListener) | [`ProjectFacetListener`](upsource:///platform/lang-api/src/com/intellij/facet/ProjectFacetListener.java) | 
|  | [com.intellij.projectSdkSetupValidator](https://jb.gg/ipe?extensions=com.intellij.projectSdkSetupValidator) | [`ProjectSdkSetupValidator`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/ProjectSdkSetupValidator.java) | 
|  | [com.intellij.projectStructure.sourceRootEditHandler](https://jb.gg/ipe?extensions=com.intellij.projectStructure.sourceRootEditHandler) | [`ModuleSourceRootEditHandler`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/ui/configuration/ModuleSourceRootEditHandler.java) | 
|  | [com.intellij.projectTaskRunner](https://jb.gg/ipe?extensions=com.intellij.projectTaskRunner) | [`ProjectTaskRunner`](upsource:///platform/lang-api/src/com/intellij/task/ProjectTaskRunner.java) | 
|  | [com.intellij.projectTemplateFileProcessor](https://jb.gg/ipe?extensions=com.intellij.projectTemplateFileProcessor) | [`ProjectTemplateFileProcessor`](upsource:///platform/lang-impl/src/com/intellij/ide/util/projectWizard/ProjectTemplateFileProcessor.java) | 
|  | [com.intellij.projectTemplateParameterFactory](https://jb.gg/ipe?extensions=com.intellij.projectTemplateParameterFactory) | [`ProjectTemplateParameterFactory`](upsource:///platform/lang-api/src/com/intellij/ide/util/projectWizard/ProjectTemplateParameterFactory.java) | 
|  | [com.intellij.projectViewNestingRulesProvider](https://jb.gg/ipe?extensions=com.intellij.projectViewNestingRulesProvider) | [`ProjectViewNestingRulesProvider`](upsource:///platform/lang-api/src/com/intellij/ide/projectView/ProjectViewNestingRulesProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectViewNodeDecorator](https://jb.gg/ipe?extensions=com.intellij.projectViewNodeDecorator) | [`ProjectViewNodeDecorator`](upsource:///platform/lang-impl/src/com/intellij/ide/projectView/ProjectViewNodeDecorator.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectViewPane](https://jb.gg/ipe?extensions=com.intellij.projectViewPane) | [`AbstractProjectViewPane`](upsource:///platform/lang-impl/src/com/intellij/ide/projectView/impl/AbstractProjectViewPane.java) | 
|  | [com.intellij.projectViewPaneSelectionHelper](https://jb.gg/ipe?extensions=com.intellij.projectViewPaneSelectionHelper) | [`ProjectViewPaneSelectionHelper`](upsource:///platform/lang-impl/src/com/intellij/ide/projectView/impl/ProjectViewPaneSelectionHelper.java) | 
|  | [com.intellij.psi.declarationProvider](https://jb.gg/ipe?extensions=com.intellij.psi.declarationProvider) | [`PsiSymbolDeclarationProvider`](upsource:///platform/core-api/src/com/intellij/model/psi/PsiSymbolDeclarationProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.psi.referenceProvider](https://jb.gg/ipe?extensions=com.intellij.psi.referenceProvider) | [`PsiReferenceProvider`](upsource:///platform/core-api/src/com/intellij/psi/PsiReferenceProvider.java) | 
|  | [com.intellij.psiViewerExtension](https://jb.gg/ipe?extensions=com.intellij.psiViewerExtension) | [`PsiViewerExtension`](upsource:///platform/lang-impl/src/com/intellij/internal/psiView/PsiViewerExtension.java) | 
|  | [com.intellij.qualifiedNameProvider](https://jb.gg/ipe?extensions=com.intellij.qualifiedNameProvider) | [`QualifiedNameProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/QualifiedNameProvider.java) | 
|  | [com.intellij.readWriteAccessDetector](https://jb.gg/ipe?extensions=com.intellij.readWriteAccessDetector) | [`ReadWriteAccessDetector`](upsource:///platform/core-api/src/com/intellij/codeInsight/highlighting/ReadWriteAccessDetector.java) | 
|  | [com.intellij.readerModeMatcher](https://jb.gg/ipe?extensions=com.intellij.readerModeMatcher) | [`ReaderModeMatcher`](upsource:///platform/editor-ui-api/src/com/intellij/codeInsight/actions/ReaderModeMatcher.kt) | 
|  | [com.intellij.readerModeProvider](https://jb.gg/ipe?extensions=com.intellij.readerModeProvider) | [`ReaderModeProvider`](upsource:///platform/editor-ui-api/src/com/intellij/codeInsight/actions/ReaderModeProvider.kt) | 
|  | [com.intellij.refGraphAnnotator](https://jb.gg/ipe?extensions=com.intellij.refGraphAnnotator) | [`RefGraphAnnotator`](upsource:///platform/analysis-api/src/com/intellij/codeInspection/reference/RefGraphAnnotator.java) | 
|  | [com.intellij.referenceImporter](https://jb.gg/ipe?extensions=com.intellij.referenceImporter) | [`ReferenceImporter`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/daemon/ReferenceImporter.java) | 
|  | [com.intellij.referenceInjector](https://jb.gg/ipe?extensions=com.intellij.referenceInjector) | [`ReferenceInjector`](upsource:///platform/analysis-api/src/com/intellij/psi/injection/ReferenceInjector.java) | 
|  | [com.intellij.referenceProviderType](https://jb.gg/ipe?extensions=com.intellij.referenceProviderType) | [`PsiReferenceProvider`](upsource:///platform/core-api/src/com/intellij/psi/PsiReferenceProvider.java) | 
|  | [com.intellij.retypeFileAssistant](https://jb.gg/ipe?extensions=com.intellij.retypeFileAssistant) | [`RetypeFileAssistant`](upsource:///platform/lang-impl/src/com/intellij/internal/retype/RetypeFileAction.kt) | 
|  | [com.intellij.roots.watchedRootsProvider](https://jb.gg/ipe?extensions=com.intellij.roots.watchedRootsProvider) | [`WatchedRootsProvider`](upsource:///platform/lang-api/src/com/intellij/openapi/roots/WatchedRootsProvider.java) | 
|  | [com.intellij.runAnything.commandCustomizer](https://jb.gg/ipe?extensions=com.intellij.runAnything.commandCustomizer) | [`RunAnythingCommandCustomizer`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/runAnything/commands/RunAnythingCommandCustomizer.java) | 
|  | [com.intellij.runAnything.commandHandler](https://jb.gg/ipe?extensions=com.intellij.runAnything.commandHandler) | [`RunAnythingCommandHandler`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/runAnything/handlers/RunAnythingCommandHandler.java) | 
|  | [com.intellij.runAnything.executionProvider](https://jb.gg/ipe?extensions=com.intellij.runAnything.executionProvider) | [`RunAnythingProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/runAnything/activity/RunAnythingProvider.java) | 
|  | [com.intellij.runAnything.helpGroup](https://jb.gg/ipe?extensions=com.intellij.runAnything.helpGroup) | [`RunAnythingHelpGroup`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/runAnything/groups/RunAnythingHelpGroup.java) | 
|  | [com.intellij.runConfigurationBeforeRunProviderDelegate](https://jb.gg/ipe?extensions=com.intellij.runConfigurationBeforeRunProviderDelegate) | [`RunConfigurationBeforeRunProviderDelegate`](upsource:///platform/execution-impl/src/com/intellij/execution/impl/RunConfigurationBeforeRunProviderDelegate.java) | 
|  | [com.intellij.runConfigurationProducer](https://jb.gg/ipe?extensions=com.intellij.runConfigurationProducer) | [`RunConfigurationProducer`](upsource:///platform/lang-api/src/com/intellij/execution/actions/RunConfigurationProducer.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.runConfigurationTemplateProvider](https://jb.gg/ipe?extensions=com.intellij.runConfigurationTemplateProvider) | [`RunConfigurationTemplateProvider`](upsource:///platform/execution-impl/src/com/intellij/execution/impl/RunManagerImpl.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.runConfigurationsSettings](https://jb.gg/ipe?extensions=com.intellij.runConfigurationsSettings) | [`RunConfigurationsSettings`](upsource:///platform/lang-api/src/com/intellij/execution/configurations/RunConfigurationsSettings.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.runDashboardCustomizer](https://jb.gg/ipe?extensions=com.intellij.runDashboardCustomizer) | [`RunDashboardCustomizer`](upsource:///platform/lang-api/src/com/intellij/execution/dashboard/RunDashboardCustomizer.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.runDashboardDefaultTypesProvider](https://jb.gg/ipe?extensions=com.intellij.runDashboardDefaultTypesProvider) | [`RunDashboardDefaultTypesProvider`](upsource:///platform/lang-api/src/com/intellij/execution/dashboard/RunDashboardDefaultTypesProvider.java) | 
|  | [com.intellij.runDashboardGroupingRule](https://jb.gg/ipe?extensions=com.intellij.runDashboardGroupingRule) | [`RunDashboardGroupingRule`](upsource:///platform/lang-api/src/com/intellij/execution/dashboard/RunDashboardGroupingRule.java) | 
|  | [com.intellij.runLineMarkerContributor](https://jb.gg/ipe?extensions=com.intellij.runLineMarkerContributor) | [`RunLineMarkerContributor`](upsource:///platform/execution-impl/src/com/intellij/execution/lineMarker/RunLineMarkerContributor.java) | 
|  | [com.intellij.runningApplicationUpdaterProvider](https://jb.gg/ipe?extensions=com.intellij.runningApplicationUpdaterProvider) | [`RunningApplicationUpdaterProvider`](upsource:///platform/execution-impl/src/com/intellij/execution/update/RunningApplicationUpdaterProvider.java) | 
|  | [com.intellij.saveFileAsTemplateHandler](https://jb.gg/ipe?extensions=com.intellij.saveFileAsTemplateHandler) | [`SaveFileAsTemplateHandler`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/SaveFileAsTemplateHandler.java) | 
|  | [com.intellij.scopeDescriptorProvider](https://jb.gg/ipe?extensions=com.intellij.scopeDescriptorProvider) | [`ScopeDescriptorProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/util/scopeChooser/ScopeDescriptorProvider.java) | 
|  | [com.intellij.scopeParserExtension](https://jb.gg/ipe?extensions=com.intellij.scopeParserExtension) | [`PackageSetParserExtension`](upsource:///platform/lang-impl/src/com/intellij/psi/search/scope/packageSet/PackageSetParserExtension.java) | 
|  | [com.intellij.scratch.creationHelper](https://jb.gg/ipe?extensions=com.intellij.scratch.creationHelper) | [`ScratchFileCreationHelper`](upsource:///platform/lang-impl/src/com/intellij/ide/scratch/ScratchFileCreationHelper.java) | 
|  | [com.intellij.scratch.rootType](https://jb.gg/ipe?extensions=com.intellij.scratch.rootType) | [`RootType`](upsource:///platform/lang-api/src/com/intellij/ide/scratch/RootType.java) | 
|  | [com.intellij.sdkDownload](https://jb.gg/ipe?extensions=com.intellij.sdkDownload) | [`SdkDownload`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/ui/configuration/projectRoot/SdkDownload.java) | 
|  | [com.intellij.sdkFinder](https://jb.gg/ipe?extensions=com.intellij.sdkFinder) | [`SdkFinder`](upsource:///platform/projectModel-impl/src/com/intellij/openapi/roots/impl/SdkFinder.java) | 
|  | [com.intellij.sdkType](https://jb.gg/ipe?extensions=com.intellij.sdkType) | [`SdkType`](upsource:///platform/lang-api/src/com/intellij/openapi/projectRoots/SdkType.java) | 
|  | [com.intellij.searchEverywhereClassifier](https://jb.gg/ipe?extensions=com.intellij.searchEverywhereClassifier) | [`SearchEverywhereClassifier`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/SearchEverywhereClassifier.java) | 
|  | [com.intellij.searchEverywhereContributor](https://jb.gg/ipe?extensions=com.intellij.searchEverywhereContributor) | [`SearchEverywhereContributorFactory`](upsource:///platform/lang-api/src/com/intellij/ide/actions/searcheverywhere/SearchEverywhereContributorFactory.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.searchEverywhereResultsEqualityProvider](https://jb.gg/ipe?extensions=com.intellij.searchEverywhereResultsEqualityProvider) | [`SEResultsEqualityProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/searcheverywhere/SEResultsEqualityProvider.java) | 
|  | [com.intellij.searchScopesProvider](https://jb.gg/ipe?extensions=com.intellij.searchScopesProvider) | [`SearchScopeProvider`](upsource:///platform/analysis-impl/src/com/intellij/psi/search/SearchScopeProvider.java) | 
|  | [com.intellij.searcher](https://jb.gg/ipe?extensions=com.intellij.searcher) | [`Searcher`](upsource:///platform/indexing-api/src/com/intellij/model/search/Searcher.java) | 
|  | [com.intellij.semContributor](https://jb.gg/ipe?extensions=com.intellij.semContributor) | [`SemContributor`](upsource:///platform/lang-api/src/com/intellij/semantic/SemContributor.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.serviceViewContributor](https://jb.gg/ipe?extensions=com.intellij.serviceViewContributor) | [`ServiceViewContributor`](upsource:///platform/lang-api/src/com/intellij/execution/services/ServiceViewContributor.java) | 
|  | [com.intellij.silentChangeVetoer](https://jb.gg/ipe?extensions=com.intellij.silentChangeVetoer) | [`SilentChangeVetoer`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/impl/SilentChangeVetoer.kt) | 
|  | [com.intellij.stacktrace.fold](https://jb.gg/ipe?extensions=com.intellij.stacktrace.fold) | `n/a` | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.stacktrace.fold.line.modifier](https://jb.gg/ipe?extensions=com.intellij.stacktrace.fold.line.modifier) | [`ConsoleLineModifier`](upsource:///platform/lang-impl/src/com/intellij/execution/console/ConsoleLineModifier.java) | 
|  | [com.intellij.statistician](https://jb.gg/ipe?extensions=com.intellij.statistician) | [`Statistician`](upsource:///platform/analysis-api/src/com/intellij/psi/statistics/Statistician.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.stepsBeforeRunProvider](https://jb.gg/ipe?extensions=com.intellij.stepsBeforeRunProvider) | [`BeforeRunTaskProvider`](upsource:///platform/lang-api/src/com/intellij/execution/BeforeRunTaskProvider.java) | 
|  | [com.intellij.structureViewBuilder](https://jb.gg/ipe?extensions=com.intellij.structureViewBuilder) | [`StructureViewBuilder`](upsource:///platform/editor-ui-api/src/com/intellij/ide/structureView/StructureViewBuilder.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.symbolNavigation](https://jb.gg/ipe?extensions=com.intellij.symbolNavigation) | [`SymbolNavigationProvider`](upsource:///platform/core-api/src/com/intellij/navigation/SymbolNavigationProvider.java) | 
|  | [com.intellij.symbolPresentation](https://jb.gg/ipe?extensions=com.intellij.symbolPresentation) | [`SymbolPresentationProvider`](upsource:///platform/core-api/src/com/intellij/model/presentation/SymbolPresentationProvider.java) | 
|  | [com.intellij.targetElementEvaluator](https://jb.gg/ipe?extensions=com.intellij.targetElementEvaluator) | [`TargetElementEvaluator`](upsource:///platform/core-impl/src/com/intellij/codeInsight/TargetElementEvaluator.java) | 
|  | [com.intellij.targetElementUtilExtender](https://jb.gg/ipe?extensions=com.intellij.targetElementUtilExtender) | [`TargetElementUtilExtender`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/TargetElementUtilExtender.java) | 
|  | [com.intellij.templateCompletionProcessor](https://jb.gg/ipe?extensions=com.intellij.templateCompletionProcessor) | [`TemplateCompletionProcessor`](upsource:///platform/analysis-impl/src/com/intellij/codeInsight/template/macro/TemplateCompletionProcessor.java) | 
|  | [com.intellij.testActionProvider](https://jb.gg/ipe?extensions=com.intellij.testActionProvider) | [`ToggleModelActionProvider`](upsource:///platform/testRunner/src/com/intellij/execution/testframework/ToggleModelActionProvider.java) | 
|  | [com.intellij.testCreator](https://jb.gg/ipe?extensions=com.intellij.testCreator) | [`TestCreator`](upsource:///platform/lang-api/src/com/intellij/testIntegration/TestCreator.java) | 
|  | [com.intellij.testFinder](https://jb.gg/ipe?extensions=com.intellij.testFinder) | [`TestFinder`](upsource:///platform/lang-api/src/com/intellij/testIntegration/TestFinder.java) | 
|  | [com.intellij.testSourcesFilter](https://jb.gg/ipe?extensions=com.intellij.testSourcesFilter) | [`TestSourcesFilter`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/TestSourcesFilter.java) | 
|  | [com.intellij.testSrcLocator](https://jb.gg/ipe?extensions=com.intellij.testSrcLocator) | [~~`TestLocationProvider`~~](upsource:///platform/execution-impl/src/com/intellij/testIntegration/TestLocationProvider.java) | 
|  | [com.intellij.todoExtraPlaces](https://jb.gg/ipe?extensions=com.intellij.todoExtraPlaces) | [`ExtraPlaceChecker`](upsource:///platform/indexing-impl/src/com/intellij/psi/impl/cache/impl/todo/TodoIndexers.java) | 
|  | [com.intellij.todoIndexer](https://jb.gg/ipe?extensions=com.intellij.todoIndexer) | [`DataIndexer`](upsource:///platform/util/src/com/intellij/util/indexing/DataIndexer.java) | 
|  | [com.intellij.toolsCustomizer](https://jb.gg/ipe?extensions=com.intellij.toolsCustomizer) | [`ToolsCustomizer`](upsource:///platform/lang-impl/src/com/intellij/tools/ToolsCustomizer.java) | 
|  | [com.intellij.toolsProvider](https://jb.gg/ipe?extensions=com.intellij.toolsProvider) | [`ToolsProvider`](upsource:///platform/lang-impl/src/com/intellij/tools/ToolsProvider.java) | 
|  | [com.intellij.trafficLightRendererContributor](https://jb.gg/ipe?extensions=com.intellij.trafficLightRendererContributor) | [`TrafficLightRendererContributor`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/daemon/impl/TrafficLightRendererContributor.java) | 
|  | [com.intellij.treeGenerator](https://jb.gg/ipe?extensions=com.intellij.treeGenerator) | [`TreeGenerator`](upsource:///platform/core-impl/src/com/intellij/psi/impl/source/tree/TreeGenerator.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.treeStructureProvider](https://jb.gg/ipe?extensions=com.intellij.treeStructureProvider) | [`TreeStructureProvider`](upsource:///platform/editor-ui-api/src/com/intellij/ide/projectView/TreeStructureProvider.java) | 
|  | [com.intellij.typeDeclarationProvider](https://jb.gg/ipe?extensions=com.intellij.typeDeclarationProvider) | [`TypeDeclarationProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/navigation/actions/TypeDeclarationProvider.java) | 
|  | [com.intellij.typeHierarchyProvider](https://jb.gg/ipe?extensions=com.intellij.typeHierarchyProvider) | [`HierarchyProvider`](upsource:///platform/lang-api/src/com/intellij/ide/hierarchy/HierarchyProvider.java) | 
|  | [com.intellij.typeIcon](https://jb.gg/ipe?extensions=com.intellij.typeIcon) | `Object` | 
|  | [com.intellij.typeName](https://jb.gg/ipe?extensions=com.intellij.typeName) | `Object` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.uiDebuggerExtension](https://jb.gg/ipe?extensions=com.intellij.uiDebuggerExtension) | [`UiDebuggerExtension`](upsource:///platform/lang-impl/src/com/intellij/ui/debugger/UiDebuggerExtension.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.usageContextPanelProvider](https://jb.gg/ipe?extensions=com.intellij.usageContextPanelProvider) | [`Provider`](upsource:///platform/usageView/src/com/intellij/usages/UsageContextPanel.java) | 
|  | [com.intellij.usageFilteringRuleProvider](https://jb.gg/ipe?extensions=com.intellij.usageFilteringRuleProvider) | [`UsageFilteringRuleProvider`](upsource:///platform/usageView/src/com/intellij/usages/rules/UsageFilteringRuleProvider.java) | 
|  | [com.intellij.usageGroupingRuleProvider](https://jb.gg/ipe?extensions=com.intellij.usageGroupingRuleProvider) | [`UsageGroupingRuleProvider`](upsource:///platform/usageView/src/com/intellij/usages/rules/UsageGroupingRuleProvider.java) | 
|  | [com.intellij.usageTargetProvider](https://jb.gg/ipe?extensions=com.intellij.usageTargetProvider) | [`UsageTargetProvider`](upsource:///platform/usageView/src/com/intellij/usages/UsageTargetProvider.java) | 
|  | [com.intellij.usageToPsiElementProvider](https://jb.gg/ipe?extensions=com.intellij.usageToPsiElementProvider) | [`UsageToPsiElementProvider`](upsource:///platform/usageView/src/com/intellij/usages/UsageToPsiElementProvider.java) | 
|  | [com.intellij.usageTypeProvider](https://jb.gg/ipe?extensions=com.intellij.usageTypeProvider) | [`UsageTypeProvider`](upsource:///platform/usageView/src/com/intellij/usages/impl/rules/UsageTypeProvider.java) | 
|  | [com.intellij.usageViewElementsListener](https://jb.gg/ipe?extensions=com.intellij.usageViewElementsListener) | [`UsageViewElementsListener`](upsource:///platform/usageView/src/com/intellij/usages/impl/UsageViewElementsListener.java) | 
|  | [com.intellij.usageViewFactory](https://jb.gg/ipe?extensions=com.intellij.usageViewFactory) | [`UsageViewFactory`](upsource:///platform/usageView/src/com/intellij/usages/impl/UsageViewFactory.java) | 
|  | [com.intellij.virtualFileQualifiedNameProvider](https://jb.gg/ipe?extensions=com.intellij.virtualFileQualifiedNameProvider) | [`VirtualFileQualifiedNameProvider`](upsource:///platform/lang-impl/src/com/intellij/ide/actions/CopyReferenceAction.java) | 

## [lint-plugin.xml](upsource:///android/lint/src/META-INF/lint-plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.lint.common.lintIdeSupport](https://jb.gg/ipe?extensions=com.android.tools.idea.lint.common.lintIdeSupport) | [`LintIdeSupport`](upsource:///android/lint/src/com/android/tools/idea/lint/common/LintIdeSupport.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.tools.idea.lint.common.lintQuickFixProvider](https://jb.gg/ipe?extensions=com.android.tools.idea.lint.common.lintQuickFixProvider) | [`LintIdeQuickFixProvider`](upsource:///android/lint/src/com/android/tools/idea/lint/common/LintIdeQuickFixProvider.java) | 

## [ManifestSupport.xml](upsource:///java/manifest/src/META-INF/ManifestSupport.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.manifest.parser.provider](https://jb.gg/ipe?extensions=com.intellij.manifest.parser.provider) | [`HeaderParserProvider`](upsource:///java/manifest/src/org/jetbrains/lang/manifest/header/HeaderParserProvider.java) | 

## [org.editorconfig.editorconfigjetbrains](upsource:///plugins/editorconfig/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [editorconfig.exportProvider](https://jb.gg/ipe?extensions=editorconfig.exportProvider) | [`EditorConfigExportProvider`](upsource:///plugins/editorconfig/src/org/editorconfig/settings/EditorConfigExportProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [editorconfig.optionDescriptorProvider](https://jb.gg/ipe?extensions=editorconfig.optionDescriptorProvider) | [`EditorConfigOptionDescriptorProvider`](upsource:///plugins/editorconfig/src/org/editorconfig/language/extensions/EditorConfigOptionDescriptorProvider.kt) | 

## [org.intellij.groovy](upsource:///plugins/groovy/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.intellij.groovy.applicabilityProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.applicabilityProvider) | [`GroovyApplicabilityProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyApplicabilityProvider.java) | 
|  | [org.intellij.groovy.astTransformationSupport](https://jb.gg/ipe?extensions=org.intellij.groovy.astTransformationSupport) | [`AstTransformationSupport`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/transformations/AstTransformationSupport.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.intellij.groovy.callTypeCalculator](https://jb.gg/ipe?extensions=org.intellij.groovy.callTypeCalculator) | [`GrCallTypeCalculator`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/typing/GrCallTypeCalculator.kt) | 
|  | [org.intellij.groovy.classDescriptor](https://jb.gg/ipe?extensions=org.intellij.groovy.classDescriptor) | `n/a` | 
|  | [org.intellij.groovy.closureCompleter](https://jb.gg/ipe?extensions=org.intellij.groovy.closureCompleter) | [`ClosureCompleter`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/lang/completion/ClosureCompleter.java) | 
|  | [org.intellij.groovy.closureMissingMethodContributor](https://jb.gg/ipe?extensions=org.intellij.groovy.closureMissingMethodContributor) | [`ClosureMissingMethodContributor`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/ClosureMissingMethodContributor.java) | 
|  | [org.intellij.groovy.configSlurperSupport](https://jb.gg/ipe?extensions=org.intellij.groovy.configSlurperSupport) | [`ConfigSlurperSupport`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/configSlurper/ConfigSlurperSupport.java) | 
|  | [org.intellij.groovy.convertToJava.customMethodInvocator](https://jb.gg/ipe?extensions=org.intellij.groovy.convertToJava.customMethodInvocator) | [`CustomMethodInvocator`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/refactoring/convertToJava/invocators/CustomMethodInvocator.java) | 
|  | [org.intellij.groovy.customAnnotationChecker](https://jb.gg/ipe?extensions=org.intellij.groovy.customAnnotationChecker) | [`CustomAnnotationChecker`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/annotator/checkers/CustomAnnotationChecker.java) | 
|  | [org.intellij.groovy.delegatesToProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.delegatesToProvider) | [`GrDelegatesToProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/delegatesTo/GrDelegatesToProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.intellij.groovy.elementFilter](https://jb.gg/ipe?extensions=org.intellij.groovy.elementFilter) | [`GroovyElementFilter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/GroovyElementFilter.kt) | 
|  | [org.intellij.groovy.expectedPackageNameProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.expectedPackageNameProvider) | [`ExpectedPackageNameProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/ExpectedPackageNameProvider.kt) | 
|  | [org.intellij.groovy.expectedTypesContributor](https://jb.gg/ipe?extensions=org.intellij.groovy.expectedTypesContributor) | [`GroovyExpectedTypesContributor`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/expectedTypes/GroovyExpectedTypesContributor.java) | 
|  | [org.intellij.groovy.gdslScriptProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.gdslScriptProvider) | [`GdslScriptProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/dsl/GdslScriptProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.intellij.groovy.gdslTopLevelProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.gdslTopLevelProvider) | [`GdslMembersProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/dsl/dsltop/GdslMembersProvider.java) | 
|  | [org.intellij.groovy.groovyFrameworkConfigNotification](https://jb.gg/ipe?extensions=org.intellij.groovy.groovyFrameworkConfigNotification) | [`GroovyFrameworkConfigNotification`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/annotator/GroovyFrameworkConfigNotification.java) | 
|  | [org.intellij.groovy.groovySourceFolderDetector](https://jb.gg/ipe?extensions=org.intellij.groovy.groovySourceFolderDetector) | [`GroovySourceFolderDetector`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/actions/GroovySourceFolderDetector.java) | 
|  | [org.intellij.groovy.importContributor](https://jb.gg/ipe?extensions=org.intellij.groovy.importContributor) | [`GrImportContributor`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/imports/GrImportContributor.java) | 
|  | [org.intellij.groovy.inlayHintFilter](https://jb.gg/ipe?extensions=org.intellij.groovy.inlayHintFilter) | [`GroovyInlayHintFilter`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/editor/GroovyInlayHintFilter.java) | 
|  | [org.intellij.groovy.mapContentProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.mapContentProvider) | [`GroovyMapContentProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyMapContentProvider.java) | 
|  | [org.intellij.groovy.membersContributor](https://jb.gg/ipe?extensions=org.intellij.groovy.membersContributor) | [`NonCodeMembersContributor`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/NonCodeMembersContributor.java) | 
|  | [org.intellij.groovy.methodComparator](https://jb.gg/ipe?extensions=org.intellij.groovy.methodComparator) | [`GrMethodComparator`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/GrMethodComparator.java) | 
|  | [org.intellij.groovy.methodDescriptor](https://jb.gg/ipe?extensions=org.intellij.groovy.methodDescriptor) | `n/a` | 
|  | [org.intellij.groovy.methodMayBeStaticInspectionFilter](https://jb.gg/ipe?extensions=org.intellij.groovy.methodMayBeStaticInspectionFilter) | [`GrMethodMayBeStaticInspectionFilter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/codeInspection/declaration/GrMethodMayBeStaticInspectionFilter.java) | 
|  | [org.intellij.groovy.mvc.command.executor](https://jb.gg/ipe?extensions=org.intellij.groovy.mvc.command.executor) | [`MvcCommandExecutor`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/mvc/MvcCommandExecutor.java) | 
|  | [org.intellij.groovy.mvc.framework](https://jb.gg/ipe?extensions=org.intellij.groovy.mvc.framework) | [`MvcFramework`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/mvc/MvcFramework.java) | 
|  | [org.intellij.groovy.mvc.runCommandHandler](https://jb.gg/ipe?extensions=org.intellij.groovy.mvc.runCommandHandler) | [`MvcRunCommandActionHandler`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/mvc/actions/MvcRunCommandActionHandler.java) | 
|  | [org.intellij.groovy.namedArgumentProvider](https://jb.gg/ipe?extensions=org.intellij.groovy.namedArgumentProvider) | [`GroovyNamedArgumentProvider`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyNamedArgumentProvider.java) | 
|  | [org.intellij.groovy.overloadResolver](https://jb.gg/ipe?extensions=org.intellij.groovy.overloadResolver) | [`GroovyOverloadResolver`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/resolve/api/GroovyOverloadResolver.java) | 
|  | [org.intellij.groovy.positionManagerDelegate](https://jb.gg/ipe?extensions=org.intellij.groovy.positionManagerDelegate) | [`ScriptPositionManagerHelper`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/extensions/debugger/ScriptPositionManagerHelper.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [org.intellij.groovy.psiEnhancerCategory](https://jb.gg/ipe?extensions=org.intellij.groovy.psiEnhancerCategory) | [`PsiEnhancerCategory`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/dsl/psi/PsiEnhancerCategory.java) | 
|  | [org.intellij.groovy.referenceTypeEnhancer](https://jb.gg/ipe?extensions=org.intellij.groovy.referenceTypeEnhancer) | [`GrReferenceTypeEnhancer`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/typeEnhancers/GrReferenceTypeEnhancer.java) | 
|  | [org.intellij.groovy.renameHelper](https://jb.gg/ipe?extensions=org.intellij.groovy.renameHelper) | [`GrRenameHelper`](upsource:///plugins/groovy/src/org/jetbrains/plugins/groovy/refactoring/rename/GrRenameHelper.java) | 
|  | [org.intellij.groovy.scriptTypeDetector](https://jb.gg/ipe?extensions=org.intellij.groovy.scriptTypeDetector) | [`GroovyScriptTypeDetector`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyScriptTypeDetector.java) | 
|  | [org.intellij.groovy.signatureHintProcessor](https://jb.gg/ipe?extensions=org.intellij.groovy.signatureHintProcessor) | [`SignatureHintProcessor`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/typeEnhancers/SignatureHintProcessor.java) | 
|  | [org.intellij.groovy.typeAugmenter](https://jb.gg/ipe?extensions=org.intellij.groovy.typeAugmenter) | [`TypeAugmenter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/dataFlow/types/TypeAugmenter.kt) | 
|  | [org.intellij.groovy.typeCalculator](https://jb.gg/ipe?extensions=org.intellij.groovy.typeCalculator) | [`GrTypeCalculator`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/typing/GrTypeCalculator.java) | 
|  | [org.intellij.groovy.typeConverter](https://jb.gg/ipe?extensions=org.intellij.groovy.typeConverter) | [`GrTypeConverter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/typeEnhancers/GrTypeConverter.java) | 
|  | [org.intellij.groovy.unresolvedHighlightFileFilter](https://jb.gg/ipe?extensions=org.intellij.groovy.unresolvedHighlightFileFilter) | [`GroovyUnresolvedHighlightFileFilter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyUnresolvedHighlightFileFilter.java) | 
|  | [org.intellij.groovy.unresolvedHighlightFilter](https://jb.gg/ipe?extensions=org.intellij.groovy.unresolvedHighlightFilter) | [`GroovyUnresolvedHighlightFilter`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/extensions/GroovyUnresolvedHighlightFilter.java) | 
|  | [org.intellij.groovy.variableEnhancer](https://jb.gg/ipe?extensions=org.intellij.groovy.variableEnhancer) | [`GrVariableEnhancer`](upsource:///plugins/groovy/groovy-psi/src/org/jetbrains/plugins/groovy/lang/psi/typeEnhancers/GrVariableEnhancer.java) | 

## [org.intellij.intelliLang](upsource:///plugins/IntelliLang/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.intellij.intelliLang.injectionConfig](https://jb.gg/ipe?extensions=org.intellij.intelliLang.injectionConfig) | `n/a` | 
|  | [org.intellij.intelliLang.languageSupport](https://jb.gg/ipe?extensions=org.intellij.intelliLang.languageSupport) | [`LanguageInjectionSupport`](upsource:///plugins/IntelliLang/src/org/intellij/plugins/intelliLang/inject/LanguageInjectionSupport.java) | 

## [org.jetbrains.debugger.streams](upsource:///plugins/stream-debugger/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.debugger.streams.librarySupport](https://jb.gg/ipe?extensions=org.jetbrains.debugger.streams.librarySupport) | [`LibrarySupportProvider`](upsource:///plugins/stream-debugger/src/com/intellij/debugger/streams/lib/LibrarySupportProvider.java) | 

## [org.jetbrains.idea.eclipse](upsource:///plugins/eclipse/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.idea.eclipse.natureImporter](https://jb.gg/ipe?extensions=org.jetbrains.idea.eclipse.natureImporter) | [`EclipseNatureImporter`](upsource:///plugins/eclipse/src/org/jetbrains/idea/eclipse/importWizard/EclipseNatureImporter.java) | 

## [org.jetbrains.idea.gradle.dsl.impl](upsource:///plugins/gradle-dsl-impl/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.idea.gradle.dsl.parserFactory](https://jb.gg/ipe?extensions=org.jetbrains.idea.gradle.dsl.parserFactory) | [`GradleDslConverterFactory`](upsource:///plugins/gradle-dsl-impl/src/com/android/tools/idea/gradle/dsl/parser/GradleDslConverterFactory.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [org.jetbrains.idea.gradle.dsl.upToDateChecker](https://jb.gg/ipe?extensions=org.jetbrains.idea.gradle.dsl.upToDateChecker) | [`UpToDateChecker`](upsource:///plugins/gradle-dsl-impl/src/com/android/tools/idea/gradle/dsl/UpToDateChecker.java) | 

## [org.jetbrains.idea.maven](upsource:///plugins/maven/src/main/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.idea.maven.additional.importing.settings](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.additional.importing.settings) | [`AdditionalMavenImportingSettings`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/project/AdditionalMavenImportingSettings.java) | 
|  | [org.jetbrains.idea.maven.archetypesProvider](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.archetypesProvider) | [`MavenArchetypesProvider`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/indices/MavenArchetypesProvider.java) | 
|  | [org.jetbrains.idea.maven.artifactBuilder](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.artifactBuilder) | [`MavenArtifactBuilder`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/execution/build/MavenArtifactBuilder.java) | 
|  | [org.jetbrains.idea.maven.compiler](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.compiler) | [`MavenCompilerExtension`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/importing/MavenCompilerExtension.java) | 
|  | [org.jetbrains.idea.maven.executionEnvironmentProvider](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.executionEnvironmentProvider) | [`MavenExecutionEnvironmentProvider`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/execution/build/MavenExecutionEnvironmentProvider.java) | 
|  | [org.jetbrains.idea.maven.importer](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.importer) | [`MavenImporter`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/importing/MavenImporter.java) | 
|  | [org.jetbrains.idea.maven.manifestImporter](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.manifestImporter) | [`ManifestImporter`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/importing/ManifestImporter.java) | 
|  | [org.jetbrains.idea.maven.pluginDescriptor](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.pluginDescriptor) | `n/a` | 
|  | [org.jetbrains.idea.maven.repositoryProvider](https://jb.gg/ipe?extensions=org.jetbrains.idea.maven.repositoryProvider) | [`MavenRepositoryProvider`](upsource:///plugins/maven/src/main/java/org/jetbrains/idea/maven/indices/MavenRepositoryProvider.java) | 

## [org.jetbrains.plugins.gradle](upsource:///plugins/gradle/java/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [org.jetbrains.plugins.gradle.buildTasksProvider](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.buildTasksProvider) | [`GradleBuildTasksProvider`](upsource:///plugins/gradle/java/src/execution/build/GradleBuildTasksProvider.java) | 
|  | [org.jetbrains.plugins.gradle.frameworkSupport](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.frameworkSupport) | [`GradleFrameworkSupportProvider`](upsource:///plugins/gradle/java/src/frameworkSupport/GradleFrameworkSupportProvider.java) | 
|  | [org.jetbrains.plugins.gradle.kotlinDslFrameworkSupport](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.kotlinDslFrameworkSupport) | [`KotlinDslGradleFrameworkSupportProvider`](upsource:///plugins/gradle/java/src/frameworkSupport/KotlinDslGradleFrameworkSupportProvider.java) | 
|  | [org.jetbrains.plugins.gradle.testTasksProvider](https://jb.gg/ipe?extensions=org.jetbrains.plugins.gradle.testTasksProvider) | [`GradleTestTasksProvider`](upsource:///plugins/gradle/java/src/execution/test/runner/GradleTestTasksProvider.java) | 

## [org.jetbrains.plugins.yaml](upsource:///plugins/yaml/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.yaml.customStructureViewFactory](https://jb.gg/ipe?extensions=com.intellij.yaml.customStructureViewFactory) | [`YAMLCustomStructureViewFactory`](upsource:///plugins/yaml/src/org/jetbrains/yaml/structureView/YAMLCustomStructureViewFactory.java) | 

## [PlatformExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/PlatformExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.ApplicationLoadListener](https://jb.gg/ipe?extensions=com.intellij.ApplicationLoadListener) | [`ApplicationLoadListener`](upsource:///platform/platform-impl/src/com/intellij/ide/ApplicationLoadListener.java) | 
|  | [com.intellij.aboutPopupDescriptionProvider](https://jb.gg/ipe?extensions=com.intellij.aboutPopupDescriptionProvider) | [`AboutPopupDescriptionProvider`](upsource:///platform/platform-impl/src/com/intellij/ide/AboutPopupDescriptionProvider.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.achromatopsiaSupport](https://jb.gg/ipe?extensions=com.intellij.achromatopsiaSupport) | [`ColorBlindnessSupport`](upsource:///platform/editor-ui-api/src/com/intellij/ide/ui/ColorBlindnessSupport.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.actionConfigurationCustomizer](https://jb.gg/ipe?extensions=com.intellij.actionConfigurationCustomizer) | [`ActionConfigurationCustomizer`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/impl/ActionConfigurationCustomizer.java) | 
|  | [com.intellij.actionFromOptionDescriptorProvider](https://jb.gg/ipe?extensions=com.intellij.actionFromOptionDescriptorProvider) | [`ActionFromOptionDescriptorProvider`](upsource:///platform/platform-api/src/com/intellij/ide/ui/search/ActionFromOptionDescriptorProvider.java) | 
|  | [com.intellij.actionPromoter](https://jb.gg/ipe?extensions=com.intellij.actionPromoter) | [`ActionPromoter`](upsource:///platform/platform-api/src/com/intellij/openapi/actionSystem/ActionPromoter.java) | 
|  | [com.intellij.additionalTextAttributes](https://jb.gg/ipe?extensions=com.intellij.additionalTextAttributes) | `n/a` | 
|  | [com.intellij.appStarter](https://jb.gg/ipe?extensions=com.intellij.appStarter) | [`ApplicationStarter`](upsource:///platform/platform-api/src/com/intellij/openapi/application/ApplicationStarter.java) | 
|  | [com.intellij.applicationConfigurable](https://jb.gg/ipe?extensions=com.intellij.applicationConfigurable) | [`Configurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/Configurable.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.applicationInitializedListener](https://jb.gg/ipe?extensions=com.intellij.applicationInitializedListener) | [`ApplicationInitializedListener`](upsource:///platform/platform-api/src/com/intellij/ide/ApplicationInitializedListener.java) | 
|  | [com.intellij.breadcrumbsPresentationProvider](https://jb.gg/ipe?extensions=com.intellij.breadcrumbsPresentationProvider) | [`BreadcrumbsPresentationProvider`](upsource:///platform/platform-api/src/com/intellij/xml/breadcrumbs/BreadcrumbsPresentationProvider.java) | 
|  | [com.intellij.bundledColorScheme](https://jb.gg/ipe?extensions=com.intellij.bundledColorScheme) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.bundledInspectionProfile](https://jb.gg/ipe?extensions=com.intellij.bundledInspectionProfile) | `n/a` | 
|  | [com.intellij.bundledKeymap](https://jb.gg/ipe?extensions=com.intellij.bundledKeymap) | `n/a` | 
|  | [com.intellij.bundledQuickListsProvider](https://jb.gg/ipe?extensions=com.intellij.bundledQuickListsProvider) | [`BundledQuickListsProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/impl/BundledQuickListsProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.cachedValuesFactory](https://jb.gg/ipe?extensions=com.intellij.cachedValuesFactory) | [`CachedValuesFactory`](upsource:///platform/core-impl/src/com/intellij/util/CachedValuesFactory.java) | 
|  | [com.intellij.cachesInvalidator](https://jb.gg/ipe?extensions=com.intellij.cachesInvalidator) | [`CachesInvalidator`](upsource:///platform/platform-api/src/com/intellij/ide/caches/CachesInvalidator.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.classpathStorageProvider](https://jb.gg/ipe?extensions=com.intellij.classpathStorageProvider) | [`ClasspathStorageProvider`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/impl/storage/ClasspathStorageProvider.java) | 
|  | [com.intellij.codeInsight.folding.collapseBlockHandler](https://jb.gg/ipe?extensions=com.intellij.codeInsight.folding.collapseBlockHandler) | [`CollapseBlockHandler`](upsource:///platform/lang-api/src/com/intellij/codeInsight/folding/CollapseBlockHandler.java) | 
|  | [com.intellij.codeInsight.linkHandler](https://jb.gg/ipe?extensions=com.intellij.codeInsight.linkHandler) | [`TooltipLinkHandler`](upsource:///platform/platform-api/src/com/intellij/codeInsight/highlighting/TooltipLinkHandler.java) | 
|  | [com.intellij.codeInsight.template.postfixTemplateProvider](https://jb.gg/ipe?extensions=com.intellij.codeInsight.template.postfixTemplateProvider) | [`PostfixTemplateProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/template/postfix/templates/PostfixTemplateProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.colorAndFontOptionsImportHandler](https://jb.gg/ipe?extensions=com.intellij.colorAndFontOptionsImportHandler) | [`ImportHandler`](upsource:///platform/platform-impl/src/com/intellij/application/options/colors/ImportHandler.java) | 
|  | [com.intellij.colorPickerListenerFactory](https://jb.gg/ipe?extensions=com.intellij.colorPickerListenerFactory) | [`ColorPickerListenerFactory`](upsource:///platform/platform-impl/src/com/intellij/ui/ColorPickerListenerFactory.java) | 
|  | [com.intellij.config.inlaySettingsProvider](https://jb.gg/ipe?extensions=com.intellij.config.inlaySettingsProvider) | [`InlaySettingsProvider`](upsource:///platform/lang-api/src/com/intellij/codeInsight/hints/settings/InlaySettingsProvider.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.credentialStore](https://jb.gg/ipe?extensions=com.intellij.credentialStore) | [`CredentialStoreFactory`](upsource:///platform/credential-store/src/CredentialStoreFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.customFileDropHandler](https://jb.gg/ipe?extensions=com.intellij.customFileDropHandler) | [`CustomFileDropHandler`](upsource:///platform/platform-impl/src/com/intellij/openapi/editor/CustomFileDropHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.customizableActionGroupProvider](https://jb.gg/ipe?extensions=com.intellij.customizableActionGroupProvider) | [`CustomizableActionGroupProvider`](upsource:///platform/platform-impl/src/com/intellij/ide/ui/customization/CustomizableActionGroupProvider.java) | 
|  | [com.intellij.cutElementMarker](https://jb.gg/ipe?extensions=com.intellij.cutElementMarker) | [`CutElementMarker`](upsource:///platform/platform-api/src/com/intellij/openapi/ide/CutElementMarker.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.dataValidator](https://jb.gg/ipe?extensions=com.intellij.dataValidator) | [`DataValidator`](upsource:///platform/platform-impl/src/com/intellij/ide/impl/DataValidator.java) | 
|  | [com.intellij.dateTimeFormatter](https://jb.gg/ipe?extensions=com.intellij.dateTimeFormatter) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.defaultProjectTypeProvider](https://jb.gg/ipe?extensions=com.intellij.defaultProjectTypeProvider) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.deuteranopiaSupport](https://jb.gg/ipe?extensions=com.intellij.deuteranopiaSupport) | [`ColorBlindnessSupport`](upsource:///platform/editor-ui-api/src/com/intellij/ide/ui/ColorBlindnessSupport.java) | 
|  | [com.intellij.diff.DiffExtension](https://jb.gg/ipe?extensions=com.intellij.diff.DiffExtension) | [`DiffExtension`](upsource:///platform/diff-api/src/com/intellij/diff/DiffExtension.java) | 
|  | [com.intellij.diff.DiffTool](https://jb.gg/ipe?extensions=com.intellij.diff.DiffTool) | [`DiffTool`](upsource:///platform/diff-api/src/com/intellij/diff/DiffTool.java) | 
|  | [com.intellij.diff.actions.ShowDiffAction.ExtensionProvider](https://jb.gg/ipe?extensions=com.intellij.diff.actions.ShowDiffAction.ExtensionProvider) | [`AnActionExtensionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/AnActionExtensionProvider.java) | 
|  | [com.intellij.diff.impl.DiffToolSubstitutor](https://jb.gg/ipe?extensions=com.intellij.diff.impl.DiffToolSubstitutor) | [`DiffToolSubstitutor`](upsource:///platform/diff-impl/src/com/intellij/diff/impl/DiffToolSubstitutor.java) | 
|  | [com.intellij.diff.lang.DiffIgnoredRangeProvider](https://jb.gg/ipe?extensions=com.intellij.diff.lang.DiffIgnoredRangeProvider) | [`DiffIgnoredRangeProvider`](upsource:///platform/diff-impl/src/com/intellij/diff/lang/DiffIgnoredRangeProvider.java) | 
|  | [com.intellij.diff.merge.MergeTool](https://jb.gg/ipe?extensions=com.intellij.diff.merge.MergeTool) | [`MergeTool`](upsource:///platform/diff-api/src/com/intellij/diff/merge/MergeTool.java) | 
|  | [com.intellij.diff.merge.external.AutomaticExternalMergeTool](https://jb.gg/ipe?extensions=com.intellij.diff.merge.external.AutomaticExternalMergeTool) | [`AutomaticExternalMergeTool`](upsource:///platform/diff-api/src/com/intellij/diff/merge/external/AutomaticExternalMergeTool.java) | 
|  | [com.intellij.directoryProjectConfigurator](https://jb.gg/ipe?extensions=com.intellij.directoryProjectConfigurator) | [`DirectoryProjectConfigurator`](upsource:///platform/platform-impl/src/com/intellij/platform/DirectoryProjectConfigurator.java) | 
|  | [com.intellij.directoryProjectGenerator](https://jb.gg/ipe?extensions=com.intellij.directoryProjectGenerator) | [`DirectoryProjectGenerator`](upsource:///platform/platform-impl/src/com/intellij/platform/DirectoryProjectGenerator.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.documentWriteAccessGuard](https://jb.gg/ipe?extensions=com.intellij.documentWriteAccessGuard) | [`DocumentWriteAccessGuard`](upsource:///platform/core-impl/src/com/intellij/openapi/editor/impl/DocumentWriteAccessGuard.java) | 
|  | [com.intellij.documentationActionProvider](https://jb.gg/ipe?extensions=com.intellij.documentationActionProvider) | [`DocumentationActionProvider`](upsource:///platform/lang-impl/src/com/intellij/codeInsight/documentation/DocumentationActionProvider.java) | 
|  | [com.intellij.dynamicActionConfigurationCustomizer](https://jb.gg/ipe?extensions=com.intellij.dynamicActionConfigurationCustomizer) | [`DynamicActionConfigurationCustomizer`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/impl/DynamicActionConfigurationCustomizer.java) | 
|  | [com.intellij.editor.injectedFileChangesHandlerProvider](https://jb.gg/ipe?extensions=com.intellij.editor.injectedFileChangesHandlerProvider) | [`InjectedFileChangesHandlerProvider`](upsource:///platform/editor-ui-api/src/com/intellij/injected/editor/InjectedFileChangesHandlerProvider.java) | 
|  | [com.intellij.editor.linePainter](https://jb.gg/ipe?extensions=com.intellij.editor.linePainter) | [`EditorLinePainter`](upsource:///platform/platform-impl/src/com/intellij/openapi/editor/EditorLinePainter.java) | 
|  | [com.intellij.editorActionHandler](https://jb.gg/ipe?extensions=com.intellij.editorActionHandler) | [`EditorActionHandler`](upsource:///platform/platform-api/src/com/intellij/openapi/editor/actionSystem/EditorActionHandler.java) | 
|  | [com.intellij.editorFactoryMouseListener](https://jb.gg/ipe?extensions=com.intellij.editorFactoryMouseListener) | [`EditorMouseListener`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/event/EditorMouseListener.java) | 
|  | [com.intellij.editorFactoryMouseMotionListener](https://jb.gg/ipe?extensions=com.intellij.editorFactoryMouseMotionListener) | [`EditorMouseMotionListener`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/event/EditorMouseMotionListener.java) | 
|  | [com.intellij.editorFileAssociateFinder](https://jb.gg/ipe?extensions=com.intellij.editorFileAssociateFinder) | [`FileEditorAssociateFinder`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/FileEditorAssociateFinder.java) | 
|  | [com.intellij.editorFileSwapper](https://jb.gg/ipe?extensions=com.intellij.editorFileSwapper) | [`EditorFileSwapper`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/EditorFileSwapper.java) | 
|  | [com.intellij.editorFloatingToolbarProvider](https://jb.gg/ipe?extensions=com.intellij.editorFloatingToolbarProvider) | [`FloatingToolbarProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/editor/toolbar/floating/FloatingToolbarProvider.kt) | 
|  | [com.intellij.editorHighlighterProvider](https://jb.gg/ipe?extensions=com.intellij.editorHighlighterProvider) | [`EditorHighlighterProvider`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/fileTypes/EditorHighlighterProvider.java) | 
|  | [com.intellij.editorNavigation](https://jb.gg/ipe?extensions=com.intellij.editorNavigation) | [`EditorNavigationDelegate`](upsource:///platform/platform-api/src/com/intellij/openapi/editor/EditorNavigationDelegate.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.editorNotificationProvider](https://jb.gg/ipe?extensions=com.intellij.editorNotificationProvider) | [`Provider`](upsource:///platform/platform-api/src/com/intellij/ui/EditorNotifications.java) | 
|  | [com.intellij.editorTabColorProvider](https://jb.gg/ipe?extensions=com.intellij.editorTabColorProvider) | [`EditorTabColorProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/EditorTabColorProvider.java) | 
|  | [com.intellij.editorTabTitleProvider](https://jb.gg/ipe?extensions=com.intellij.editorTabTitleProvider) | [`EditorTabTitleProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/EditorTabTitleProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.editorTypedHandler](https://jb.gg/ipe?extensions=com.intellij.editorTypedHandler) | [`TypedActionHandler`](upsource:///platform/platform-api/src/com/intellij/openapi/editor/actionSystem/TypedActionHandler.java) | 
|  | [com.intellij.errorHandler](https://jb.gg/ipe?extensions=com.intellij.errorHandler) | [`ErrorReportSubmitter`](upsource:///platform/platform-api/src/com/intellij/openapi/diagnostic/ErrorReportSubmitter.java) | 
|  | [com.intellij.eventLogCategory](https://jb.gg/ipe?extensions=com.intellij.eventLogCategory) | [`EventLogCategory`](upsource:///platform/platform-api/src/com/intellij/notification/EventLogCategory.java) | 
|  | [com.intellij.experimentalFeature](https://jb.gg/ipe?extensions=com.intellij.experimentalFeature) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.exportable](https://jb.gg/ipe?extensions=com.intellij.exportable) | `n/a` | 
|  | [com.intellij.externalComponentSource](https://jb.gg/ipe?extensions=com.intellij.externalComponentSource) | [`ExternalComponentSource`](upsource:///platform/platform-impl/src/com/intellij/ide/externalComponents/ExternalComponentSource.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.featureStatisticsBundle](https://jb.gg/ipe?extensions=com.intellij.featureStatisticsBundle) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.feedbackDescriptionProvider](https://jb.gg/ipe?extensions=com.intellij.feedbackDescriptionProvider) | [`FeedbackDescriptionProvider`](upsource:///platform/platform-impl/src/com/intellij/ide/FeedbackDescriptionProvider.kt) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.fileBreadcrumbsCollector](https://jb.gg/ipe?extensions=com.intellij.fileBreadcrumbsCollector) | [`FileBreadcrumbsCollector`](upsource:///platform/platform-api/src/com/intellij/codeInsight/breadcrumbs/FileBreadcrumbsCollector.java) | 
|  | [com.intellij.fileDocumentManagerListener](https://jb.gg/ipe?extensions=com.intellij.fileDocumentManagerListener) | [`FileDocumentManagerListener`](upsource:///platform/platform-api/src/com/intellij/openapi/fileEditor/FileDocumentManagerListener.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.fileDocumentSynchronizationVetoer](https://jb.gg/ipe?extensions=com.intellij.fileDocumentSynchronizationVetoer) | [`FileDocumentSynchronizationVetoer`](upsource:///platform/platform-api/src/com/intellij/openapi/fileEditor/FileDocumentSynchronizationVetoer.java) | 
|  | [com.intellij.fileEditorProvider](https://jb.gg/ipe?extensions=com.intellij.fileEditorProvider) | [`FileEditorProvider`](upsource:///platform/analysis-api/src/com/intellij/openapi/fileEditor/FileEditorProvider.java) | 
|  | [com.intellij.fileIconPatcher](https://jb.gg/ipe?extensions=com.intellij.fileIconPatcher) | [`FileIconPatcher`](upsource:///platform/core-api/src/com/intellij/ide/FileIconPatcher.java) | 
|  | [com.intellij.fileIconProvider](https://jb.gg/ipe?extensions=com.intellij.fileIconProvider) | [`FileIconProvider`](upsource:///platform/core-api/src/com/intellij/ide/FileIconProvider.java) | 
|  | [com.intellij.fileType](https://jb.gg/ipe?extensions=com.intellij.fileType) | [`FileType`](upsource:///platform/core-api/src/com/intellij/openapi/fileTypes/FileType.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.fileTypeFactory](https://jb.gg/ipe?extensions=com.intellij.fileTypeFactory) | [~~`FileTypeFactory`~~](upsource:///platform/platform-api/src/com/intellij/openapi/fileTypes/FileTypeFactory.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.fileTypeOverrider](https://jb.gg/ipe?extensions=com.intellij.fileTypeOverrider) | [`FileTypeOverrider`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileTypes/impl/FileTypeOverrider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.fileTypeRegistrar](https://jb.gg/ipe?extensions=com.intellij.fileTypeRegistrar) | [`FileTypeRegistrar`](upsource:///platform/platform-api/src/com/intellij/ide/highlighter/FileTypeRegistrar.java) | 
|  | [com.intellij.fileTypeUsageSchemaDescriptor](https://jb.gg/ipe?extensions=com.intellij.fileTypeUsageSchemaDescriptor) | [`FileTypeUsageSchemaDescriptor`](upsource:///platform/platform-impl/src/com/intellij/internal/statistic/collectors/fus/fileTypes/FileTypeUsageSchemaDescriptor.java) | 
|  | [com.intellij.filetype.decompiler](https://jb.gg/ipe?extensions=com.intellij.filetype.decompiler) | [`BinaryFileDecompiler`](upsource:///platform/core-api/src/com/intellij/openapi/fileTypes/BinaryFileDecompiler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.generalOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.generalOptionsProvider) | [`SearchableConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/SearchableConfigurable.java) | 
|  | [com.intellij.generalTroubleInfoCollector](https://jb.gg/ipe?extensions=com.intellij.generalTroubleInfoCollector) | [`GeneralTroubleInfoCollector`](upsource:///platform/platform-impl/src/com/intellij/troubleshooting/GeneralTroubleInfoCollector.java) | 
|  | [com.intellij.getDataRule](https://jb.gg/ipe?extensions=com.intellij.getDataRule) | [`GetDataRule`](upsource:///platform/platform-impl/src/com/intellij/ide/impl/dataRules/GetDataRule.java) | 
|  | [com.intellij.groupConfigurable](https://jb.gg/ipe?extensions=com.intellij.groupConfigurable) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.gutterMarkPreprocessor](https://jb.gg/ipe?extensions=com.intellij.gutterMarkPreprocessor) | [`GutterMarkPreprocessor`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/editor/GutterMarkPreprocessor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.handleTypeFactory](https://jb.gg/ipe?extensions=com.intellij.handleTypeFactory) | [`HandleTypeFactory`](upsource:///platform/platform-impl/src/com/intellij/openapi/vcs/readOnlyHandler/HandleTypeFactory.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.http.fileEditorActionProvider](https://jb.gg/ipe?extensions=com.intellij.http.fileEditorActionProvider) | [`RemoteFileEditorActionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/http/RemoteFileEditorActionProvider.java) | 
|  | [com.intellij.http.localFileFinder](https://jb.gg/ipe?extensions=com.intellij.http.localFileFinder) | [`LocalFileFinder`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/http/LocalFileFinder.java) | 
|  | [com.intellij.iconDescriptionBundle](https://jb.gg/ipe?extensions=com.intellij.iconDescriptionBundle) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.iconLayerProvider](https://jb.gg/ipe?extensions=com.intellij.iconLayerProvider) | [`IconLayerProvider`](upsource:///platform/core-api/src/com/intellij/ide/IconLayerProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.ideRootPaneNorth](https://jb.gg/ipe?extensions=com.intellij.ideRootPaneNorth) | [`IdeRootPaneNorthExtension`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/IdeRootPaneNorthExtension.java) | 
|  | [com.intellij.interactiveCourseFactory](https://jb.gg/ipe?extensions=com.intellij.interactiveCourseFactory) | [`InteractiveCourseFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/InteractiveCourseFactory.kt) | 
|  | [com.intellij.itemPresentationProvider](https://jb.gg/ipe?extensions=com.intellij.itemPresentationProvider) | [`ItemPresentationProvider`](upsource:///platform/core-api/src/com/intellij/navigation/ItemPresentationProvider.java) | 
|  | [com.intellij.iw.actionProvider](https://jb.gg/ipe?extensions=com.intellij.iw.actionProvider) | [`InspectionWidgetActionProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/editor/markup/InspectionWidgetActionProvider.kt) | 
|  | [com.intellij.jbProtocolCommand](https://jb.gg/ipe?extensions=com.intellij.jbProtocolCommand) | [`JBProtocolCommand`](upsource:///platform/platform-impl/src/com/intellij/openapi/application/JBProtocolCommand.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.jcef.appRequiredArgumentsProvider](https://jb.gg/ipe?extensions=com.intellij.jcef.appRequiredArgumentsProvider) | [`JBCefAppRequiredArgumentsProvider`](upsource:///platform/platform-api/src/com/intellij/ui/jcef/JBCefAppRequiredArgumentsProvider.kt) | 
|  | [com.intellij.jdkDownloader.jdkInstallerListener](https://jb.gg/ipe?extensions=com.intellij.jdkDownloader.jdkInstallerListener) | [`JdkInstallerListener`](upsource:///platform/lang-impl/src/com/intellij/openapi/projectRoots/impl/jdkDownloader/JdkInstaller.kt) | 
|  | [com.intellij.jdkUpdateCheckContributor](https://jb.gg/ipe?extensions=com.intellij.jdkUpdateCheckContributor) | [`JdkUpdateCheckContributor`](upsource:///platform/lang-impl/src/com/intellij/openapi/projectRoots/impl/jdkDownloader/JdkUpdater.kt) | 
|  | [com.intellij.jps.plugin](https://jb.gg/ipe?extensions=com.intellij.jps.plugin) | `n/a` | 
|  | [com.intellij.keymapExtension](https://jb.gg/ipe?extensions=com.intellij.keymapExtension) | [`KeymapExtension`](upsource:///platform/platform-api/src/com/intellij/openapi/keymap/KeymapExtension.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.lafProvider](https://jb.gg/ipe?extensions=com.intellij.lafProvider) | [`LafProvider`](upsource:///platform/platform-impl/src/com/intellij/ide/ui/LafProvider.java) | 
|  | [com.intellij.lang.syntaxHighlighterFactory](https://jb.gg/ipe?extensions=com.intellij.lang.syntaxHighlighterFactory) | [`SyntaxHighlighterFactory`](upsource:///platform/editor-ui-api/src/com/intellij/openapi/fileTypes/SyntaxHighlighterFactory.java) | 
|  | [com.intellij.library.toolWindow](https://jb.gg/ipe?extensions=com.intellij.library.toolWindow) | [`ToolWindowFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/ToolWindowFactory.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.lightEditTabAttributesProvider](https://jb.gg/ipe?extensions=com.intellij.lightEditTabAttributesProvider) | [`LightEditTabAttributesProvider`](upsource:///platform/editor-ui-api/src/com/intellij/ide/lightEdit/LightEditTabAttributesProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.nonProjectFileWritingAccessExtension](https://jb.gg/ipe?extensions=com.intellij.nonProjectFileWritingAccessExtension) | [`NonProjectFileWritingAccessExtension`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/NonProjectFileWritingAccessExtension.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.notification.group](https://jb.gg/ipe?extensions=com.intellij.notification.group) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.notification.parentGroup](https://jb.gg/ipe?extensions=com.intellij.notification.parentGroup) | `n/a` | 
|  | [com.intellij.notificationAllowlist](https://jb.gg/ipe?extensions=com.intellij.notificationAllowlist) | `n/a` | 
|  | [com.intellij.notificationGroup](https://jb.gg/ipe?extensions=com.intellij.notificationGroup) | `n/a` | 
|  | [com.intellij.notificationWhitelist](https://jb.gg/ipe?extensions=com.intellij.notificationWhitelist) | `n/a` | 
|  | [com.intellij.obsoleteStorage](https://jb.gg/ipe?extensions=com.intellij.obsoleteStorage) | `n/a` | 
|  | [com.intellij.pathMacroContributor](https://jb.gg/ipe?extensions=com.intellij.pathMacroContributor) | [`PathMacroContributor`](upsource:///platform/core-api/src/com/intellij/openapi/application/PathMacroContributor.java) | 
|  | [com.intellij.pathMacroExpandableProtocol](https://jb.gg/ipe?extensions=com.intellij.pathMacroExpandableProtocol) | `n/a` | 
|  | [com.intellij.pathMacroFilter](https://jb.gg/ipe?extensions=com.intellij.pathMacroFilter) | [`PathMacroFilter`](upsource:///jps/model-serialization/src/com/intellij/openapi/application/PathMacroFilter.java) | 
|  | [com.intellij.pluginReplacement](https://jb.gg/ipe?extensions=com.intellij.pluginReplacement) | [`PluginReplacement`](upsource:///platform/platform-api/src/com/intellij/ide/plugins/PluginReplacement.java) | 
|  | [com.intellij.preloadingActivity](https://jb.gg/ipe?extensions=com.intellij.preloadingActivity) | [`PreloadingActivity`](upsource:///platform/platform-impl/src/com/intellij/openapi/application/PreloadingActivity.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.productivityFeaturesProvider](https://jb.gg/ipe?extensions=com.intellij.productivityFeaturesProvider) | [`ProductivityFeaturesProvider`](upsource:///platform/platform-api/src/com/intellij/featureStatistics/ProductivityFeaturesProvider.java) | 
|  | [com.intellij.projectAttachProcessor](https://jb.gg/ipe?extensions=com.intellij.projectAttachProcessor) | [`ProjectAttachProcessor`](upsource:///platform/platform-api/src/com/intellij/projectImport/ProjectAttachProcessor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.projectCloseHandler](https://jb.gg/ipe?extensions=com.intellij.projectCloseHandler) | [`ProjectCloseHandler`](upsource:///platform/projectModel-api/src/com/intellij/openapi/project/ProjectCloseHandler.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectConfigurable](https://jb.gg/ipe?extensions=com.intellij.projectConfigurable) | [`Configurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/Configurable.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.projectNameProvider](https://jb.gg/ipe?extensions=com.intellij.projectNameProvider) | [`ProjectNameProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/project/ex/ProjectNameProvider.java) | 
|  | [com.intellij.projectOpenProcessor](https://jb.gg/ipe?extensions=com.intellij.projectOpenProcessor) | [`ProjectOpenProcessor`](upsource:///platform/platform-api/src/com/intellij/projectImport/ProjectOpenProcessor.java) | 
|  | [com.intellij.projectServiceContainerCustomizer](https://jb.gg/ipe?extensions=com.intellij.projectServiceContainerCustomizer) | [`ProjectServiceContainerCustomizer`](upsource:///platform/platform-impl/src/com/intellij/openapi/project/impl/projectLoader.kt) | 
|  | [com.intellij.projectServiceContainerInitializedListener](https://jb.gg/ipe?extensions=com.intellij.projectServiceContainerInitializedListener) | [`ProjectServiceContainerInitializedListener`](upsource:///platform/platform-impl/src/com/intellij/openapi/project/impl/projectLoader.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.projectSetProcessor](https://jb.gg/ipe?extensions=com.intellij.projectSetProcessor) | [`ProjectSetProcessor`](upsource:///platform/platform-api/src/com/intellij/projectImport/ProjectSetProcessor.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.projectStoreClassProvider](https://jb.gg/ipe?extensions=com.intellij.projectStoreClassProvider) | [`ProjectStoreFactory`](upsource:///platform/platform-impl/src/com/intellij/openapi/project/impl/ProjectStoreFactory.java) | 
|  | [com.intellij.projectTemplate](https://jb.gg/ipe?extensions=com.intellij.projectTemplate) | `n/a` | 
|  | [com.intellij.projectTemplatesFactory](https://jb.gg/ipe?extensions=com.intellij.projectTemplatesFactory) | [`ProjectTemplatesFactory`](upsource:///platform/platform-impl/src/com/intellij/platform/ProjectTemplatesFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectUndoProvider](https://jb.gg/ipe?extensions=com.intellij.projectUndoProvider) | [`UndoProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/command/impl/UndoProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.protanopiaSupport](https://jb.gg/ipe?extensions=com.intellij.protanopiaSupport) | [`ColorBlindnessSupport`](upsource:///platform/editor-ui-api/src/com/intellij/ide/ui/ColorBlindnessSupport.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.rawEditorTypedHandler](https://jb.gg/ipe?extensions=com.intellij.rawEditorTypedHandler) | [`TypedActionHandler`](upsource:///platform/platform-api/src/com/intellij/openapi/editor/actionSystem/TypedActionHandler.java) | 
|  | [com.intellij.registryKey](https://jb.gg/ipe?extensions=com.intellij.registryKey) | `n/a` | 
|  | [com.intellij.remote.credentialsLanguageContribution](https://jb.gg/ipe?extensions=com.intellij.remote.credentialsLanguageContribution) | [`CredentialsLanguageContribution`](upsource:///platform/platform-impl/src/com/intellij/remote/ext/CredentialsLanguageContribution.java) | 
|  | [com.intellij.remote.credentialsType](https://jb.gg/ipe?extensions=com.intellij.remote.credentialsType) | [`CredentialsType`](upsource:///platform/platform-impl/src/com/intellij/remote/CredentialsType.java) | 
|  | [com.intellij.remote.pathMappingProvider](https://jb.gg/ipe?extensions=com.intellij.remote.pathMappingProvider) | [`PathMappingProvider`](upsource:///platform/platform-impl/src/com/intellij/remote/PathMappingProvider.java) | 
|  | [com.intellij.schemeExporter](https://jb.gg/ipe?extensions=com.intellij.schemeExporter) | [`SchemeExporter`](upsource:///platform/platform-api/src/com/intellij/openapi/options/SchemeExporter.java) | 
|  | [com.intellij.schemeImporter](https://jb.gg/ipe?extensions=com.intellij.schemeImporter) | [`SchemeImporter`](upsource:///platform/platform-api/src/com/intellij/openapi/options/SchemeImporter.java) | 
|  | [com.intellij.search.optionContributor](https://jb.gg/ipe?extensions=com.intellij.search.optionContributor) | [`SearchableOptionContributor`](upsource:///platform/platform-api/src/com/intellij/ide/ui/search/SearchableOptionContributor.java) | 
|  | [com.intellij.search.projectOptionsTopHitProvider](https://jb.gg/ipe?extensions=com.intellij.search.projectOptionsTopHitProvider) | [`ProjectLevelProvider`](upsource:///platform/platform-impl/src/com/intellij/ide/ui/OptionsSearchTopHitProvider.java) | 
|  | [com.intellij.search.topHitProvider](https://jb.gg/ipe?extensions=com.intellij.search.topHitProvider) | [`SearchTopHitProvider`](upsource:///platform/platform-api/src/com/intellij/ide/SearchTopHitProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.search.traverseUiHelper](https://jb.gg/ipe?extensions=com.intellij.search.traverseUiHelper) | [`TraverseUIHelper`](upsource:///platform/platform-impl/src/com/intellij/ide/ui/search/TraverseUIHelper.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.selectInTarget](https://jb.gg/ipe?extensions=com.intellij.selectInTarget) | [`SelectInTarget`](upsource:///platform/platform-api/src/com/intellij/ide/SelectInTarget.java) | 
|  | [com.intellij.smartSelectProvider](https://jb.gg/ipe?extensions=com.intellij.smartSelectProvider) | [`SmartSelectProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/ide/SmartSelectProvider.java) | 
|  | [com.intellij.sshCredentialProvider](https://jb.gg/ipe?extensions=com.intellij.sshCredentialProvider) | [`SshCredentialProvider`](upsource:///platform/platform-impl/src/com/intellij/remote/SshCredentialProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.statistic.eventLog.eventLoggerProvider](https://jb.gg/ipe?extensions=com.intellij.statistic.eventLog.eventLoggerProvider) | [`StatisticsEventLoggerProvider`](upsource:///platform/statistics/src/com/intellij/internal/statistic/eventLog/StatisticsEventLogger.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.statistic.eventLog.fusStateEventTracker](https://jb.gg/ipe?extensions=com.intellij.statistic.eventLog.fusStateEventTracker) | [`FeatureUsageStateEventTracker`](upsource:///platform/statistics/src/com/intellij/internal/statistic/eventLog/fus/FeatureUsageStateEventTracker.kt) | 
|  | [com.intellij.statistics.actionCustomPlaceAllowlist](https://jb.gg/ipe?extensions=com.intellij.statistics.actionCustomPlaceAllowlist) | `n/a` | 
|  | [com.intellij.statistics.applicationUsagesCollector](https://jb.gg/ipe?extensions=com.intellij.statistics.applicationUsagesCollector) | [`ApplicationUsagesCollector`](upsource:///platform/statistics/src/com/intellij/internal/statistic/service/fus/collectors/ApplicationUsagesCollector.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.statistics.collectorExtension](https://jb.gg/ipe?extensions=com.intellij.statistics.collectorExtension) | [`FeatureUsageCollectorExtension`](upsource:///platform/statistics/src/com/intellij/internal/statistic/service/fus/collectors/FeatureUsageCollectorExtension.java) | 
|  | [com.intellij.statistics.counterUsagesCollector](https://jb.gg/ipe?extensions=com.intellij.statistics.counterUsagesCollector) | [`FeatureUsagesCollector`](upsource:///platform/statistics/src/com/intellij/internal/statistic/service/fus/collectors/FeatureUsagesCollector.java) | 
|  | [com.intellij.statistics.gotItTooltipAllowlist](https://jb.gg/ipe?extensions=com.intellij.statistics.gotItTooltipAllowlist) | `n/a` | 
|  | [com.intellij.statistics.notificationIdsHolder](https://jb.gg/ipe?extensions=com.intellij.statistics.notificationIdsHolder) | [`NotificationIdsHolder`](upsource:///platform/platform-impl/src/com/intellij/notification/impl/NotificationIdsHolder.java) | 
|  | [com.intellij.statistics.projectUsagesCollector](https://jb.gg/ipe?extensions=com.intellij.statistics.projectUsagesCollector) | [`ProjectUsagesCollector`](upsource:///platform/statistics/src/com/intellij/internal/statistic/service/fus/collectors/ProjectUsagesCollector.java) | 
|  | [com.intellij.statistics.validation.customValidationRule](https://jb.gg/ipe?extensions=com.intellij.statistics.validation.customValidationRule) | [`CustomValidationRule`](upsource:///platform/statistics/src/com/intellij/internal/statistic/eventLog/validator/rules/impl/CustomValidationRule.java) | 
|  | [com.intellij.statistics.validation.customWhiteListRule](https://jb.gg/ipe?extensions=com.intellij.statistics.validation.customWhiteListRule) | [~~`CustomWhiteListRule`~~](upsource:///platform/statistics/src/com/intellij/internal/statistic/eventLog/validator/rules/impl/CustomWhiteListRule.java) | 
|  | [com.intellij.statusBarWidgetFactory](https://jb.gg/ipe?extensions=com.intellij.statusBarWidgetFactory) | [`StatusBarWidgetFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/StatusBarWidgetFactory.java) | 
|  | [com.intellij.statusBarWidgetProvider](https://jb.gg/ipe?extensions=com.intellij.statusBarWidgetProvider) | [~~`StatusBarWidgetProvider`~~](upsource:///platform/platform-api/src/com/intellij/openapi/wm/StatusBarWidgetProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.streamProviderFactory](https://jb.gg/ipe?extensions=com.intellij.streamProviderFactory) | [`StreamProviderFactory`](upsource:///platform/projectModel-impl/src/com/intellij/configurationStore/StreamProviderFactory.kt) | 
|  | [com.intellij.stripTrailingSpacesFilterFactory](https://jb.gg/ipe?extensions=com.intellij.stripTrailingSpacesFilterFactory) | [`StripTrailingSpacesFilterFactory`](upsource:///platform/core-api/src/com/intellij/openapi/editor/StripTrailingSpacesFilterFactory.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.systemProperty](https://jb.gg/ipe?extensions=com.intellij.systemProperty) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.testStatusListener](https://jb.gg/ipe?extensions=com.intellij.testStatusListener) | [`TestStatusListener`](upsource:///platform/testRunner/src/com/intellij/execution/testframework/TestStatusListener.java) | 
|  | [com.intellij.textEditorCustomizer](https://jb.gg/ipe?extensions=com.intellij.textEditorCustomizer) | [`TextEditorCustomizer`](upsource:///platform/platform-impl/src/com/intellij/openapi/fileEditor/impl/text/TextEditorCustomizer.java) | 
|  | [com.intellij.themeMetadataProvider](https://jb.gg/ipe?extensions=com.intellij.themeMetadataProvider) | `n/a` | 
|  | [com.intellij.themeProvider](https://jb.gg/ipe?extensions=com.intellij.themeProvider) | `n/a` | 
|  | [com.intellij.tipAndTrick](https://jb.gg/ipe?extensions=com.intellij.tipAndTrick) | `n/a` | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.titleInfoProvider](https://jb.gg/ipe?extensions=com.intellij.titleInfoProvider) | [`TitleInfoProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/wm/impl/TitleInfoProvider.kt) | 
|  | [com.intellij.toolWindow](https://jb.gg/ipe?extensions=com.intellij.toolWindow) | [`ToolWindowFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/ToolWindowFactory.java) | 
|  | [com.intellij.toolWindowAllowlist](https://jb.gg/ipe?extensions=com.intellij.toolWindowAllowlist) | `n/a` | 
|  | [com.intellij.trailingSpacesOptionsProvider](https://jb.gg/ipe?extensions=com.intellij.trailingSpacesOptionsProvider) | [`TrailingSpacesOptionsProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/fileEditor/TrailingSpacesOptionsProvider.java) | 
|  | [com.intellij.tree.CustomLanguageASTComparator](https://jb.gg/ipe?extensions=com.intellij.tree.CustomLanguageASTComparator) | [`CustomLanguageASTComparator`](upsource:///platform/core-api/src/com/intellij/psi/tree/CustomLanguageASTComparator.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.tritanopiaSupport](https://jb.gg/ipe?extensions=com.intellij.tritanopiaSupport) | [`ColorBlindnessSupport`](upsource:///platform/editor-ui-api/src/com/intellij/ide/ui/ColorBlindnessSupport.java) | 
|  | [com.intellij.troubleInfoCollector](https://jb.gg/ipe?extensions=com.intellij.troubleInfoCollector) | [`TroubleInfoCollector`](upsource:///platform/platform-impl/src/com/intellij/troubleshooting/TroubleInfoCollector.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.ui.optionEditorProvider](https://jb.gg/ipe?extensions=com.intellij.ui.optionEditorProvider) | [`OptionEditorProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/options/OptionEditorProvider.java) | 
|  | [com.intellij.ui.suitableFontProvider](https://jb.gg/ipe?extensions=com.intellij.ui.suitableFontProvider) | [`SuitableFontProvider`](upsource:///platform/platform-api/src/com/intellij/ui/SuitableFontProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.uiDropperActions](https://jb.gg/ipe?extensions=com.intellij.uiDropperActions) | [`UiDropperActionExtension`](upsource:///platform/platform-impl/src/com/intellij/internal/inspector/UiDropperActionExtension.java) | 
|  | [com.intellij.undoProvider](https://jb.gg/ipe?extensions=com.intellij.undoProvider) | [`UndoProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/command/impl/UndoProvider.java) | 
|  | [com.intellij.unknownSdkContributor](https://jb.gg/ipe?extensions=com.intellij.unknownSdkContributor) | [`UnknownSdkContributor`](upsource:///platform/lang-impl/src/com/intellij/openapi/projectRoots/impl/UnknownSdkCollector.kt) | 
|  | [com.intellij.unknownSdkResolver](https://jb.gg/ipe?extensions=com.intellij.unknownSdkResolver) | [`UnknownSdkResolver`](upsource:///platform/lang-impl/src/com/intellij/openapi/roots/ui/configuration/UnknownSdkResolver.java) | 
|  | [com.intellij.updateSettingsProvider](https://jb.gg/ipe?extensions=com.intellij.updateSettingsProvider) | [`UpdateSettingsProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/updateSettings/impl/UpdateSettingsProvider.kt) | 
|  | [com.intellij.utf8BomOptionProvider](https://jb.gg/ipe?extensions=com.intellij.utf8BomOptionProvider) | [`Utf8BomOptionProvider`](upsource:///platform/core-api/src/com/intellij/openapi/vfs/encoding/Utf8BomOptionProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.vfs.local.pluggableFileWatcher](https://jb.gg/ipe?extensions=com.intellij.vfs.local.pluggableFileWatcher) | [`PluggableFileWatcher`](upsource:///platform/platform-api/src/com/intellij/openapi/vfs/local/PluggableFileWatcher.java) | 
|  | [com.intellij.webBrowserUrlProvider](https://jb.gg/ipe?extensions=com.intellij.webBrowserUrlProvider) | [`WebBrowserUrlProvider`](upsource:///platform/platform-api/src/com/intellij/ide/browsers/WebBrowserUrlProvider.kt) | 
|  | [com.intellij.webHelpProvider](https://jb.gg/ipe?extensions=com.intellij.webHelpProvider) | [`WebHelpProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/help/WebHelpProvider.java) | 
|  | [com.intellij.welcomeFrameProvider](https://jb.gg/ipe?extensions=com.intellij.welcomeFrameProvider) | [`WelcomeFrameProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/WelcomeFrameProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.welcomeScreen](https://jb.gg/ipe?extensions=com.intellij.welcomeScreen) | [`WelcomeScreenProvider`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/WelcomeScreenProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.welcomeScreenCustomization](https://jb.gg/ipe?extensions=com.intellij.welcomeScreenCustomization) | [`WelcomeScreenCustomization`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/WelcomeScreenCustomization.java) | 
|  | [com.intellij.welcomeTabFactory](https://jb.gg/ipe?extensions=com.intellij.welcomeTabFactory) | [`WelcomeTabFactory`](upsource:///platform/platform-api/src/com/intellij/openapi/wm/WelcomeTabFactory.java) | 
|  | [org.jetbrains.javaScriptDebuggerStarter](https://jb.gg/ipe?extensions=org.jetbrains.javaScriptDebuggerStarter) | [`JavaScriptDebuggerStarter`](upsource:///platform/platform-impl/src/com/intellij/ide/browsers/JavaScriptDebuggerStarter.java) | 
|  | [org.jetbrains.urlOpener](https://jb.gg/ipe?extensions=org.jetbrains.urlOpener) | [`UrlOpener`](upsource:///platform/platform-api/src/com/intellij/ide/browsers/UrlOpener.java) | 

## [project-system-plugin.xml](upsource:///android/project-system/src/META-INF/project-system-plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.android.project.projectsystem](https://jb.gg/ipe?extensions=com.android.project.projectsystem) | [`AndroidProjectSystemProvider`](upsource:///android/project-system/src/com/android/tools/idea/projectsystem/AndroidProjectSystemProvider.kt) | 

## [ProjectModel.xml](upsource:///platform/projectModel-api/resources/META-INF/ProjectModel.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.customLibraryTable](https://jb.gg/ipe?extensions=com.intellij.customLibraryTable) | [`CustomLibraryTableDescription`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/libraries/CustomLibraryTableDescription.java) | 
|  | [com.intellij.filePropertyPusher](https://jb.gg/ipe?extensions=com.intellij.filePropertyPusher) | [`FilePropertyPusher`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/impl/FilePropertyPusher.java) | 
|  | [com.intellij.moduleExtension](https://jb.gg/ipe?extensions=com.intellij.moduleExtension) | [`ModuleExtension`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/ModuleExtension.java) | 
|  | [com.intellij.orderEnumerationHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.orderEnumerationHandlerFactory) | [`Factory`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/OrderEnumerationHandler.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.orderRootType](https://jb.gg/ipe?extensions=com.intellij.orderRootType) | [`OrderRootType`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/OrderRootType.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.projectFileScanner](https://jb.gg/ipe?extensions=com.intellij.projectFileScanner) | [`ProjectFileScanner`](upsource:///platform/projectModel-api/src/com/intellij/openapi/roots/impl/ProjectFileScanner.java) | 

## [ProjectModelImpl.xml](upsource:///platform/projectModel-impl/resources/META-INF/ProjectModelImpl.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.additionalLibraryRootsProvider](https://jb.gg/ipe?extensions=com.intellij.additionalLibraryRootsProvider) | [`AdditionalLibraryRootsProvider`](upsource:///platform/projectModel-impl/src/com/intellij/openapi/roots/AdditionalLibraryRootsProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.directoryIndexExcludePolicy](https://jb.gg/ipe?extensions=com.intellij.directoryIndexExcludePolicy) | [`DirectoryIndexExcludePolicy`](upsource:///platform/projectModel-impl/src/com/intellij/openapi/roots/impl/DirectoryIndexExcludePolicy.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.projectExtension](https://jb.gg/ipe?extensions=com.intellij.projectExtension) | [`ProjectExtension`](upsource:///platform/projectModel-impl/src/com/intellij/openapi/roots/ProjectExtension.java) | 

## [python-core-common.xml](upsource:///python/src/META-INF/python-core-common.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [Pythonid.breakpointHandler](https://jb.gg/ipe?extensions=Pythonid.breakpointHandler) | [`PyBreakpointHandlerFactory`](upsource:///python/src/com/jetbrains/python/debugger/PyBreakpointHandlerFactory.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.condaSdkCustomizer](https://jb.gg/ipe?extensions=Pythonid.condaSdkCustomizer) | [`PyCondaSdkCustomizer`](upsource:///python/src/com/jetbrains/python/sdk/conda/PyCondaSdkCustomizer.kt) | 
|  | [Pythonid.consoleOptionsProvider](https://jb.gg/ipe?extensions=Pythonid.consoleOptionsProvider) | [`PyConsoleOptionsProvider`](upsource:///python/src/com/jetbrains/python/console/PyConsoleOptionsProvider.java) | 
|  | [Pythonid.dataViewPanelFactory](https://jb.gg/ipe?extensions=Pythonid.dataViewPanelFactory) | [`PyDataViewPanelFactory`](upsource:///python/src/com/jetbrains/python/debugger/containerview/PyDataViewPanelFactory.java) | 
|  | [Pythonid.debugSessionFactory](https://jb.gg/ipe?extensions=Pythonid.debugSessionFactory) | [`PyDebugSessionFactory`](upsource:///python/src/com/jetbrains/python/debugger/PyDebugSessionFactory.java) | 
|  | [Pythonid.documentationLinkProvider](https://jb.gg/ipe?extensions=Pythonid.documentationLinkProvider) | [`PythonDocumentationLinkProvider`](upsource:///python/openapi/src/com/jetbrains/python/documentation/PythonDocumentationLinkProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.interpreterTargetEnvironmentFactory](https://jb.gg/ipe?extensions=Pythonid.interpreterTargetEnvironmentFactory) | [`PythonInterpreterTargetEnvironmentFactory`](upsource:///python/src/com/jetbrains/python/run/PythonInterpreterTargetEnvironmentFactory.kt) | 
|  | [Pythonid.magicLiteral](https://jb.gg/ipe?extensions=Pythonid.magicLiteral) | [`PyMagicLiteralExtensionPoint`](upsource:///python/python-psi-impl/src/com/jetbrains/python/magicLiteral/PyMagicLiteralExtensionPoint.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.packageManagerProvider](https://jb.gg/ipe?extensions=Pythonid.packageManagerProvider) | [`PyPackageManagerProvider`](upsource:///python/src/com/jetbrains/python/packaging/PyCustomPackageManagers.kt) | 
|  | [Pythonid.pep8ProblemSuppressor](https://jb.gg/ipe?extensions=Pythonid.pep8ProblemSuppressor) | [`Pep8ProblemSuppressor`](upsource:///python/src/com/jetbrains/python/validation/Pep8ProblemSuppressor.java) | 
|  | [Pythonid.projectSynchronizerProvider](https://jb.gg/ipe?extensions=Pythonid.projectSynchronizerProvider) | [`PyProjectSynchronizerProvider`](upsource:///python/src/com/jetbrains/python/remote/PyProjectSynchronizer.kt) | 
|  | [Pythonid.pyAddSdkProvider](https://jb.gg/ipe?extensions=Pythonid.pyAddSdkProvider) | [`PyAddSdkProvider`](upsource:///python/src/com/jetbrains/python/sdk/add/PyAddSdkProvider.kt) | 
|  | [Pythonid.pyAnnotator](https://jb.gg/ipe?extensions=Pythonid.pyAnnotator) | [`PyAnnotator`](upsource:///python/python-psi-impl/src/com/jetbrains/python/validation/PyAnnotator.java) | 
|  | [Pythonid.pyCustomSdkUiProvider](https://jb.gg/ipe?extensions=Pythonid.pyCustomSdkUiProvider) | [`PyCustomSdkUiProvider`](upsource:///python/src/com/jetbrains/python/sdk/PyCustomSdkUiProvider.java) | 
|  | [Pythonid.pyPregeneratedSkeletonsProvider](https://jb.gg/ipe?extensions=Pythonid.pyPregeneratedSkeletonsProvider) | [`PyPregeneratedSkeletonsProvider`](upsource:///python/src/com/jetbrains/python/sdk/skeletons/PyPregeneratedSkeletonsProvider.java) | 
|  | [Pythonid.pyRootTypeProvider](https://jb.gg/ipe?extensions=Pythonid.pyRootTypeProvider) | [`PyRootTypeProvider`](upsource:///python/src/com/jetbrains/python/module/PyRootTypeProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.pySdkProvider](https://jb.gg/ipe?extensions=Pythonid.pySdkProvider) | [`PySdkProvider`](upsource:///python/src/com/jetbrains/python/sdk/PySdkProvider.kt) | 
|  | [Pythonid.pyTestConfigurationSelector](https://jb.gg/ipe?extensions=Pythonid.pyTestConfigurationSelector) | [`PyTestConfigurationSelector`](upsource:///python/src/com/jetbrains/python/testing/PyTestConfigurationSelector.kt) | 
|  | [Pythonid.pyTestFixtureExtension](https://jb.gg/ipe?extensions=Pythonid.pyTestFixtureExtension) | [`PyTestFixtureExtension`](upsource:///python/src/com/jetbrains/python/testing/pyTestFixtures/PyTestFixtureExtension.kt) | 
|  | [Pythonid.pythonCommandLineEnvironmentProvider](https://jb.gg/ipe?extensions=Pythonid.pythonCommandLineEnvironmentProvider) | [`PythonCommandLineEnvironmentProvider`](upsource:///python/src/com/jetbrains/python/run/PythonCommandLineEnvironmentProvider.java) | 
|  | [Pythonid.pythonSdkComparator](https://jb.gg/ipe?extensions=Pythonid.pythonSdkComparator) | [`PySdkComparator`](upsource:///python/src/com/jetbrains/python/sdk/PySdkComparator.java) | 
|  | [Pythonid.remoteConsoleProcessCreator](https://jb.gg/ipe?extensions=Pythonid.remoteConsoleProcessCreator) | [`PythonConsoleRemoteProcessCreator`](upsource:///python/src/com/jetbrains/python/console/PythonConsoleRemoteProcessCreator.kt) | 
|  | [Pythonid.remoteInterpreterManager](https://jb.gg/ipe?extensions=Pythonid.remoteInterpreterManager) | [`PythonRemoteInterpreterManager`](upsource:///python/src/com/jetbrains/python/remote/PythonRemoteInterpreterManager.java) | 
|  | [Pythonid.remoteProcessStarterManager](https://jb.gg/ipe?extensions=Pythonid.remoteProcessStarterManager) | [`PyRemoteProcessStarterManager`](upsource:///python/src/com/jetbrains/python/run/PyRemoteProcessStarterManager.java) | 
|  | [Pythonid.remoteSdkValidator](https://jb.gg/ipe?extensions=Pythonid.remoteSdkValidator) | [`PyRemoteSdkValidator`](upsource:///python/python-psi-impl/src/com/jetbrains/python/sdk/PyRemoteSdkValidator.kt) | 
|  | [Pythonid.remoteSkeletonGeneratorFactory](https://jb.gg/ipe?extensions=Pythonid.remoteSkeletonGeneratorFactory) | [`PyRemoteSkeletonGeneratorFactory`](upsource:///python/src/com/jetbrains/python/remote/PyRemoteSkeletonGeneratorFactory.java) | 
|  | [Pythonid.runConfigurationEditorExtension](https://jb.gg/ipe?extensions=Pythonid.runConfigurationEditorExtension) | [`PyRunConfigurationEditorExtension`](upsource:///python/src/com/jetbrains/python/run/PyRunConfigurationEditorExtension.java) | 
|  | [Pythonid.runConfigurationExtension](https://jb.gg/ipe?extensions=Pythonid.runConfigurationExtension) | [`PythonRunConfigurationExtension`](upsource:///python/src/com/jetbrains/python/run/PythonRunConfigurationExtension.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.runConfigurationTargetEnvironmentAdjuster](https://jb.gg/ipe?extensions=Pythonid.runConfigurationTargetEnvironmentAdjuster) | [`PythonRunConfigurationTargetEnvironmentAdjuster`](upsource:///python/src/com/jetbrains/python/run/PythonRunConfigurationTargetEnvironmentAdjuster.kt) | 
|  | [Pythonid.runnableScriptFilter](https://jb.gg/ipe?extensions=Pythonid.runnableScriptFilter) | [`RunnableScriptFilter`](upsource:///python/src/com/jetbrains/python/run/RunnableScriptFilter.java) | 
|  | [Pythonid.sshInterpreterManager](https://jb.gg/ipe?extensions=Pythonid.sshInterpreterManager) | [`PythonSshInterpreterManager`](upsource:///python/src/com/jetbrains/python/remote/PythonSshInterpreterManager.java) | 
|  | [Pythonid.unresolvedReferenceQuickFixProvider](https://jb.gg/ipe?extensions=Pythonid.unresolvedReferenceQuickFixProvider) | [`PyUnresolvedReferenceQuickFixProvider`](upsource:///python/openapi/src/com/jetbrains/python/inspections/PyUnresolvedReferenceQuickFixProvider.java) | 

## [PythonPsi.xml](upsource:///python/python-psi-api/resources/META-INF/PythonPsi.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [Pythonid.canonicalPathProvider](https://jb.gg/ipe?extensions=Pythonid.canonicalPathProvider) | [`PyCanonicalPathProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/resolve/PyCanonicalPathProvider.java) | 
|  | [Pythonid.customPackageIdentifier](https://jb.gg/ipe?extensions=Pythonid.customPackageIdentifier) | [`PyCustomPackageIdentifier`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/PyCustomPackageIdentifier.java) | 
|  | [Pythonid.dialectsTokenSetContributor](https://jb.gg/ipe?extensions=Pythonid.dialectsTokenSetContributor) | [`PythonDialectsTokenSetContributor`](upsource:///python/python-psi-api/src/com/jetbrains/python/PythonDialectsTokenSetContributor.java) | 
|  | [Pythonid.importResolver](https://jb.gg/ipe?extensions=Pythonid.importResolver) | [`PyImportResolver`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/impl/PyImportResolver.java) | 
|  | [Pythonid.inspectionExtension](https://jb.gg/ipe?extensions=Pythonid.inspectionExtension) | [`PyInspectionExtension`](upsource:///python/python-psi-api/src/com/jetbrains/python/inspections/PyInspectionExtension.java) | 
|  | [Pythonid.keywordArgumentProvider](https://jb.gg/ipe?extensions=Pythonid.keywordArgumentProvider) | [`PyKeywordArgumentProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/impl/PyKeywordArgumentProvider.java) | 
|  | [Pythonid.knownDecoratorProvider](https://jb.gg/ipe?extensions=Pythonid.knownDecoratorProvider) | [`PyKnownDecoratorProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/PyKnownDecoratorProvider.java) | 
|  | [Pythonid.pyClassInheritorsSearch](https://jb.gg/ipe?extensions=Pythonid.pyClassInheritorsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [Pythonid.pyClassMembersProvider](https://jb.gg/ipe?extensions=Pythonid.pyClassMembersProvider) | [`PyClassMembersProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/types/PyClassMembersProvider.java) | 
|  | [Pythonid.pyModuleMembersProvider](https://jb.gg/ipe?extensions=Pythonid.pyModuleMembersProvider) | [`PyModuleMembersProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/types/PyModuleMembersProvider.java) | 
|  | [Pythonid.pyOverridingMethodsSearch](https://jb.gg/ipe?extensions=Pythonid.pyOverridingMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [Pythonid.pyReferenceResolveProvider](https://jb.gg/ipe?extensions=Pythonid.pyReferenceResolveProvider) | [`PyReferenceResolveProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/resolve/PyReferenceResolveProvider.java) | 
|  | [Pythonid.pySuperMethodsSearch](https://jb.gg/ipe?extensions=Pythonid.pySuperMethodsSearch) | [`QueryExecutor`](upsource:///platform/core-api/src/com/intellij/util/QueryExecutor.java) | 
|  | [Pythonid.pythonDocumentationQuickInfoProvider](https://jb.gg/ipe?extensions=Pythonid.pythonDocumentationQuickInfoProvider) | [`PythonDocumentationQuickInfoProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/documentation/PythonDocumentationQuickInfoProvider.java) | 
|  | [Pythonid.resolveResultRater](https://jb.gg/ipe?extensions=Pythonid.resolveResultRater) | [`PyResolveResultRater`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/impl/PyResolveResultRater.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [Pythonid.thirdPartySdkDetector](https://jb.gg/ipe?extensions=Pythonid.thirdPartySdkDetector) | [`PyThirdPartySdkDetector`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/resolve/PyThirdPartySdkDetector.java) | 
|  | [Pythonid.typeProvider](https://jb.gg/ipe?extensions=Pythonid.typeProvider) | [`PyTypeProvider`](upsource:///python/python-psi-api/src/com/jetbrains/python/psi/impl/PyTypeProvider.java) | 

## [RefactoringExtensionPoints.xml](upsource:///platform/platform-resources/src/META-INF/RefactoringExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.automaticRenamerFactory](https://jb.gg/ipe?extensions=com.intellij.automaticRenamerFactory) | [`AutomaticRenamerFactory`](upsource:///platform/lang-impl/src/com/intellij/refactoring/rename/naming/AutomaticRenamerFactory.java) | 
|  | [com.intellij.changeSignatureDetector](https://jb.gg/ipe?extensions=com.intellij.changeSignatureDetector) | [`LanguageChangeSignatureDetector`](upsource:///platform/lang-impl/src/com/intellij/refactoring/changeSignature/inplace/LanguageChangeSignatureDetector.java) | 
|  | [com.intellij.inlineActionHandler](https://jb.gg/ipe?extensions=com.intellij.inlineActionHandler) | [`InlineActionHandler`](upsource:///platform/lang-api/src/com/intellij/lang/refactoring/InlineActionHandler.java) | 
|  | [com.intellij.lang.namesValidator](https://jb.gg/ipe?extensions=com.intellij.lang.namesValidator) | [`NamesValidator`](upsource:///platform/analysis-api/src/com/intellij/lang/refactoring/NamesValidator.java) | 
|  | [com.intellij.lang.refactoringSupport](https://jb.gg/ipe?extensions=com.intellij.lang.refactoringSupport) | [`RefactoringSupportProvider`](upsource:///platform/lang-api/src/com/intellij/lang/refactoring/RefactoringSupportProvider.java) | 
|  | [com.intellij.lang.refactoringSupport.classMembersRefactoringSupport](https://jb.gg/ipe?extensions=com.intellij.lang.refactoringSupport.classMembersRefactoringSupport) | [`ClassMembersRefactoringSupport`](upsource:///platform/lang-api/src/com/intellij/refactoring/classMembers/ClassMembersRefactoringSupport.java) | 
|  | [com.intellij.moveFileHandler](https://jb.gg/ipe?extensions=com.intellij.moveFileHandler) | [`MoveFileHandler`](upsource:///platform/lang-impl/src/com/intellij/refactoring/move/moveFilesOrDirectories/MoveFileHandler.java) | 
|  | [com.intellij.nameSuggestionProvider](https://jb.gg/ipe?extensions=com.intellij.nameSuggestionProvider) | [`NameSuggestionProvider`](upsource:///platform/lang-api/src/com/intellij/refactoring/rename/NameSuggestionProvider.java) | 
|  | [com.intellij.refactoring.changeSignatureUsageProcessor](https://jb.gg/ipe?extensions=com.intellij.refactoring.changeSignatureUsageProcessor) | [`ChangeSignatureUsageProcessor`](upsource:///platform/lang-api/src/com/intellij/refactoring/changeSignature/ChangeSignatureUsageProcessor.java) | 
|  | [com.intellij.refactoring.copyHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.copyHandler) | [`CopyHandlerDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/copy/CopyHandlerDelegate.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.refactoring.elementListenerProvider](https://jb.gg/ipe?extensions=com.intellij.refactoring.elementListenerProvider) | [`RefactoringElementListenerProvider`](upsource:///platform/analysis-api/src/com/intellij/refactoring/listeners/RefactoringElementListenerProvider.java) | 
|  | [com.intellij.refactoring.extractIncludeHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.extractIncludeHandler) | [`RefactoringActionHandler`](upsource:///platform/lang-api/src/com/intellij/refactoring/RefactoringActionHandler.java) | 
|  | [com.intellij.refactoring.helper](https://jb.gg/ipe?extensions=com.intellij.refactoring.helper) | [`RefactoringHelper`](upsource:///platform/lang-impl/src/com/intellij/refactoring/RefactoringHelper.java) | 
|  | [com.intellij.refactoring.inlineHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.inlineHandler) | [`InlineHandler`](upsource:///platform/lang-api/src/com/intellij/lang/refactoring/InlineHandler.java) | 
|  | [com.intellij.refactoring.introduceParameterObject](https://jb.gg/ipe?extensions=com.intellij.refactoring.introduceParameterObject) | [`IntroduceParameterObjectDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/introduceParameterObject/IntroduceParameterObjectDelegate.java) | 
|  | [com.intellij.refactoring.invertBoolean](https://jb.gg/ipe?extensions=com.intellij.refactoring.invertBoolean) | [`InvertBooleanDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/invertBoolean/InvertBooleanDelegate.java) | 
|  | [com.intellij.refactoring.moveDirectoryWithClassesHelper](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveDirectoryWithClassesHelper) | [`MoveDirectoryWithClassesHelper`](upsource:///platform/lang-impl/src/com/intellij/refactoring/move/moveClassesOrPackages/MoveDirectoryWithClassesHelper.java) | 
|  | [com.intellij.refactoring.moveHandler](https://jb.gg/ipe?extensions=com.intellij.refactoring.moveHandler) | [`MoveHandlerDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/move/MoveHandlerDelegate.java) | 
|  | [com.intellij.refactoring.pushDown](https://jb.gg/ipe?extensions=com.intellij.refactoring.pushDown) | [`PushDownDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/memberPushDown/PushDownDelegate.java) | 
|  | [com.intellij.refactoring.safeDeleteProcessor](https://jb.gg/ipe?extensions=com.intellij.refactoring.safeDeleteProcessor) | [`SafeDeleteProcessorDelegate`](upsource:///platform/lang-impl/src/com/intellij/refactoring/safeDelete/SafeDeleteProcessorDelegate.java) | 
|  | [com.intellij.rename.inplace.resolveSnapshotProvider](https://jb.gg/ipe?extensions=com.intellij.rename.inplace.resolveSnapshotProvider) | [`ResolveSnapshotProvider`](upsource:///platform/lang-api/src/com/intellij/refactoring/rename/ResolveSnapshotProvider.java) | 
|  | [com.intellij.rename.referenceRenameUsageFactory](https://jb.gg/ipe?extensions=com.intellij.rename.referenceRenameUsageFactory) | [`ReferenceRenameUsageFactory`](upsource:///platform/lang-impl/src/com/intellij/refactoring/rename/symbol/ReferenceRenameUsageFactory.java) | 
|  | [com.intellij.rename.symbolRenameTargetFactory](https://jb.gg/ipe?extensions=com.intellij.rename.symbolRenameTargetFactory) | [`SymbolRenameTargetFactory`](upsource:///platform/lang-impl/src/com/intellij/refactoring/rename/symbol/SymbolRenameTargetFactory.java) | 
|  | [com.intellij.renameFileActionProvider](https://jb.gg/ipe?extensions=com.intellij.renameFileActionProvider) | [`RenameFileActionProvider`](upsource:///platform/lang-impl/src/com/intellij/refactoring/actions/RenameFileActionProvider.java) | 
|  | [com.intellij.renameHandler](https://jb.gg/ipe?extensions=com.intellij.renameHandler) | [`RenameHandler`](upsource:///platform/lang-api/src/com/intellij/refactoring/rename/RenameHandler.java) | 
|  | [com.intellij.renameInputValidator](https://jb.gg/ipe?extensions=com.intellij.renameInputValidator) | [`RenameInputValidator`](upsource:///platform/lang-api/src/com/intellij/refactoring/rename/RenameInputValidator.java) | 
|  | [com.intellij.renamePsiElementProcessor](https://jb.gg/ipe?extensions=com.intellij.renamePsiElementProcessor) | [`RenamePsiElementProcessor`](upsource:///platform/lang-impl/src/com/intellij/refactoring/rename/RenamePsiElementProcessor.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.renamerFactory](https://jb.gg/ipe?extensions=com.intellij.renamerFactory) | [`RenamerFactory`](upsource:///platform/lang-api/src/com/intellij/refactoring/rename/RenamerFactory.java) | 
|  | [com.intellij.suggestedRefactoringSupport](https://jb.gg/ipe?extensions=com.intellij.suggestedRefactoringSupport) | [`SuggestedRefactoringSupport`](upsource:///platform/lang-api/src/com/intellij/refactoring/suggested/SuggestedRefactoringSupport.kt) | 
|  | [com.intellij.updateAddedFileProcessor](https://jb.gg/ipe?extensions=com.intellij.updateAddedFileProcessor) | [`UpdateAddedFileProcessor`](upsource:///platform/core-impl/src/com/intellij/psi/impl/file/UpdateAddedFileProcessor.java) | 
|  | [com.intellij.vetoRenameCondition](https://jb.gg/ipe?extensions=com.intellij.vetoRenameCondition) | [`Condition`](upsource:///platform/util-rt/src/com/intellij/openapi/util/Condition.java) | 

## [RegExpPlugin.xml](upsource:///RegExpSupport/resources/META-INF/RegExpPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.regExpCapabilitiesProvider](https://jb.gg/ipe?extensions=com.intellij.regExpCapabilitiesProvider) | [`RegExpCapabilitiesProvider`](upsource:///RegExpSupport/src/org/intellij/lang/regexp/RegExpCapabilitiesProvider.java) | 
|  | [com.intellij.regExpLanguageHost](https://jb.gg/ipe?extensions=com.intellij.regExpLanguageHost) | [`RegExpLanguageHost`](upsource:///RegExpSupport/src/org/intellij/lang/regexp/RegExpLanguageHost.java) | 
|  | [com.intellij.regExpMatcherProvider](https://jb.gg/ipe?extensions=com.intellij.regExpMatcherProvider) | [`RegExpMatcherProvider`](upsource:///RegExpSupport/src/org/intellij/lang/regexp/RegExpMatcherProvider.java) | 
|  | [com.intellij.regExpModifierProvider](https://jb.gg/ipe?extensions=com.intellij.regExpModifierProvider) | [`RegExpModifierProvider`](upsource:///RegExpSupport/src/org/intellij/lang/regexp/RegExpModifierProvider.java) | 

## [RemoteServers.xml](upsource:///platform/remote-servers/impl/src/META-INF/RemoteServers.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.remoteServer.defaultConfigurable.includeServerType](https://jb.gg/ipe?extensions=com.intellij.remoteServer.defaultConfigurable.includeServerType) | [`ServerType`](upsource:///platform/remote-servers/api/src/com/intellij/remoteServer/ServerType.java) | 
|  | [com.intellij.remoteServer.deploymentSource.type](https://jb.gg/ipe?extensions=com.intellij.remoteServer.deploymentSource.type) | [`DeploymentSourceType`](upsource:///platform/remote-servers/api/src/com/intellij/remoteServer/configuration/deployment/DeploymentSourceType.java) | 
|  | [com.intellij.remoteServer.runConfigurationExtension](https://jb.gg/ipe?extensions=com.intellij.remoteServer.runConfigurationExtension) | [`DeployToServerRunConfigurationExtension`](upsource:///platform/remote-servers/impl/src/com/intellij/remoteServer/impl/configuration/deployment/DeployToServerRunConfigurationExtension.java) | 
|  | [com.intellij.remoteServer.type](https://jb.gg/ipe?extensions=com.intellij.remoteServer.type) | [`ServerType`](upsource:///platform/remote-servers/api/src/com/intellij/remoteServer/ServerType.java) | 

## [RemoteServersJava.xml](upsource:///java/remote-servers/impl/src/META-INF/RemoteServersJava.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.remoteServer.moduleBuilderContribution](https://jb.gg/ipe?extensions=com.intellij.remoteServer.moduleBuilderContribution) | [`CloudModuleBuilderContributionFactory`](upsource:///java/remote-servers/impl/src/com/intellij/remoteServer/impl/module/CloudModuleBuilderContributionFactory.java) | 

## [resources-explorer.xml](upsource:///android/android/src/com/android/tools/idea/ui/resourcemanager/META-INF/resources-explorer.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.resourceImporter](https://jb.gg/ipe?extensions=com.android.resourceImporter) | [`ResourceImporter`](upsource:///android/android/src/com/android/tools/idea/ui/resourcemanager/plugin/ResourceImporter.kt) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.android.resourceViewer](https://jb.gg/ipe?extensions=com.android.resourceViewer) | [`DesignAssetRenderer`](upsource:///android/android/src/com/android/tools/idea/ui/resourcemanager/plugin/DesignAssetRenderer.kt) | 

## [rest.xml](upsource:///python/rest/resources/META-INF/rest.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [restructured.text.html.preview.provider](https://jb.gg/ipe?extensions=restructured.text.html.preview.provider) | [`RestPreviewProvider`](upsource:///python/rest/src/com/jetbrains/rest/editor/RestPreviewProvider.java) | 

## [smRunner.xml](upsource:///platform/smRunner/resources/META-INF/smRunner.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.importTestOutput](https://jb.gg/ipe?extensions=com.intellij.importTestOutput) | [`ImportTestOutputExtension`](upsource:///platform/smRunner/src/com/intellij/execution/testframework/sm/runner/history/ImportTestOutputExtension.java) | 

## [SpellCheckerPlugin.xml](upsource:///spellchecker/src/META-INF/SpellCheckerPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.spellchecker.bundledDictionaryProvider](https://jb.gg/ipe?extensions=com.intellij.spellchecker.bundledDictionaryProvider) | [`BundledDictionaryProvider`](upsource:///spellchecker/src/com/intellij/spellchecker/BundledDictionaryProvider.java) | 
|  | [com.intellij.spellchecker.dictionary.customDictionaryProvider](https://jb.gg/ipe?extensions=com.intellij.spellchecker.dictionary.customDictionaryProvider) | [`CustomDictionaryProvider`](upsource:///spellchecker/src/com/intellij/spellchecker/dictionary/CustomDictionaryProvider.java) | 
|  | [com.intellij.spellchecker.dictionary.runtimeDictionaryProvider](https://jb.gg/ipe?extensions=com.intellij.spellchecker.dictionary.runtimeDictionaryProvider) | [`RuntimeDictionaryProvider`](upsource:///spellchecker/src/com/intellij/spellchecker/dictionary/RuntimeDictionaryProvider.java) | 
|  | [com.intellij.spellchecker.support](https://jb.gg/ipe?extensions=com.intellij.spellchecker.support) | [`SpellcheckingStrategy`](upsource:///spellchecker/src/com/intellij/spellchecker/tokenizer/SpellcheckingStrategy.java) | 

## [structuralsearch.xml](upsource:///platform/structuralsearch/source/META-INF/structuralsearch.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.structuralsearch.filter](https://jb.gg/ipe?extensions=com.intellij.structuralsearch.filter) | [`FilterAction`](upsource:///platform/structuralsearch/source/com/intellij/structuralsearch/plugin/ui/filters/FilterAction.java) | 
|  | [com.intellij.structuralsearch.profile](https://jb.gg/ipe?extensions=com.intellij.structuralsearch.profile) | [`StructuralSearchProfile`](upsource:///platform/structuralsearch/source/com/intellij/structuralsearch/StructuralSearchProfile.java) | 

## [tasks.xml](upsource:///platform/tasks-platform-impl/resources/META-INF/tasks.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.tasks.contextProvider](https://jb.gg/ipe?extensions=com.intellij.tasks.contextProvider) | [`WorkingContextProvider`](upsource:///platform/tasks-platform-api/src/com/intellij/tasks/context/WorkingContextProvider.java) | 

## [terminal.xml](upsource:///plugins/terminal/resources/META-INF/terminal.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.terminal.shellCommandHandler](https://jb.gg/ipe?extensions=com.intellij.terminal.shellCommandHandler) | [`TerminalShellCommandHandler`](upsource:///platform/platform-impl/src/com/intellij/terminal/TerminalShellCommandHandler.kt) | 
|  | [org.jetbrains.plugins.terminal.localTerminalCustomizer](https://jb.gg/ipe?extensions=org.jetbrains.plugins.terminal.localTerminalCustomizer) | [`LocalTerminalCustomizer`](upsource:///plugins/terminal/src/org/jetbrains/plugins/terminal/LocalTerminalCustomizer.java) | 

## [TestNG-J](upsource:///plugins/testng/resources/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.theoryinpractice.testng.listener](https://jb.gg/ipe?extensions=com.theoryinpractice.testng.listener) | [`IDEATestNGListener`](upsource:///plugins/testng_rt/src/com/intellij/rt/testng/IDEATestNGListener.java) | 

## [UICore.xml](upsource:///platform/platform-resources/src/componentSets/UICore.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.registerToolWindowTaskProvider](https://jb.gg/ipe?extensions=com.intellij.registerToolWindowTaskProvider) | [`RegisterToolWindowTaskProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/wm/impl/ToolWindowManagerImpl.kt) | 

## [vcs-log.xml](upsource:///platform/vcs-log/impl/src/META-INF/vcs-log.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.customVcsLogUiFactoryProvider](https://jb.gg/ipe?extensions=com.intellij.customVcsLogUiFactoryProvider) | [`CustomVcsLogUiFactoryProvider`](upsource:///platform/vcs-log/impl/src/com/intellij/vcs/log/impl/CustomVcsLogUiFactoryProvider.java) | 
|  | [com.intellij.logHighlighterFactory](https://jb.gg/ipe?extensions=com.intellij.logHighlighterFactory) | [`VcsLogHighlighterFactory`](upsource:///platform/vcs-log/impl/src/com/intellij/vcs/log/ui/highlighters/VcsLogHighlighterFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.logProvider](https://jb.gg/ipe?extensions=com.intellij.logProvider) | [`VcsLogProvider`](upsource:///platform/vcs-log/api/src/com/intellij/vcs/log/VcsLogProvider.java) | 
|  | [com.intellij.vcsLogCustomColumn](https://jb.gg/ipe?extensions=com.intellij.vcsLogCustomColumn) | [`VcsLogCustomColumn`](upsource:///platform/vcs-log/impl/src/com/intellij/vcs/log/ui/table/column/VcsLogCustomColumn.kt) | 

## [VcsExtensionPoints.xml](upsource:///platform/vcs-impl/resources/META-INF/VcsExtensionPoints.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.changesGroupingPolicy](https://jb.gg/ipe?extensions=com.intellij.changesGroupingPolicy) | [`ChangesGroupingPolicyFactory`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ui/ChangesGroupingPolicyFactory.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.changesViewContent](https://jb.gg/ipe?extensions=com.intellij.changesViewContent) | [`ChangesViewContentProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ui/ChangesViewContentProvider.java) | 
|  | [com.intellij.checkinHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.checkinHandlerFactory) | [`CheckinHandlerFactory`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/checkin/CheckinHandlerFactory.java) | 
|  | [com.intellij.checkoutCompletedListener](https://jb.gg/ipe?extensions=com.intellij.checkoutCompletedListener) | [`CheckoutListener`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/checkout/CheckoutListener.java) | 
|  | [com.intellij.checkoutListener](https://jb.gg/ipe?extensions=com.intellij.checkoutListener) | [`CheckoutListener`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/checkout/CheckoutListener.java) | 
|  | [com.intellij.checkoutProvider](https://jb.gg/ipe?extensions=com.intellij.checkoutProvider) | [`CheckoutProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/CheckoutProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.editChangelistSupport](https://jb.gg/ipe?extensions=com.intellij.editChangelistSupport) | [`EditChangelistSupport`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ui/EditChangelistSupport.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.ignoredFileContentProvider](https://jb.gg/ipe?extensions=com.intellij.ignoredFileContentProvider) | [`IgnoredFileContentProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/IgnoredFileContentProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.ignoredFileProvider](https://jb.gg/ipe?extensions=com.intellij.ignoredFileProvider) | [`IgnoredFileProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/IgnoredFileProvider.java) | 
|  | [com.intellij.openapi.vcs.actions.AnnotateToggleAction.Provider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.actions.AnnotateToggleAction.Provider) | [`Provider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/actions/AnnotateToggleAction.java) | 
|  | [com.intellij.openapi.vcs.changes.actions.<br/>CreatePatchFromChangesAction.Clipboard.ExtensionProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.actions.CreatePatchFromChangesAction.Clipboard.ExtensionProvider) | [`AnActionExtensionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/AnActionExtensionProvider.java) | 
|  | [com.intellij.openapi.vcs.changes.actions.<br/>CreatePatchFromChangesAction.Dialog.ExtensionProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.actions.CreatePatchFromChangesAction.Dialog.ExtensionProvider) | [`AnActionExtensionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/AnActionExtensionProvider.java) | 
|  | [com.intellij.openapi.vcs.changes.actions.<br/>diff.ChangeDiffRequestProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.actions.diff.ChangeDiffRequestProvider) | [`ChangeDiffRequestProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/actions/diff/ChangeDiffRequestProvider.java) | 
|  | [com.intellij.openapi.vcs.changes.actions.<br/>diff.ChangeDiffViewerWrapperProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.actions.diff.ChangeDiffViewerWrapperProvider) | [`ChangeDiffViewerWrapperProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/actions/diff/ChangeDiffViewerWrapperProvider.java) | 
|  | [com.intellij.openapi.vcs.changes.ui.filePathIconProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.ui.filePathIconProvider) | [`FilePathIconProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/FilePathIconProvider.java) | 
|  | [com.intellij.openapi.vcs.changes.vcsPreservingExecutor](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.changes.vcsPreservingExecutor) | [`VcsPreservingExecutor`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/VcsPreservingExecutor.java) | 
|  | [com.intellij.openapi.vcs.history.actions.<br/>ShowDiffAfterWithLocalAction.ExtensionProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.history.actions.ShowDiffAfterWithLocalAction.ExtensionProvider) | [`AnActionExtensionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/AnActionExtensionProvider.java) | 
|  | [com.intellij.openapi.vcs.history.actions.<br/>ShowDiffBeforeWithLocalAction.ExtensionProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.history.actions.ShowDiffBeforeWithLocalAction.ExtensionProvider) | [`AnActionExtensionProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/actionSystem/AnActionExtensionProvider.java) | 
|  | [com.intellij.openapi.vcs.impl.LocalLineStatusTrackerProvider](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.impl.LocalLineStatusTrackerProvider) | [`LocalLineStatusTrackerProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/impl/LineStatusTrackerManager.kt) | 
|  | [com.intellij.openapi.vcs.ui.cloneDialog.VcsCloneDialogExtension](https://jb.gg/ipe?extensions=com.intellij.openapi.vcs.ui.cloneDialog.VcsCloneDialogExtension) | [`VcsCloneDialogExtension`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/ui/cloneDialog/VcsCloneDialogExtension.kt) | 
|  | [com.intellij.patch.extension](https://jb.gg/ipe?extensions=com.intellij.patch.extension) | [`PatchEP`](upsource:///platform/vcs-api/vcs-api-core/src/com/intellij/openapi/diff/impl/patch/PatchEP.java) | 
|  | [com.intellij.unresolvedMergeCheckProvider](https://jb.gg/ipe?extensions=com.intellij.unresolvedMergeCheckProvider) | [`UnresolvedMergeCheckProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/checkin/UnresolvedMergeCheckProvider.java) | 
|  | [com.intellij.vcs](https://jb.gg/ipe?extensions=com.intellij.vcs) | [`AbstractVcs`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/AbstractVcs.java) | 
|  | [com.intellij.vcs.actions.ScheduleForAdditionActionExtension](https://jb.gg/ipe?extensions=com.intellij.vcs.actions.ScheduleForAdditionActionExtension) | [`ScheduleForAdditionActionExtension`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/actions/ScheduleForAdditionActionExtension.kt) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.baseContentProvider](https://jb.gg/ipe?extensions=com.intellij.vcs.baseContentProvider) | [`VcsBaseContentProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/impl/VcsBaseContentProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.branchStateProvider](https://jb.gg/ipe?extensions=com.intellij.vcs.branchStateProvider) | [`BranchStateProvider`](upsource:///platform/vcs-api/src/com/intellij/vcs/branch/BranchStateProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.changeListChangeAssigner](https://jb.gg/ipe?extensions=com.intellij.vcs.changeListChangeAssigner) | [`ChangeListChangeAssigner`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ChangeListChangeAssigner.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.changeListDecorator](https://jb.gg/ipe?extensions=com.intellij.vcs.changeListDecorator) | [`ChangeListDecorator`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/ChangeListDecorator.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.changes.changesViewModifier](https://jb.gg/ipe?extensions=com.intellij.vcs.changes.changesViewModifier) | [`ChangesViewModifier`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ChangesViewModifier.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.changes.localCommitExecutor](https://jb.gg/ipe?extensions=com.intellij.vcs.changes.localCommitExecutor) | [`LocalCommitExecutor`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/LocalCommitExecutor.java) | 
|  | [com.intellij.vcs.checkoutProcessor](https://jb.gg/ipe?extensions=com.intellij.vcs.checkoutProcessor) | [`VcsCheckoutProcessor`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/VcsCheckoutProcessor.java) | 
|  | [com.intellij.vcs.commitMessageProvider](https://jb.gg/ipe?extensions=com.intellij.vcs.commitMessageProvider) | [`CommitMessageProvider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ui/CommitMessageProvider.java) | 
|  | [com.intellij.vcs.consoleFolding](https://jb.gg/ipe?extensions=com.intellij.vcs.consoleFolding) | [`VcsConsoleFolding`](upsource:///platform/vcs-impl/src/com/intellij/vcs/console/VcsConsoleView.kt) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.fileStatusProvider](https://jb.gg/ipe?extensions=com.intellij.vcs.fileStatusProvider) | [`FileStatusProvider`](upsource:///platform/platform-impl/src/com/intellij/openapi/vcs/impl/FileStatusProvider.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.ignoredFilesHolder](https://jb.gg/ipe?extensions=com.intellij.vcs.ignoredFilesHolder) | [`Provider`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/VcsIgnoredFilesHolder.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcs.taskHandler](https://jb.gg/ipe?extensions=com.intellij.vcs.taskHandler) | [`VcsTaskHandler`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/VcsTaskHandler.java) | 
|  | [com.intellij.vcsAnnotationGutterActionProvider](https://jb.gg/ipe?extensions=com.intellij.vcsAnnotationGutterActionProvider) | [`AnnotationGutterActionProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/annotate/AnnotationGutterActionProvider.java) | 
|  | [com.intellij.vcsAnnotationGutterColumnProvider](https://jb.gg/ipe?extensions=com.intellij.vcsAnnotationGutterColumnProvider) | [`AnnotationGutterColumnProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/annotate/AnnotationGutterColumnProvider.java) | 
|  | [com.intellij.vcsAwareCheckoutListener](https://jb.gg/ipe?extensions=com.intellij.vcsAwareCheckoutListener) | [`VcsAwareCheckoutListener`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/checkout/VcsAwareCheckoutListener.java) | 
|  | [com.intellij.vcsBulkMovesOnlyChangesFilter](https://jb.gg/ipe?extensions=com.intellij.vcsBulkMovesOnlyChangesFilter) | [`BulkMovesOnlyChangesFilter`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/changes/ui/browser/BulkMovesOnlyChangesFilter.java) | 
|  ![Project-Level](https://img.shields.io/badge/-Project--Level-yellow) | [com.intellij.vcsChangesViewRefresher](https://jb.gg/ipe?extensions=com.intellij.vcsChangesViewRefresher) | [`ChangesViewRefresher`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/changes/ChangesViewRefresher.java) | 
|  | [com.intellij.vcsCheckinHandlerFactory](https://jb.gg/ipe?extensions=com.intellij.vcsCheckinHandlerFactory) | [`VcsCheckinHandlerFactory`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/checkin/VcsCheckinHandlerFactory.kt) | 
|  | [com.intellij.vcsConfigurableProvider](https://jb.gg/ipe?extensions=com.intellij.vcsConfigurableProvider) | [`VcsConfigurableProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/VcsConfigurableProvider.java) | 
|  | [com.intellij.vcsIgnoreChecker](https://jb.gg/ipe?extensions=com.intellij.vcsIgnoreChecker) | [`VcsIgnoreChecker`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/VcsIgnoreChecker.java) | 
|  | [com.intellij.vcsPopupProvider](https://jb.gg/ipe?extensions=com.intellij.vcsPopupProvider) | [`VcsQuickListContentProvider`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/actions/VcsQuickListContentProvider.java) | 
|  | [com.intellij.vcsRepositoryInitializer](https://jb.gg/ipe?extensions=com.intellij.vcsRepositoryInitializer) | [`VcsRepositoryInitializer`](upsource:///platform/vcs-api/src/com/intellij/vcs/VcsRepositoryInitializer.java) | 
|  | [com.intellij.vcsRootChecker](https://jb.gg/ipe?extensions=com.intellij.vcsRootChecker) | [`VcsRootChecker`](upsource:///platform/vcs-api/src/com/intellij/openapi/vcs/VcsRootChecker.java) | 
|  | [com.intellij.vcsSelectionProvider](https://jb.gg/ipe?extensions=com.intellij.vcsSelectionProvider) | [`VcsSelectionProvider`](upsource:///platform/vcs-api/src/com/intellij/vcsUtil/VcsSelectionProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.vcsStartupActivity](https://jb.gg/ipe?extensions=com.intellij.vcsStartupActivity) | [`VcsStartupActivity`](upsource:///platform/vcs-impl/src/com/intellij/openapi/vcs/impl/VcsStartupActivity.java) | 

## [WorkspaceModelExtensions.xml](upsource:///platform/workspaceModel/ide/src/META-INF/WorkspaceModelExtensions.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.workspaceModel.customModuleComponentSerializer](https://jb.gg/ipe?extensions=com.intellij.workspaceModel.customModuleComponentSerializer) | [`CustomModuleComponentSerializer`](upsource:///platform/workspaceModel/ide/src/com/intellij/workspaceModel/ide/impl/jps/serialization/CustomModuleComponentSerializer.kt) | 
|  | [com.intellij.workspaceModel.customModuleRootsSerializer](https://jb.gg/ipe?extensions=com.intellij.workspaceModel.customModuleRootsSerializer) | [`CustomModuleRootsSerializer`](upsource:///platform/workspaceModel/ide/src/com/intellij/workspaceModel/ide/impl/jps/serialization/CustomModuleRootsSerializer.kt) | 

## [xdebugger.xml](upsource:///platform/xdebugger-impl/resources/META-INF/xdebugger.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.xdebugger.attachDebuggerProvider](https://jb.gg/ipe?extensions=com.intellij.xdebugger.attachDebuggerProvider) | [`XAttachDebuggerProvider`](upsource:///platform/xdebugger-impl/src/com/intellij/xdebugger/attach/XAttachDebuggerProvider.java) | 
|  | [com.intellij.xdebugger.attachHostProvider](https://jb.gg/ipe?extensions=com.intellij.xdebugger.attachHostProvider) | [`XAttachHostProvider`](upsource:///platform/xdebugger-impl/src/com/intellij/xdebugger/attach/XAttachHostProvider.java) | 
|  | [com.intellij.xdebugger.breakpointType](https://jb.gg/ipe?extensions=com.intellij.xdebugger.breakpointType) | [`XBreakpointType`](upsource:///platform/xdebugger-api/src/com/intellij/xdebugger/breakpoints/XBreakpointType.java) | 
|  | [com.intellij.xdebugger.configurableProvider](https://jb.gg/ipe?extensions=com.intellij.xdebugger.configurableProvider) | [`DebuggerConfigurableProvider`](upsource:///platform/xdebugger-api/src/com/intellij/xdebugger/settings/DebuggerConfigurableProvider.java) | 
|  | [com.intellij.xdebugger.debuggerSupport](https://jb.gg/ipe?extensions=com.intellij.xdebugger.debuggerSupport) | [~~`DebuggerSupport`~~](upsource:///platform/xdebugger-impl/src/com/intellij/xdebugger/impl/DebuggerSupport.java) | 
|  | [com.intellij.xdebugger.localAttachDebuggerProvider](https://jb.gg/ipe?extensions=com.intellij.xdebugger.localAttachDebuggerProvider) | [~~`XLocalAttachDebuggerProvider`~~](upsource:///platform/xdebugger-impl/src/com/intellij/xdebugger/attach/XLocalAttachDebuggerProvider.java) | 
|  | [com.intellij.xdebugger.settings](https://jb.gg/ipe?extensions=com.intellij.xdebugger.settings) | [`XDebuggerSettings`](upsource:///platform/xdebugger-api/src/com/intellij/xdebugger/settings/XDebuggerSettings.java) | 

## [XmlPlugin.xml](upsource:///platform/platform-resources/src/META-INF/XmlPlugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  | [com.intellij.embeddedTokenHighlighter](https://jb.gg/ipe?extensions=com.intellij.embeddedTokenHighlighter) | [`EmbeddedTokenHighlighter`](upsource:///xml/xml-psi-impl/src/com/intellij/ide/highlighter/EmbeddedTokenHighlighter.java) | 
|  | [com.intellij.embeddedTokenTypesProvider](https://jb.gg/ipe?extensions=com.intellij.embeddedTokenTypesProvider) | [`EmbeddedTokenTypesProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/lexer/EmbeddedTokenTypesProvider.java) | 
|  | [com.intellij.html.attributeValueProvider](https://jb.gg/ipe?extensions=com.intellij.html.attributeValueProvider) | [`HtmlAttributeValueProvider`](upsource:///xml/impl/src/com/intellij/html/impl/providers/HtmlAttributeValueProvider.java) | 
|  | [com.intellij.html.codestyle.panel](https://jb.gg/ipe?extensions=com.intellij.html.codestyle.panel) | [`HtmlCodeStylePanelExtension`](upsource:///xml/impl/src/com/intellij/application/options/HtmlCodeStylePanelExtension.java) | 
|  | [com.intellij.html.embeddedContentSupport](https://jb.gg/ipe?extensions=com.intellij.html.embeddedContentSupport) | [`HtmlEmbeddedContentSupport`](upsource:///xml/xml-psi-impl/src/com/intellij/html/embedding/HtmlEmbeddedContentSupport.kt) | 
|  | [com.intellij.html.htmlScriptInjectionBlocker](https://jb.gg/ipe?extensions=com.intellij.html.htmlScriptInjectionBlocker) | [`HtmlScriptInjectionBlocker`](upsource:///xml/impl/src/com/intellij/psi/impl/source/html/HtmlScriptInjectionBlocker.java) | 
|  | [com.intellij.html.inlineScriptTokenTypesProvider](https://jb.gg/ipe?extensions=com.intellij.html.inlineScriptTokenTypesProvider) | [~~`HtmlInlineScriptTokenTypesProvider`~~](upsource:///xml/xml-psi-impl/src/com/intellij/lang/HtmlInlineScriptTokenTypesProvider.java) | 
|  | [com.intellij.html.scriptContentProvider](https://jb.gg/ipe?extensions=com.intellij.html.scriptContentProvider) | [`HtmlScriptContentProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/lang/HtmlScriptContentProvider.java) | 
|  | [com.intellij.html.scriptDocumentationProvider](https://jb.gg/ipe?extensions=com.intellij.html.scriptDocumentationProvider) | [`DocumentationProvider`](upsource:///platform/analysis-api/src/com/intellij/lang/documentation/DocumentationProvider.java) | 
|  | [com.intellij.standardResource](https://jb.gg/ipe?extensions=com.intellij.standardResource) | `n/a` | 
|  | [com.intellij.standardResourceProvider](https://jb.gg/ipe?extensions=com.intellij.standardResourceProvider) | [`StandardResourceProvider`](upsource:///xml/xml-psi-api/src/com/intellij/javaee/StandardResourceProvider.java) | 
|  | [com.intellij.webSmartKeysConfigurable](https://jb.gg/ipe?extensions=com.intellij.webSmartKeysConfigurable) | [`UnnamedConfigurable`](upsource:///platform/platform-api/src/com/intellij/openapi/options/UnnamedConfigurable.java) | 
|  | [com.intellij.xml.attributeDescriptorsProvider](https://jb.gg/ipe?extensions=com.intellij.xml.attributeDescriptorsProvider) | [`XmlAttributeDescriptorsProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/xml/XmlAttributeDescriptorsProvider.java) | 
|  | [com.intellij.xml.elementDescriptorProvider](https://jb.gg/ipe?extensions=com.intellij.xml.elementDescriptorProvider) | [`XmlElementDescriptorProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/psi/impl/source/xml/XmlElementDescriptorProvider.java) | 
|  | [com.intellij.xml.fileNSInfoProvider](https://jb.gg/ipe?extensions=com.intellij.xml.fileNSInfoProvider) | [`XmlFileNSInfoProvider`](upsource:///xml/xml-psi-api/src/com/intellij/psi/xml/XmlFileNSInfoProvider.java) | 
|  | [com.intellij.xml.idContributor](https://jb.gg/ipe?extensions=com.intellij.xml.idContributor) | [`XmlIdContributor`](upsource:///xml/xml-psi-impl/src/com/intellij/xml/util/XmlIdContributor.java) | 
|  | [com.intellij.xml.implicitIdRefProvider](https://jb.gg/ipe?extensions=com.intellij.xml.implicitIdRefProvider) | [`ImplicitIdRefProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/psi/impl/source/resolve/reference/impl/providers/ImplicitIdRefProvider.java) | 
|  | [com.intellij.xml.implicitNamespaceDescriptorProvider](https://jb.gg/ipe?extensions=com.intellij.xml.implicitNamespaceDescriptorProvider) | [`ImplicitNamespaceDescriptorProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/javaee/ImplicitNamespaceDescriptorProvider.java) | 
|  | [com.intellij.xml.namedReferenceProvider](https://jb.gg/ipe?extensions=com.intellij.xml.namedReferenceProvider) | [`PsiSymbolReferenceProvider`](upsource:///platform/core-api/src/com/intellij/model/psi/PsiSymbolReferenceProvider.java) | 
|  | [com.intellij.xml.namespaceHelper](https://jb.gg/ipe?extensions=com.intellij.xml.namespaceHelper) | [`XmlNamespaceHelper`](upsource:///xml/xml-psi-impl/src/com/intellij/xml/XmlNamespaceHelper.java) | 
|  | [com.intellij.xml.nsColorProvider](https://jb.gg/ipe?extensions=com.intellij.xml.nsColorProvider) | [`XmlNSColorProvider`](upsource:///xml/xml-analysis-impl/src/com/intellij/codeInsight/daemon/impl/analysis/XmlNSColorProvider.java) | 
|  | [com.intellij.xml.psiPolicy](https://jb.gg/ipe?extensions=com.intellij.xml.psiPolicy) | [`XmlPsiPolicy`](upsource:///xml/xml-psi-impl/src/com/intellij/psi/impl/source/xml/XmlPsiPolicy.java) | 
|  | [com.intellij.xml.relatedToHtmlFilesContributor](https://jb.gg/ipe?extensions=com.intellij.xml.relatedToHtmlFilesContributor) | [`RelatedToHtmlFilesContributor`](upsource:///xml/impl/src/com/intellij/navigation/RelatedToHtmlFilesContributor.java) | 
|  | [com.intellij.xml.schemaProvider](https://jb.gg/ipe?extensions=com.intellij.xml.schemaProvider) | [`XmlSchemaProvider`](upsource:///xml/xml-psi-api/src/com/intellij/xml/XmlSchemaProvider.java) | 
|  | [com.intellij.xml.startTagEndToken](https://jb.gg/ipe?extensions=com.intellij.xml.startTagEndToken) | [`StartTagEndTokenProvider`](upsource:///xml/xml-psi-impl/src/com/intellij/psi/xml/StartTagEndTokenProvider.java) | 
|  | [com.intellij.xml.tagNameProvider](https://jb.gg/ipe?extensions=com.intellij.xml.tagNameProvider) | [`XmlTagNameProvider`](upsource:///xml/impl/src/com/intellij/xml/XmlTagNameProvider.java) | 
|  | [com.intellij.xml.undefinedElementFixProvider](https://jb.gg/ipe?extensions=com.intellij.xml.undefinedElementFixProvider) | [`XmlUndefinedElementFixProvider`](upsource:///xml/xml-analysis-impl/src/com/intellij/xml/XmlUndefinedElementFixProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [com.intellij.xml.util.htmlDoctypeProvider](https://jb.gg/ipe?extensions=com.intellij.xml.util.htmlDoctypeProvider) | [~~`HtmlDoctypeProvider`~~](upsource:///xml/xml-psi-impl/src/com/intellij/xml/util/HtmlDoctypeProvider.java) | 
|  | [com.intellij.xml.validateHandler](https://jb.gg/ipe?extensions=com.intellij.xml.validateHandler) | [`ValidateXmlHandler`](upsource:///xml/xml-psi-impl/src/com/intellij/xml/actions/validate/ValidateXmlHandler.java) | 
|  | [com.intellij.xml.xmlExtension](https://jb.gg/ipe?extensions=com.intellij.xml.xmlExtension) | [`XmlExtension`](upsource:///xml/xml-psi-impl/src/com/intellij/xml/XmlExtension.java) | 
|  | [com.intellij.xml.xmlSuppressionProvider](https://jb.gg/ipe?extensions=com.intellij.xml.xmlSuppressionProvider) | [`XmlSuppressionProvider`](upsource:///xml/xml-psi-api/src/com/intellij/codeInspection/XmlSuppressionProvider.java) | 
|  | [com.intellij.xml.xmlTagRuleProvider](https://jb.gg/ipe?extensions=com.intellij.xml.xmlTagRuleProvider) | [`XmlTagRuleProvider`](upsource:///xml/xml-analysis-api/src/com/intellij/xml/XmlTagRuleProvider.java) | 
|  ![Experimental API](https://img.shields.io/badge/-Experimental_API-red) | [com.intellij.xml.xmlTypedHandlersAdditionalSupport](https://jb.gg/ipe?extensions=com.intellij.xml.xmlTypedHandlersAdditionalSupport) | [`XmlTypedHandlersAdditionalSupport`](upsource:///xml/xml-psi-api/src/com/intellij/openapi/editor/XmlTypedHandlersAdditionalSupport.java) | 
|  | [com.intellij.xml.zenCodingFilter](https://jb.gg/ipe?extensions=com.intellij.xml.zenCodingFilter) | [`ZenCodingFilter`](upsource:///xml/impl/src/com/intellij/codeInsight/template/emmet/filters/ZenCodingFilter.java) | 
|  | [com.intellij.xml.zenCodingGenerator](https://jb.gg/ipe?extensions=com.intellij.xml.zenCodingGenerator) | [`ZenCodingGenerator`](upsource:///xml/impl/src/com/intellij/codeInsight/template/emmet/generators/ZenCodingGenerator.java) | 
|  | [com.intellij.xmlStructureViewBuilderProvider](https://jb.gg/ipe?extensions=com.intellij.xmlStructureViewBuilderProvider) | [`XmlStructureViewBuilderProvider`](upsource:///xml/xml-structure-view-api/src/com/intellij/ide/structureView/xml/XmlStructureViewBuilderProvider.java) | 
|  | [com.intellij.xmlStructureViewElementProvider](https://jb.gg/ipe?extensions=com.intellij.xmlStructureViewElementProvider) | [`XmlStructureViewElementProvider`](upsource:///xml/xml-structure-view-api/src/com/intellij/ide/structureView/xml/XmlStructureViewElementProvider.java) | 

## [XPathView](upsource:///plugins/xpath/xpath-view/src/META-INF/plugin.xml)

| Note | Extension Point | Implementation |
|---|---|---|
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [XPathView.xpath.contextProviderExtension](https://jb.gg/ipe?extensions=XPathView.xpath.contextProviderExtension) | [`ContextProviderExtension`](upsource:///plugins/xpath/xpath-lang/src/org/intellij/lang/xpath/context/ContextProviderExtension.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [XPathView.xpath.functionProvider](https://jb.gg/ipe?extensions=XPathView.xpath.functionProvider) | [`XPathFunctionProvider`](upsource:///plugins/xpath/xpath-lang/src/org/intellij/lang/xpath/context/functions/XPathFunctionProvider.java) | 
|  ![Non-Dynamic](https://img.shields.io/badge/-Non--Dynamic-orange) | [XPathView.xsltRunnerExtension](https://jb.gg/ipe?extensions=XPathView.xsltRunnerExtension) | [`XsltRunnerExtension`](upsource:///plugins/xpath/xpath-lang/src/org/intellij/lang/xpath/xslt/run/XsltRunnerExtension.java) | 