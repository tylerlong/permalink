## build

```
./node_modules/.bin/tsc
```

It is a JS project. But it uses TypeScript to compile to ES5, because TypeScript is a superset of ES6.


## deploy

```
./node_modules/.bin/serverless deploy
```

```
./node_modules/.bin/serverless deploy -s prd
```


## config

`data/config.json` is base config, it is sufficient for prod.

`data/config.dev.json` will override it to generate config for dev


## Manual config

Update API gateway settings. Edit "Binary Media Types", add an item `*/*`.


## rsa

```
node src/rsa-encrypt-url.js /restapi/v1.0/account/130829004/extension/130829004/message-store/4100158004/content/4100158004
```


```
https://b34r5y0aa1.execute-api.us-east-1.amazonaws.com/dev/proxy/N4Sc7yz4nWgyZ!H7oAPAYqJkyrDet1hCrTtBz3kEcZUBSKFf5R1JXItD2!3Uk5EsVycVR4sHixhJRkyEwwicwacjpkY6!1AUnyYnl71GRX6goryvH*6EIZKmDuFJF!ChOAHkEEQKt*94E!7wFJm*XTz2EIfCKz*4ZwU!FmgvYzHy3JDDwp5RV4ksxSCvRvwI3lBkpvQiuWKv7tuWCh2b7d5oyxQl*mDvypntSfGJe3g0D8WEctl*R3VqSFMLMQXpM3YgR8WZtQsGav!wIRlSL3TSvyMLYTFxbCPno0Z0Xh9dWEFGJFZ7z8HmcZLsB4AbYmFyKLQBK8iUiNeh6NCkqQ--?type=rsa
```


## Resources

- VoiceMail for testing: https://media.devtest.ringcentral.com/restapi/v1.0/account/130829004/extension/130829004/message-store/4319101004/content/4319101004