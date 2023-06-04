# Web scrapping using playwright

This script scrapes https://www.binance.com/ website for cheap cryptos.

### Install dependencies

```
npm install
npm init playwright@latest


```

### Modify constants:
```
const countryCoinURL_Param = 'ARS';
const criptoCoin_Param = 'USDT';
const priceThreshold : number = 200.000

```

### Run the script

npx playwright test

```
