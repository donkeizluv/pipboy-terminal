# Installation

- copy `assets` to %localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\RoamingState
- open up Terminal config JSON
- add a new profile with following setting:

```JSON
    {
        "colorScheme": "Fallout",
        "backgroundImage": "ms-appdata:///roaming/background.png",
        "backgroundImageOpacity": 0.5,
        "backgroundImageStretchMode": "fill",
        "commandline": "pwsh",
        "cursorShape": "vintage",
        "experimental.retroTerminalEffect": true,
        "font": {
          "face": "Lucida Sans Typewriter"
        },
        "guid": "{b254e6e0-cee2-42a9-8242-ef04f730257a}",
        "hidden": false,
        "icon": "ms-appdata:///roaming/fallout-boy.png",
        "name": "Pipboy",
        "padding": "24",
        "scrollbarState": "hidden",
        "startingDirectory": "%USERPROFILE%",
        "tabTitle": "Pipboy"
    }
```

- add a new corresponding color scheme:

```JSON
{
      "name": "Fallout",
      "background": "#0C0C0C",
      "black": "#0C0C0C",
      "blue": "#26E476",
      "brightBlack": "#767676",
      "brightBlue": "#26E476",
      "brightCyan": "#26E476",
      "brightGreen": "#26E476",
      "brightPurple": "#26E476",
      "brightRed": "#26E476",
      "brightWhite": "#26E476",
      "brightYellow": "#26E476",
      "cursorColor": "#FFFFFF",
      "cyan": "#26E476",
      "foreground": "#26E476",
      "green": "#022000",
      "purple": "#26E476",
      "red": "#26E476",
      "selectionBackground": "#0C0C0C",
      "white": "#26E476",
      "yellow": "#26E476"
    }

```
