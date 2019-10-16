# Writing a Player

We're going to write an algorithm that can play UTTT, exciting right? :)

At the most basic level, a player needs to be able to calculate a **valid move**, and receive **opponent moves**. Every time it receives a move from its opponent it will run some calculations, and return what it considers to be the optimal move.

This is the template we provide for you, all actions can be based on these events:

```js
// pseudo-code example of the most basic methods
    /**
     * New Game.
     * Prepare The Board.
     */
    init(){
        ...
    }

    /**
     * Get Move.
     * You Are Starting First.
     * Pick A Board And A Move.
     *
     * @return Your First Move
     */
    Move getMove(){
        ...
    }

    /**
     * Opponent Move.
     * Your Opponent Made A Move.
     * Respond With A Move Where {@return Move}{@link model.Move#board} Matches {@param opponentsMove}.{@link model.Move#board}
     *
     * @param opponentsMove the opponents move
     * @return Your Move In Response
     */
    Move opponentMove(Move opponentsMove) {
        ...
    }

    /**
     * Game Over.
     * The Game Is Over. You Might Still With The Match.
     * Another Game Will Start Soon.
     *
     * @param result (WIN, LOSE, TIE)
     * @param previousMove - Null unless you were not last move
     */
    gameOver(Result result, Move previousMove) {
        ...
    }

    /**
     * Match Over.
     * The Match Is Over.
     * You May Get To Play Again. But For Now, You Have No Opponent.
     *
     * @param result (WIN, LOSE, TIE)
     */
    matchOver(Result result){
        ...
    }
    
    /**
     * Timed Out.
     * The Match Is Over.
     */
    timeout() {
        ...
    }
```

The problem with this is that we need to store and know the **game state** - have a board, calculate whether a player has won, check if a move is valid...

## Getting Started

We provide ready to use implementations that play at random, so you only have to improve the logic that picks the moves.

Pick the one for your language of choice:

* [Python](./python.md)
* [JavaScript](./javascript.md)
* [Other languages...](./other_languages.md)

## Continue: [Analyse Your Games](analyse_games.md)
