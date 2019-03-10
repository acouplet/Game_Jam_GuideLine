# Game Jam - v.2.0
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
