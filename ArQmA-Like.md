# **Copyright 2018-2019 The ArQma Project**

## The ArQmA Project - Secured Digital Currency

#### Arqma&#39;s Vision:

1 Flexible, private, crypto currency with a payment gateway for e-commerce and personal use.

##### ArQmA Features

2.1 Secure
2.2 Lightweight
2.3 Private and Untraceable
2.4 Low Barrier to Participation
2.5 No pseudo-centralization by ASICS, no arbitrage by Nicehash

##### ArQmA Differentiation

3.1 vs. Bitcoin
3.2 vs. Litecoin
3.3 vs. Monero
3.4 vs. Dash
3.5 vs. Zcash
3.6 vs. Ripple

##### ArQmA Implementation

4.1 Achieving Trust-less Transactions
4.2 Achieving Anonymous Transactions, Open Alias support.
4.3 Coin Minting Process
4.4 Transaction Fees

##### ArQmA Community

5.1 Links
5.2 Mining
5.3 Exchanges
5.4 Wallets
5.5 Development Team
5.6 Current Work and Future Plans
5.6.1 Road map of future work
5.6.2 Future plans
5.7 Network design and redundancy.
5.8 Github repository report and sources of original code.

## Disclaimer

This White paper does not provide a legally binding agreement.

Neither the ArQmA development team, nor the community members, accept any legal liability arising from the use of ArQmA or the material contained in this White paper.

This White paper represents, at the date of the latest update, the current state and plans of the ArQmA community and developers. Since ArQmA is an open source project, details may change, and should not be considered final.  We are a community led project which is self financed. ArQmA is open to new ideas and technology to pursue and develop.

## Vision

Technology impacts our financial lives in new ways every day, and the pace of change is accelerating. In the first decade of the 21st century broadband internet became Widely available, giving rise to the concept of online marketing and commerce. By 2015, mobile phone usage increased to rival desktop usage for online shopping. Researchers have estimated that by 2021 there may be over 2 billion mobile banking users.  In Some countries with unstable fiat currency situations, the people have considered going to crypto currency solutions for local banking.

Truly, we are realizing a more convenient reality with our personal finances.

This convenience, however, comes with many challenges. On any given week, it is not difficult to find a news story about financial accounts being hacked and/or personal identity information being stolen. And in spite of the technological advances, the current e-commerce solutions cannot solve the problems inherent With local currencies; such as the difficulty of transacting across national borders, and the occasions When centralized powers negatively impact economies via poor decisions or manipulation.  Local banks extract high fees for transacting within borders and administration.
Also the banking infrastructure is not without some power cost, and amortization of large numbers of real estate parcels for branches. The infrastructure, even when based on Linux/Unix has been revealed to have some issues with maintaining one point or centralized security. It has been shown that data breaches happen and can overwrite transactions or suffer catastrophic data loss when centralized. Even with a disaster recovery plan, the confidence of the users can be compromised since there is no transparent proof of consensus of what your balance are, should be, and could have been.

Enter the concept of decentralized digital currency and operations.

Imagine a time in the not-so-distant future where personal financial management is not only convenient and mobile, but also secure, private, and impervious to national borders and centralized control.

ArQmA is about enabling this era, enabling an age where all people everywhere have the freedom to privately receive, spend, and manage their finances with whatever gadget they already own.

This new era in personal banking is closer than you think.

## 2.0 ArQmA Features

Does ArQmA stands for Anonymous Real Quality Mastery of Algorithms? It should.
The name was also started as a montage of the two principle founders names ArqTras and Malbit.

It was launched on June 14, 2018 at 19:05:26 PM UTC.

The following features are critical to the vision of a digital currency for everyone :

A payment gateway with transactions completing in under ten seconds for e-commerce and personal usage.

The specs for the coin are:

- PoW algorithm: CryptoNight-Lite PoW

- Max supply: ~50 million

- Block reward: ~20 smoothly varying

- Block time: 240 seconds , changing to 120 seconds at V10 fork.

- Difficulty: re-targets at every block

- Block confirmation: 18 blocks

- Properly set 1MB Scratchpad to eliminate time-waste hashing by trying to divide into a 2MB Scratchpad like other projects have done.

- Asic resistance : Yes, deliberately for miner equitably fair support.

- Nicehash resistance: Yes, deliberately for miner equitably fair support.

- BulletProof Ring CT, minimum level 7, maximum 41

- True DNS SEC authorization between nodes.

- LWMA 2 Difficulty Algorithm securing network against 51%+ hash rate attacks and difficulty

- swings of an extreme nature.

- Ticker: ARQ

- Emission rate planned on 30 years

- Support for integrated addresses, and Open Alias for short names to private addresses.

- Cross compiling capable code for even Android and iPhone systems. The same security measures applied to PCs are retained for tablets and phones.

## 2.1 Secure

ArQmA takes security seriously. Each transaction is secured with robust cryptography and distributed through a global peer-to-peer consensus network. The cryptographic implementation ensures that nobody is able to &quot;steal&quot; an online transaction, and a coin&#39;s owner is unable to spend the coin more than once.
ArQmA has bulletproof transactions turned on which just recently passed another audit by and external firm for Monero from which we took the code and made it our own.

Another point to make is that we don&#39;t just arbitrarily copy code from Monero and paste it in there. Arqma has a process to receive alerts for issues, defects, and then do the code integration via a pull request. The code is actually tested on a stagenet/testnet where applicable before it is made into a release.
There is an automated build engine that was made for all the platforms, if such an addition of code or a patch is created, the static binaries are created with less effort.

For example, the double deposit bug, a variant of double spend, which affected exchanges of varying code bases of Monero were being attacked before ArQmA was launched. We detected it from an alert from an exchange and took steps accordingly matching it to an outstanding issue listed for several weeks.  We discovered that other Monero coins were being affected by code review of others, and decided to push the issue to a higher visibility. Using the ethical disclosure method to Monero, we escalated the issue&#39;s importance of it being fixed due to losses from the exchange.
Within a few days, many exchanges were saved from being exploited.

## 2.2 Lightweight

ArQmA seeks to be mobile—friendly by implementing, among other things, the following technical features:

A lightweight Proof of Work algorithm: Cryptonight-lite variant 1.

- Blockchain pruning

- Optional lightweight semi-traceable transactions for the ones you want to trace with your secret keys. But also it is not traceable for anyone to log and trace due to random mixins of transactions and ring CT security.

