# Adding Acrechain Mainnet (Arable Protocol) to Keplr wallet

[![Adding Acrechain Mainnet (Arable Protocol) to Keplr wallet](https://www.synergynodes.com/youtube/Acrechain-Mainnet-Keplr-Youtube.jpg)](https://youtu.be/4w5zkVkFJ8Y)

You can follow these steps in Google Chrome, Brave browser or any other browser which supports Keplr wallet extension. 

## 1) Open Keplr wallet, right click on it and click on ``Inspect``.

This will open ``DevTools`` window.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-01-min.png)

## 2) On the ``DevTools`` window, click on ``Console`` tab.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-02-min.png)

## 3) Copy the following code.

```
window.keplr.experimentalSuggestChain({
  	"chainId": "acre_9052-1",
  	"chainName": "Acrechain Mainnet",
    "rpc": "https://rpc-acre.synergynodes.com",
    "rest": "https://lcd-acre.synergynodes.com",
  	"bip44": {
  		"coinType": 60
  	},
  	"coinType": 60,
  	"bech32Config": {
  		"bech32PrefixAccAddr": "acre",
  		"bech32PrefixAccPub": "acrepub",
  		"bech32PrefixValAddr": "acrevaloper",
  		"bech32PrefixValPub": "acrevaloperpub",
  		"bech32PrefixConsAddr": "acrevalcons",
  		"bech32PrefixConsPub": "acrevalconspub"
  	},
    "eip55Config": {
  		"eip55PrefixAccAddr": "0x"
  	},
  	"currencies": [
  		{
  			"coinDenom": "acre",
  			"coinMinimalDenom": "aacre",
  			"coinDecimals": 18,
  			"coinGeckoId": "arable-protocol"
  		}
  	],
  	"feeCurrencies": [
  		{
  			"coinDenom": "acre",
  			"coinMinimalDenom": "aacre",
  			"coinDecimals": 18,
  			"coinGeckoId": "arable-protocol"
  		}
  	],
  	"stakeCurrency": {
  		"coinDenom": "acre",
  		"coinMinimalDenom": "aacre",
  		"coinDecimals": 18,
  		"coinGeckoId": "arable-protocol"
  	},
  	"gasPriceStep": {
  		"low": 10000000000,
  		"average": 20000000000,
  		"high": 30000000000
  	},
  	"features": [
  		"ibc-transfer",
  		"ibc-go",
  		"eth-address-gen",
  		"eth-key-sign"
  	]
});
```

## 4) Paste the code in ``Console`` tab.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-03-min.png)

## 5) Press ``Enter``.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-04-min.png)

## 6) Click on ``Approve`` button on Keplr Wallet window.

<img src="https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-05-min.png" width="350">

## 7) Close Keplr Wallet and re-open it.

## 8) Click on the networks present at top of Keplr Wallet, scroll down, and select ``Acrechain Mainnet``.

<img src="https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-06-min6.png" width="350">

## 9) The wallet is ready and you can copy the address.

NOTE: After adding Arable testnet to Keplr wallet, you can import any wallet using the backed up Mnemonic phrase.

<img src="https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-07-min7.png" width="350">
