# Setting customization values
Change cosmetics.

## Data `POST`
ID: `Cosmetic ID (Easily found in the DataTables)`	

## URL

`https://api.splitgate.com/game-client/update-chosen-customizations`

## Body
```json
{
	"chosenCustomizations": [
		{
			"customizationType": "Armor",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Jetpack",
			"customizationValue": "ID"
		},
		{
			"customizationType": "PortalGun",
			"customizationValue": "ID"
		},
		{
			"customizationType": "AssaultRifle",
			"customizationValue": "ID"
		},
		{
			"customizationType": "BattleRifle",
			"customizationValue": "ID"
		},
		{
			"customizationType": "DMR",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Pistol",
			"customizationValue": "ID"
		},
		{
			"customizationType": "PlasmaRifle",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Railgun",
			"customizationValue": "ID"
		},
		{
			"customizationType": "RocketLauncher",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Shotgun",
			"customizationValue": "ID"
		},
		{
			"customizationType": "SMG",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Sniper",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Portal",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Spray",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Emote",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Oddball",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Bat",
			"customizationValue": "ID"
		},
		{
			"customizationType": "NameTag",
			"customizationValue": "ID"
		},
		{
			"customizationType": "Banner",
			"customizationValue": "ID"
		}
	]
}
```

## Header's
- `Authorization`: TOKEN