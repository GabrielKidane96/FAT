# Frequently Asked Questions



[TOC]

### What Is a Data-Only Protocol/Standard?

A data only protocol is, well, a protocol that exists and functions only using data! In contrast, Ethereum runs smart contract code in parallel across the network to function and reach consensus. Ethereum is a computational blockchain distributes computation and data across the network. 

Data protocols only share the data at the blockchain layer, and defer the computation to users of the to filter and validate the data according to protocols like FAT.

Sharding data is a "solved"  problem in that it has been successfully implemented in many production database systems, whereas sharding computation remains a very difficult challenge that plagues the scalability of many blockchains to this day and for years to come.



### Is FAT comparable with Ethereum?

Let's compare an ERC-20 token (Ethereum) and a FAT-0 token functionality:

| Criteria                                                  | ERC-20 | FAT-0 |
| --------------------------------------------------------- | ------ | ----- |
| Decentralized Blockchain                                  | Y      | Y     |
| Anyone Can Issue & Trade                                  | Y      | Y     |
| Decentralized Trade                                       | Y      | Y     |
| Tokens Tradable in Fractions                              | Y      | Y     |
| Trustless Issuance/Exchange                               | Y      | N     |
| Decentralized Issuance                                    | Y      | Y     |
| Decentralized Trustless Code Execution (see below :wink:) | Y      | N     |



Now, before you go all complaining about the couple N's on the right side, let's list some killer pros for FAT:



| Criteria                                                     | ERC-20 | FAT-0 |
| ------------------------------------------------------------ | ------ | ----- |
| Fixed Cost of Operation ($0.001 USD per transaction/KB, Forever) | N      | Y     |
| Securities/Regulatory concerns of operating token            | Y      | N     |
| Purchase operating tokens in Fiat, no exchange/regulation    | N      | Y     |
| Anchors into the oldest and most secure Blockchain: Bitcoin  | N      | Y     |
| ~~Can Anchor into Ethereum. Ethereum can't anchor into itself~~ **LOL** | ~~N~~  | ~~Y~~ |



### So, Why _can't_ it do everything Ethereum does?

FAT is a data only protocol, it can only achieve consensus on the order and content of data that is published to the blockchain.

 In Ethereum an addresses behavior (often called a contract) can be defined in code, and forced to act a certain way by the miners via consensus. No signing with private keys is needed because the behavior can be trusted by everyone in the network. For example, I send ether to a contract and get back an ICO token, guaranteed.

FAT cannot _force_ an issuer to perform an action like the smart contract in the example. The issuer needs to use their private keys to sign coinbase transactions to issue new tokens in response to events. Since private keys cannot be published, the issuer must coordinate a token sale with a degree of trust from participants:

- Set Exchange Rate **=>** Accept Payments/Verify **=>** Send Tokens Back
  - Manually
  - Automatically by running a piece of software

 This means to have smart contract like functionality without a computational consensus layer on FAT, trusted issuing parties must run, frequently or 24/7, pieces of software to honor client requests for exchanging tokens.  This is perhaps the biggest caveat of FAT.

At the same time this meshes with how our legal and social systems regulate behavior in the real world. The publicly viewable, immutable evidence of lack of action on behalf of a trusted well known issuer is likely admissible in court. It is most certainly admissible to cause public distress and outcry.



### So, Why should I use FAT over Ethereum or Colored Coins?

1. They are crazy affordable. ($0.001/KB vs \$2.86/KB & \$3.83/KB). We're talking 1000%+ less expensive than the competition.
2. They are crazy easy to learn. FAT tokens are written in simple JSON and optionally your choice of programming language. Libraries are available to facilitate easy contract module development.
3. They are crazy flexible. Add whatever metadata you want to define custom programmatic behavior as an issuer. Choose any programming language you want just be trustworthy and run reliable high availability code.



### How many transactions per second (TPS) can FAT do?

FAT TPS is equal to Factom's TPS. Currently Factom can do around 7 TPS stably, which comparable to Ethereum. Factom has been pushed over to 10 TPS before in testing. Factom will be capable of sharding to accommodate increasing volume in the near future as part of the core development grant by Factom Inc.



### Can I try FAT out without spending real money?

Absolutely. Factom has a thriving and responsive [Testnet](.) that allows you to try FAT out at no cost.



### Who Owns FAT?

You do. FAT is completely open source under Creative Commons 2.0. FAT's development and administration is spearheaded by DBGrow Inc., one of the 41 proud Factom Authority Node Operators