With this intentional focus, ArQmA requires a smaller technology footprint than comparable crypto currencies, and the time to sync with the blockchain on lower end devices improves by a significant factor.
There are trusted remote nodes available for the mobile and graphic based wallets.  There is also trusted remote nodes available to the command line interface(CLI) wallets.
There are three main nodes for the ArQmA network based in the US, EU, and Japan.
They are also backed by several layers of remote servers distributed across the internet. Cloudflare for web services provides anti-DDOS protection.
The main software repository for software is [www.github.com](http://www.github.com/) under the GPL3 license.

The compiled binary executables are also available on [https://www.arqma.com](https://www.arqma.com/)

## 2.3 Private and Untraceable

Privacy is paramount. Funds are transferred without the identifying information of the user becoming visible on the blockchain. In addition, the receiving wallet addresses are obfuscated with ring signature technology and non-repeating one-time addresses derived from the receiving public key. These measures make the blockchain highly resistant to analysis.
Specifically, the reuse of shared keys used to be a detriment of allowing a trace back, but that was closed just after ArQmA was launched. The code was evaluated and tested to be worthy and added.

Open Aliases of addresses are allowed and have added to the code base.
One can have am easy to remember address to be paid at to that decodes to the full private address. Open Aliases are registered within the ArQmA node system and decoded similar to a DNS address within the wallet applications.

## 2.4 Low Barrier to Participation

Founded as an Open Source project, ArQmA is free to use without restriction.
In addition, there was a pre mine of 7.5 million coins.  It is to be locked on a schedule basis to cover operating costs of the 1Gbits high speed network, and server hardware infrastructure, firewalls.

Pre mine wallet address: ar4DExwEr4qM2dBRimSjZ5B11rZbAS9HEFeMYkgw3Ts4NQvS2NY2ra22M5CoQBDifWVxfig8fz7QvQ3xDmGtRt1o1UP8jPTEQ

View key: 3ee53c136c57080c340e56f0545dad23a591b8bd5d2b89cff3c4182c88aa36fc Premine wallet includes Dev income (1.5 mln to Malbit and 1.5mln to ArqTras).

There are no ICO tokens involved, produced, or burned, or secured.
That means this is not a security as defined by some governmental parties. Check with your local authorities for updates.
ArQmA is not an ERC-20 token, therefore doesn&#39;t fall under the US SEC restrictions.

ArQmA Community donation wallet address: ar46iCiw5uB7SjnYhL5EJLP1LpqGkZbCcWhWgdbLL1c4DicNuYi3ZeRJPi8FFmEhYnagbxRyaQKyTYBA95JqmPcr1XZytK9o3

Viewkey: 4e5373dfd5ba67fa2988107a605bc960575c465bd07aba624915d3f660b73d62


The network is resistant to specialized hardware (ASICs), allowing more people to participate directly with their PC by mining or running a full node. Everyone is welcome to contribute to the ongoing effort. There are two primary chat servers, Discord and Telegram. A Reddit discussion forum, and a forum on Bitcointalk.org .

NOTE: Many of the points referenced above are covered in more detail in section


## 3 ArQmA Differentiation

With the astounding amount of &quot;alt coins&quot; now available, it is worth noting how ArQmA differs from others, and specifically how it improves upon some of the similar offerings.

The first thing to note is that within the alt coin universe, there are different classes of block chains and coins. There are smart contract block chains (i.e. Ethereum) which provide a mechanism to manage complex transactions such as business contracts and decentralized application (&quot;dApp&quot;) hosting. There are also token coins (i.e. STEEM token) which supply a payment mechanism for use of a particular decentralized application or service.

ArQmA is a currency coin, intended to provide an alternative to local fiat currencies. Therefore, this section will provide comparisons only to other well—known currency coins.

(NOTE: for more details on the concepts in this section, see section 4 ArQmA Implementation and Specifications.)

ArQmA vs. Bitcoin

Bitcoin is the best—known of all crypto currency blockchains, as it was the first to achieve a measure of success. There are considerable differences between ArQmA and Bitcoin, in the areas of privacy and usability.

## 3.1.1 Privacy and Transaction Linkages

Regarding the critical feature of privacy, Bitcoin falls short of the ArQmA blockchain. In order to maintain privacy of individual expenditures, it must be exceedingly difficult for an outside party to link a transaction back to its owner.

Consider that each transaction consists of some inputs (coins which are being spent) and some outputs (one or more addresses which receive the spent coins). Additionally, each input in a transaction actually links to an output of a previous transaction, forming a set of transaction paths.

In Bitcoin, these transaction linkages are explicitly transparent on the blockchain. Any blockchain explorer can follow the graph, which has allowed for sophisticated analysis to break anonymity of transactions. This privacy issue is alleviated in various ways, such as creating a unique address for

every transaction, using centralized &quot;mixers&quot; to randomly &quot;mix up&quot; several people&#39;s Bitcoins, and employing methods to hide IP addresses when making transactions. The fact remains, however, that the Bitcoin inputs and outputs can be directly followed on the blockchain.

ArQmA resolves this privacy concern by intentionally obscuring transaction linkages on the blockchain. Every transaction has a default number of &quot;decoy&quot; input links (also known as mixins). Anyone making a transaction can request a higher number of decoy inputs. to increase anonymity. As the blockchain grows over time, the increasing number of decoy input links will make the overall graph of transactions exceedingly difficult, if not impossible. to correctly decipher.

## 3.1.2 Mining and Barriers to Participation

Bitcoin uses a SHA-256 Proof-of-Work (POW) algorithm which is dependent primarily on CPU power, and there are several specialized ASIC hardware devices made for mining Bitcoin has driven the hash rate high enough that currently only ASIC hardware mining is profitable. The result is that the average person with a PC cannot readily participate in the transaction validation process of mining and acquiring Bitcoins.  Also only a few major manufacturers compete for the production of ASICS and there are long term concerns of market manipulation through deployment and pre-deployment usage by less scrupulous actors. There is always the long term concern of a possible backdoor of security embedded within these devices where a centralized take over can happen and disrupt several coins and markets.  Those few manufacturers can also be nullified by natural disasters or governmental interference from any source.

By using regular, off the shelf devices have a value for decentralization:
1. A large majority of them are secure in the sense that any major breach is addressed by the OEMs with funding and support paid for by the consumer and public oversight by developers, support media, social media, and creative innovators of technology using a mass adopted platform.  ASICS are only growing by a very small group to which there is less oversight, and dim transparency due to proprietary hardware knowledge withheld.

2. Off the shelf platforms had been mostly bug proofed, reliable, and have been through hundreds of design iterations by hardware/firmware/software developers.
Also there is innovation by the community that have access to the tools which are cheaper,  more flexible to develop and can be worked on in collaboration on a exponential scale.

ArQmA uses a CPU friendly Proof Of Work (POW) algorithm that limits the advantage of GPUs and is ASIC resistant. This allows almost anyone with a PC to participate in mining and acquiring ArQmA. It also lends to decentralization of authentication, verification and storage of the blockchain.

## 3.1.3 General Usability and Transactions-Per-Second

Regarding usability and the vision of a lightweight digital currency for everyone, ArQmA has distinct advantages over Bitcoin.

The maximum block size of Bitcoin (1 MB) and the block creation time of 10 minutes limits the transactions—per—second (TPS) processing power to no more than , TPS. This low TPS severely hinders the ability of the Bitcoin blockchain to process transactions for the masses. While there are ways to remedy this limitation, the Bitcoin community has not achieved consensus on doing so. Thus, the coin has become more of a high—end investment with limited use as a currency, not unlike physical gold coins versus U.S. dollar bills.

ArQmA solves the TPS limitation by using an algorithm to automatically adjust the maximum block size up or down, based on the previous 100 blocks. This approach allows the ArQmA blockchain to self adjust it&#39;s TPS throughput as transaction traffic increases and decreases over time.

## 3.2 ArQmA vs. Litecoin

Litecoin was started as a fork of the Bitcoin code in 2011, with the goal of being a lighter—weight currency, offering low—cost transactions with fast confirmation status.
The majority of Litecoin is mined by ASICS and therefore has the same issues entrenched with the pseudo-centralization of the network.

## 3.2.1 Privacy and Transaction Linkages

See the description of the privacy issues in section 3.1 vs. Bitcoin. Litecoin has the same issues as Bitcoin.

## 3.2.2 Mining and Barriers to Participation

Litecoin uses a Proof-of-Work algorithm called scrypt which depends not only on the CPU, but also on fast access to a memory area. This POW makes it difficult to develop specialized ASIC hardware, and renders GPU,s to be only about 10X faster than CPU,s. This is a great improvement over Bitcoin, but still leaves mining largely in the hands of those who can purchase high end graphics cards or special built ASICS.

ArQmA actually uses an improved version of the scrypt algorithm which employs a larger memory area. The result is that ArQmA is even more resistant than Litecoin to specialized hardware, and the GPU cards do not have as great an advantage over the CPU. This ensures that CPU mining with an average PC is an option for everyone.

## 3.2.3 General Usability and Transactions-Per-Second

Being a &quot;lightweight Bitcoin&quot; it is no surprise that Litecoin is able to boast roughly 8 times the TPS of Bitcoin. This brings the maximum capacity of Litecoin up to 56 transactions per second.

For comparison, credit card processors typically see tens of thousands of transactions per second. While the Litecoin network can currently process transactions fast enough for its volume of users, at some point , long before Litecoin can become a currency for the masses , its TPS must be greatly increased.

See the prior section 3.1 vs. Bitcoin for a description of ArQmA,s solution to the TPS limitation.

## 3.3 vs. Monero

It is public knowledge that ArQmA is a fork of the Monero project, and it continues to incorporate improvements directly from the Monero code base.  Since Monero itself is well known as a security/privacy coin, it requires some attention, to address exactly why ArQmA might be preferred. We evaluate the merit of a change in the features, security being the paramount priority.  We listen to the community and add features that Monero develops, but also a few security solutions not developed yet in some other coins.

Such as providing static build binaries to which can be internally verifiable within it&#39;s own code at run time for tamper proofing by external applications. Also memory clearing, wiping, and encryption of data workspace areas while the applications are running to further stop hacks or leaks of data from a possible operating system flaw.  Also, this prevents possible data leaks from virtual machine operations within architectures chip flaws. For example the recent Intel meltdown and AMD Spectre defects. The amount of extra code running is a negligible drag to the speed of the applications.

## 3.3.1 General Usability and Mobile Friendliness

The advantages that ArQmA has over Monero are in the area of being lightweight and mobile friendly. ArQmA has chosen a different Proof of Work(POW) algorithm which requires half the CPU memory and allows for faster verification of the blockchain. The blockchain is pruned in a manner that keeps it smaller than Monero&#39;s, resulting in faster blockchain synchronization. ArQmA also allows the option for a limited number of fast, really low fee transfers (which are more traceable on the blockchain) for non sensitive payments. Monero, on the other hand, requires all payments to be fully anonymous which adds to the validation times and blockchain size.

Also, the mobile wallets and desktop wallet can use the three primary trusted remote nodes for access to balance, and send ArQmA.  The web wallet can also facilitate the same functionality with any decent browser on an internet capable device.

All of these aspects, among others, put ArQmA in a better position to be the secure, private

currency that can be used by the general public with cell phones and tablets on the go.

## 3.4 vs. Dash

Dash stands for &quot;digital cash&quot; and is meant to work like physical cash when purchasing items online or in stores. Like ArQmA, Dash embraces the importance of Security and Privacy. There are some disadvantages, however, when comparing this coin to ArQmA.

## 3.4.1 General Usability and Transactions-Per-Second

In November 2017, the Dash blockchain hard—forked to double its maximum blocksize, to 2 MB. That change allowed Dash to process roughly 48 transactions per second. For comparison, credit card processors typically see tens of thousands of transactions per second. At some point the Dash TPS must be increased again, and likely again after that. This continued increasing of TPS via disruptive blockchain modifications which is not conducive to massive adoption.

See section 3.1 vs. Bitcoin for a description of ArQmA,s solution to the TPS limitation.

## 3.4.2 Mining, Governance and Barriers to Participation

Dash uses a Proof-of-Work algorithm which is dependent primarily on CPU power, and the network welcomes the use of specialized hardware for mining. This has driven the hashrate high enough that currently only ASIC hardware mining is profitable. The result is that the average person with a PC cannot readily participate in the transaction validation process of mining.  Also, this puts the few ASIC miners in the driver seat and can determine a coin&#39;s direction possibly against a democratic majority of miners/community wishes.

Additionally, Dash implements a complex form of Governance consisting of a 2nd tier network node, called a master node. In order to own a master node, one must obtain and hold 1000 Dash. (At the time of this writing, this is an investment of roughly $200,000 USD.) Only master node owners vote on proposed enhancements to the coin, as well as prioritize which projects get paid from the development fund. Similar to ArQmA, new coins are disbursed as a block reward when a miner successfully validates a block of transactions. But unlike ArQmA, the miner must split the block reward between the master nodes and the development fund.

Because special hardware is required to mine Dash, and a large monetary investment is necessary to participate in the governance of the currency, the barriers to participation are much higher than with ArQmA&#39;s simple open source project model. Even to submit a proposal for a vote by the master node owners, costs a fee of 5 Dash (roughly $1000 USD at the time of this writing). These factors work against a true decentralization for a currency.

ArQmA uses the traditional Open Source Model of participation and governance, which has been shown to work well for many large technology efforts for many years. It allows a diverse community to grow organically, which is an advantage for ArQmA&#39;s plans to become widely used by all walks of life.

## 3.5 vs. Zcash / Bitcoin Gold

Zcash is another fork of the Bitcoin code base, with the intent of adding the element of privacy to the blockchain.

## 3.5.1 Privacy and Shielded Transactions

Zcash achieves privacy by using a cryptographic approach called &quot;zero—knowledge cryptography&quot; to create &quot;shielded transactions&quot;. However, this is not the default option, and there is no limit to the number of non-private transactions in each block. A recent report by ICO research ﬁrm Satis Group (&quot;Cryptoasset Market Coverage Initiation: Valuation&quot;, August 30, 2018) states:

&quot;Only 5% of the Zcash network uses ,shielded, addresses currently, with the rest of the addresses being used for transactions functionally and technically no different than Bitcoin.&quot;

The paper concludes that since there are so many more addresses in the blockchain that are not private, the Zcash network as a whole is not fungible. Meaning the coins in any given wallet could possibly be traced back to their prior transactions. (This is important, because nobody wants to ﬁnd out that the coins in their wallet were used previously to commit a crime, etc.)

In contrast, the research states specifically that Monero , and therefore we can conclude ArQmA as well , is a fungible network. Both Monero and ArQmA default to a private transaction, and ArQmA only allows no zero level ring CT transactions in any block to be switched to non-private.  Therefore a bad actor or spy will find it extremely difficult to trace transactions by a process of elimination by making a sifted database of transactions.

## 3.5.2 Mining and Barriers to Participation

Zcash went away from the Bitcoin POW algorithm, and implemented the Equihash POW algorithm, to provide ASIC resistance, and allow people to mine with their GPU,s and CPU,s. The problems with the Equihash algorithm are that:
1) it does not limit the advantage of GPU over CPU
2) An ASIC was recently developed which could mine Zcash, threatening the future viability of GPU and CPU mining. As of the date of this paper, the Zcash project has not created a fork of the blockchain to provide ASIC resistance once again.
3) The algo variant 155 used by Bitcoin Gold requires larger 3GB GPU memory cards and neglects the older architecture such as Nvidia Fermi cards which mostly are 1-1.5GB. Even with a 3GB or 6GB Tesla M series cards do not hash this variant algorithm.
This also probably affects lower end AMD non GCN cards and lower end GCN cards that don&#39;t have at least 2GB ram. This prevents mass adoption and using GPUs that probably already paid for themselves, but can function in areas where electricity is cheap/free.

