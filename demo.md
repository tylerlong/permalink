## Sample voice mail

https://media.devtest.ringcentral.com/restapi/v1.0/account/130829004/extension/130829004/message-store/4319101004/content/4319101004



## `encodeURIComponent` to get rid of special characters

https%3A%2F%2Fmedia.devtest.ringcentral.com%2Frestapi%2Fv1.0%2Faccount%2F130829004%2Fextension%2F130829004%2Fmessage-store%2F4319101004%2Fcontent%2F4319101004



## encode the uri

https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/encode/https%3A%2F%2Fmedia.devtest.ringcentral.com%2Frestapi%2Fv1.0%2Faccount%2F130829004%2Fextension%2F130829004%2Fmessage-store%2F4319101004%2Fcontent%2F4319101004


```json
{"permaLink":"https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/proxy/TxcTwHNGOhbTJapPszXmJNYN3PV*kGqeCBrBAkEJJdtXdqGN!mmtRiJdrV9OlQu1u*xrT7Ru*SSKuWZWM2mDrPeOrdCTwUbxUirw3LT1tFQG*MzZu8SQ4V9w4jJHA3Zv?brand=1210","error":null,"message":"ok"}
```



## Visit the permalink

https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/proxy/TxcTwHNGOhbTJapPszXmJNYN3PV*kGqeCBrBAkEJJdtXdqGN!mmtRiJdrV9OlQu1u*xrT7Ru*SSKuWZWM2mDrPeOrdCTwUbxUirw3LT1tFQG*MzZu8SQ4V9w4jJHA3Zv?brand=1210



## Bonus content: encode the url locally

```
node src/rsa-encrypt-url.js /restapi/v1.0/account/130829004/extension/130829004/message-store/4319101004/content/4319101004
```

Result is:

```
JiX5TqMm0Nk8oCEgixMmZm1J4AVeiPQMa2NcQfot4KnlBQYzrthF9XPpE1sbXtCRyRRRFfW2i2jKQGX8mqnZUQ8TH6ooYQEdSvIXYuNpFYzHxWj%2FXhcxCL65rkm%2BChnMk%2FzjFzdqs01AncoOToQS6C7a5A4vyaxo53V2vMWD5d8rEfaFUFib%2BTZR8NuG5Rp7r%2BZl8CGslGnkad57dDvPVoVeC%2FbfF6Wute0iuSiuZqFW0BmowpNoGT4ndas7w%2BT8aHxDCTyZ69K95x7wQoisI7q6GNM83TXmjvQYd2kXMllKFoTMKNAZ8XH3xc6WWJFN8oAcxdaZ7OM4ijsKa3BILA%3D%3D
```


encodeURIComponent:

```
JiX5TqMm0Nk8oCEgixMmZm1J4AVeiPQMa2NcQfot4KnlBQYzrthF9XPpE1sbXtCRyRRRFfW2i2jKQGX8mqnZUQ8TH6ooYQEdSvIXYuNpFYzHxWj%252FXhcxCL65rkm%252BChnMk%252FzjFzdqs01AncoOToQS6C7a5A4vyaxo53V2vMWD5d8rEfaFUFib%252BTZR8NuG5Rp7r%252BZl8CGslGnkad57dDvPVoVeC%252FbfF6Wute0iuSiuZqFW0BmowpNoGT4ndas7w%252BT8aHxDCTyZ69K95x7wQoisI7q6GNM83TXmjvQYd2kXMllKFoTMKNAZ8XH3xc6WWJFN8oAcxdaZ7OM4ijsKa3BILA%253D%253D
```

Final url:

```
https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/proxy/JiX5TqMm0Nk8oCEgixMmZm1J4AVeiPQMa2NcQfot4KnlBQYzrthF9XPpE1sbXtCRyRRRFfW2i2jKQGX8mqnZUQ8TH6ooYQEdSvIXYuNpFYzHxWj%252FXhcxCL65rkm%252BChnMk%252FzjFzdqs01AncoOToQS6C7a5A4vyaxo53V2vMWD5d8rEfaFUFib%252BTZR8NuG5Rp7r%252BZl8CGslGnkad57dDvPVoVeC%252FbfF6Wute0iuSiuZqFW0BmowpNoGT4ndas7w%252BT8aHxDCTyZ69K95x7wQoisI7q6GNM83TXmjvQYd2kXMllKFoTMKNAZ8XH3xc6WWJFN8oAcxdaZ7OM4ijsKa3BILA%253D%253D?type=rsa
```
