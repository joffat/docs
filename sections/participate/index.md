---
showToc: true
---

# Before You Arrive

You will shortly start your workshop, but we need to make sure you're prepared.

**Please read everything carefully!**

> Socialgorithm is a community of software developers that want to keep coding fun by designing workshops, competitions and challenges for students and companies. If this sounds interesting to you, [join us](https://socialgorithm.org/team/)!

These are the minimum requirements to participate in your workshop:

1. Have a **code editor**. Try [Visual Studio Code](https://code.visualstudio.com/).
1. Install [Git](https://git-scm.com/downloads)
1. Install [NodeJS >7](https://nodejs.org/en/download/current/)

# Getting Your Player
1. Install UABC: `npm install -g @socialgorithm/uabc`
1. Download the player/algorithm starter: `git clone git@github.com:socialgorithm/${GAME}-player`  
e.g. `git clone git@github.com:socialgorithm/tic-tac-toe-player`

# On The Day

## Create a Test Tournament Lobby

You will first need to create a test lobby on our tournament server. You will use this lobby to test your algorithm/player implementation(s).

To create a lobby:

1. Go to https://play-uttt-tournament.herokuapp.com
1. Click "Create Match"
    1. If disconnected, connect to https://play-uttt-tournament.herokuapp.com
1. Click "Get Started"

This is your lobby. You will shortly use the command in the "Connect Your Player" section to test your player.

# Continue: 

Pick the game you are playing today:

* [Tic-Tac-Toe](./tic-tac-toe.md)
* [Ultimate Tic-Tac-Toe](./ultimate-tic-tac-toe/start.md)

-----

# Troubleshooting

### Permission Denied / EACCES

If you see an **EACCES** error when you try to install an NPM package globally: See the [npm docs on permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions).

