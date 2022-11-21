# Adding Acrechain Mainnet (Arable Protocol) to Keplr wallet

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
  	"chainName": "Arable Mainnet",
    "rpc": "https://rpc-acre.synergynodes.com",
    "rest": "https://lcd-acre.synergynodes.com",
  	"bip44": {
  		"coinType": "60"
  	},
  	"coinType": "60",
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
  			"coinDecimals": "18",
  			"coinGeckoId": "unknown"
  		}
  	],
  	"feeCurrencies": [
  		{
  			"coinDenom": "acre",
  			"coinMinimalDenom": "aacre",
  			"coinDecimals": "18",
  			"coinGeckoId": "unknown"
  		}
  	],
  	"stakeCurrency": {
  		"coinDenom": "acre",
  		"coinMinimalDenom": "aacre",
  		"coinDecimals": "18",
  		"coinGeckoId": "unknown"
  	},
  	"gasPriceStep": {
  		"low": 0.01,
  		"average": 0.025,
  		"high": 0.03
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

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-05-min.png width=100)

## 7) Close Keplr Wallet and re-open it.

## 8) Click on the networks present at top of Keplr Wallet, scroll down, and select ``Arable Testnet``.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-06-min.png)

## 9) The wallet is ready and you can copy the address.

NOTE: After adding Arable testnet to Keplr wallet, you can import any wallet using the backed up Mnemonic phrase.

![](https://www.synergynodes.com/images/acrechain-mainnet-keplr/Acrechain-Mainnet-Keplr-07-min.png)
