## STAR NOTARY DAPP
Decetralized applications for star notary, refering Udacity blockchain engineer nanodegree course.
example

### Test on local network
1. Execute the following commands on terminal.
```
truffle compile
truffle migrate --reset
truffle test
```

### Running on public network
1. Edit truffle-config.js file to connect metamask and infura.
```
const infuraKey = "[YOUR_INFURA_KEY]";
const mnemonic = "[YOUR_METAMASK_SEED_PHRASE]";
```
2. Deploy the contract to Rinkeby network
```
truffle migrate --reset --network rinkeby
```

### Running DApp
1. Execute the following commands on terminal.
```bash
cd app
npm run dev
```
2. Open http://localhost:8080/ on a web browser.
