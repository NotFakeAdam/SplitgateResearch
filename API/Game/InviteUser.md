# Invite User
Invite a user from your auth token.

## Data `POST`
ID: `User's ID`

EncodedPlatformUserId: `Platform ID`

## URL

`https://api.splitgate.com/game-client/send-invite`

## Body
```json
{
	"id": "ID",
	"type": "Party",
	"encodedCompositePlatformId": "Platform ID"
}
```

## Header's
- `Authorization`: TOKEN