# Darkland

## About

Darkland is a simple theme and accompanying color scheme for Sublime Text 2 & 3. It is derived from Flatland Dark which was mostly derived from [Soda](https://github.com/buymeasoda/soda-theme), the right place to start for any custom theme development for Sublime. Thanks Soda!

## Design

![Screen Shot!](TODO)


## Installation
Darkland is a Sublime package. There are several ways to install it.

### Sublime Package Control
You can install it using the excellent [Package Control][] package manager for Sublime Text:

1. Open "Package Control: Install Package" from the Sublime quick menu (Command-Shift-P).
2. Select the 'Theme - Darkland' option to install Darkland.

[Package Control]: http://wbond.net/sublime_packages/package_control

### Git Installation
Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

While inside the `Packages` directory, clone the theme repository using the command below:

```bash
git clone git://github.com/thinkpixellab/Darkland.git "Theme - Darkland"
```

### Manual Installation
You can also install it manually by following these instructions:

1. [Download theme files](TODO)
2. Unzip the files and copy the folder newly created folder into your Sublime Text Packages directory with the name `Theme - Darkland`. You can find that directory by selecting "Preferences > Browse Packages ...".


## Activating the Theme
Activate the theme by modifying your user preferences to include the following:

```javascript
{
  "theme": "Darkland Dark.sublime-theme",
  "color_scheme": "Packages/Darkland/Darkland.tmTheme"
}
```

If you need help locating your user preferences file, you can find it selecting "Preferences > Settings - User".

## Optional Settings
The following options can be set in your user preferences:

```javascript
{
  // square file tabs instead of rounded corners
  "Darkland_square_tabs": true,

  // Monokai color scheme (SublimeText's default) with Darkland background color
  "color_scheme": "Packages/Darkland/Darkland-Monokai.tmTheme",

  // Ability to change row height of sidebar tree
  // Options: xsmall, small, medium, large, xlarge
  "Darkland_sidebar_tree_xsmall" : true
}
```