The new ArQmA daemon also allows true multi thread mining on the CPU. From non AES architectures to the latest threadrippers. It is considered a bit more greener than regular Cryptonight CN0 or CN7/8 algorithms since it uses less CPU cycles to mine by a factor of almost 2-2.5 depending on the comparisons of benchmarked hashrates.

ArQmA&#39;s POW, as stated previously, is more CPU friendly, and more ASIC resistant. In addition, when an ASIC was successfully developed for the CryptoNight algorithm, the Monero developers did not quickly move to fork the blockchain to regain ASIC resistance.
Some Monero and CryptoNight plain algorithm pool operators discovered in early 2018 that ASICS were deployed before release to the public. The transition to v7, then v8 forks/algorithm changes were slow.  Also, the manufacturers of ASICS were selling used equipment as new and the peak return on investment had mostly passed when finally the new ASIC models were released to the public.

ArQmA took note of this event and will ensure to make the necessary changes to their coin to stay resistant to ASICS, and the arbitration of Nicehash in a more timely manner.
ArQmA has three different possible technologies of defeating FPGA based mining manipulation .  One is including floating point math which would require the ASIC like nature of FPGA streams to interrupt their workflow and require a CPU or GPU thread to compute the solution.
Another method is including a java based random code blob to be executed, which would require a CPU thread to slow down or break single FPGA applications with streams that are not adaptable.  Thirdly, just changing the algorithm itself is enough to send the stream developers of FPGA to consider it not profitable to mine an ever changing situation.

