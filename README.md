# Multi-Armed Bandit API Challenge

## API Information
Register as a user:
https://bandit.swanhack.co.uk/api/register 
```json
{"auth": "<STUDENT_ID>", "nick": "<YOUR_NICKNAME>"}
```
This returns your api key. Keep it safe, you only get it once!

===============================================================

Create a new game:
https://bandit.swanhack.co.uk/api/game/new 
```json
{"reg": "<YOUR_API_KEY>"}
```
This creates a new game and returns the game ID and game information.

===============================================================

Pull a lever:
https://bandit.swanhack.co.uk/api/<GAME_ID> 
```json
{"reg": "<YOUR_API_KEY>"}
```
This returns the game information.

===============================================================

Pull a lever:
https://bandit.swanhack.co.uk/api/<GAME_ID>/<LEVER_ID> 
```json
{"reg": "<YOUR_API_KEY>"}
```
This pulls a lever, returns the reward and the game information.
