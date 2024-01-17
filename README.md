# BCH Admin
### _Client-side Bitcoin Cash web wallet with utxo coin control_

[![bch-admin](https://keepbitcoinfree.org/wp-content/uploads/bch-admin.png)](https://wallet.keepbitcoinfree.org)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://www.redhat.com/en/topics/open-source/what-is-open-source) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://mainnet.cash) 
[![forthebadge](https://keepbitcoinfree.org/wp-content/uploads/built-with-bitcoin-cash.svg)](https://keepbitcoinfree.org)

BCH Admin is a simple, serverless Bitcoin Cash web wallet. It is built using HTML5, CSS and JavaScript. Client-side JavaScript libraries [MainnetJS](https://mainnet.cash) & [indexeddb-storage](https://mainnet.cash) are included in the source code and utilized to create and manage a persistent Bitcoin Cash web wallet in the browser. 

### Wallet Features: 
- Persistent wallet stored in browser IndexedDB
- Single deposit address with QR code
- Transaction notification for incoming tx to deposit address
- Mnemonic seed phrase for backup
- Wallet balance displayed in BCH, Satoshis & USD
- Coin Control/UTXO selection (or custom amount) for sending BCH 
- Ability to sign/verify messages using the private key of the wallet address
 
##### *Possibly* Planned Features: 
- Transaction history
- Restore from seed/private key
- set custom derivation path
- Create multiple wallets/tabs
- Functionality for a Point of Sale system (use pubX to simply generate a new page with a new address for each order for a specific amount (with a QR) that will watch for incoming txs and notify user.

Please note: This wallet was developed to be used internally. It is a beta version and is not meant to be used to hold large amounts - as it is still a web wallet. There is no server, we DO NOT EVER save or store your private keys. All private keys for the wallet are created and saved within the browser and are local/accessible to the computer/device, the browser & the website you are using. For example, you can visit https://wallet.keepbitcoinfree.org and a new wallet will be created. Every time you visit that site on the same device, with the same browser, then your same wallet will be displayed. 

If you open another browser on the same device and visit the same site, a new wallet will be created. If you download the source code files and access the website locally, then a new wallet will be created. In all of these instances, the seed phrase/mnemonic is stored within the browser's IndexedDB storage and accessible to that device, browser, & website. In no cases are the private keys ever sent anywhere malicous. The code is open source and accessible to everyone to review - https://github.com/KeepBitcoinFree-org/bch-admin. 


Bitcoin was meant to be a peer-to-peer electronic cash system for the world. Bitcoin was meant to scale.
As [Satoshi Nakamoto](https://satoshi.nakamotoinstitute.org/) wrote in the [Bitcoin Whitepaper](https://keepbitcoinfree.org/bitcoin.pdf):

> What is needed is an electronic payment system based on cryptographic proof instead of trust,
allowing any two willing parties to transact directly with each other without the need for a trusted
third party. 


## Tech

BCH Admin uses a few tools to provide a BCH wallet in the browser:

- HTML
- CSS
- JavaScript
    - [MainnetJS](https://mainnet.cash)
- [Bootstrap](https://getbootstrap.com/)

## Installation

BCH Admin requires only hosting the source code (locally, on your own web server/VPS, or using a hosted instance elsewhere - such as https://wallet.keepbitcoinfree.org), accessing it via a browser with JavaScript support, and an internet connection. Once the files have been downloaded, you can open the index.html file in your browser and a new wallet will be created.

Get started by cloning the source code:
```sh
git clone https://github.com/KeepBitcoinFree-org/bch-admin
```

## Development

This project was started as an local browser wallet and was not meant to be released. As I worked on it more, I started to like it. BCH Admin will be worked on when possible as a side project. [Want to contribute? Great! Clone the source code, make some changes and submit a merge request. ](https://github.com/KeepBitcoinFree-org/bch-admin)

Want to send some Bitcoin our way to help fund dev? We enjoy Bitcoin Cash :)
[![Bitcoin Cash](https://keepbitcoinfree.org/wp-content/uploads/KBF-donation-addr-bitcoincash-qzgl22szd975lgghhd6um392g8dvkjzz7syn6mg8gz.png)](https://blockchair.com/bitcoin-cash/address/qzgl22szd975lgghhd6um392g8dvkjzz7syn6mg8gz)
bitcoincash:qzgl22szd975lgghhd6um392g8dvkjzz7syn6mg8gz



## License

MIT

**Free Software, FRIG Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>
