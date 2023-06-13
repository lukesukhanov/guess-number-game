<a name="readme-top"></a>

## About the 'Guess my number' game

The game is simple - the player has to guess a number from 1 to 50 with minimal count of attempts.<br />
Information about players can be saved for the future.<br />
Each player has the id, the username and the count of his best attempts.<br />
The player can register, login and logout.

## How to run the game
Execute 'docker-compose up -d' in the directory with docker-compose.yml.
<p>
The following services will start:
<ul>
  <li><b>web</b> on 127.0.0.1:8081 (frontend, API URL set on 127.0.0.1:8082)</li>
  <li><b>player-service</b> on 127.0.0.1:8082 (REST API, CORS set on 127.0.0.1:8081)</li>
</ul>

See also:
<ul>
  <li><a href="https://github.com/lukesukhanov/guess-number-game-web">the frontend part of this project</a></li>
  <li><a href="https://github.com/lukesukhanov/guess-number-game-player-service">the REST API part of this project</a></li>
</ul>
