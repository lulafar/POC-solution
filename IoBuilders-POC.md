# IoBuilders Tokenized Money
One of the key components of Iobuilders, will be the Tokenized Money Feature. A quick summary of this feature is the ability of converting a fiat currency into a token, and viceversa, on an easy and fast way, following all the defined regulations and laws.
To be able to build this functionality, the following puzzle pieces need to be build:

![](https://www.lucidchart.com/publicSegments/view/bbc8eda2-83c8-4971-90ea-184442d01643/image.jpeg)

* Mobile App. The end user will us a mobile based wallet, where he can
  * Create an identity, via a Self sovereign Identity implementation  
  * Pass the wallet KYC, attesting his official id on the platform (id scan)
  * Operate with the wallet: topup, transfer, withdraw, buy ....
  * App Services. There will be several components ( backend services), that will support the mobile features and business flow
* Tokens, identity and wallet will be based on ethereum ( or Quorum)
* To be able to operate on the banking system, and work with e-money we need an e-money  License (already provided), an acquirer (momopocket) and banking tech (inversis). We will attach to the ethaccount, an IBAN, being able somehow, to be white label bank. That allows us:
  * To bring fiat into the blockchain via the tokenizer
  * Guard, trace and monitor all the transactions, backed by an omnibus account
  * To up money into the wallet via Iban, or normal credit card acquirement
  * Instant transactions

## POC Exercise 1

### Tech + Architecture

Based on this scenario, we need to decide:
* Tech risks, to decide how to tackle them, based on the priorities we identify. To decide about the overall risks, we need to think about the team skills, POC complexity, and key components too.

Technologies. architectures to be used on every single component, need to be defined, based on the following context:

 * Mobile Wallet needs to be delivered for IOS and Android
 * Usability and design is very important
 * Performance, traceability and security is key, due that real money is used, regulation etc.
 * Every single event on the system, must be audited
 * All the components will be reusable, for all the ventures that will be build by iobuilders
 * Usage of the most optimal tech, framework and language, finding the right balance team skills with the challenging
 * It's a POC, we need to find quick wins and fast lanes

**(1) What are your thoughts, ideas about tech, architecture with this context?**

### Team
* We need to hire a team to develop the hypothetical POC. Which skills, roles and team size, you think is needed, based on the following details:

  * Timing for the POC is 4 months
  * This project will be, a base component for the company

**(2) Describe the skills, roles and team size, that you think is the best fit for this project.**

### Culture

* The tech culture, methodologies that will be part of the ADN of the company, are going to be shaped during this project. Which is your proposal, personal point of view, to have a common sense culture, methodologies, mindset, knowing the context, business needs, and a usual venture builder operation? Some base concepts that are a must:

  * Multifunctional, autonomous and business oriented teams is the base line. The business domain is the centre
  * Everybody counts, and is able to propose things, and communication is key
  * Listen to others before arguing. Empathy!
  * Continuous improvement must be tattooed on every single member's body :)
  * We are building POC's to test business scenarios and then based on the insights, decide if it makes sense to create a venture or not.


**(3) Go into the details, about which tech/business methodologies, tools, etc..., you think fit best to the scenario, and the culture you like and makes sense to apply on this company**

To deliver the answers to this questions, create a pull request on the following project https://github.com/Ferparishuertas/iobuilders, with a markdown file, containing your reviews.




