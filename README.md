# Foreglow — Windows Terminal Theme

## Installation

1. Copy `foreglow.json` to `%LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\` or keep it anywhere you like.

2. Open Windows Terminal settings (Ctrl+,) or edit `settings.json`.

3. Add `Foreglow` to the `schemes` array and reference it in your profile:
   ```json
   "schemes": [
     {
       "name": "Foreglow",
       "background": "#161221",
       "foreground": "#E8E3F2",
       "cursorColor": "#F471C8",
       "selectionBackground": "#3D2556",
       "black": "#161221",
       "red": "#E46772",
       "green": "#6BC7A8",
       "yellow": "#F2A65A",
       "blue": "#75C6D7",
       "purple": "#CB81E4",
       "cyan": "#EC93BF",
       "white": "#A49BBF",
       "brightBlack": "#322C44",
       "brightRed": "#E46772",
       "brightGreen": "#6BC7A8",
       "brightYellow": "#F2A65A",
       "brightBlue": "#75C6D7",
       "brightPurple": "#CB81E4",
       "brightCyan": "#EC93BF",
       "brightWhite": "#E8E3F2"
     }
   ],
   "profiles": {
     "defaults": {
       "colorScheme": "Foreglow"
     }
   }
   ```

4. Restart Windows Terminal.
