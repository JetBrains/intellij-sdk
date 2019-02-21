---
title: UI Themes - Editor Schemes and Background Images
---

UI Themes can also provide custom color and font settings, as well as custom images for display in the IntelliJ IDEA application window.
 
## Adding a Custom Editor Scheme
IntelliJ IDEA users can set preferences to configure the colors and fonts used in the Editor. 
These custom color and font settings are called _Editor Color Schemes_.

### Creating a Custom Editor Scheme Using Settings/Preferences
Custom editor color schemes can be specified and exported using the _Settings/Preferences_ dialog.
Note that editor [Colors and Fonts](https://www.jetbrains.com/help/idea/configuring-colors-and-fonts.html), and [Colors for Version Control File Status](https://www.jetbrains.com/help/idea/file-status-highlights.html) are customized in different sections of IntelliJ IDEA _Settings/Preferences_.

Use the following procedure to customize an editor color scheme for a UI Theme: 
* Create the desired custom editor color scheme using the IDE preferences. 
* Export the color scheme. Name the file for the custom scheme.
* Once exported, change the file extension from `*.icls` to `*.xml`.
* See [Customizing Editor Scroll Bar Colors](#customizing-editor-scroll-bar-colors) to change the colors of editor scroll bars. 

### Incorporating the Editor Color Scheme in the Custom UI Theme
The next step is to add the color scheme to the UI Theme plugin project:
* Place the color scheme XML file in the `resources` folder of the UI Theme plugin project.
* Add a key-value pair to the UI Theme description file for the scheme. 
The `key` is always "editorScheme". The `value` is the name of the editor color scheme file.

The example below adds an editor scheme named "Lightning" to the _Theme Basics_ custom UI Theme:
```json
{
  "name": "Theme Basics",
  "dark": false,
  "author": "IntelliJ Platform SDK",
  "ui": {
  },
  "editorScheme": "/Lightning.xml"
}
```

### Editor Color Scheme XML Files
When an editor color scheme is exported as a file, the color options appear as `name`-`value` attributes of `option` elements.
The `name` is the aspect of the editor to be changed, and the `value` is the new color in six-digit RGB or eight-digit RGBA hexadecimal notation.
For example, the snippet below sets the color of the line numbers displayed in the editor:
```xml
<colors>
  <option name="LINE_NUMBERS_COLOR" value="999999" />
</colors>
```
For additional examples of `name` and `value` attributes, review the editor color scheme XML file for the [High Contrast editor scheme](upsource:///platform/platform-resources/src/themes/highContrastScheme.xml).

### Customizing Version Control File Status Colors
As [described above](#creating-a-custom-editor-scheme-using-settingspreferences), colors corresponding to the VCS status of files can be customized and exported via the [IntelliJ IDEA Preferences/Settings](https://www.jetbrains.com/help/idea/file-status-highlights.html).
No other procedure is necessary to customize these colors.
In the exported color scheme file the `name` is the VCS file status, and the `value` is the new color corresponding to that status.
For example, customized VCS colors for a subset of file statuses will appear in the editor scheme file as:
```xml
<colors>
  <option name="FILESTATUS_ADDED" value="62cc47" />
  <option name="FILESTATUS_COPIED" value="62cc47" />
  <option name="FILESTATUS_DELETED" value="ed864a" />
</colors>

```
For additional examples of `FILESTATUS` color `name` attributes, see the editor color scheme XML file for the [High Contrast editor scheme](upsource:///platform/platform-resources/src/themes/highContrastScheme.xml).

### Customizing Editor Scroll Bar Colors
Editor scroll bar colors should be coordinated with, and switch together with an editor color scheme.
Please note that Custom UI Theme (`*.theme.json`) files also contain `ScrollBar.*` name attributes, but these are for scroll bars outside the context of the editor.

>**Note** The Editor Scroll Bar colors are the only custom editor scheme settings that cannot be customized and exported through the IntelliJ IDEA preferences.

Customizing the editor scroll bar colors requires manually changing an editor color scheme XML file.
At this time there isn't code completion functionality for editing color scheme XML files, so the `name` attributes are described below.

#### Editor Scroll Bar Attribute Name Format
The typical format of a scroll bar `name` attribute is `ScrollBar.usage`, where `usage` describes where the color is to be applied.
In some cases `usage` itself can be compound such as `ScrollBar.Mac.Transparent.thumbColor`. 
In these compound cases, the last portion of the compound `usage` still describes where the color is to be applied.

Note that the following example snippet uses an eight-digit hexadecimal color `value` to give `ScrollBar.Mac.thumbColor` transparency:
```xml
<color>
<option name="ScrollBar.background" value="000000"/>
<option name="ScrollBar.Mac.trackColor" value="000000"/>
<option name="ScrollBar.Mac.thumbColor" value="FFFFFFBE"/>
</color>
```

#### Editor Scroll Bar Attribute Names
The full list of scroll bar `name` attributes is in the [High Contrast editor scheme](upsource:///platform/platform-resources/src/themes/highContrastScheme.xml) file. 
These name attributes cannot be accessed from anywhere in the UI at this time, so they must be manually added to an editor color scheme XML file.

The following list explains the `usage` format of the `name` attribute, i.e. where a custom scroll bar color is applied:
* `*.trackColor` — The scroll bar thumb moves across this area.
* `*.thumbColor` — The movable rectangle that corresponds to the visible content's size.
* `*.thumbBorderColor` — The thumb border.
* `*.hoverTrackColor` — Same `usage` as above but for hover.
* `*.hoverThumbColor` — Same `usage` as above but for hover.
* `*.hoverThumbBorderColor` — Same `usage` as above but for hover.

The `name` attribute patterns are enumerated below. 

**Platform Independent Name Attributes**

`ScrollBar.background` sets the background color for the horizontal scroll bar. 
This background color is visible only if the horizontal scroll bar's `*.trackColor` has transparency.

**Windows/Linux Name Attributes** 

The `name` attributes for Windows and Linux have the pattern `ScrollBar.Transparent.*`, where the wildcard portion corresponds to the `usage` definitions above.

**macOS Name Attributes** 

The `name` attribute pattern for the vertical scroll bar is `ScrollBar.Mac.*`.

The `name` attribute pattern for the horizontal scroll bar depends on the macOS preferences _Show scroll bars_ setting:
  * `ScrollBar.Mac.*` when the _Always_ setting is selected.
  * `ScrollBar.Mac.Transparent.*` when the _When scrolling_ setting is selected.

The wildcard portion of these patterns corresponds to the `usage` definitions above.


## Adding a Custom Background Image
The IDE supports setting an image as a background in the application window. 
Users can do this manually in [Preferences](https://www.jetbrains.com/help/idea/setting-background-image.html).

UI Themes support specifying a background image as a key-value pair in the `"background": {}` section of a Theme description file:
* The `image` key uses the file name of the image as the value.
The background image is placed in the UI Theme plugin project's resources folder. 
* The `transparency` key uses a `value` of 1-100. 
A `value` of 100 is opaque.
* The `fill` key uses a value of `scale`, meaning to expand the image to fill the space as the window gets resized.
* The `anchor` key uses a value of `center`, meaning to locate the center of the image in the center of the window. 


The following example adds an image of the Austrian countryside to the _Theme Basics_
Theme description file:
```json
{
  "name": "Theme Basics",
  "dark": false,
  "author": "IntelliJ Platform SDK",
  "ui": {
  },
  "background": {
    "image": "/austria.png",
    "transparency": 10,
    "fill": "scale",
    "anchor": "center"
  }
}
```