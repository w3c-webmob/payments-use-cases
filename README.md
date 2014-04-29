Use Cases and Requirements for Web Payments on Mobile
==================

This document outlines the use cases and requirements for payments on mobile. The use cases and requirements were gathered by gathering data on web and native applications with payment functionality, as well as looking at native payment platforms. 

## Motivation
The main questions this document seeks to expore are:
* What functionality is being achieved by native payment applications and platforms which is missing from the web?
* What functionality is being offered through proprietary plugins to the web for payments?
* What methods of payments are being offered to users through these other methods of payments?

On March 24-25 the W3C will hold a [Workshop on Web Payments](http://www.w3.org/2013/10/payments/Overview.html). We have been asked to submit our use cases to help define the work the W3C will do on web payments in the future. 

## Use Case Amalgamation
In the sections below we have taken use cases from a selection of native and web mobile payment applications. In this section we will list the common use cases amongst those listed below.

Mobile specific use cases or use cases which has a specific mobile implementation are marked with an [M].

###Common Use Cases
__Act of Payment__
* Send / receive money to other users
* Pay for goods and services from third parties
* [M] Pay for goods and services in store 
* Request money from another user
* Allow for reoccuring payments
* Automated payments
* [M] Streaming payments (pay-as-you-go)
* Crowd-funding (all-or-nothing funding models)
* Subscriptions
* Delayed payments
* Deposit payments directly to user's bank accounts
* Micropayments
* Enter into legally binding contracts
* 3rd party contract arbitration
* Buy and sell debt on an open market
* Peer-to-peer loans via trust limits
* Purchase via pin / identity
* [M] Send Notifications
* [M] Peer-to-peer payment

__UI__
* [M] Do not have to re-enter account information (RequestAutoComplete)
* [M] Use of NFC, Bluetooth LE, QR Codes
* [M] SMS-based payment
* [M] Accept payments through mobile phone by swiping of a credit card on an encrypted card reader
* Simple Web-based Payment Links
* [M] One Touch Payments in mobile 
* Embedded form or Custom form
* [M] Offline mobile payments

__Refunds and Errors__
* Retry failed payments
* Invalidate charges and send receipts again
* Refund payments

__Security__
* End-to-End Encryption 
* Automatic fraud protection
* [M] Mobile-based two-factor authorization of large payment amounts (e.g. SMS)
* Skip signatures on small tickets

__User Management__
* Identify users by email
* Identify users by phone number
* Identify users by social network account
* [M] Identify mobile users based on header injection
* [M] Identify mobile users based on RADIUS lookup
* [M] Identify mobile users based on SMS MO/MT fallback
* Identify users by bank-issued OpenID
* Allow multiple user accounts
* Connect all your payment options and use them without revealing any financial details

__Payment Methods__
* Pay using credit and debit card
* Link and pay by a bank acocunt
* Cheques
* Electronic balance transfer
* Direct Debit
* [M] Convert cash into identifier which you can use to spend at stores
* Split balances between multiple payment options
* Ability to add charges to mobile user's bill (for contract users) or
  discount from user account credit (for prepay users)  with a single API across countries/operators 

__Loyalty Schemes__
* [M] Manage loyalty schemes

__Wallets__
* [M] Add funds via a wallet system
* [M] Withdraw funds via a wallet system
* [M] Pay via wallet system
* [M] Transferring funds from e-wallets / bank cards
* [M] Sending funds to e-wallets and bank cards

__Pay Receipts__
* [M] Link mobile phone number to account and use for pay receipts
* Proof-of-Purchase and Verifiable Digital Receipts

__International Use Cases__
* Acceptance of payments globally, and deposit into users bank account
* Charge customers in their own local currency
* Automatic foreign exchange
* Alternative Currencies (Support for Bitcoin, Ripple, Ven, etc.)
* Apply sales tax with geolocation

__Vendor Use Cases__
* [M] Turn mobile into Point-of-Sale Device
* [M] Ability to re-sell digital content (automatic redistribution licenses)
* Complete verifiability (digital signatures on assets, listings, digital receipts, and identity) 
* Decentralized, Machine-readable Metadata (Assets and Services)
* Separation of Content from Licenses
* [M] Generate revenue by applying your own transaction fees to payments on your platform

###Developers-specific Use Cases
See specific solutions for good API use cases / requirements, these can be found in ["Use Cases as per Existing Payment Solutions"](/existingpaymentsolutions.md):

* Paypal
* Google Wallet
* Stripe
* Balanced Payments
* Paymill
* GoCardless
* Yandex

###Use Case Notes
* Removed account viewing info (app specific)
* Removed when you pay (app specific)
* Removed security details (PCI compliant, SSL, tokenization, address verification system, and credit card security code for fraud protection, OAuth2, OpenID Connect)  
* Payment-end flows, so what happens at the bank (business issue)
* Some digital currency related use cases that are the same for desktop and mobile
* Removed payment plans (business issue)

## Use Case Sources
We captured use cases from current native and proprietary web solutions. Below are links to the documentation containing the solutions.

###Use Cases as per Existing Payment Solutions
We took use cases from existing payment solutions in native apps and proprietary web solutions, these are detailed in ["Use Cases as per Existing Payment Solutions"](/existingpaymentsolutions.md).

###Other Use Cases
We may find some other use cases which are not detailed in current native or proprietary web solutions, these will be detailed in ["Other Use Cases"](/otherusecases.md).
