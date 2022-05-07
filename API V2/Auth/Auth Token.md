# Auth Token

Authentication to interact with the splitgate api!!!!

## Data `POST`

PLATFORMTOKEN: Steam Token (I Think).

ENDPOINT

`https://splitgate.accelbyte.io/iam/v3/oauth/platforms/steam/token`

## Headers

- `Authorization`: Bearer TOKEN

## Body (x-www-form-urlencoded)

```
platform_token:PLATFORMTOKEN
```

## Response Example

```json
{
   "access_token":ACCESSTOKEN,
   "bans":[
    
   ],
   "display_name":DISPLAYNAME,
   "expires_in":3600,
   "is_comply":true,
   "jflgs":0,
   "namespace":"splitgate",
   "namespace_roles":[
      {
         "roleId":ROLEID,
         "namespace":"*"
      }
   ],
   "permissions":[
    
   ],
   "platform_id":"steam",
   "platform_user_id":PLATFORMID,
   "refresh_expires_in":86400,
   "refresh_token":REFRESHTOKEN,
   "roles":[
      ROLES
   ],
   "scope":"account commerce social publishing analytics",
   "token_type":"Bearer",
   "user_id":USERID,
   "xuid":""
}
```
