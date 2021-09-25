# Setting time on the leaderboard
Add to the leaderboard.

## Data `POST`
Map: `Name of the map to complete`

TimeMS: `Time in milliseconds`	

## URL

`https://api.splitgate.com/game-client/finish-race-course`

## Body
```json
{
	"map": `MAP`,
	"timeMs": `TIME`, 
    	"updatedAt": NULL
}
```

## Headers
- `Authorization`: TOKEN