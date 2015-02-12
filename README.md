# Theme - LP

Light and Purple (LP) theme for Sublime Text 2/3.
Project site - [github.com/dubeg/theme-lp](https://github.com/dubeg/theme-lp)

## Screenshots

![Default window](http://i.imgur.com/kBnPxek.png)

![Dirty tab styles](http://i.imgur.com/lEVadkE.png)

![Compare folders](http://i.imgur.com/Q0RnPzl.png)

![Compare groups](http://i.imgur.com/2PsbNHp.png)

![Tab styles](http://i.imgur.com/BizXGW1.png)

![Tab sizes](http://i.imgur.com/wiUnRPt.png)

![Sidebar row styles](http://i.imgur.com/5j8ZjmB.png)

## Visual Studio Light Style

![VS Skin](http://i.imgur.com/5kIekBD.png)

## Installation

### Using Sublime Package Control

Using Will Bond's [Sublime Package Control](http://wbond.net/sublime_packages/package_control),

- Open the Command Palette `Tools -> Command Palette...`.
- Type `Package Control: Install Package`.
- Search for `Theme - LP` in the packages list.

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - LP`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activation

To configure Sublime Text to use the theme, follow the instructions below.

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`.
* Add (or update) your theme entry according to your version of Sublime text.

**ST3**

    "theme": "LP3.sublime-theme"

**ST2**

    "theme": "LP2.sublime-theme"

### Visual Studio Style

To use the vs style, you must add a file named 'Widget - LP3.sublime-settings' (OR 'Widget - LP2.sublime-settings' for ST2) in your User directory, with the following content:

    {
        "color_scheme": "Packages/Theme - LP/assets/Widget_VS.stTheme"
    }

In your User Settings, add the following line:

    "lp_use_vs" : true

Note that this style overrides settings for tabs and the active sidebar row.  To use the vs folder icon, add this line to your User settings:

    "lp_use_folder_icon2": true


## Configuration

You can use the settings below to customize the theme to your liking.

**All possible User Settings**

    "lp_hide_btn_close_tab" : true,
    "lp_always_show_minimap_viewport" : true,
    "lp_autohide_scrollbars" : true,
    "lp_bold_folder_labels" : true,
    "lp_mouse_wheel_switches_tabs" : true,
    "lp_highlight_active_sidebar_row" : true,
    
    "lp_hide_file_icons" : true,
    "lp_hide_folders" : true,
    "lp_hide_group_icons" : true,
    "lp_hide_scrollbars" : true,

    "lp_use_folder_icon1" : true, // Default
    "lp_use_folder_icon2" : true,
    "lp_use_folder_icon3" : true,
    "lp_use_folder_icon4" : true,

    "lp_use_group_icon1" : true, // Default
    "lp_use_group_icon2" : true,
    "lp_use_group_icon3" : true,
    "lp_use_group_icon4" : true,

    "lp_use_sidebar_active_row_style1": true, // Default
    "lp_use_sidebar_active_row_style2": true,
    "lp_use_sidebar_active_row_style3": true,
    
    "lp_use_tab_dirty_icon1": true, // Default 
    "lp_use_tab_dirty_icon2": true, 

    "lp_use_tab_style0" : true, // Default
    "lp_use_tab_style1" : true,
    "lp_use_tab_style2" : true,
    "lp_use_tab_style3" : true,
    "lp_use_tab_style4" : true,
    "lp_use_tab_style5" : true,

    "lp_use_small_tabs": true,
    "lp_use_mini_tabs": true,

    // -----------------------------------------------
    // New with 1.1.0
    // -----------------------------------------------
    "lp_use_vs" : true,          // Visual Studio UI Style


    // -----------------------------------------------
    // New with 1.2.0
    // -----------------------------------------------
    "lp_use_vs_medium_tabs" : true ,        // Medium height
    "lp_use_vs_medium_wide_tabs" : true,    // Medium height and width



## Resolution Support

No support for High DPI displays yet. If you have issues with some UI parts, please tell me.

## Bonus

### Color Scheme

The color scheme seen in the screenshots is simply called Visual Studio, available at [mihaifm's github page.](https://github.com/mihaifm/Visual-Studio.tmTheme).


## Credits

Some assets used in this theme are from (or modified from):

- Soda theme, by Ian Hill [(buymeasoda.com)](http://buymeasoda.com/)
- Numix project [(Numix - ST3)](https://github.com/Zetch/sublime-text-numix)
- Seti project [(Seti UI - Atom)](https://github.com/jesseweed/seti-ui) [(Seti - ST3)](https://github.com/ctf0/Seti_ST3)
- Visual Studio 2013 


## License

LP Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on LP Theme.

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "LP Theme" (or a close variant) in the main project title, repo name or Package Control name.
