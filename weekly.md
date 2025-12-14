## Index

1. General questions
2. Wallet: CLI & GUI
3. Wallet: Ledger
4. Nodes

# 1. General questions

## **Where can I download the Monero wallet?**

There are multiple Monero wallets for a wide range of devices at your disposal. Check the table below for details and download links. **Attention:** for extra security make sure to calculate and compare the `checksum` of your downloaded files when possible.

**Please note the following usage of the labels:**

⚠️ - Relatively new and/or beta. Use wallet with caution.

☢️ - Closed source.

---
### Desktop wallets
| Wallet       | Device       | Description | Download link   |
|:------------:|:------------:|-------------|:---------------:|
| *"Official"* GUI / CLI|  Windows, macOS, Linux|Default implementation maintained by the core team. Use this wallet to run a full node and obtain maximum privacy. Integrates with hardware wallets. *Current version: 0.18.3.1 / 0.18.3.1*.| [GetMonero.org](https://getmonero.org/downloads/)|
|MyMonero|Windows, macOS, Linux|Lightweight wallet -- you don't need to download the blockchain and run a node. MyMonero was developed with the assistance of the core team. It also has web-based and iOS versions.|[MyMonero.com](https://mymonero.com/)|
|Feather Wallet|Windows,macOS, Linux|Feather Wallet is a free, open-source Monero wallet for Linux, Tails, macOS and Windows. Supports hardware wallets (Trezor and Ledger) as well.|[Featherwallet.org](https://featherwallet.org)|
|Exodus|Windows, macOS, Linux|⚠️ / Multi-asset wallet.|[Exodus.io](https://www.exodus.io/monero/)|
|ZelCore|Windows, macOS, Linux|⚠️ / Multi-asset wallet. It also has Android and iOS versions.|[Zelcore.io](https://zelcore.io/)|
|Guarda|Windows, macOS, Linux|⚠️ ☢️ / Multi-asset wallet.|[Guarda.co](https://guarda.co/desktop)|
|Coin Wallet|Windows, macOS, Linux|⚠️ / Multi-asset wallet.|[Coin.space](https://coin.space/#download)|


### Mobile wallets
| Wallet       | Device       | Description | Download link   |
|:------------:|:------------:|-------------|:---------------:|
|Monerujo|Android|Integrates with Ledger (hardware wallet). Website: https://www.monerujo.io/. |[Google Play](https://play.google.com/store/apps/details?id=com.m2049r.xmrwallet) / [F-Droid](https://f-droid.monerujo.io/) / [GitHub](https://github.com/m2049r/xmrwallet/releases)|
|MyMonero|Android / iOS|Website: https://mymonero.com/|[Google Play](https://play.google.com/store/apps/details?id=com.mymonero.official_android_application) / [App Store](https://itunes.apple.com/app/mymonero-send-money-privately/id1372508199)|
|Cake Wallet|Android / iOS|Website: https://cakewallet.io/|[Google Play](https://play.google.com/store/apps/details?id=com.cakewallet.cake_wallet) / [App Store](https://itunes.apple.com/app/cake-wallet-for-xmr-monero/id1334702542)|
|Edge Wallet|Android / iOS|Multi-asset wallet. Website: https://edge.app/ |[Google Play](https://play.google.com/store/apps/details?id=co.edgesecure.app) / [App Store](https://itunes.apple.com/app/edge-bitcoin-wallet/id1344400091)|
|ZelCore|Android / iOS|⚠️ / Multi-asset wallet. Website: https://zelcore.io/|[Google Play](https://play.google.com/store/apps/details?id=com.zelcash.zelcore) / [App Store](https://itunes.apple.com/app/zelcore/id1436296839)|
|Coinomi|Android / iOS|⚠️ ☢️ / Multi-asset wallet. Website: https://www.coinomi.com/|[Google Play](https://play.google.com/store/apps/details?id=com.coinomi.wallet) / [App Store](https://itunes.apple.com/app/coinomi-wallet/id1333588809)|
|Moxi / Guarda|Android / iOS|⚠️ ☢️ / Multi-asset wallet. Website: https://guarda.co/|[Google Play](https://play.google.com/store/apps/details?id=com.crypto.multiwallet) / [App Store](https://itunes.apple.com/app/apple-store/id1442083982)|
|Exodus|Android / iOS| ⚠️ / Multi-asset wallet. Website: https://www.exodus.io/monero/)|[Google Play](https://play.google.com/store/apps/details?id=com.exodusmovement.exodus) / [App Store](https://apps.apple.com/app/exodus-crypto-wallet/id1414384820)|
|Coin Wallet|Android / iOS|⚠️ / Multi-asset wallet. Website: https://coin.space/|[Google Play](https://play.google.com/store/apps/details?id=com.coinspace.app) / [App Store](https://apps.apple.com/us/app/coinspace-bitcoin-wallet/id980719434)|
|Wallet Anonero|Android|⚠️ Website: http://anonero5wmhraxqsvzq2ncgptq6gq45qoto6fnkfwughfl4gbt44swad.onion/|[Website](http://anonero5wmhraxqsvzq2ncgptq6gq45qoto6fnkfwughfl4gbt44swad.onion/)|
|Mysu|Android|⚠️ Website: http://rk63tc3isr7so7ubl6q7kdxzzws7a7t6s467lbtw2ru3cwy6zu6w4jad.onion/|[Website](http://rk63tc3isr7so7ubl6q7kdxzzws7a7t6s467lbtw2ru3cwy6zu6w4jad.onion/)|
|StackWallet|Android / iOS|⚠️ / Multi-asset wallet. Website: https://stackwallet.com/|[Google Play](https://play.google.com/store/apps/datasafety?id=com.cypherstack.stackwallet) / [F-Droid](https://fdroid.stackwallet.com/) / [App Store](https://apps.apple.com/us/app/stack-wallet-by-cypher-stack/id1634811534)|

### Web-based wallets
| Wallet       | Description | Link   |
|:------------:|-------------|:---------------:|
|MyMonero|Web version of the MyMonero wallet.|[Web](https://wallet.mymonero.com/)|
|Guarda|Multi-asset wallet.|[Web](https://guarda.co/app)|
|Coin Wallet|Multi-asset wallet.|[Web](https://coin.space/wallet/)|
|RINO Wallet|Self-custody Monero multisignature web wallet.|[Web](https://rino.io/)|



## **How long does it take for my balance to unlock?**

Your balance is unlocked after 10 confirmations (which means 10 mined blocks). A block is mined approximately every two minutes on the Monero network, so that would be around 20 minutes.

## **How can I prove that I sent a payment?**

The fastest and most direct way is by using the [ExploreMonero](https://www.exploremonero.com/receipt) blockchain explorer. You will need to recover the transaction key from your wallet ([complete guide](https://getmonero.org/resources/user-guides/prove-payment.html) for GUI / CLI).

## **How do I buy Monero (XMR) with Bitcoin (BTC)?**

There are dozens of exchanges that trade Monero against Bitcoin and other cryptocurrencies. Check out the list on [CoinMarketCap](https://coinmarketcap.com/currencies/monero/#markets) and choose the option that suits you best.

## **How do I buy Monero (XMR) with fiat?**

- [Kraken](https://kraken.com/) (USD and EUR): old-school, decent exchange. They might require your documents for verification and approval of your account.

## **How can I quickly exchange my Monero (XMR) for Bitcoin (BTC)?**

There are multiple ways to exchange your Monero for Bitcoin, but first of all, I'd like to remind you that if you really want to do your part for Monero, one of the simplest ways is to **get in touch with your merchant/service provider and request for it to accept Monero directly as payment.** Ask the service provider to visit the [official website](https://getmonero.org/) and our communication channels if he or she needs help with system integration.
    
That being said, [KYCNot.me](https://kycnot.me/?categories=exchange&currency-mode=or&currencies=xmr) maintains an up-to-date list of exchanges. These services are only recommendations (which change over time) and are operated by entities outside the control of the Monero Project. DYOR and be diligent.

## **How do I mine Monero? And other mining questions.**

The correct place to ask questions and discuss the Monero mining scene is in the dedicated subreddit r/MoneroMining. That being said, you can find a list of pools and available mining software in the [GetMonero.org](https://getmonero.org/get-started/mining/) website.

---

# 2. Wallet: CLI & GUI

## **Why I can't see my balance? Where is my XMR?**

Before any action there are two things to check:

1. Are you using the latest available version of the wallet? A new version is released roughly every 6 months, so make sure you're using the current release (compare the release on [GetMonero.org](https://getmonero.org/downloads/) with your wallet's version on `Settings`, under `Debug info`).
2. Is your wallet fully synchronized? If it isn't, wait the sync to complete.

Because Monero is different from Bitcoin, wallet synchronization is not instant. The software needs to synchronize the blockchain and use your private keys to identify your transactions. Check in the lower left corner (GUI) if the wallet is synchronized.

**You can't send transactions and your balance might be wrong or unavailable if the wallet is not synced with the network**. So please wait.

If this is not a sufficient answer for your case and you're looking for more information, please see this answer on [StackExchange](https://monero.stackexchange.com/questions/6640/i-am-missing-not-seeing-a-transaction-to-in-the-gui-zero-balance).

## **How do I upgrade my wallet to the newest version?**

This question is beautifully answered on [StackExchange](https://monero.stackexchange.com/questions/7991/how-do-i-upgrade-my-software-to-the-newest-version).

## **Why does it take so long to sync the wallet [for the first time]?**

You have decided to use Monero's wallet and run a local node. Congratulations! You have chosen the safest and most secure option for your privacy, but unfortunately this has an initial cost. The first reason for the slowness is that you will need to download the entire blockchain, which is considerably heavy (+70 GB) and constantly growing. There are technologies being implemented in Monero to slow this growth, however it is inevitable to make this initial download to run a full node. Consider syncing to a device that has an SSD instead of an HDD, as this greatly impacts the speed of synchronization.

Now that the blockchain is on your computer, the next time you run the wallet you only need to download new blocks, which should take seconds or minutes (depending on how often you use the wallet).

## **I don't want to download the blockchain, how can I skip that?**

The way to skip downloading the blockchain is connecting your wallet to a public remote node. You can follow [this guide](https://getmonero.org/resources/user-guides/remote_node_gui.html) on how to set it up. You can find a list of public remote nodes on [MoneroWorld](https://moneroworld.com/#nodes).

*Be advised that when using a public remote node you lose some of your privacy. A public remote node is able to identify your IP and opens up a range for [certain attacks](https://moneroworld.com/) that further diminish your privacy.* ***A remote node can't see your balance and it can't spend your XMR.***

## **How do I restore my wallet from the mnemonic seed or from the keys?**

To restore your wallet with the 25 word mnemonic seed, please see [this guide](https://getmonero.org/resources/user-guides/restore_account.html).

To restore your wallet with your keys, please see [this guide](https://getmonero.org/resources/user-guides/restore_from_keys.html).

---

# 3. Wallet: Ledger

## **How do I generate a Ledger Monero Wallet with the GUI or CLI?**

This question is beautifully answered on StackExchange. Check [this page](https://monero.stackexchange.com/questions/9901/how-do-i-generate-a-ledger-monero-wallet-with-the-gui-monero-wallet-gui) for the GUI instructions, and [this page](https://monero.stackexchange.com/questions/8503/how-do-i-generate-a-ledger-monero-wallet-with-the-cli-monero-wallet-cli) for the CLI instructions.

---

# 4. Wallet: Trezor

## **How do I generate a Trezor Monero Wallet with the GUI or CLI?**

This question is beautifully answered on StackExchange. Check [this page](https://monero.stackexchange.com/questions/11437/how-do-i-generate-a-trezor-monero-wallet-with-the-gui-monero-wallet-gui) for the GUI instructions, and [this page](https://monero.stackexchange.com/questions/11353/how-do-i-generate-a-trezor-monero-wallet-with-the-cli-monero-wallet-cli) for the CLI instructions.

---

# 5. Nodes

## **How can my local node become a public remote node?**

If you want to support other Monero users by making your node public, you can [follow the instructions on MoneroWorld](https://moneroworld.com/#contribute), under the section *"How To Include Your Node On Moneroworld"*.


## **How can I connect my node via Tor?**

This question is beautifully answered on [StackExchange](https://monero.stackexchange.com/questions/467/running-a-full-node-without-revealing-my-home-ip-address).
