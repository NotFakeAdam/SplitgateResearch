# Profile Referral Data

Get your current referral pass info (The user ID may be anyones but I am not sure I haven't tried it).

## Method `GET`

USERID: You can get this in Auth or just remember it.  
TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/social/public/namespaces/splitgate/users/USERID/referral/info`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "namespace":"splitgate",
   "userId":"🏳️‍⚧️",
   "seasonName":"season1",
   "referrerId":"",
   "canBeReferred":true,
   "passLevel":0
}
```
