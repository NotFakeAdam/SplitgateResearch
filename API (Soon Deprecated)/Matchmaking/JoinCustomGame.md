# Joining Custom Matches
Joining private session's via Session ID.

## Data `POST`

Game Session ID: Session ID

Password: Text

AsSpectator: True/False 	

## URL

`https://api.splitgate.com/game-client/join-custom-game`

## Body
```json
{
	"gameSessionId": "ID",
	"password": "PASSWORD",
	"asSpectator": false
}
```

## Headers
- `Authorization`: TOKEN