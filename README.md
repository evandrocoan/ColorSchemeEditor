ColorSchemeEditor
=================
Real-time color scheme editor plugin for Sublime Text 2/3.

Screenshots
===========
### Automatic scope display
![Real-time scope display](https://raw.github.com/bobef/ColorSchemeEditor/master/screenshots/screen1.png)

### Quick color selection (thirdparty plugin)
![Quick color selection (thirdparty plugin)](https://raw.github.com/bobef/ColorSchemeEditor/master/screenshots/screen2.png)

### Real-time preview
![Real-time preview](https://raw.github.com/bobef/ColorSchemeEditor/master/screenshots/screen3.png)


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `ColorSchemeEditor` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


Usage
=====
- Activate the color scheme you want to edit. **it must be an editable file on your disk, not inside a `.sublime-package`.** If you are using Sublime Text 3 and your theme is inside a package, install the [`PackageResourceViewer`](https://packagecontrol.io/packages/PackageResourceViewer) plugin, open the Command Palette, type ***prv***, and select **`PackageResourceViewer: Open Resource`**. Scroll down until you find the name of the package you want (the built-in color schemes are in `Color Scheme - Default`) and hit Enter. You can now find the `.tmTheme` file you want and hit Enter. The interface allows you to select more files, just hit Escape when you're done. Now, finally, you need to select **`File -> Save`** for each file you extracted, or it won't show up in your `Packages` folder (**`Preferences -> Browse Packages...`**). Once you're done, you can close the `.tmTheme` file tabs.
- Open some code and press Shift+F12.
- Your color scheme should open in a separate pane.
- As you put the cursor on different source elements, the other pane will find and display the XML element that is affecting this element.
- If more than one style element affects the code element, the most relevant style match is displayed first. You can go to the other matches with `Ctrl+Alt+Right` and `Ctrl+Alt+Left`.
- Change the styles as you wish and save so Sublime Text will reload the styles and display your changes.
- When you are done editing press Shift+F12 again or close the view of the color scheme file.

Authors
=======
Borislav Peev (borislav.asdf at gmail dot com)
