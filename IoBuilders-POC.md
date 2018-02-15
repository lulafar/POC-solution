# IoBuilders Tokenized Money
One of the key components of Iobuilders, will be the Tokenized Money Feature. A quick summary of this feature is the ability of converting a fiat currency into a token, and viceversa, on an easy and fast way, following all the defined regulations and laws.
To be able to build this functionality, the following puzzle pieces need to be build:

![](https://www.lucidchart.com/publicSegments/view/bbc8eda2-83c8-4971-90ea-184442d01643/image.jpeg)

* Mobile App. The end user will us a mobile based wallet, where he can
** Create an identity, via a Self sovereign Identity implementation
** Pass the wallet KYC, attesting his official id on the platform ( id scan )
** Operate on with wallet: topup, transer, withdraw, buy ....
* App Services. There will be several components ( backend services), that will support the mobile features and business flow
* Tokens, identity and wallet will be based on ethereum ( or Quorum)
* To be able to operate on the banking system, and work with e-money we need an e-money  License ( already provided), an acquirer (momopocket) and banking tech (inversis). We will attach to the ethaccount, an IBAN being able to be white label bank. That allows us
  * To bring fiat into the blockchain via the tokenizer
  * Guard, trace and monitor all the transactions, backed by an omnibus account
  * To up money into the wallet via Iban, or normal credit card acquirement
  * Instant transactions



