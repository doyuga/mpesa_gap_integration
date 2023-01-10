# mpesa_gap_integration
API for GAP integration with MPESA, CARD, and other payment methods within East Africa

Sample Mpesa payload
{
"transKey": "2",
"bank": "4",
"amount": 1,
"cashBack":"0",
"tillNo": "12",
"cashierId": "1",
"mobileId":"0729566878"
}

Sample response
{
    "amount": "1",
    "authCode": "7249420",
    "cardExpiry": "9999",
    "cashBack": "0",
    "currency": null,
    "invoiceNo": null,
    "mid": null,
    "msg": "Successful",
    "pan": "254729566878",
    "paymentDetails": null,
    "pin": null,
    "respCode": "00",
    "rrn": "QEA0R4Q5RQ",
    "sign": null,
    "slip": null,
    "tid": "DAN  ",
    "transactionType": null
{
    "amount": "1",
    "authCode": "7249420",
    "cardExpiry": "9999",
    "cashBack": "0",
    "currency": null,
    "invoiceNo": null,
    "mid": null,
    "msg": "Successful",
    "pan": "254729566878",
    "paymentDetails": null,
    "pin": null,
    "respCode": "00",
    "rrn": "QEA0R4Q5RQ",
    "sign": null,
    "slip": null,
    "tid": "DAN  ",
    "transactionType": null
}
