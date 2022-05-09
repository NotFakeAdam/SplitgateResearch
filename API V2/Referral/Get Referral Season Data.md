# Profile Referral Data

Get your current referral pass data in other terms the items in the pass (The user ID may be anyones but I am not sure I haven't tried it).

## Method `GET`

USERID: You can get this in Auth or just remember it.  
TOKEN: Auth Token.   
SEASON: Season1 at the minute.   

## Endpoint

`https://splitgate.accelbyte.io/social/public/namespaces/splitgate/users/USERID/referral/data?seasonName=SEASON`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "namespace":"splitgate",
   "seasonName":"season1",
   "hasData":true,
   "refereeProgressionLevelThreshold":10,
   "maxProgressionLevel":10,
   "maxReferralPassLevel":50,
   "data":[
      {
         "id":1,
         "rewards":[
            {
               "type":"ITEM",
               "item":{
                  "itemType":"CUSTOMIZATION",
                  "itemSku":"NameTag-37"
               },
               "quantity":1
            }
         ]
      }
   ]
}
```
