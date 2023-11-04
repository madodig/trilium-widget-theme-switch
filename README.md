# Trilium widget - Theme Switch
Trilium widget for changing themes 
<br><br>
<table><tr></tr><td><img src="https://github.com/madodig/trilium-widget-theme-switch/assets/14966219/6f103d3b-c0f7-4a0c-8157-33e17833c7c8"></td><td>Trilium Notes (https://github.com/zadam/trilium)<br>A hierarchical note taking application with focus on building large personal knowledge bases</td></tr></table>
<br>

### Features
This Trilium widget enables:
- easy switching between themes (optionally without the Frontend reload) via a button (or a switch);
- automatic switching between light/dark mode based on the time of the day.

Possible customizations:
- change appearance of the widget button:
  - static button, in accordance with Trilium title bar buttons design;
  - animated switch, in accordance with current theme style;
- change icon for the button and the dropdown items;
- whether the Trilium frontend reload is triggered to activate the new theme;
- whether to show the dropdown list of available themes or show the button to toggle between current theme's available modes;
- time range that defines when the light and dark mode should be activeted

> The widget activates the new theme by updating stylesheets in the DOM (Document Object Model). This results in more fluid UX, but might not be the preferred way. It is possible to configure the frontend to reload when changing themes.                         

> Toggling between theme modes works for themes that have light/dark variant set in the theme ID (appTheme label).
> To support toggling, when importing new themes in Trilium, make sure you either append the '-light' and '-dark' suffixes or configure the alternate modes in the 'configuration' note.
<br>

### Installation
Download the ZIP file from releases and import it to Trilium (mark the 'Safe import'). When imported, select the 'installer' note and execute it, or add owned attribute #widget to the 'Theme Switch' note and reload the Frontend.

The 'installer' note can be removed after the installation.
<br><br>

> Tested on Trilium desktop v0.60.4
<br>

### Demo
https://github.com/madodig/trilium-widget-theme-switch/assets/14966219/17033f83-0eed-45af-aac0-9df3a37646dc
