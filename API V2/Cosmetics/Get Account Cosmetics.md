# Cosmetics

Get your locker using this so you could make cool and wacky wonderful bots or something!!!!

## Method `GET`

USERID: You can get this in Auth or just remember it.

## Endpoint

`https://splitgate.accelbyte.io/platform/public/namespaces/splitgate/users/USERID/customizations/chosen`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "namespace":"splitgate",
   "userId": USERID,
   "customizations":{
      "Sniper":[
         "0-0",
      ],
      "Jetpack":[
         "0-0"
      ],
      "AssaultRifle":[
         "0-0"
      ],
      "Railgun":[
         "0-0"
      ],
      "NameTag":[
         "0"
      ],
      "RocketLauncher":[
         "0-0"
      ],
      "Emote":[
         "0"
      ],
      "Pistol":[
         "0-0"
      ],
      "PlasmaRifle":[
         "0-0"
      ],
      "Oddball":[
         "0-0"
      ],
      "DMR":[
         "0-0"
      ],
      "Spray":[
         "0"
      ],
      "BattleRifle":[
         "0-0"
      ],
      "Portal":[
         "0"
      ],
      "Bat":[
         "0-0"
      ],
      "PortalGun":[
         "0-0"
      ],
      "Shotgun":[
         "0-0"
      ],
      "Armor":[
         "0-0"
      ],
      "SMG":[
         "0-0"
      ],
      "Banner":[
         "0"
      ]
   },
   "chosenCustomizations":{
      "PortalGun":"0-0",
      "BattleRifle":"0-0",
      "DMR":"0-0",
      "PlasmaRifle":"0-0",
      "Bat":"0-0",
      "Armor":"0-0",
      "Jetpack":"0-0",
      "Shotgun":"0-0",
      "SMG":"0-0",
      "Sniper":"0-0",
      "Spray":"0",
      "Emote":"0",
      "AssaultRifle":"0-0",
      "Banner":"0",
      "NameTag":"0",
      "Oddball":"0-0",
      "Pistol":"0-0",
      "Portal":"0",
      "Railgun":"0-0",
      "RocketLauncher":"0-0"
   }
}
```
