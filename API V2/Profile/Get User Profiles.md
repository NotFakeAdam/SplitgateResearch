# User Profiles

Get a ton of peoples profiles idk why you would but go crazy!!!!!

## Method `POST`

TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/iam/v3/public/namespaces/splitgate/users/bulk/basic`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Body (Json)

```json
{
	"userIds": [
		"🐪"
	]
}
```

## Response 

```json
{
   "data":[
      {
         "userId":"🐪",
         "displayName":"Adam",
         "avatarUrl":"https://cdn.discordapp.com/attachments/770696401776672813/929569341228351508/Jimmy_McGill_BCS_S3.png",
         "platformUserIds":{
            "steam":"hi"
         }
      }
   ]
}
```
