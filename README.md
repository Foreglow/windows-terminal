<p align="center"><img width="320" alt="foreglow-logo" src="https://github.com/user-attachments/assets/5b0f629b-9800-4c97-b23b-fa3f22681ea4" /></p>

<h3 align="center">Foreglow Theme for <a href="https://apps.microsoft.com/detail/9n0dx20hk701?hl=en-US&gl=US">Windows Terminal</a></h3>

<p align="center">
  <a href="https://github.com/Foreglow/windows-terminal/stargazers"><img src="https://img.shields.io/github/stars/Foreglow/windows-terminal?style=for-the-badge&labelColor=313244&color=CB81E4" alt="Stars" /></a>
  <a href="https://github.com/Foreglow/windows-terminal/issues"><img src="https://img.shields.io/github/issues/Foreglow/windows-terminal?style=for-the-badge&labelColor=313244&color=8930A6" alt="Issues" /></a>
  <a href="https://github.com/Foreglow/windows-terminal/graphs/contributors"><img src="https://img.shields.io/github/contributors/Foreglow/windows-terminal?style=for-the-badge&labelColor=313244&color=FF6B8A" alt="Contributors" /></a>
  <a href="https://github.com/Foreglow/windows-terminal/blob/main/LICENSE"><img src="https://img.shields.io/github/license/Foreglow/windows-terminal?style=for-the-badge&labelColor=313244&color=2EE8C8" alt="License" /></a>
</p>

<img width="885" height="815" alt="winterm" src="https://github.com/user-attachments/assets/8635f93c-29c9-4a0c-9a79-0cd608a3026c" />

## Previews

<details>
  <summary>🌃 Foreglow</summary>
  <img width="585" height="515" alt="winterm-foreglow" src="https://github.com/user-attachments/assets/45f0fe99-2ba9-4f17-9ad4-b6ec9fd11d06" />
</details>

<details>
  <summary>🌇 Afterglow</summary>
  <img width="585" height="515" alt="winterm-afterglow" src="https://github.com/user-attachments/assets/5440021b-c8e6-4c42-a8f2-1e7b8b5e5a04" />
</details>

<details>
  <summary>🌉 Alpenglow</summary>
  <img width="585" height="515" alt="winterm-alpenglow" src="https://github.com/user-attachments/assets/ded32caa-138b-4e96-92f2-6c515187ade3" />
</details>

<details>
  <summary>🌌 Airglow</summary>
  <img width="585" height="515" alt="winterm-airglow" src="https://github.com/user-attachments/assets/a8f73257-c238-4f6a-a3a9-5c1d1399e79f" />
</details>

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
