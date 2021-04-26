[![Fastwallet](/images/header-ios.png)](https://itunes.apple.com/us/app/loafwallet/id1119332592)
=======================================

[![Release](https://img.shields.io/github/v/release/fastcoin-project/fastwallet-ios?style=plastic)](https://img.shields.io/github/v/release/fastcoin-project/fastwallet-ios)
[![MIT License](https://img.shields.io/github/license/fastcoin-project/fastwallet-ios?style=plastic)](https://img.shields.io/github/license/fastcoin-project/fastwallet-ios?style=plastic)

![screenshots](/images/screenshots.jpg)
=======================================


|                                   Hardware Campaign                                   	|                              General Fastcoin Project                              	|
|:-------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------:	|
| [QR Code](https://blockchair.com/litecoin/address/MVRj1whQ8hqcpffjRxLLCJG1mD27V9YygY) 	| [QR Code](https://blockchair.com/litecoin/address/MDPqwDf9eUErGLcZNt1HN9HqnbFCSCSRme) 	|


### The easy and secure Fastcoin wallet

Fastwallet is the best way to get started with Fastcoin. Our simple, streamlined design is easy for beginners, yet powerful enough for experienced users. This is a free app produced by the Fastcoin Project.

iOS Users can visit the iOS version of the code here: [Fastwallet iOS](https://github.com/fastcoin-project/fastwallet-ios)

### Completely decentralized

Unlike other iOS Fastcoin wallets, **Fastwallet** is a standalone Fastcoin client. It connects directly to the Fastcoin network using [SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients) mode, and doesn't rely on servers that can be hacked or disabled. Even if Fastwallet is removed from the App Store, the app will continue to function, allowing users to access their valuable Fastcoin at any time.

### Cutting-edge security

**Fastwallet** utilizes AES hardware encryption, app sandboxing, and the latest iOS security features to protect users from malware, browser security holes, and even physical theft. Private keys are stored only in the secure enclave of the user's phone, inaccessible to anyone other than the user.

### Designed with new users in mind

Simplicity and ease-of-use is **Fastwallet**'s core design principle. A simple recovery phrase (which we call a paper key) is all that is needed to restore the user's wallet if they ever lose or replace their device. **Fastwallet** is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), which means the user's balance and transaction history can be recovered just from the paper key.

### Features:

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification


### Localization

**Fastwallet** is available in the following languages:

- Chinese (Simplified and traditional)
- Danish
- Dutch
- English
- French
- German
- Italian
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Swedish

---
### Fastwallet Development:
[![GitHub issues](https://img.shields.io/github/issues/fastcoin-project/fastwallet-ios?style=plastic)](https://github.com/fastcoin-project/fastwallet-ios/re-frame/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/fastcoin-project/fastwallet-ios?color=00ff00&style=plastic)](https://github.com/fastcoin-project/fastwallet-ios/pulls)

### Building & Developing Fastwallet for iOS:
***Installation on jailbroken devices is strongly discouraged.***

Any jailbreak app can grant itself access to every other app's keychain data. This means it can access your wallet and steal your Fastcoin by self-signing as described [here](http://www.saurik.com/id/8) and including `<key>application-identifier</key><string>*</string>` in its .entitlements file.

### Fastwallet Team:
* [Development Code of Conduct](/development.md)
---
**Fastcoin** source code is available at https://github.com/fastcoin-project
