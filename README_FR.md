[🇫🇷](README_FR.md)  [🇬🇧](README.md)

# Installation

1. Télécharger [The_Cycle_Release.zip](https://mega.nz/file/NcQn1Lqa#ElIDb0Nk3xVF7MlbyGuLpPo2iDgNjPXGeM7Y1d1hEZw) et [YDeveloperSettings.ini](YDeveloperSettings.ini)
2. Remplacer dans `%AppData%\Local\Prospect\Saved\Config\WindowsNoEditor` le fichier `YDeveloperSettings.ini` (si le dossier n'exsite pas, lancer le jeu une fois)
3. Multijoueur uniquement : Télécharger et installer [RadminVPN](https://www.radmin-vpn.com/fr/) ou [Hamachi](https://vpn.net/)

# Jouer au jeu

Lancer `run_game.bat`

Vous avez accès à la console du jeu si vous appuyez sur `F1`

## Commandes utiles

- Changer de carte : `open <map>` (Liste des cartes : MP_Map01_P, MP_Map02_P, Station_P)
- Changer de nom : `setname <YourName>`
- Ouvrir un serveur : `open <map>?Listen`
- Rejoindre un serveur : `open <@IP>`
- Se tuer : `suicide` 

## Multijoueur

1. Connectez vous ensemble à l'aide du VPN de votre choix 
2. Un joueur devra être l'hôte (Un bon ordinateur et une bonne connexion sont recommandés), il ouvrira un serveur (Par exemple : `open <MP_Map01_P>?Listen`)
3. Les autre joueurs rejoingnent le serveur avec `open <@IP>`, et `@IP` étant l'IP de l'hôte du serveur sur le réseau VPN

> [!CAUTION]
> L'hôte ne peut pas intérragir avec le jeu sans être bloqué/crash. Néanmoins, il peut lancer une deuxième fois The Cycle et se connecter avec `open 127.0.0.1`

...
