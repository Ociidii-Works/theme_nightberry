# Graphene Theme

A very dark theme for Sublime Text 3.

In truth, I just wanted a darker variant of the default theme that didn't break the features I liked about the stock theme.

## Design

Graphene is designed to work with the latest verion of Sublime Text, [Sublime Text 3](http://www.sublimetext.com/3dev).

 [![Preview][thumb]][full]

 The font used is Monaco (TTF version)

## Installation

### Using Sublime Package Control

~~If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Graphene Theme via the `Package Control: Install Package` menu item. The Graphene Theme package is listed as `Theme - Graphene` in the packages list.~~

Soon!

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/ociidii-works/Theme---Graphene Theme - Graphene"

### Download Manually

* Download the files using the GitHub .zip download option
* Unzip the files and rename the folder to `Theme - Graphene`
* Find your `Packages` directory using the menu item  `Preferences -> Browse Packages...`
* Copy the folder into your Sublime Text `Packages` directory

## Activating the theme

To configure Sublime Text to use the theme, follow the instructions below for your specific version.

### Sublime Text 3

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be `"theme": "Graphene.sublime-theme"`

**Example User Settings**

    {
        "theme": "Graphene.sublime-theme",
    }

## Extras

### Syntax Highlighting Colour Schemes

We recommend using [Pastel-Paws](https://github.com/Ociidii-Works/pastel_paws) (Graphene variant) as a color scheme since they are meant to be used together.

* Download Pastel Paws through Package Control
* Enable the colour scheme via `Preferences -> Color Scheme -> User`

## License

Graphene Theme is licensed under the [CC-BY-NC-SA 4.0 License](http://creativecommons.org/licenses/by-nc-sa/4.0/) ([TLDR version](https://tldrlegal.com/license/creative-commons-attribution-noncommercial-(cc-nc))). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: `Based on the Graphene Theme by David "Xenhat" Turenne`

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Graphene Theme" (or a close variant) in the main project title, repo name or Package Control name.

[thumb]: https://raw.githubusercontent.com/Ociidii-Works/Theme---Graphene/master/preview/graphene_thumb.png
[full]: https://raw.githubusercontent.com/Ociidii-Works/Theme---Graphene/master/preview/graphene_full.png
