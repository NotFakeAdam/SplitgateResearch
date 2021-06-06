# Auth Token
Authentication (Not really needed).

## Data `POST`

PlatformAuthToken: TOKEN

AuthToken: AUTHTOKEN 	

## URL

`https://api.splitgate.com/game-client/auth-token`

## Body
```json
{
	"platform": "STEAM",
	"platformAuthToken": "TOKEN",
	"platformTitleId": "677620",
	"authToken": "AUTHTOKEN",
	"timeDifferenceFromUTC": 1
}
```

## Header's
- `Authorization`: TOKEN