# Profile

Get your profile but now you can send a timezone... wowie!!!!

## Method `PUT`

TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/basic/v1/public/namespaces/splitgate/users/me/profiles`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Body (Json)

```json
{
	"timezone": "+01:00"
}
```

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
