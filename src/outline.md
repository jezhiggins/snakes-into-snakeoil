## Intro


## Snakes

What is a blockchain? 
* overview
* immutability
* consensus
  * PoW
  * PoA
  * PoS

Transaction mechanisms
* ordering
* double spending

Smart contracts

Well known examples - Bitcoin, Ethereum, Hyperledger Fabric
Less known examples - on 5 January 2018, coinmarketcap listed 2086 different cryptocurrencies and tokens

## Snake oil

Blockchains are all very clever, but basically they're slow databases. Yes, you can verify the database, but you need all of it in order to do so.

Cryptocurrencies? That list of 2086.  Number 23 was Tezos, with a valuation of $293,840,524 (down from $958 billion in August 2018 and ) In July 2017, Tezos raised $232 million in an "ICO". Note that's $232 million in ETH and BTC. The co-founders then immediately fell out, and there was a lot of legal wrangling.  The project now has a new head and has "converting assets out of cryptocurrencies".  The network itself is "in beta" with maybe 100 "bakers". 
Number 24 was Dogecoin at $270 million. "Dogecoin is an open source peer-to-peer digital currency, favored by Shiba Inus worldwide." It was created as a joke.

Most successful DApp?  Crypto Kitties.

Immutability is great, but it's also a problem. The only way to fix bugs or to upgrade capabilities is by "hard fork".

The situation is similar for smart contracts, but worse. How do you fix bugs in an unchangeable piece of code? How do you even debug the problem?

And what if the data is wrong?
* Art - https://shkspr.mobi/blog/2018/06/how-i-became-leonardo-da-vinci-on-the-blockchain/
* Land registry - map of my house in Pembrokeshire. Title is established, although unclear. Precise northern boundary not known. Ownership of this lane is unknown. Ownership of woodland adjacent litagated recently. Boundaries of neighbouring farm delayed in probate. Land registry data often based on maps, but those maps are inaccurate. Older deeds refer to the land demarquated by landscape features. What if those are lost or move (eg watercourses).  
* CVs
* Anything else?
* Jurisditional issues - it might, perhaps, be a theoretical issue but having a copy of the Bitcoin database might well be illegal in the UK. 

Blockchains can only verify things which happen on the blockchain. Anything off the chain relies on external validation.

What about hacking? Well, you can theoretically attack the chain if you have 50% of the miners (in a PoW scheme anyway), but it's the off chain stuff that's the problem again.  

```Under our company's provenance platform, it is not possible for you to register as Damien Hirst. Why? Because you do not control Damien Hirst's website. Only Damien Hirst can publish his master bitcoin address on his website, and therefore only Damien Hirst can register with our platform.```
https://shkspr.mobi/blog/2018/06/how-i-became-leonardo-da-vinci-on-the-blockchain/#comment-55290

The event-stream attack - https://medium.com/intrinsic/compromised-npm-package-event-stream-d47d08605502

## Blockchain "applications"

https://dappradar.com/
Gambling, games, exchanges, erm, that's it

https://everydapp.com/


17 Blockchain Applications That Are Transforming Society
https://blockgeeks.com/guides/blockchain-applications/
Doesn't actually list any real examples.

8 Blockchain Applications That Could Help Your Small Business
```“Smart contracts” are “self-automated computer programs that can carry out the terms of any contract,” writes Chris DeRose in American Banker. In a nutshell “it is a financial security held in escrow by a network that is routed to recipients based on future events, and computer code.” With “smart contracts” businesses will be able to bypass regulations and “lower the costs for a subset of our most common financial transactions.” Additionally, these contracts will be unbreakable.```
https://www.upwork.com/hiring/for-clients/8-blockchain-applications-help-small-business/

Here's a simple contract - https://github.com/github/balanced-employee-ip-agreement/blob/master/Balanced_Employee_IP_Agreement.md 

What about a will? What about a simple leasehold?

Walmart is betting on the blockchain to improve food safety
https://techcrunch.com/2018/09/24/walmart-is-betting-on-the-blockchain-to-improve-food-safety/?guccounter=1

https://twitter.com/davidgerard/status/1068863934894145536
```"IBM's systems for Walmart and Maersk are completely centralised, but the back-end database is Hyperledger, so they're trumpeted as "GOOD NEWS FOR BLOCKCHAIN" - the correct perspective is "with sufficient thrust, pigs fly just fine", and boy are IBM strapping Porky to a rocket."```

https://twitter.com/ruskin147/status/1049353345259978752
```This chart from a rather good US department of Homeland Security report on blockchain shows how rarely it’s needed```

## Cryptocurrencies

https://www.weusecoins.com/

https://coincentral.com/how-long-do-bitcoin-transfers-take/
```These are the estimated fees you should use depending on how fast you would like to obtain the first confirmation for a typical transaction. The transaction fee you pay will only affect the time you have to wait until the first confirmation. When making a Bitcoin transaction, recipients usually require somewhere between 2 and 6 confirmations to consider the transaction as valid. Once your transaction is included in a Bitcoin block and thus obtains the first confirmation, you will need to wait approximately 10 minutes for each additional confirmation. After the first confirmation, the waiting time for each additional confirmation is completely independent of the transaction fee you paid.Because of the decentralized nature of the Bitcoin network and the fact that there is sometimes congestion in the available block space (because of the 1 MB limit), the amounts shown here are probabilistic and there are no guarantees that they will work.```

https://bitinfocharts.com/comparison/bitcoin-transactionfees.html

https://en.wikipedia.org/wiki/Bitcoin_scalability_problem
```The transaction processing capacity maximum is estimated between 3.3 and 7 transactions per second.```

Visa?
```VisaNet handles an average of 150 million transactions every day and is capable of handling more than 24,000 transactions per second.```  ~1700 tx/sec average

PayPal - 193 tx/sec average, so peak must be higher

https://news.bitcoin.com/no-visa-doesnt-handle-24000-tps-and-neither-does-your-pet-blockchain/

But it's anonymous!
No, no it isn't
https://blog.acolyer.org/2017/02/20/a-fistful-of-bitcoins-characterizing-payments-among-men-with-no-names/
https://blog.acolyer.org/2018/09/14/an-empirical-analysis-of-anonymity-in-zcash/

Traffic analysis? 
