# Profile

Get your locker using this so you could make cool and wacky wonderful bots or something!!!!

## Method `GET`

TOKEN: Auth Token.  
USERID: You can get this in Auth or just remember it.

## Endpoint

`https://splitgate.accelbyte.io/basic/v1/public/namespaces/splitgate/users/me/profiles`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "userId":"Adam",
   "namespace":"splitgate",
   "firstName":"",
   "lastName":"",
   "avatarSmallUrl":"",
   "avatarUrl":"",
   "avatarLargeUrl":"",
   "status":"ACTIVE",
   "language":"en",
   "customAttributes":{

   },
   "publicId":"",
   "referralId":"🏳️‍⚧️",
   "userRoles":[

   ],
   "privateCustomAttributes":{

   }
}
```
