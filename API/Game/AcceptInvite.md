# Party Invitations
Accept ivites to parties.

## Data `POST`
EncodedCompositePlatformIds: `ID`

Id: `USERID`	

## URL

`https://api.splitgate.com/game-client/accept-invite`

## Body
```json
{
	"id": "USERID",
	"type": "Party",
	"encodedCompositePlatformId": "ID"
}
```

## Headers
- `Authorization`: TOKEN