# Splitgate Websocket
Contains player info, challenges etc.

## Data `WEBSOCKET`
 	

## URL

`wss://api.splitgate.com/socket.io/?EIO=3&transport=websocket&authToken=AUTHKEY?encodedMetadata=DATA`

## Headers

- Metadata
  - The encoded metadata is a Base64 code of your game client.	
```
{
	"clientVersion": "5.0.0",
	"systemPlatform": "WINDOWS",
	"osVersion": "Windows 10 (Release 2009)",
	"deviceId": "38a34bfa89787e62db9d4e839579b395",
	"screenResolution": "1920x1080",
	"language": "en",
	"fullInstall": true
}
```
  - This equates to `ewoJImNsaWVudFZlcnNpb24iOiAiNS4wLjAiLAoJInN5c3RlbVBsYXRmb3JtIjogIldJTkRPV1MiLAoJIm9zVmVyc2lvbiI6ICJXaW5kb3dzIDEwIChSZWxlYXNlIDIwMDkpIiwKCSJkZXZpY2VJZCI6ICIzOGEzNGJmYTg5Nzg3ZTYyZGI5ZDRlODM5NTc5YjM5NSIsCgkic2NyZWVuUmVzb2x1dGlvbiI6ICIxOTIweDEwODAiLAoJImxhbmd1YWdlIjogImVuIiwKCSJmdWxsSW5zdGFsbCI6IHRydWUKfQ`.	


- Auth Token
  - To find your authentication token go to your `LocalAppData/PortalWars/Saved/SaveGames/*.sav`, 
  - Open the most recently made *.sav and search for `LoginAuthToken`, the code there will be used to authenticate with the splitgate API.

*Referenced in [the main page](https://github.com/NotFakeAdam/SplitgateResearch/blob/main/README.md#L8).*