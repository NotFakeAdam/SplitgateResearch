# Profile

Take a look at all the currently live playlists.

## Method `GET`

TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/splitgate/public/namespaces/splitgate/playlist/config`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
[
   {
      "name":"UNRANKED_TEAM_DEATHMATCH",
      "state":{
         "minProgressionLevel":0,
         "xpBoostPercentage":0,
         "gameModes":[
            {
               "gameMode":"TDM",
               "minPlayer":1,
               "maxPlayer":4,
               "minTeam":1,
               "maxTeam":2,
               "frequency":1,
               "freeForAll":false,
               "includedMaps":[
                  
               ],
               "excludedMaps":[
                  
               ],
               "placementMaps":[
                  
               ]
            }
         ],
         "maxPartySize":4,
         "matchmakingName":"CASUAL",
         "isActive":true,
         "isCrossplayRequired":false,
         "isFeatured":false,
         "isEligibleForHalfBotGames":true,
         "isRanked":false,
         "isWaitingArea":false
      }
   }
]
```
