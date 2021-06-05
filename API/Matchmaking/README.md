# Start Matchmaking
Starting the a match.

## Data
Game Types: `UNRANKED_TEAM_SOCIAL` `RANKED_TAKEDOWN`
Game Modes: `LTAG, TBC, FFA, TDM, DOM, ` "Select at least 3"
Region: `US_WEST, US_EAST, EUROPE, JAPAN`

## Body
```json
{
	"playlists": [
		{
			"type": "UNRANKED_TEAM_SOCIAL",
			"gameModes": [
				"GAMEMODE",
				"GAMEMODE",
				"GAMEMODE"
			]
		}
	],
	"region": "US_WEST",
	"crossPlatform": true,
	"queueReason": "NORMAL"
}
```

## Authorization
- `Authorization`: `TOKEN`