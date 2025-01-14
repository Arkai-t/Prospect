[🇫🇷](README_FR.md)  [🇬🇧](README.md)

# Installation

1. Download [The_Cycle_Release.zip](https://mega.nz/file/NcQn1Lqa#ElIDb0Nk3xVF7MlbyGuLpPo2iDgNjPXGeM7Y1d1hEZw) and [YDeveloperSettings.ini](YDeveloperSettings.ini)
2. Replace in `%AppData%\Local\Prospect\Saved\Config\WindowsNoEditor` the file attached `YDeveloperSettings.ini` (if the folder doesn't exist just launch the game)
3. Multiplayer Only : Download and install [RadminVPN](https://www.radmin-vpn.com/fr/) or [Hamachi](https://vpn.net/)

# Play the game

Open `run_game.bat`

You now have access to the in-game console if you press `F1`

## Usefull commands

- Change map : `open <map>` (List of maps: MP_Map01_P, MP_Map02_P, Station_P)
- Change name : `setname <YourName>`
- Open a server : `open <map>?Listen`
- Join a server : `open <@IP>`
- Foam yourself : `suicide` 

## Multiplayer

1. Connect each other through the VPN of you choice 
2. One player will be the host (Good PC and connection required), he will open a server (For example : `open <MP_Map01_P>?Listen`)
3. Others players will join with `open <@IP>` with `@IP` being the host IP address on the VPN

> [!CAUTION]
> Host cannot interact with the game. But he can launch another instance of the game and connect to the game with `open 127.0.0.1`

> [!WARNING]
> There is still an anti-AFK system, so if the host is not in spectator mode, it will kick everyone out of the server. To fix that, wait for a player to connect to the server, then use `suicide` command on the host and everything will be fine until the end of the game
>
> 
> Sniper scopes are bugged in multiplayer : if a player scope, he become invisible for everyone

For now, you can only have access to random suits, weapons and ability. If you re-connect to the host, you will have another loadout.
