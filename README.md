# Bingo!
![Purse](d.png)
This is an online bingo game. Here is the data diagram:

## Team
Name | Email | Phone
--- | --- | ---
John | J@example.com | (887) 657-2323
Lem | L@example.com | (337) 337-2323

## APIs
[Join Game](README.md#join-game )

[Anti Up](README.md#anti-up)

[Draw Cards](README.md#draw-cards)


## Join Game
This API allows the user to join the game. It uses the "GET" HTTP method.

Sample Call:
```http
http://bingo.com/api/joingame?name=Sean
```
This allows a player named Sean to join the game. 

Sample Response:
```javascript
{"status": "success"}
```
Sample Error:
```javaxcript
{"status":"fail-player not old enough"}
```
## Anti Up
## Draw Cards

