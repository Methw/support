{
"title"       : "How to Create a Wallet",
"sort"        : "05",
"category"    : "Getting Started",
"description" : "Getting Started",
"date_published" : "2015-10-05T08:00:00+08:00",
"date_modified"  : "2018-07-24T08:00:00+08:00"
}

---%


### Preface

We highly recommend getting a hardware wallet or using MetaMask as a method to access your wallet and to store your funds.

The following assumes you are **not** using a hardware wallet or MetaMask. Due to their ease of use and security, [we recommend a hardware wallet for cold storage](https://support.mycrypto.com/hardware-wallets/hardware-wallet-recommendations.html).

Remember to back up any wallets you create! Including the 12-word private seed phrase for your hardware wallets! MyCrypto <em>CAN NOT</em> recover any lost passwords or access accounts. MyCrypto only has access to information that is publicly avaliable on the blockchain. The security and responsibilty of your funds rests on your own shoulders! But MyCrypto will always be here for guidance and to answer any questions that you may have on how to be safe with your funds.  

### How To Create A New Wallet

* Go to https://mycrypto.com/generate

![](https://i.imgur.com/N7xEOtS.png)

If you do not choose to use a hardware wallet, MetaMask or Parity Signer, then we recommend to use MyCrypto's desktop app. The desktop app is available for Mac, Windows, Linux or as a standalone app.

* [Download the MyCrypto Desktop App](https://download.mycrypto.com/)

Once you have downloaded and successfully installed the app, open the app from your applications folder. This should open the MyCrypto Desktop interface.

![](https://i.imgur.com/dlXS2Xd.png)

* Click "Create New Wallet" in the side navigation bar. This will bring up three options.

![](https://i.imgur.com/xFEwshp.png)

* Select an option for a type of wallet to create. In this case, click "Generate a Wallet" in the "Create New Wallet" box.

![](https://i.imgur.com/1JgaeHB.png)

##### Generate a Keystore File

1. Enter a strong password. Using a randomly generated password is recommended. Make sure that you write this password down on multiple pieces of paper! Place the paper somewhere safe!
    * You can also create a text file on a USB and save your password there
    * _This password encrypts (protects) your private key. It does not generate your private key. This password alone will **not** be enough to access your Ether._
2. Enter the password again to confirm it.
3. Click the `"Create New Wallet"` button.
4. Download your `Keystore File`
    * Save this file to a USB drive.
    * _This is the encrypted version of your private key. You need the password to access it. It is safer than your unencrypted private key but you must have your password to access it in the future._
5. Read the warning. If you understand it, click the `"Continue"` button.
6. Print your paper wallet backup
7. Print out the current page to save your Private key, by using your web browser's print option.
    * You can write it out by hand, but it is not recommended _If you are writing it, it is recommended you write it 2 or 3 times. This decreases the chance your messy handwriting will prevent you from accessing your wallet later._
8. Copy & paste your address into a text document and save it.
    * _Search your address on [https://etherscan.io/](https://etherscan.io/). Bookmark this page. This is how you will view your balance at any time_

##### Mnemonic Phrase

1. Click the `"Generate a Mnemonic Phrase"` button

2. You can click "Regenerate Phrase" as many times as you want until you get a set of words that you like.

3. Write down the 12-word phrase that you have listed.

3. Click the `"Confirm Phrase"` button.

4. Click the words on your phrase in order.
    * This is to double check that you wrote down your 12-word phrase correctly

##### Congratulations! You've successfully created a wallet!

Things to double check:

* Unlock your new wallet using the method you chose to generate your wallet: Keystore File or Mnemonic Phrase.  Ensure it unlocks the wallet you generated and that it matches the bookmark you have.
    * _Do not simply leave your new wallet open. Pretend you are coming back a year later to access your riches. Can you do it?_
* Send a small amount of Ether (0.0001 ETH) from your previous wallet or exchange to your new wallet's public address (The one beginning with '0x').
* Send a small amount of Ether (0.00001 ETH) from this new wallet to another address.
    * _Perhaps our donation address? We are a free, open-source service. There are no fees, no ads, no tracking, no cookies, no selling your data._
* Ensure you have recorded all necessary bits of information and the addresses match at all times. If they don't, you mis-wrote something somewhere. That means it's time to start from the beginning in order to make sure you never lose access to your funds.

Doing all of this is tedious, but it ensures (1) you have complete access to your funds (2) the address you sent to is correct and matches the private key you have saved and (3) you can rest easily for years to come, knowing you will be able to access your ETH later.

### Safe Storage of Backups

It is recommended that you store backups of both forms of your key (the Keystore or Mnemonic Phrase and paper wallet version) in physically separate, offline environments.

This prevents loss of the private key & password due to: dead hard drive, lost USB drive, wet piece of paper, etc. Keep in mind that physical loss can affect an entire area (e.g. fire, flood).

### MyCrypto cannot recover your key

MyCrypto is not a web wallet and cannot recover your private key or password, access your account, move funds, recover funds, nor cancel/reverse transactions.

We are a client-side interface that allows you to interact with the Ethereum blockchain. Please secure & back up your key like the millions of dollars it could someday be worth.


### Related Reading

* [What is the difference between private key & Keystore / UTC file?](https://support.mycrypto.com/private-keys-passwords/difference-beween-private-key-and-keystore-file.html)

* [Protecting yourself and your funds](https://support.mycrypto.com/security/securing-your-ethereum.html)


### Short Version (Advanced Users Only)

[Download the MyCrypto Desktop App](https://download.mycrypto.com/)
1.  Open the app and select "Create New Wallet"
2.  Select "Generate a Wallet"

###### Keystore File Option

1.  Select "Generate a Keystore File"
2.  Enter a strong but easy to remember password. Type it in again to confirm.
3.  Click the `"Create New Wallet"` button.
4.  Click the `"Download"` button & save your `Keystore / UTC` file. Back it up.
5.  Read the warning. If you understand it and promise not to lose your private key, click the `"Continue"` button.
6.  You now have the option of printing a paper wallet, saving your private key, or saving a QR code of your private key. Back up at least one (offline).
7.  Then click `"Next: Save your Address"`
8.  Unlock your wallet that you just created using the `Keystore / UTC` file you just downloaded or the `private key`.
9. Save your address to a text document & bookmark the link to it on [https://etherscan.io/](https://etherscan.io/).
10. Ensure all information matches. Don't lose this information. Double check your work.

###### Mnemonic Phrase Option

1.  Select the `"Generate a Mnemonic Phrase"` button.
2.  **Optional** You can click "Regenerate phrase" until you have a set of words you like.
3.  Write down the phrase in order.
4.  Select the `"Confirm Phrase"` button.
5.  Follow the directions to confirm the mnemonic phrase.
6.  Log into the account on [https://mycrypto.com/account](https://mycrypto.com/account) using the mnemonic phrase option.
7.  Save your address to a text document & bookmark the link to it on [https://etherscan.io/](https://etherscan.io/).
8.  Ensure all information matches. Don't lose this information. Double check your work.
