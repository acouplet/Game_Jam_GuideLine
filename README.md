# Louvain-li-Nux's GAME JAM 2.0
Welcome to the Louvain-li-Nux's GAME JAM 2.0. If you are reading this guide, it means that you like challenges and you want to code your game in 24 hours. In this guide, you will find all the necessary information to finish this Game Jam safe and alive. 

### About the organizers and sponsors
**Louvain-li-Nux**: This Game Jam is organized by the Louvain-li-Nux, a kot-à-projet that aims to defend and promote the values of free software through the student and academic community of Louvain-la-Neuve. To do this, we organize many activities allowing participants to meet and exchange around computing, while discovering a plethora of open-sourced and, often, free tools. 

![Logo of Louvain-li-Nux](https://louvainlinux.org/images/logo.png)

**INGI**: The INGI department graciously offered the computer rooms for the Game Jam. 

![Logo of INGI](https://avatars3.githubusercontent.com/u/8342035?s=100&v=4)

## Schedule
* **Saturday**
    * *Sat 2.00PM* - Introduction speech by the Louvain-li-Nux and presentation of the sponsors
    * *Sat 2.30PM* - Start of the Game Jam with the revelation of the theme
    * *Sat 7.00PM* - Dinner available (2 hours)
* **Sunday**
    * *Sun 8.00AM* - Breakfast available (2 hours)
    * *Sun 12.00PM* - Lunch available (2 hours)
    * *Sun 2.30PM* - End of the Game Jam and presentation to the jury
    * *Sun 3.30PM* - Announcement of the winner by the jury
    * *Sun 4.00PM* - Final drink

* **H24** Snacks and drinks will be available to buy during the 24 hours of the Game Jam. 

## Structure of the Game Jam
* You will form groups of 3 to 4 people.
* The Louvain-li-Nux's team is there to help you if you have any question about the Game Jam. Be aware that some of them are not proficient in ``python``. For questions about python's syntax, libraries or APIs, please use https://stackoverflow.com/ or the Official Game Jam 2.0 Discord at https://discord.gg/CthqEKs

## Organization
### General information about the structure
* Group of 3 or 4 have been formed or will be formed for the D-day.
* A coach is designated to your team and can help on questions or organization. (As the coach may have multiple groups it is possible that he will not be 100% available)
* planning :
  * Beginning at 2 PM  on Saturday
  * Presentation of sponsor and deployment of the rules and resources.
  * code session till 2 PM on Sunday ( the lab will be close between midnight and 8 in the morning )
  * Presentation of all the games to the jury.
  * 3 PM announcement of the winner by the jury.
  * Final drink.
  * 6 PM finish of the event.

### Guideline through a creative project
* First make an brain storming with out censuring ideas.
* Make a list of criterion you want for your game.
* Then make a first selection of about 10 to 20 ideas following your criterion.
* After that second brain storming around this ideas.
* Now select the 3 best ideas still following your criterion.
* Begin the specification of your 3 ideas.
* Select the most enthusiast one.
* If there is some problem during the conception of your chosen game, you can still come back to one previous idea.

note : this section is given as indication and do not need to be followed.

## Minimum specifications
### General information about the implemented game
* The game must not use non open source resources. ( External API can be used but are not recommended because of the time limitation )
* The game must use Python 3.7.1 ( last stable version of Python)
* The game must use at least the PyGame library as it is a ready to use library for creating game in python.

# Ressources de la Game-Jam 2.0

## L'API Pygame :

> lien de [l'API Pygame](https://www.pygame.org/docs/)

## Les tilesets 2D :

### Animations pour personnage :
   #### 2D Horizontal :

   - [multiples personnages style cartoon](https://www.gameart2d.com/freebies.html)

   - [archer, mage, chevalier style cartoon](https://www.gamedevmarket.net/asset/fantasy-heroes-character-sprite-sheet-10156/)

### Décors :

  - [contrée désertique](https://craftpix.net/freebies/free-2d-rpg-desert-tileset/)

### Entités inertes :

  - [maisons, statues, arbres, rochers, ...](https://vxresource.wordpress.com/category/resources/tilesets/)

### Entités vivantes :

  - [fantasy monstres et boss](https://www.gamedevmarket.net/asset/free-rpg-monster-pack/)

### Items :

  - [Epées, arcs, casques, ...](https://www.gamedevmarket.net/asset/rpg-item-pack-16x16-free/)
  - [8 RPG items](https://www.gamedevmarket.net/asset/free-item-pack-9232/)
  - [48 gemmes différentes](https://www.gamedevmarket.net/asset/free-48-gems-icon-pack/)

## Liens des sites de tilesets :

  - [Gamedevmarket](https://www.gamedevmarket.net/category/2d/?type=free&genre=fantasy&orderby=popularity)

  - [RPG maker](https://rpgmaker.net/resources/)

  - [RPG maker MV](https://rpgmakermv.co/resources/categories/tilesets.9/)

```
$ pip install pygame
```
if pip is not installed by default :
```
$ sudo apt-get install python3-pip
$ sudo apt-get update
```
* The game have to be creative and must not be an imitation of an other game.

### game-play
* The game can be single player or multiplayer.( but creating a LAN network for your game could take too time so we advise to make a multiplayer game local to your machine, ex : 2 layer playing on the same keyboard)
* There is no need to implement I.A in the game.( as you will not have enough time to implement it )
* The game must contain at least one character or object movable by player.
* All kind of input/output can be use but we cannot guarantee the availability of the materials.( for example we cannot give you micros or cameras )
* There is no need to give a main menu with options to change the game parameters. When the script is lunch the game can directly begin.


### Layout
* The game must use at least one of the tile sets provided ( or if it is one find on the web it has to be an open source one ).
* The map don't need to follow the player displacement.
