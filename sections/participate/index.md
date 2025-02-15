# Before You Arrive

You will shortly start your workshop, but we need to make sure you're prepared.

**Please read everything carefully!**

> Socialgorithm is a community of software developers that want to keep coding fun by designing workshops, competitions and challenges for students and companies. If this sounds interesting to you, [join us](https://socialgorithm.org/team/)!

These are the minimum requirements to participate in your workshop:

1. Have a **code editor**. Either:
    1. [Visual Studio Code](https://code.visualstudio.com/)
    1. [Intellij](https://www.jetbrains.com/idea/download/)
1. Install [Git](https://git-scm.com/downloads)
1. Install [NodeJS >8](https://nodejs.org/en/download/current/)
1. Install Additional Language Support
    1. Java - [Java >8](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)
    1. Python - [Python >3.6](https://www.python.org/downloads/)
    1. Javascript [NodeJS >8](https://nodejs.org/en/download/current/)

# Getting Your Player
1. Install UABC: `npm install -g @socialgorithm/uabc`
1. Download the player/algorithm starter.

| Language   | Repo                                                                               |
| ---------- |:----------------------------------------------------------------------------------:|
| Java       | [ultimate-ttt-player-java](https://github.com/joffat/ultimate-ttt-player-java.git) |
| Python     | [ultimate-ttt-player-py](https://github.com/joffat/ultimate-ttt-player-py.git)     |
| Javascript | [ultimate-ttt-player-js](https://github.com/joffat/ultimate-ttt-player-js.git)     |

# On The Day

## Create a Test Tournament Lobby

You will first need to create a test lobby on our tournament server. You will use this lobby to test your algorithm/player implementation(s).

To create a lobby:

1. Go to https://play-uttt.herokuapp.com
1. Go to the "Tournaments" tab
1. Click "Create Match"
    1. If disconnected, connect to https://play-uttt-tournament.herokuapp.com
1. Select a Game - e.g Ultimate Tic Tac Toe
1. Select a Timeout and Number of Games Per Match
1. Select a Tournament Type - eg. Double Elimination


This is your lobby. You will shortly use the command in the "Connect Your Player" section to test your player.

## Connect To The Lobby
Find Out How To Connect On The Player Docs

| Language   | Repo                                                                               |
| ---------- |:----------------------------------------------------------------------------------:|
| Java       | [ultimate-ttt-player-java](https://github.com/joffat/ultimate-ttt-player-java.git) |
| Python     | [ultimate-ttt-player-py](https://github.com/joffat/ultimate-ttt-player-py.git)     |
| Javascript | [ultimate-ttt-player-js](https://github.com/joffat/ultimate-ttt-player-js.git)     |


# Continue: 

Pick the game you are playing today:

* [Tic-Tac-Toe](./tic-tac-toe.md)
* [Ultimate Tic-Tac-Toe](./ultimate-tic-tac-toe/index.md)

-----

# Troubleshooting

### Permission Denied / EACCES

If you see an **EACCES** error when you try to install an NPM package globally: See the [npm docs on permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions).

