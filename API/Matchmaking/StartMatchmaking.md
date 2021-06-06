# Start Matchmaking
Starting a match of splitgate.

## Data `POST`
Game Types: `UNRANKED_TEAM_SOCIAL` `RANKED_TAKEDOWN`	 

Game Modes: `LTAG, TDM, KOTH, DOM, VIP, TOB, SWAT, SHOTSNIP, FFA, GG, TD, IG, TBC` "Select at least 3"	
 	
Region: `US_WEST, US_EAST, EUROPE, JAPAN`
	 	
## URL

`https://api.splitgate.com/game-client/start-matchmaking`

## Body
```json
{
	"playlists": [
		{
			"type": "GAMETYPE",
			"gameModes": [
				"GAMEMODE",
				"GAMEMODE",
				"GAMEMODE"
			]
		}
	],
	"region": "REGION",
	"crossPlatform": true,
	"queueReason": "NORMAL"
}
```

## Header's
- `Authorization`: TOKEN