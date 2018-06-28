# Diamond Sweeper

## Game

The Game is built on plain Javascript. You can do following actions in game.

1. Game initiates without hint
2. You can re initiate the game at any point of time by clicking (new game or new game with hints button)
3. If you play with hints arrow will appear on click pointing in general direction of nearest diamond if diamond is not found on clicked cell
4. You can save current state of your game at any point of time in game 
5. You can load your last saved game at any point of time in game 


Requirements:

* node.js (the app was built against v9.2.1, but any node > 6 should work)
* npm
* webpack

To start the Application:

* Install the dependencies: `npm install`
* Compile assets: `npm run compile`
* Start the webserver: `npm start`
* Visit http://localhost:3000 to see the application
