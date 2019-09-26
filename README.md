# Color Proxy

## How to use 

To generate Certificates other then localhost update your CN name if needed in task/certificates/certificates.sh

e.g CN=localhost

run following command 

```
yarn certificates
```

To run proxy

```
yarn proxy
```


By default it will run on `https://lcd.testnet.color-platform.rnssol.com`

to change this update value of target in proxy.js
