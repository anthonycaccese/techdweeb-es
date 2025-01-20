WIP

# TechDweeb (Batocera ES Version)

> Of all the Emulation Station themes you could have downloaded, you chose this one. I hope you're proud of yourself. - [TechDweeb](https://youtube.com/techdweeb)

## **Preview**

| System View | Gamelist View |
|----|----|
| <img src="https://github.com/user-attachments/assets/dde088b0-188e-4057-98c4-fc065ea911d1" /> | <img src="https://github.com/user-attachments/assets/6944cf31-9a39-4857-a2b7-139e89e523bf" /> |

## **Features**

- Custom TD Background artwork
- 9 unique colour schemes to choose from (and the ability to define your own)
- System icons for all the popular systems
- Custom fonts and interface design
- Detailed gameslist view with pixel-riffic overlay
- Grid view with overlay
- Font size options
- Game box or logo thumbnail style
- Aspect ratio correction for ultrawide displays
- "That's all you get. More than you deserve, to be honest." - [TechDweeb](https://youtube.com/techdweeb)

## Theme Configuration

The following options can be changed directly from the main menu under `User Interface Settings > Theme Configuration`

| Setting | Description | Options |
| -- | -- | -- |
| Distribution | Used to define which folder to look in for Theme Customization files. | `Batocera/Knulli`, `RockNIX`, `RetroBat` |
| Aspect Ratio | Enables you to select the correct aspect ratio for your screen.  This will automatically set itself so you should not need to change it but if the theme layout looks odd or spacing looks incorrect you can use this setting to make sure the aspect ratio matches your screen. | `16:9`, `16:10`, `4:3`, `3:2`, `1:1` |
| Color Scheme | Sets the color scheme that is used for the theme.  There is a set of prebuilt color schemes that you can select and an option to supply your custom color scheme (selected by choosing `Custom Chaos`). You can see details on customizations below under [Theme Customizations](#theme-customizations). | `Orange Stuff` (Default), `Purple Slime`, `Aqua Slush`, `Green Ooze`, `Pink Fluff`, `Blue Goo`, `Red Squish`, `Grey Gunk`, `DMG Dungeon`, `Custom Choas` |
| Font Size | Set the size for text elements throughout the theme. | `Medium` (Default), `Small`, `Large` |
| System Count | Allows you to turn the game count display on System View On/Off | `Off` (Default), `On` |
| Gamelist View Style | Allows you to select the layout used for the gamelist view | `Detailed + Metdata` (Default), `Basic`, `Detailed` |

### Additional UI Settings 

The following EmulationStation settings can also be changed and will update the look of the theme accordingly:
* `User Interface Settings > Show Clock` - This will allow you to turn the system clock on or off
* `User Interface Settings > Show Battery Status` - This will allow you to change what is displayed for the battery status.

## Theme Customizations

TechDweeb allows customizations to color schemes without the need to edit the source XML.  This enables you to change the look of the theme and still retain your changes when the theme is updated.

### Start Here
- Make sure the `Distribution` setting is set to the correct value for your current OS (e.g. Batocera/Knulli, RetroBat or Rocknix)
- This value determines the folder where you will add your customizations
    - Batocera/Knulli = `/userdata/theme-customizations/techdweeb/`
    - RockNIX = `/roms/_userdata/theme-customizations/techdweeb/`
    - Retrobat = `C:\RetroBat\emulationstation\.emulationstation\theme-customizations\techdweeb\`
- Create the folders that match your distribution and then move on to the options below...

### Color Scheme

You can create your own custom color scheme to use for the theme

* Download this template: https://github.com/anthonycaccese/techdweeb-es/blob/main/resources/colors.xml
* Upload it in the path you created above and make sure its called `colors.xml`
* Change any values in the template to the colors you prefer.
* I tried to make the values as self explanatory as possible but if you have questions regarding which property does what please don't hesitate to ask.
* After your colors are defined; in theme configuration change `Color Scheme` to `Custom Chaos`

## **Additional Notes**

### Media Scraping:

* To make game artwork look as good as possible the recommneded settings for the built-in scraper are:
    * Image Source = `Screenshot`
    * Box Source = `Box 2D`
    * Logo Source = `Wheel`

### Versions for other ES forks:
- If you use ES-DE... then check out the version [here](https://github.com/anthonycaccese/techdweeb-es-de)

## **Credits**
- All artwork designed and created by [TechDweeb](https://youtube.com/techdweeb)
- Dogica font created by [Roberto Mocci](https://www.dafont.com/roberto-mocci.d8882)
- DWB_Title font designed by [TechDweeb](https://youtube.com/techdweeb) and converted to `.ttf` by JWG.LLC
- Sounds effects created by [Roetaka](https://www.youtube.com/@-roetaka)
- XML and theme build by [Ant](https://github.com/anthonycaccese)

## **License**
Creative Commons CC-BY-NC-SA - https://creativecommons.org/licenses/by-nc-sa/2.0/
You are free to share and adapt this theme as long as you provide attribution back to me (and the above credits) as well share any updates you make under the same licence terms.
