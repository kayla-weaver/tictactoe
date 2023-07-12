describe: game
test: should create 2 players and a board, be able to move to the next turn, know which player's turn it is, and be able to tell if the game is over or not
code:
```javascript

class Game
constructors() {
    this.player = {};
    this.score = ();
}

expected outcome: when clicked will generate new play board, create two players, 

describe:  2 Players Created on Start Game
test: When a new game is started, two players should be created
code:  
```javascript
Player1 === {x};
Player2 === {o};
```
expected outcome:  Player 1 === True, Player2 === True

describe: Space
test: it will create a space object with a initial marked value of false
code:
```javascript

const x1 = new Space();

x1.marked;
```
expected outcome:
x1.marked should be false
