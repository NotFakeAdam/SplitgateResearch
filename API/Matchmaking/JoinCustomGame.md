# Finding Custom Matches
Joining private session's via Session ID.

## Data `POST`

Game Session ID: Session ID

Password: Text

AsSpectator: True/False 	

## Body
```json
{
	"gameSessionId": "ID",
	"password": "PASSWORD",
	"asSpectator": false
}
```

## Header's
- `Authorization`: TOKEN