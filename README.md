#API Reference

The following resources are made available by the *GitNes* API:

* [Games](#games)
* [Matches](#matches)
* [Leaderboards](#leaderbaords)


##Games

Register in the datastore

| Property    | Data Type | Description                                                                             |
|:------------|-----------|:----------------------------------------------------------------------------------------|
| id          | string    | Key in the datastore										        					|
| name        | string    | Name of the Game                 														|
| uploader	  | string    | Key of the user who uploads a games 													|
| description | string    | Brief description of the caracteristics  of the game                                    |
| category    | string    | Category of the name                                                                    |
| uploaddate  | string    | Date in which the game was added                            |


###Methods

| Method | Request URI                              		| Description                              |
|:-------|:-------------------------------------------------|:-----------------------------------------|
| GET    | [/games](#users-1)                       		| Obtains all the games in the system      |
| GET    | [/gamesearch/*{id}*](#users-1)           		| Obtains a specific game  with the key    |
| POST   | [/game/*{id}*/*{id}*/*{id}*/*{id}*](#usersid)    | Add a game in the system                 |
