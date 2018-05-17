## Slides

https://docs.google.com/presentation/d/1-9vvlFfC5UWDPft6qOTWZCVrL5xTLPEUhzs-Mo7SrLg/edit#slide=id.p


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



## Bonus content: encode the url locally (RSA encryption)

```
node src/rsa-encrypt-url.js /restapi/v1.0/account/130829004/extension/130829004/message-store/4319101004/content/4319101004
```

Result is:

```
vLSiVnkb%2FQB12NJYcAfxr%2FJgj9M7xx8DO1HxwaR%2BWBaAv9YSnz92Q1925Rc%2FVLf4fcO%2BY9WWf1LrXBQWNpDfFklqBrPzrxl4NG8L3Mh%2BUQl8DzrpTSYljj4Se4QSjYCDlYVvBLgmG0wQmDku4MOSq%2BGKvMuSsEzbVjEc%2FiNkqcKNH5wxybwTRQejXUl5GSSpAfUlyVnJSFgyRmFKbV2%2FGoO%2BHJKqyd6BfHeWywJb1f2XcyDVFzlAqhonZAi1kpmnqfWhjeW4QQx3%2F9de5oxo27lECGQTmACxMiMMhByE4WiJYp1FvZpjBHkOSIRRBWd1uxIFZmGjqs9DrXWb3lGW3A%3D%3D
```

Final url:

```
https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/proxy/vLSiVnkb%2FQB12NJYcAfxr%2FJgj9M7xx8DO1HxwaR%2BWBaAv9YSnz92Q1925Rc%2FVLf4fcO%2BY9WWf1LrXBQWNpDfFklqBrPzrxl4NG8L3Mh%2BUQl8DzrpTSYljj4Se4QSjYCDlYVvBLgmG0wQmDku4MOSq%2BGKvMuSsEzbVjEc%2FiNkqcKNH5wxybwTRQejXUl5GSSpAfUlyVnJSFgyRmFKbV2%2FGoO%2BHJKqyd6BfHeWywJb1f2XcyDVFzlAqhonZAi1kpmnqfWhjeW4QQx3%2F9de5oxo27lECGQTmACxMiMMhByE4WiJYp1FvZpjBHkOSIRRBWd1uxIFZmGjqs9DrXWb3lGW3A%3D%3D?type=rsa
```
