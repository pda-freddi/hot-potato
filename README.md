# Hot Potato

This project was built for Codecademy's [Learn WebSockets course](https://www.codecademy.com/learn/learn-websockets).

It's a Hot Potato multiplayer game that runs on the browser and uses WebSockets to establish a bidirectional client-server communication, allowing real-time communication and the implementation of a broadcast pattern to pass data to multiple clients at the same time.

The game's logic and file structure were provided by Codecademy as starter code, I built on the WebSockets logic.

## Rules

* Upon connecting to the server, a player will be assigned a character and a yellow star with the text "You" will appear above that character. The game will not start until exactly four players join the room.
* Once the 4th player has joined, the game will start and the clock begins counting down from 30.
* At game start, one player will be chosen randomly to hold the potato.
* If you are holding the potato, click on another player to pass the potato.
* If you are holding the potato when the time is up, you will lose!
* When the game ends, the player count is restarted and the same four players (or other players) can connect to the server to play a new match.

## Setup Instructions

To run the application, start by cloning this repository and navigating to its directory.
```
git clone https://github.com/Pedro-Freddi/hot-potato.git
cd hot-potato
```
Install the necessary dependencies with:
```
npm install
```
And start the server with:
```
node server.js
```
Open the browser and navigate to ``localhost:8080``, where the application should be available.

You can open multiple tabs to simulate other players connecting and test the game logic once it starts.
