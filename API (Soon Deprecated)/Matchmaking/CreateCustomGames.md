# Create Custom Game's
Starting a custom game.

## Data `POST`
MaxSpectators: `VALUE`	 

MaxPlayers: `VALUE`

Name: `Any text`
 	
Region: `US_WEST, US_EAST, EU_CENTRAL, JAPAN`	
 	
## URL

`https://api.splitgate.com/game-client/create-custom-game`

## Body
```json
{
	"serverType": "Custom",
    	"groupName": "NULL",
     	"gameMode": null,
	"name": "NAME",
	"region": "REGION",
	"password": "PASSWORD",
    	"maxPlayers": 1,
    	"maxSpectators": 400,
    	"map": "Lobby",
    	"mode": null,
	"crossPlatform": true
}
```

## Headers
- `Authorization`: TOKEN