Even if ArQmA decides to change algorithms, it will be extremely fast, completed in weeks instead of months, and support the profitable miners that are decentralized.



## 3.5.3 General Usability and Transactions-Per-Second

Zcash improved upon Bitcoin by doubling the maximum block size to 2 MB, and decreasing the block interval down to 2.5 minutes. However the transaction size is larger in Zcash, so the maximum TPS will only reach about 26, and could be far less if more of the transactions happen to be shielded. As with Bitcoin, the TPS throughput will need to be increased into the thousands before Zcash will become a currency used by the masses.

See section 3.1 vs. Bitcoin for a description of ArQmA,s solution to the TPS limitation.

## 3.6 vs. Ripple

Of all the currencies discussed in this section, Ripple is one which may not belong. The Ripple blockchain is open source. But Ripple is also a private company. From their homepage: &quot;Ripple connects banks, payment providers, digital asset exchanges and corporates via RippleNet to provide one friction less experience to send money globally.&quot; Consider the ways in which Ripple&#39;s vision is different from ArQmA:

- Ripple does not decentralize the management of personal wealth; it seeks to strengthen the ability of central entities to control the movement of wealth on a global scale.

- Working with banks, Ripple does not provide privacy, but instead provides full traceability of funds.

- There is no mining process, by which individuals can receive coins for themselves. All coins have been produced, and the Ripple company releases a certain number of coins per month.

Ripple might be determined a security and might be controlled and legislated against by certain Governments that wish to ban or manipulate which coins are allowed withing their sphere of influence. Also, the banks spread out through the world may decide to de list or not list Ripple in certain parts of the world which might prevent mass adoption.

