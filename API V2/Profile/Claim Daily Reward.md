# Profile Daily Reward

Just send this request and it will claim your daily reward.

## Method `GET`

USERID: You can get this in Auth or just remember it.    
TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/splitgate/public/namespaces/splitgate/users/USERID/dailyCheckIn/status`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "dayOfWeek":6,
   "daysClaimedCount":1,
   "daysMissedCount":5,
   "weekExpiresAtMs":1652054400000
}
```
