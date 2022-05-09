# Current Season Pass

This just tells you whats in the current season pass.

## Method `GET`

TOKEN: Auth Token.  

## Endpoint

`https://splitgate.accelbyte.io/seasonpass/public/namespaces/splitgate/seasons/current?language=en`

## Headers

- `Authorization`: Bearer [TOKEN](../Auth/Auth%20Token.md)

## Response 

```json
{
   "title":"Season 1",
   "description":"",
   "id":"6d8061702dd34e8780e97ad57fe1ca9d",
   "namespace":"splitgate",
   "name":"season1",
   "start":"2022-01-27T00:00:00.000Z",
   "end":"2022-05-28T00:00:00.000Z",
   "tierItemId":"cc83b482a9b04ecfb36287f7d7bf624d",
   "autoClaim":false,
   "passCodes":[
      "premiumrewards",
      "freerewards"
   ],
   "status":"PUBLISHED",
   "publishedAt":"2022-04-27T13:07:35.010Z",
   "createdAt":"2022-02-10T04:54:51.363Z",
   "updatedAt":"2022-04-27T13:07:35.019Z",
   "passes":[
      {
         "title":"Free Pass",
         "description":"",
         "seasonId":"6d8061702dd34e8780e97ad57fe1ca9d",
         "code":"freerewards",
         "namespace":"splitgate",
         "displayOrder":"1",
         "autoEnroll":true,
         "passItemId":"c0f1ddfb3794452192f7307c067a799e",
         "createdAt":"2022-02-10T04:55:17.826Z",
         "updatedAt":"2022-02-10T04:55:17.926Z"
      }
   ]
}
```
