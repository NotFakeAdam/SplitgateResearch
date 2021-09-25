# Finalize Transaction
Buying items.

## Data `POST`
TransactionId: `ID of item`

PurchasableId: `Purchase ID of item`

Price: `Cost`

## URL

`https://api.splitgate.com/game-client/finalize-transaction`

## Body
```json
{
	"transactionId": "ID",
	"purchasableId": PURCHASEID,
	"creatorCode": "",
	"price": PRICE,
	"currencyCode": "REGION"
}
```

## Headers
- `Authorization`: TOKEN