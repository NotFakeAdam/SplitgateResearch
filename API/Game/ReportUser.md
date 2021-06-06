# Report user
Report a user from your auth token.

## Data `POST`
EncodedCompositeUserId: `User ID`

EncodedPlatformUserId: `Platform ID`

## URL

`https://api.splitgate.com/game-client/user-events`

## Body
```json
{
	"encodedCompositeUserId": "User ID",
	"encodedPlatformUserId": "Platform ID",
	"category": "Other",
	"description": "",
	"gameSessionId": ""
}
```

## Header's
- `Authorization`: TOKEN