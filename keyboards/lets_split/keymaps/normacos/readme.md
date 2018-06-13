# normacos
The normacos keymap is designed for a Let's Split (or any 4x12) keyboard used on a MacOS High Sierra system.

It includes a multitude of macros that open regularly used applications through Spotlight Search.

It also includes several useful macros for the default Terminal.


Norman keyboard layout [info page.](https://normanlayout.info/)

Some Norman layout keys were placed on different layers and different positions based on available space and preference.


Macros:
- CtlEsc sends Escape when tapped, and Control when held.
- SftEnt sends Enter when tapped, and Shift when held.
- Lock locks the computer
- Slack opens Slack through Spotlight Search
- Term opens Terminal through Spotlight Search
- Spot opens Spotify through Spotlight Search
- Chrome opens Chrome through Spotlight Search
- OutLk opens Microsoft Outlook through Spotlight Search
- ScnSht allows the user to take a screenshot of a selected portion of the screen
- ClrHom clears Terminal line from beginning of line up to cursor
- ClrEnd clears Terminal line from cursor up to end of line
- ShHome moves Terminal cursor to beginning of line
- ShEnd moves Terminal cursor to end of line
- Search activates Terminal Reverse Search Command History
- Log opens the 'Log Work' modal on Atlassian's Jira web client
- UpDir moves working directory to its parent

All macros that make use of the SEND_STRING command have a 100 millisecond delay between steps so the OS/app catch up.
Any and all empty keys shown below will be set eventually, and do nothing as of the time of this writing.



## Default (Norman)
```
,-----------------------------------------. ,-----------------------------------------.
|  Tab |   Q  |   W  |   D  |   F  |   K  | |   J  |   U  |   R  |   L  |   ;  | Bksp |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|CtlEsc|   A  |   S  |   E  |   T  |   G  | |   Y  |   N  |   I  |   O  |   H  |  '   |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Shift|   Z  |   X  |   C  |   V  |   B  | |   P  |   M  |   ,  |   .  |   /  |  Ent |
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
| Shift|  F9  |  F10 |  F11 |  F12 |      | |   /  |   1  |   2  |   3  |   -  |  Ent |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Lock | Home |  End |  Alt | Lower|  GUI | |   .  | Raise|   0  | Spot |Chrome|      |
`-----------------------------------------' `-----------------------------------------'
```


## Raise

```
,-----------------------------------------. ,-----------------------------------------.
|  Tab |   !  |   @  |   #  |   $  |   %  | |   ^  |   &  |   *  |   (  |   )  |  Del |
|------+------+------+------+------+------| |------+------+------+------+------+------|
|CtlEsc|  Log | UpDir| Slack| Term | OutLk| |   =  |   -  |   \  |   [  |   ]  |   `  |
|------+------+------+------+------+------| |------+------+------+------+------+------|
| Shift|ClrHom|ClrEnd|ShHome| ShEnd|Search| | Play | Mute | VolDn| VolUp|ScnSht|  Ent |
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
