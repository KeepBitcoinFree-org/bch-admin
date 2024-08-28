# BCH Admin
### _Client-side Bitcoin Cash web wallet with utxo coin control_

[![bch-admin](https://keepbitcoinfree.org/wp-content/uploads/bch-admin.png)](https://wallet.keepbitcoinfree.org)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://www.redhat.com/en/topics/open-source/what-is-open-source) [![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://mainnet.cash) 
[![forthebadge](https://keepbitcoinfree.org/wp-content/uploads/built-with-bitcoin-cash.svg)](https://keepbitcoinfree.org)

BCH Admin is a simple, client-side Bitcoin Cash web wallet with utxo coin control. It is built using HTML5, CSS and Vanilla JavaScript. The client-side JavaScript libraries [MainnetJS](https://mainnet.cash) & [indexeddb-storage](https://mainnet.cash) are included within the source code and utilized to create and manage a persistent Bitcoin Cash web wallet created and stored locally within the browser's IndexedDB storage. 

### Wallet Features: 
- Persistent wallet stored in browser IndexedDB
- Restore from seed/private key, or create a new wallet
- Single deposit address with QR code
- Transaction notification for incoming tx to watched deposit address
- Mnemonic seed phrase & Derivation path info for backup
- Wallet balance displayed in BCH, Satoshis & USD
- Coin Control/UTXO selection (or custom amount) selection for sending BCH 
- Sign messages using the private key of the wallet address
- Verify that a message & signature combination are valid
- Light / Dark mode toggle switch
- Print the page to use as a paper wallet
- Delete wallet to reset IndexedDB storage & start anew
 
##### *Possibly* Planned Features: 
- Transaction history
- ~~Restore from seed/private key~~
- Set custom derivation path
- Create multiple wallets/tabs/addresses
- Functionality for a Point of Sale system, and/or ability to create/track sub-wallets for each order. These could be created for a specific amount (with a custom QR) that will watch for incoming txs and notify the user on screen.

Please note: This wallet was developed as a personal project by KeepBitcoinFree.org. It is a beta version (the mainnet.cash libraries as well), may have some bugs, and is subject to change at any time. This wallet is not meant to be used to hold large amounts, as it is still a web wallet and stored within your browser on your device. We DO NOT have the ability to save or store your private keys and we DO NOT add any tracking, analysis, or data harvesting of any kind. All private keys for the wallet are created and saved within the browser's IndexedDB Storage and are local/accessible only to the device, the browser & the domain/website you are using to create the wallet. 

You can visit https://wallet.keepbitcoinfree.org to create or restore a wallet. Every time you visit that domain on the same device, with the same browser, that same wallet will be automatically loaded and displayed for you. If you open another browser on the same device and visit the same domain, a new wallet will be created and saved within that browser. If you download the source code files and access the website locally, then a new wallet will be created. In all of these instances, the seed phrase/mnemonic is stored within the browser's IndexedDB storage and is only accessible to that device, browser, & domain/website. In no case are the private keys or seed phrase ever sent/saved anywhere other than your browser. The code for this wallet, as well as the mainnet-js library, is open source and accessible to everyone to review, fork and/or contribute to - https://github.com/KeepBitcoinFree-org/bch-admin. 


> What is needed is an electronic payment system based on cryptographic proof instead of trust,
allowing any two willing parties to transact directly with each other without the need for a trusted
third party. 
- [Satoshi Nakamoto](https://satoshi.nakamotoinstitute.org/), [Bitcoin Whitepaper](https://keepbitcoinfree.org/bitcoin.pdf)

## Tech

BCH Admin uses a few tools to provide a Bitcoin Cash, BCH, wallet within the browser:

- HTML
- CSS
- JavaScript
    - [MainnetJS](https://mainnet.cash)
- [Bootstrap](https://getbootstrap.com/)

## Installation

BCH Admin requires only hosting the source code (locally, on your own web server/VPS, or using a hosted instance elsewhere - such as https://wallet.keepbitcoinfree.org), a browser with JavaScript support, and an internet connection. Once the files have been downloaded, you can open the index.html file in your browser to create or restore a wallet.

Get started by cloning the source code:
```sh
git clone https://github.com/KeepBitcoinFree-org/bch-admin
```

## Development

This project was started as an internal browser wallet and was not meant to be released. As I worked on it more, I started to enjoy it and simply wanted to share. BCH Admin will be worked on when possible as a side project. [Want to contribute? Great! Clone the source code, make some changes and submit a merge request. ](https://github.com/KeepBitcoinFree-org/bch-admin)

Want to send some Bitcoin our way to help fund dev? We enjoy the Bitcoin that works best, Bitcoin Cash :)
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