## 4 ArQmA Implementation

The implementation of ArQmA is derived from two other open source projects: CryptoNote and Monero. Additional code has been added by two main developers, and three engineers developers who also do support.  The motto is in short, &quot;If you want something done right, do it yourself.&quot;

The CryptoNote technology focuses on the ability to create crypto-currencies with untraceable transactions, CPU—friendly Proof of Work(POW)  algorithm, and the ability of self adjusting parameters such as block size and difficulty. Several crypto coins have been based on the CryptoNote technology.

Monero is one of the earliest crypto currencies to use the features of CryptoNote, and has grown to be the most popular with a market cap well within the top 20 crypto coins. ArQmA was started from the Monero code base, and modified only in ways that meet the specfic vision and goals of the ArQmA community.

This section will provide an overview of the implementation of the ArQmA cryptocurrency.

## 4.1 Achieving Trustless Transactions

One of the goals for ArQmA transactions is to have the properties of physical cash payments, as opposed to electronic payments.

Consider the example of paying for a meal at a restaurant. With electronic payment (i.e. a credit card), there is a trusted 3rd party (i.e. Visa) which carries out the transaction for the payer and receiver. The trusted party must know both the payer&#39;s and receivers identities and account information to settle the transaction. Additionally, the receiver may also receive the payer&#39;s name and partial account information.

In contrast, paying for a meal with cash is trustless (requires no trusted 3rd party to carry out the transaction). It is also anonymous in that it does not require the payer to give their name or any other personal information to the receiver.

To achieve trustless. decentralized transactions, ArQmA utilizes a proof of work &quot;mining&quot; process. For a definition of POW, the Bitcoin Wiki at https://en.bitcoin.it/wiki/Proof\_of\_work offers this:

&quot;A proof of work is a piece of data which is difficult (costly. time—consuming) to produce but easy for others to verify and which satisfies certain requirements. Producing a proof of work can be a random process with low probability so that a lot of trial and error is required on average before a valid proof of work is generated.&quot;

The goal of the proof of work process, is to provide decentralization of both the distribution of coins and the validation of transactions. The difficult trial—and—error nature of producing the POW is an effective means of randomizing which miner will create and correctly validate the next block of transactions, and receive the reward of new coins. This randomization ensures that the processing of transactions is spread indiscriminately over the entire network.

A disadvantage of the POW function for many cryptocurrencies (including Bitcoin) is that it relies solely on processor speed, which allows high—end GPU,s and specialized mining hardware (ASICs) to have a great advantage in producing the correct proof of work. This condition leaves the majority of PC owners unable to participate in the mining process for coins, and creates an environment where relatively few miners control the network. Thus, the goal of decentralization is somewhat defeated.

