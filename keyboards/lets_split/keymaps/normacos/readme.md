# normacos
The normacos keymap is designed for a Let's Split (or any 4x12) keyboard used on a MacOS High Sierra system.

It includes a multitude of macros that open regularly used applications through Spotlight Search.

It also includes several useful macros for the default Terminal.


Norman keyboard layout [info page.](https://normanlayout.info/)

Some Norman layout keys were placed on different layers and different positions based on available space and preference.


Macros (in alphabetical order):
- Chrome opens Chrome through Spotlight Search
- ClrEnd clears Terminal line from cursor up to end of line
- ClrHom clears Terminal line from beginning of line up to cursor
- CtlEsc sends Escape when tapped, and Control when held.
- Lock locks the computer
- Log opens the 'Log Work' modal on Atlassian's Jira web client
- Min hides and minimizes all windows
- OutLk opens Microsoft Outlook through Spotlight Search
- ScnSht allows the user to take a screenshot of a selected portion of the screen
- Search activates Terminal Reverse Search Command History
- SftEnt sends Space Cadet Shift Enter.
- ShHome moves Terminal cursor to beginning of line
- ShEnd moves Terminal cursor to end of line
- Slack opens Slack through Spotlight Search
- Spot opens Spotify through Spotlight Search
- Teams opens Microsoft Teams through Spotlight Search
- Term opens Terminal through Spotlight Search

All macros that make use of the SEND_STRING command have a 100 millisecond delay between steps so the OS/app catches up.
Any and all empty keys below may or may not be set in time, and do nothing as of the time of this writing.



## Default (Norman)
```
,-----------------------------------------. ,-----------------------------------------.
|  Tab |   Q  |   W  |   D  |   F  |   K  | |   J  |   U  |   R  |   L  |   ;  | Bksp |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|CtlEsc|   A  |   S  |   E  |   T  |   G  | |   Y  |   N  |   I  |   O  |   H  |  '   |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Shift|   Z  |   X  |   C  |   V  |   B  | |   P  |   M  |   ,  |   .  |   /  |SftEnt|
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Lock | Home |  End |  Alt | Lower|  GUI | | Space| Raise| Left | Down |  Up  | Right|
`-----------------------------------------' `-----------------------------------------'
```


## Lower
```
,-----------------------------------------. ,-----------------------------------------.
|  Tab |  F1  |  F2  |  F3  |  F4  |      | |NumLck|   7  |   8  |   9  |   =  | Bksp |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|CtlEsc|  F5  |  F6  |  F7  |  F8  |      | |   *  |   4  |   5  |   6  |   +  |  Del |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Shift|  F9  |  F10 |  F11 |  F12 |      | |   /  |   1  |   2  |   3  |   -  |SftEnt|
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Lock | Home |  End |  Alt | Lower|  GUI | | Space| Raise|   0  |   .  | Spot |Chrome|
`-----------------------------------------' `-----------------------------------------'
```


## Raise

```
,-----------------------------------------. ,-----------------------------------------.
|  Tab |   !  |   @  |   #  |   $  |   %  | |   ^  |   &  |   *  |   (  |   )  |  Del |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|CtlEsc|  Log | Teams| Slack| Term | OutLk| |   =  |   -  |   \  |   [  |   ]  |   `  |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Shift|ClrHom|ClrEnd|ShHome| ShEnd|Search| | Play | Mute | VolDn| VolUp|ScnSht|SftEnt|
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Lock | Home |  End |  Alt | Lower|  GUI | | Space| Raise| Left | Down |  Up  | Right|
`-----------------------------------------' `-----------------------------------------'
```

## Adjust (Lower + Raise)

```
,-----------------------------------------. ,-----------------------------------------.
|      |      |      |      |      |      | |      |      |      |      |      |      |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|      |      |      |      | Reset|      | |      | Reset|      |      |      |      |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|      |      |      |      |      |      | |      |      |      |      |      |      |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|      |      |      |      | Lower|      | |      | Raise|      |      |      |      |
`-----------------------------------------' `-----------------------------------------'
```
