# Server status
Get current server status.

## Data `GET`
 	
## URL

`https://api.splitgate.com/server-status` *(THIS IS DEPRECATED PLEASE USE THE ONE BELOW)*

`https://api.splitgate.com/server-status?encodedCompositePlatformId=encodedCompositeUserId` (I thought this did nothing special originally credit [Henrik-3](https://github.com/Henrik-3) for noticing!

## Information
- `encodedCompositeUserId`: not sure where you could find your own just use mine if you want `eyJ1c2VySWQiOiI1ZThjMGRmMzczOTk0YWY1ODllMzAyMTciLCJwbGF0Zm9ybSI6IlNURUFNIiwicGxhdGZvcm1JZCI6Ijc2NTYxMTk4NDAzNzA3MjM2In0`,

This decodes to
```
{
	"userId":"5e8c0df373994af589e30217",
	"platform":"STEAM",
	"platformId":"76561198403707236"
}
```