An improved POW algorithm, eventually called CryptoNight, was proposed in 2012 by the CryptoNote project. According to the CryptoNote white paper ([https://cryptonote.org/whitepaper.pdf](https://cryptonote.org/whitepaper.pdf))

&quot;Our primary goal is to close the gap between CPU (majority) and GPU/FPGA/ASIC (minority) miners. It is appropriate that some users can have a certain advantage over others, but their in vestments should grow at least linearly with the power. More generally, producing special purpose devices has to be as less profitable as possible.&quot;

The CryptoNight algorithm accomplishes this goal in 2 primary ways.

a It uses built—in CPU instructions, which are difficult to implement in specialized hardware.

It relies on access to unpredictable locations in a 2 MB &quot;scratchpad&quot; of CPU memory, rather than relying solely on CPU processing speed.

These factors effectively limit the advantages of GPU,s over CPU,s and make it too costly to produce specialized ASIC hardware for mining.

For its proof of work, ArQmA implements a variation of this algorithm, called CryptoNight—Lite.

As the name suggests, this is a lightweight version of the original algorithm, which utilizes a 1 MB scratchpad. This results in half the iterations needed to compute a hash, and half the required L3  cache CPU memory. Many lower end processors (on mobile devices) will have the required 1 MB of CPU cache, and multi—core CPU processors will see up to a 4X performance boost over the heavier CryptoNight algorithm.
Many other CPU only based coins have blossomed over the simplicity of mining with a faster algorithm using less resources (cores, CPU cycles, cache amount, iterations). Therefore it is perceived as &quot;greener&quot; mining using less electricity.

## 4.2 Achieving Anonymous Transactions..Open Alias Support.

The previous section explained how the POW algorithm creates a decentralized trustless network of miners to process transactions. To achieve anonymity. The payer&#39;s and receivers identities and account (wallet) information must be kept hidden on the public blockchain.

This is achieved in a two fold process with ArQmA. One is the standard number of mixins for fake transactions listed on the block explorer is set to a minimum of seven.

Also the number of levels of Ring CT is enforced so that there are no public transactions.

Open Alias can be used where a short, DNS style name can be recorded and set within the DNS SEC resolver instead of a typical 109 character payee address. By typing in the open alias address in the payment address field, then clicking on &#39;resolve address&#39;, it will lookup the full payment address of the user you wish to send to. This is helpful for labeling brand name e-commerce stores and locations by branch number.

For example:
A customer wishes to send funds to specific branch #321 of a store called &quot;Bob&#39;s Burger&quot;.
Bob&#39;s Burger can have the accounts registered for public use to eliminate confusion.
The Open Alias address could be &quot;[Bobburger321@arqma.com](mailto:Bobburger321@arqma.com)&quot; instead of a long address like,

&quot;ar34szdgR9WhapJASiMyGU2dtQz993TK9Y3ZAeFTLDC5LY2tu2kqR1YbXqKu3buoQfFSUGexxKcxNazUSJN272f52eNenP5zp&quot;.

However, this is convenient, but lacks privacy on the receiver&#39;s side. The receiver can change the registration to provide obfuscation, or provide a similar integrated address instead.

## 4.2.1 One-Time-Use Keys

ArQmA uses the CryptoNote solution to receive payments at a one—time—use public key address, rather than the recipients public wallet address. The public key is generated by the sender, using both the recipients public wallet address and some random data. Once generated, funds are sent directly to this public key, which can be used only once. The recipient can later spend any received coins, by using a one—time—use private key (called a ring signature) which corresponds to the one—time public key.

The following picture, from the CryptoNote white paper, shows that the one—time public keys are never linked to the receivers public wallet address on the blockchain. This effectively keeps the receiving wallet anonymous.

## 4.2.2 One-Time Ring Signatures

After funds are received via a one—time public key, the recipient is able to spend the funds at any time, using a one—time ring signature. The goal of the ring signature is to keep the sending address anonymous on the blockchain.

In non-private implementations. the sender will &quot;sign&quot; their payment transaction with a private key that can be validated only by using the senders corresponding public key. Only the sender knows the private key, but the whole world can see that the senders public key was used to validate the transaction.

The idea behind the ring signature is straightforward: a sender produces a signature which can be validated by a set of public keys rather than a unique public key. The identity of the one who produced the signature is indistinguishable from the owners of the additional public keys within the set.

Consider an example: Bob wishes to send 5 ArQmA to Kim. The picture below shows the ring signature concept for this transaction on the blockchain, using a default ring size of 3.

Note in the example, that the 2 &quot;decoy&quot; public signatures are actually past transaction outputs that are pulled from the ArQmA blockchain. Thus, all 3 inputs in the set are valid signed inputs for 5 ArQmA, but only Bob&#39;s is valid for this transaction. It is impossible for someone looking at this transaction on the blockchain to determine which of the 3 inputs was the valid one. Additionally, all 3 of the inputs will likely show up as decoys in multiple other transactions.

In the ArQmA blockchain, the total number of inputs. known as the ring size, is set to 7 by default. The sender may choose a different ring size for their transaction, and the selection of each decoy input is handled automatically by ArQmA. More than 3 inputs will result in a higher level of anonymity, but will require a higher transaction fee.

Lower priority transactions will be processed with a slightly lower fee.

## 4.2.3 Known Weaknesses

One possible attack against anonymity is analysis based on the amounts sent in a transaction.
The Aeon coin allows 10% of the transaction to be public. Which can expose a trail to follow or exclude from searches of the blockchain.
If a bad actor knows, for example, that 0.9 coins have been sent at a certain time, then they may search for transactions containing 0.9 coins to attempt to identify a sender. This is negated by the use of one—time keys and other factors, but the visibility of the amounts on the blockchain is a downside. But by using explicitly forced ring CT level of 7, this method is thwarted.

Furthermore, as seen in the illustration in the previous section, the ring signature approach requires the specific  amount of each of the inputs to match. For less common amounts, there will be fewer public keys available for decoys, reducing the level of anonymity.

The Monero development team has created a solution for these weaknesses, known as Ring Confidential Transactions (RingCT), which will obscure transaction amounts on the blockchain.  The ArQmA community has adopted this solution

There are more details on the new RingCT protocol in the Monero publication &quot;Ring

Confidential Transactions.&quot; (See https://lab.getmonero.org/pubs/MRL—0005.pdf.)

Also, the bulletproof RingCT level we use currently is simple Bulletproofs.

Bulletproof is a very recent protocol allowing to dramatically reduce the size of proofs of interval used in Monero to ensure every value manipulated is positive without revealing it.

## 4.3 Coin Minting Process

As mentioned in section 4.1 Achieving Trustless Transactions. new ArQmA coins are distributed over time, to mining applications (called nodes), as a reward for calculating the correct Proof Of Work. This section will focus on the details of the coin distribution process.
We have added many security procedures to new daemon as well to wallets.

After a while you will not be able to see balance either blockchain height while refreshing without putting in the wallet password.

But password is shadowed and console listening is off.  This help prevent hackers from gaining access through surveillance of your machine tactics on some levels. Everything is made in memory which is wiped straight after you press enter.

All keys (private and public) are coded all the time and keys files are locked.

Keys are become decoded and unlocked only while needed and no data is stored on any drive

All is made in memory on-the-fly and after pressing Enter memory is wiped.

## 4.3.1 Block Creation

One of the main functions of the mining node is to validate transactions as they are submitted to the network. For a transaction to be valid, it must pass several checks. The transaction must be properly formatted. The coins being spent must be &quot;signed&quot; by the valid owner of the coins. Also the coins being spent must not have already been spent by their owner in a previous transaction (a double spend). As the node receives and validates transactions, it places them together in a collection, called a block.

As mentioned earlier in this paper, ArQmA implements an algorithm to automatically adjust the

allowed block size up or down, based on the previous 100 blocks. This effectively allows miners

to include more transactions in each block when the network transaction rate requires it. Miners are not allowed to increase their block size indiscriminately, and are assessed a reward penalty if they create a block larger than the median size. Twice the median size is the largest block allowed. The reward penalty is calculated by the following formula:

The reward penalty is calculated by the following formula: P enalty = BaseReward ∗ ((BlockSize M ) − 1)2 where BaseReward = the current block reward BlockSize = the size of the new block M = median block size for last 100 blocks Governing the block size is necessary, to keep the transaction processing speed uniform across all nodes in the network.

where

BaseReward = the current block reward, in this case 20 for ArQmA

BlockSize = the size of the new block

M = median block size for last 100 blocks

Governing the block size is necessary, to keep the transaction processing speed uniform across all nodes in the network.

## 4.3.2 Block Time Interval and related difficulty adjustment

A single block of ArQmA transactions is added to the public blockchain once every 4 minutes, on average. This timing must be ensured by constantly adjusting the difficulty of the Proof Of Work calculation. Otherwise the addition of more miners to the network would result in calculating the correct POW faster than the desired 4 minutes.

After a mining node assembles a single block of valid transactions, it races with other nodes to calculate the correct POW. The node which calculates the correct POW will broadcast its block to the other nodes it knows about, and they will also validate the entire block of transactions. Each node that accepts the block as valid will add the block to its copy of the public ArQmA blockchain, then broadcast the block to other nodes, and begin assembling a new block. This continues until all the network nodes add the block.

The proposed block time will be 120 seconds in version 0.2. on the next fork.

The main issue is getting the difficulty adjustment algorithm, currently version 2, to behave within a range of not over swinging to too low of a difficulty in intermittent spikes of the opposite adjustment.  When the over swing occurs from a deliberate increase of hash rate with mining with Nicehash or a solo pool operator, then they time the window to cease hashing at peak difficulty to cause the drop to be below the lowest average difficulty in a window of N number of blocks. The rapid rise of hash rate instantly does not necessarily need to be a \&gt;51% hashrate attack, but commonly is used in tandem.

Zawy12, a developer who has been optimizing the difficulty algorithm has been collecting real time data sets on the performance of Cryptonight coins. Currently ArQmA uses his LWMA version 2 and will likely implement version 4.

## 4.3.3 Block Reward

When a mining node calculates a correct POW and adds a block to the blockchain, it includes a transaction of new coins, paid to its own mining wallet. This payment of new coins is known as the block reward. The number of coins in the block reward decreases with each block on a smooth curve, known as the emission curve. Each reward is calculated based on the following elliptical curve  formula.

Since the current supply of coins (A) increases with every new block, each successive reward will decrease by a small fraction of a coin. The reward continues to decrease until it equals  XX ArQmA per block. At that time, the initial emission curve will end, and the tail emission reward (ArQmA for each 2 minute block) will begin. The tail is estimated to begin in the  time frame of 20xx(year)


ArQmA launches:

- June 14; 2018.

- Block time = 4 minutes for blocks 2-65000(est) .

- At V10 fork, the block time is 2 minutes. Estimated 12/14/2018.

ArQmA forks:

Block 7000:
 12/14/2018 V10 Fork 2 minute block time.

Tail emission begins

June 14, 2049. Reward = ~.42 ArQmA per block solved.

## REWARD AND COIN SPECIFICATIONS

Initial ARQ reward was 20.26 subtracted from the curve amount computed.
Block 1 included the 7.5 Million ARQ pre mine.

- PoW algorithm: CryptoNight-Lite PoW

- Max supply: ~50 million

- Block reward: ~20 smoothly varying

- Block time: 240 seconds, going to 120 seconds at V10 Fork approx 12/14/2018.

- Difficulty: Re-targets at every block using LWMA2 and possibly another modification to v4.

- Block confirmation: 18 blocks, upon release of V 0.2.0 this will be 10 blocks

- Properly set 1MB Scratchpad to eliminate time-waste hashing by trying to divide into a 2MB
- Scratchpad like other projects had done.

- Asic resistance : Yes

- Nicehash resistance: Yes

- BulletProof RingCT  levels from standard 7 to 41 possible.

- LWMA Difficulty Algorithm securing network against 51% hash attacks, level 3 is coming.

- Ticker: ARQ

- Emission rate planned on 30 years

- Minimum mixins 6 and in v 0.2 the minimum goes to 10.

- Ring CT minimum 7.  Maximum 41.

- Simple Ring CT Bulletproofs transaction recording for now and we will implement full  -Bulletproofs later.

- ArQmA uses tx version 2 for transactions whereas ring CT 0 was tx version 1.

Note that the tail emission has no defined end, and provides an initial  inflation rate of less than

1%. During this phase, the rate of inflation decreases as the supply of coins grows by a constant 15,.680 ArQmA per year. By the year 20xx, there will be roughly XX million coins in total.

## 4.4 Transaction Fees

For every transaction, the sender must pay a transaction fee in addition to the coins sent. This

fee is paid to the miner who successfully calculates the POW. Thus, the miner receives the Block Reward plus the sum of all transaction fees that were included in the block.

The transaction fee will be higher if the sender increases the priority of the transaction. This

higher transaction fee will cause the mining nodes to prefer it when selecting transactions for the next block. Therefore, a transaction&#39;s priority, and consequently the speed at which it gets processed, is tied directly to its transaction fee.

The transaction fee will also be higher for transactions that contain more data, since the base fee is calculated on a per—kilobyte basis. (This increase does not impact the priority.) The amount of data in a transaction increases in the following scenarios:

The ArQmA wallet application also optimizes the money sent to the smallest number of transactions to reduce the size of the data that gets combined into each block.  The transactions from client wallets are smaller in footprint to be sent to the mempool of the blockchain.

0 The amount sent consists of many small amounts that the sender received

0 The sender increases the level of privacy, by requesting a higher ring size than the default

Note on transaction fees, block size, and transaction throughput:

When creating a block of transactions, if the sum of the transaction fees are greater than the block size penalty, miners are likely to increase the number of transactions combined in a block. This approach allows the ArQmA blockchain to self-adjust its processing speed as transaction traffic changes over time, while also creating a dynamic market for transaction fees.

## 5 ArQmA Community

## 5.1 Links

## 5.1.1 Social/Community

Website: https://arqma.com/

BitcoinTalk ANN: https://bitcointalk.org/index.php?topic=4474605.0

Youtube channel: https://www.youtube.com/channel/UC24ZbH8J1SKpxmdakIJotoA

Discord invite: https://discord.gg/s9BQpJT

Github: https://github.com/Arqma (source, binaries, wallets, explorer, pool)

IRC:  To be determined

Medium blog: https://medium.com/@arqma

Reddit: https://www.reddit.com/r/arqma/

Telegram: https://t.me/joinchat/HNpOMRIiNSoCn0zYrAOofw

Twitter: [https://twitter.com/ArQmA\_Network](https://twitter.com/ArQmA_Network)

## 5.1.2 Block Explorers

ArQmA block explorer: https://blocks.arqma.com

ArQmA Pool Statistics: [https://pools.arqma.com](https://pools.arqma.com/)

Android pool status monitor for Android at: https://play.google.com/store/apps/details?id=com.arqma.poolmonitor

## 5.2 Mining

Any miner application that can mine cryptonight-lite algorithm variant1, (also described as aeon7 by XMR-STAK miner as the &quot;currency type&quot;) can mine ArQmA with pools or solo with a standalone node.

## 5.2.1 Mining Applications

The most popular mining applications are xmr-stak and xmrig. For additional options, check with the community. There is a ArQmA mining standalone application based on a fork from Stellite GUI Miner. It is not required to use it, but does display and operate all the typical controls of xmr-stak,xmrig, and has status information from the API interface at ArQmA, and commonly helpful links to check into updates of ArQmA.

The ArQmA GUI wallet application for desktops and tablets can mine on a local setting with the new function of the correct number of threads.
It is technically possible to mine on mobile devices, but at an extreme usage of battery and low hash rate below even pre-AES capable desktop CPUs.

The GUI wallet is available on Windows, Linux, Mac OS desktops, and soon the iPhone. There is also a pool status monitor available for Android.
All of these tools are available on the main ArQmA download section at: [https://arqma.com/download/](https://arqma.com/download/)

There is a generic java based web miner application out there that is not sponsored, supported, or supervised by ArQmA that also mines other types of Cryptonight coins also. It is inefficient and may have security concerns of stealing hash rate or identity information. It is not advised by the founders or support to use it.

## 5.2.2 Mining Pools

There are several ArQmA mining pools operating. It is recommended to join a small to medium sized pool, to spread out the hash rate across the network as much as possible. Look on the community Links to current ArQmA mining pools. https://arqma.com/pools-explorer/

The main issue as with many coins, is that miners should spread the hashrate to prevent centralization of any pool more than 30-50% of the total. The instant returns on joining a large pool is possible, but diluted when you consider a miner&#39;s share of the total is less.

Using probabilistic rotation , one could rotate through all the pools with mining and obtain the same overall luck and effort to obtain rewards and blocks for each pool. The longer you mine, the more average this becomes.

## 5.3 Exchanges

Tradeogre : [https://tradeogre.com/](https://tradeogre.com/)

Crex24: https://crex24.com/

Visit the ArQmA website to find a current list of exchanges which trade ArQmA.

## 5.4 Wallets

ArQmA web wallet for instant creation for mining and transactions: [https://myarqma.com](https://myarqma.com/)

ArQmA Offline wallet generator, great for generating a mining address immediately: [https://generate.arqma.com/](https://generate.arqma.com/)

ArQmA GUI is the official GUI wallet for the core ArQmA implementation.
Supports Windows, Linux, Mac OS platforms: [https://arqma.com/download/](https://arqma.com/download/)

ArQmA Android Wallet is a light mobile wallet for Android which connects to a remote node of your choosing, and supports QR code scanning: [https://arqma.com/download/](https://arqma.com/download/)

The ArQmA Command Line Interface wallet that comes with the ArQmA node daemon, wallet, RPC wallet, blockchain import/export tools:

[https://github.com/arqma/arqma/releases](https://github.com/arqma/arqma/releases)

Available for download at: [https://arqma.com/download/](https://arqma.com/download/)

## 5.5 Development Team

Lead developers: ArqTras and Michal vel Malbit

Contributing developers: SmajeNz0, Bob, Argonator,

Graphic Design : UNI\_The\_Great

## 5.6 Current Work and Future Plans
The ArQmA payment gateway for sending payments under ten seconds is nearing completion:

A video demonstration here at: https://www.youtube.com/watch?v=rBPyQQFwt\_w


## 5.6.1 Work In 2018-2019  Roadmap:

Core Development:

- Implemented RingCT logic. This is an improvement to ring signatures which also obscures the amount of a transaction on the blockchain.

- Implemented the Bulletproofs improvement to RingCT. This will drastically reduce transaction sizes, making the blockchain more scalable.

- Reformatting and replacing code that allows more cross compiling to the platforms Android and iPhone.

- Automated night builds of code as updates and patches are applied.

Community Work:

-  Pay with ArQmA , payment gateways for popular eCommerce systems

- ArQmA API interface for transactions with eCommere integration.

- Various ArQmA How-To, WIKI

## 5.6.2 Future Plans

-  Community-funded marketing. Some marketing by founders.

- Additional exchange listings.

-  Additional ArQmA integrated services.

## Road Map

Quarter 3 2018

-Development of the Application Program Interface (API), mobile wallets for Android and iPhone.

-Development and testing of a payment gateway which will confirm transactions in 2-10 seconds conservatively.  Realistically it will be on the lower end of that time span.

-With great passion we give you all the opportunity to create the future expanse of ArQmA. All ideas are welcomed as we peruse the best possible block chain solution.

Quarter 4 2018
-Release of mobile wallets for Android and iPhone finalized.
Speed up synchronization and upload / download values increased for the 2p2 network.
DNS SEC enforced on code using static builds from source. This disallows modified code to be ran on the main net, as each node checks each other&#39;s versions. A moderate form of anti tampering is included within the code for consistency checking.

The blockchain database will be migrated from v2 to v3.

Unlocked daemon mining threads for GUI integral to all the daemons also.

WALLET

All keys are stored, encrypted and locked, when needed are unlocked in memory (on-the-fly) and after use just wiped from memory.

Password refresh need password each time.

The fork will be announced when all the tests are passed and code locked in. This is a hard fork, meaning that all users will have to update to the latest version or you will not be able to connect, transfer, or solo mine. Pool operators will have to update for their miners to work. The exchanges will have the upgrade ready on that date.

As always, we have a pool operators channel on discord for coordination in real time on that day. Also, tests will be done with exchanges before the execution of the fork.

Quarter 1 2019

-Marketing expansion along with team growth, we will also bring to you an online store and mobile app wallets.

-Integration with banking systems to provide instant payment transactions with zero to minimal fees.  The founders plan to form a LTD company if necessary to meet regulations and contract with them. Subject to legal changes that appear to be possible at this time since other coins have successfully done so already.

Quarter 2 2019

Media and promotional rewards to expand the name brand and social awareness of ArQmA.

Quarter 3 2019
Website improvements along with upgrades to the network, security, and block chain.

Quarter 4 2019

To be determined by community and founders.

## 5.7 Network design and redundancy.

The ArQmA network is comprised of several layers of high speed 1Gbit networks, that utilize several different internet service providers to give redundant availability across the internet.

There are several remote nodes in the US, EU, and Japan.
DDOS and network attack protection by Cloudflare.  Prepaid for a year in advance from the premine, going forward.

The DNS records and DNS SEC keys are recorded and has four principle holders of passwords and access in case of a disaster.

There is a disaster recovery plan. The ArQmA community of four developers have access to the coin network controls, passwords, and keys.

## 5.8 Github repository report and sources of original code.

Initial commit of Monero import and modifications.  Most of which were done at the same time of the first Green diamond, see red for subtraction of code. This is not just copying and pasting code. It was security mods, name changes, comments, commits of hooks for cross compiling.

Commits to Project by line count up to Devils Touch 1.2.6. ( put in update to 1.30 or v 2 later)
Further coding and additions ongoing.
Also pull requests and updates from Monero and other coins as judiciously evaluated and tested before merged. Web wallet back end was first based on Open Monero, was found wanting, and the Masari web wallet was code modified and debugged for use as myarqma web wallet.

Public release branch: https://github.com/arqma

Original Sources:

Monero base code: [https://github.com/monero-project/monero](https://github.com/monero-project/monero)
Cryptonote base code:[https://github.com/topics/cryptonote](https://github.com/topics/cryptonote)
Open Alias code: [https://github.com/arqma/openalias.rs](https://github.com/arqma/openalias.rs)

DNS proxy code for Open Alias: https://github.com/arqma/dnscrypt-proxy
