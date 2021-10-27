# PokeDX Token List
## A data-rich token list powered by PokeDX !
**Real-time, accurate and up-to-date information.** The repository will eventually contain token info from several blockchains, info on dApps etc. For every token a logo and optional additional information is available (such data is not available on-chain).

✅ PokeDX and Bullboard uses data from this source<br>
✅ Other projects can pull data from this source free of charge

### What info is supported?
- Logo
- Name
- Symbol
- Description
- Website
- Explorer
- Discord 
- Instagram
- Medium
- Reddit
- Telegram
- Twitter
- Type (ie BEP20)
- Slippage
- Decimals
- Contract address
**- Up to 5 Twitter tags !**
- RSS feed

### How to add a token
_Please note that brand new tokens are not accepted. The projects have to be sound, have information available, contracts uploaded to BSC explorer and a non-minimal circulating supply !_

**Requirements**
Min holders : 300
Min transactions : 1000
Fee : 0.5 BNB

**Tutorial**
1. Make sure the smartcontract has more than 300 address holders & 1000 transactions, otherwise it will be rejected
2. Fork the Github repository
3. Create folder with name of token smartcontact address in checksum format bsc/assets/<token_smartcontract_address>/
4. Upload your logo with file named logo.png to previously created folder with smartcontract address. Your path should look like this: bsc/assets/0x1234567461d3f8Db7496581774Bd869C83D51c93/logo.png
5. Create info.json file with info about the token/project (see below)
6. Create a pull request to the main repo
7. Pay the 0.5 BNB processing fee
8. Write @therealbullish on Telegram once done with tx confirmation

**Format**<br>
info.json
logo.png (recommended size 256x256px / 512x512px, max file size: 100kB)

```
{
    "name": "PokeDX",
    "website": "https://www.pokedx.app/",
    "telegram": "https://t.me/dextalks/",
    "instagram": "https://www.instagram.com/pokedxapp/",
    "twitter": "https://twitter.com/pokedxapp/",
    "description": "This will be updated",
    "explorer": "https://explorer.bitquery.io/bsc/token/0x3ad9594151886ce8538c1ff615efa2385a8c3a88",
    "type": "BEP20",
    "symbol": "PDX",
    "decimals": 9,
    "slippage": 5,
    "status": "active",
		"thandle": "pokedxapp",
    "id": "0x43a0c5eb1763a211aa3c05849a617f2ee0452767"
}
```

**Rules**<br>
Alerts in JSON are not accepted. Only PokeDX is permitted to add alerts to tokens.

### Disclaimer
PokeDX allows anyone to submit new assets to this repository. However, this does not mean that we are in direct partnership with all of the projects.

We will reject projects that are deemed as scam or fraudulent after careful review. PokeDX team reserves the right to change the terms of asset submissions at any time due to changing market conditions, risk of fraud, or any other factors we deem relevant.
