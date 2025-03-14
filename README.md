# Installation

1. Download [The_Cycle_Release.zip](https://drive.google.com/file/d/1M3beRG8YTR2jwcY-wJgA6Ov5ruKJlVfF/view?usp=sharing) and [YDeveloperSettings.ini](YDeveloperSettings.ini)
2. Replace in `%LocalAppData%\Local\Prospect\Saved\Config\WindowsNoEditor` the file attached `YDeveloperSettings.ini` (if the folder doesn't exist just launch the game)
3. Launch `run_game.bat` to update the game to the last version
4. Multiplayer Only : Download and install [RadminVPN](https://www.radmin-vpn.com/fr/) or [Hamachi](https://vpn.net/)

# Play the game

Open `run_game.bat`

You now have access to the in-game console if you press `F1`

## List of commands

[Prospect/wiki/Commands](https://github.com/Arkai-t/Prospect/wiki/Commands)

## Multiplayer

1. Connect each other through the VPN of you choice 
2. One player will be the host (Good PC and connection required), he will open a server (For example : `open <MP_Map01_P>?Listen`)
3. Others players will join with `open <@IP>` with `@IP` being the host IP address on the VPN

> [!CAUTION]
> Host cannot interact with the game. But he can launch another instance of the game and connect to the game with `open 127.0.0.1`

For now, you can only have access to random suits, weapons and ability. If you re-connect to the host, you will have another loadout.

## WIP
[ ] Choose you starting loadout
[ ] Choose your skins
[x] Server automation
[ ] Various fixes (Boxer jump, steal contracts)
