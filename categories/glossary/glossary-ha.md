---
title: 用語集
taxonomy:
    category:
        - glossary
---

### 日本一充実したビットコイン用語集を作りたい！

[River Financial の Bitcoin Glossary](https://river.com/learn/terms/) をベースに、日本語のビットコイン用語集を構築中です。用語集作りに参加して、**ビットコイン**を稼ぎませんか？

以下の英語の用語説明を日本語にしてください。忠実な翻訳でなくて構いません。AI翻訳にかけて内容を理解した上で、ご自身の言葉で説明してください。

日本語の提案はGitHubでプルリクエストとして受付中。プルリクエストがマージされたら、報酬をライトニング⚡️送金します。<br>
提案手順は[こちら](https://github.com/lostinbitcoin/categories/wiki)の「2. 用語集の用語説明の提案手順」をご参照ください。

--
### ビットコイン用語集

### 索引 <a id="ha"></a>は

|  用語  |  英語表記  |  説明  |  報酬  |
| ---- | ---- | ---- |---- |
|<a id="hash_function"></a>ハッシュ関数| Hash Function|There are many instances of cryptographic hash functions, but all cryptographic hash functions share a few key properties. All cryptographic hash functions take an input, called a preimage, and produce an output, called a hash or digest, of a fixed length. This length varies based on the precise function used. The output of a cryptographic hash function is deterministic. For a given input, the output will always be exactly the same. A cryptographic hash function is a one-way function. An output can easily be calculated from an input. However, there is no known way of determining the input from a given output. The output is random and unpredictable. There is no known method for targeting a specific output and calculating the proper input. Nor can a relationship be drawn between a series of inputs and their outputs. For example, if an input of 100 characters is changed by a single character, the new output bears no resemblance to the old output. These properties make cryptographic hash functions very useful for Bitcoin. Hashing is random and uncontrollable, ensuring Bitcoin mining is a fair competition. Hashing a public key or a script to obtain an address provides superior security, privacy, and convenience for users. Hashing transactions and blocks provides a simple way of creating universally unique IDs for both transactions and blocks. Finally, Merkle Trees use hashing to create reliable, immutable summaries of all transactions in a block, making mining and block verification significantly more efficient. Bitcoin only uses a few hash functions for its various aspects. The hash function SHA-256 is used for creating Proofs-of-Work, and SHA-256 is applied twice to generate txids. In order to generate public key hashes or addresses, the hash160 function is used. This is a combination of the SHA-256 and RIPEMD160 hash functions.|2,100 sats  |
|<a id="hash_rate"></a>ハッシュレート| Hash Rate |Hash rate is a measure of how many hashes miners cumulatively produce per second on the Bitcoin network. A single hash is an attempt to create a Proof-of-Work for a block, and billions of these attempts are made per second by miners around the world. The hash rate indicates how much money, energy, and computing power is being dedicated to processing transactions and securing the network. Hash rate is also an indication of how much a 51% attack on the network would cost. Since a 51% attack requires a malicious miner to control at least 51% of hash rate, the higher the hash rate, the more prohibitively expensive it is for any miner to launch such an attack. Bitcoin’s hash rate has been growing rapidly over the past decade as Bitcoin’s price appreciation incentivizes more miners to join the network. Hash rate is influenced by several factors, including Bitcoin’s price, energy prices and available quantities, local weather, and regulatory environments.|2,100 sats  |
|<a id="batching"></a>バッチ|Batching|Batching involves consolidating multiple payments into a single transaction with many outputs. Because Bitcoin fees are paid based on how much data the transaction uses, combining multiple transactions into a single transaction can lower data overhead and thus save on fees. For example, if Alice wants to pay Bob 0.5 BTC, Charlie 0.3 BTC, and David 0.2 BTC, she can create a transaction with a 1 BTC input and 3 outputs instead of creating 3 transactions with 2 outputs each—one for the payee and one for change output. The advantages of batching increases with scale. For example, an exchange wishing to serve 100 client withdrawal requests can either submit 100 transactions, or a single transaction with 100 different outputs. The latter option will offer significant fee savings.|2,100 sats  |
|<a id="hardware_wallet"></a>ハードウェアウォレット| Hardware Wallet|A hardware wallet is a digital device whose sole purpose is to generate and store public and private keys and sign transactions. Hardware wallets allow users to send and receive Bitcoin in a secure fashion. Hardware wallets are a form of cold storage, meaning that they allow a user to keep their private keys safely disconnected from the internet. Most hardware wallets implement BIP 32 and BIP 39 standards, meaning they use Hierarchical Deterministic wallets and mnemonic phrases. Like all wallets, different hardware wallets vary in terms of security, privacy, and reliability.|2,100 sats  |
|<a id="hard_cap"></a>ハードキャップ|Hard Cap|Bitcoin total supply will never exceed 21 million bitcoin or 2.1 quadrillion satoshis. The hard cap is what guarantees Bitcoin’s absolute scarcity and protects Bitcoin from the fate of many fiat currencies in the past and present—hyperinflation.|2,100 sats  |
|<a id="hard_fork"></a>ハードフォーク|Hard Fork|A fork generally is a change to a project’s source code. Bitcoin is an open-sourced project, meaning that anyone can access, download, or alter the source code without permission. A hard fork specifically is a consensus change that is not backwards compatible. Backwards incompatibility occurs when a previously invalid behavior is made valid. In order to maintain consensus across a hard fork, all nodes are required to upgrade. Otherwise, old nodes will reject transactions or blocks as invalid under the old rules, while upgraded nodes will accept them as valid. For this reason, hard forks are avoided at all costs in Bitcoin.|2,100 sats  |
|<a id="halving"></a>半減期|  Halving | The halving is an event which reduces the issuance rate of bitcoin by half every four years. Bitcoin’s issuance schedule is precisely defined by an algorithm in Bitcoin’s code. This algorithm allows a certain amount of new bitcoin to be minted in each block, as compensation for the miner of the block.This new bitcoin is called the block subsidy, and at Bitcoin’s inception, it was 50 BTC per block. However, the subsidy is cut in half in an event called the halving, which takes place every 210,000 blocks—roughly every four years. This process will continue until the subsidy reaches zero, by which time over 7 million blocks will have been mined across 34 halvings. |2,100 sats  |
|<a id="p2p"></a>ピアツーピア（P2P）|Peer-to-Peer (P2P)|A peer-to-peer network is one in which members can interact directly with one another without relying on third parties for approval or support. Bitcoin is a peer-to-peer network because nodes connect directly to one another and relay transactions and blocks. Additionally, Bitcoin users can transact in a peer-to-peer fashion because ownership of bitcoin is passed directly from sender to receiver. Even though miners process transactions, they never take custody of the bitcoin, and are never able to redirect a transaction to steal funds from users. Peer-to-peer systems are usually resistant to censorship and corruption, and Bitcoin is a prime example. Tens of thousands of peers in the Bitcoin network run nodes in order to validate the blockchain and maintain Bitcoin’s decentralization. A peer-to-peer financial system is fundamentally different from Venmo, PayPal, or ACH or wire transfers, where corporations, banks, and governments can interfere with, censor, or roll back payments without a user’s permission. While the majority of users trust these legacy institutions enough to use them, Bitcoin removes the need to trust a third party at all.|2,100 sats  |
|<a id="bft"></a>ビザンチン障害耐性|Byzantine Fault Tolerance (BFT)|Byzantine Fault Tolerance (BFT) is a trait of decentralized, permissionless systems which are capable of successfully identifying and rejecting dishonest or faulty information. Byzantine fault tolerant systems have successfully solved the Byzantine Generals Problem and are robust against sybil attacks. In a decentralized, permissionless system, anyone can join the network and start broadcasting information. Without Byzantine Fault Tolerance, any member of a network could feed invalid information to a network and undermine the reliability of the network. In the context of Bitcoin, a node can easily join the network and start broadcasting blocks and transactions. For example, a node could broadcast two transactions spending the same bitcoin—a double spend. Thus, Bitcoin needs a way for nodes to determine the validity of data they receive from other nodes. Bitcoin is Byzantine Fault Tolerant because every node can verify every transaction and block independently and in an objective way. If a node broadcasts invalid blocks or transactions, all other nodes will recognize and reject them, preventing invalid transactions from entering the blockchain. Bitcoin’s rules are objective because the validity of transactions and blocks is never ambiguous.|2,100 sats  |
|<a id="byzantine_generals_problem"></a>ビザンチン将軍問題|Byzantine Generals Problem|The Byzantine Generals Problem describes the difficulty decentralized parties have in arriving at consensus in a game theoretically safe manner. To solve this problem, all parties must agree on a method of trustlessly determining truth. The game analogy used is that several generals are besieging Byzantium. They have surrounded the city, but they must collectively decide when to attack. If all generals attack at the same time, they win, but if they attack at different times, they lose. The generals have no secure communication channels with one another because any messages they send or receive may have been intercepted or sent by Byzantium’s defenders. Bitcoin solves the Byzantine Generals Problem by implementing a Proof-of-Work mechanism. Blocks are deemed valid by all members of the network only if they contain a valid Proof-of-Work in the form of a valid hash. This allows decentralized nodes to agree on a specific blockchain in a trustless manner. This hash does not prove anything about a block other than the fact that work was expended to produce it. However, the work required to produce a block discourages miners from producing invalid or empty blocks, which would spam the network. Miners are additionally incentivized to create valid blocks by the block reward—the new bitcoin they are allowed to mint and the transaction fees they collect.|2,100 sats  |
|<a id="bitcoin"></a>ビットコイン|Bitcoin|Bitcoin is a peer-to-peer cryptocurrency based on a Proof-of-Work consensus mechanism and a decentralized ledger called a blockchain. Satoshi Nakamoto announced Bitcoin on October 31, 2008 and the network launched on January 3, 2009. Bitcoin has a limited supply of 21 million bitcoin and a fixed emission schedule. Every four years, Bitcoin’s inflation rate is cut in half, and it will eventually be reduced to zero. This trait makes Bitcoin unique among currencies; the supply of all other currencies is growing constantly, unpredictably, and boundlessly. Bitcoin also has no central controller. Instead of a single database which provides data to users, all users maintain identical copies of the database, called the blockchain. This blockchain records all transactions made on the Bitcoin network, allowing users to independently verify their balances and transaction history. Bitcoin’s blockchain is append-only, meaning new blocks can be added but old blocks cannot be removed or altered. Since Bitcoin is both a protocol and a currency, the way it is capitalized depends on the context. Bitcoin with a capital B is used to refer to the network and the asset class, while bitcoin with a lowercase b is used to refer to the coin, which is transferred in Bitcoin transactions and has a market price.|2,100 sats  |
|<a id="bitcoin_core"></a>ビットコインコア|Bitcoin Core|Bitcoin Core is the reference implementation for the Bitcoin source code, meaning all other implementations look to Bitcoin Core for guidance on maintaining consensus and upgrading. This is where most users go to download the source code. Bitcoin Core provides software for both a node and a wallet, although most users prefer to use Bitcoin Core for its node and use third party software for their wallet. There are alternatives to Bitcoin Core’s node software, but Core is the dominant implementation. Anyone wishing to download Bitcoin’s software and run a node can access Bitcoin Core via their website or their GitHub page. Bitcoin Core was created by Satoshi Nakamoto, and although ownership has been passed down and many upgrades have been added to the project, the latest version and Satoshi’s original version are still compatible. Bitcoin Core is an open source project. This means that anyone can copy the source code and edit it as they see fit. If a developer wants to improve Bitcoin, they can publish the changes they have made and propose that their changes be included in Bitcoin Core. Many developers choose to contribute to Bitcoin Core through code, review, and discussion. However, there is no authoritative entity that pays developers to work for Bitcoin Core. Instead, Bitcoin companies and individuals partially fund these developers through donations and grants.|2,100 sats  |
|<a id="bip"></a>ビットコイン改善提案 (BIP)|Bitcoin Improvement Proposal (BIP)|A Bitcoin Improvement Proposal (BIP) is a formal proposal to change Bitcoin. Upgrades and security improvements enter the Bitcoin codebase via BIPs. Upgrades such as SegWit, HD Wallets, PSBT and more were all introduced via BIPs, which then underwent a review process and community discussion before being accepted. However, not all BIPs propose code changes. Some, such as BIP 39’s standard of mnemonic phrase backups, establish standards to be used by other Bitcoin related projects. Smaller changes to Bitcoin, such as bug fixes, code refactoring, or minor efficiency improvements are not included in BIPs. Rather, these changes are submitted directly to Bitcoin’s codebase as proposed code changes.|2,100 sats  |
|<a id="bitcoin_implementations"></a>ビットコイン実装|Bitcoin Implementations|A Bitcoin implementation is a software program that is capable of running a Bitcoin node and interacting with the Bitcoin network. There are several different implementations of Bitcoin, written in various programming languages. Because Bitcoin is an open source project, anyone can copy and alter its code or replicate its functionality. This strenghthens rather than harms Bitcoin’s security and utility. Each implementation offers slightly different features and design, but all implementations must agree on the consensus rules in order to keep the Bitcoin network unified. For example, implementations can use different wallet and transaction types or coin selection and fee estimation schemes, but they must all enforce the same rules with regards to which blocks, transactions, and signatures are valid. While there are many different implementations, Bitcoin Core, the original implementation created by Satoshi Nakamoto in 2008, is by far the most dominant. Other implementations include Libbitcoin, Bitcoin Knots, and bcoin.|2,100 sats  |
|<a id="bitcoin_node"></a>ビットコインノード|Bitcoin Node|A node is a discrete member of a network which interacts with other nodes to form the network. A Bitcoin node is any computer that runs a Bitcoin implementation and stores the entire blockchain. Nodes validate, broadcast, and request new blocks and the mempool to and from peers in the network. If nodes run compatible software, consensus is achieved. Node count is vital to protecting the network from malicious or haphazard source code changes, reorganizations, and other protocol changes.|2,100 sats  |
|<a id="private_key"></a>秘密鍵|Private Key|A private key is used to send bitcoin which was received by the corresponding public key. When bitcoin is sent to a public key, only a signature produced by the private key can spend that bitcoin. Private keys must be kept safe, as only private keys can create the signatures required to spend bitcoin. Public keys, on the other hand, can be distributed publicly. A Bitcoin wallet is normally used to generate and safely store private keys. Wallets also help users sign transactions using the appropriate private keys. While a private key is used to derive the public key, the public key cannot be used to reveal the private key. This kind of one-way function is what makes cryptography so useful for Bitcoin and many other fields.|2,100 sats  |
|<a id="pow"></a>プルーフオブワーク（PoW）|Proof-of-Work (PoW)|Proof-of-Work is a method for asserting the validity of data. Bitcoin miners must submit Proof-of-Work in the form of a valid hash in order to have their block be considered valid. Proof-of-Work forces miners to expend large amounts of energy and money into producing blocks, incentivizing them to stay honest, thereby securing the network. Proof-of-Work is one of the only ways a decentralized network can agree on a single source of truth, an imperative trait for a monetary system. Miners generate a Proof-of-Work by producing a block whose hash is smaller than a set target. A hash is a randomly generated 64-digit number, so miners must generate billions of hashes to find one that is smaller than the target. This target is dynamically set by Bitcoin’s source code. As more miners join the network, the target is lowered, making it harder for miners to find a hash lower than the target. If miners leave the network, the target is raised, making it easier for miners to find a valid hash. The algorithm that recalculates the target ensures that Bitcoin blocks are found on average every 10 minutes.|2,100 sats  |
|<a id="block"></a>ブロック|Block|A block is a collection of transactions that occur on the Bitcoin network. These blocks are linked together chronologically to form a blockchain. Most Bitcoin blocks include around 2700 transactions and can be up to 4MB in size. A block can only be added to the blockchain if it has a hash that satisfies Bitcoin’s Proof-of-Work requirement and includes the previous block’s hash. The inclusion of the previous block’s hash in a block ensures that no block can be altered without invalidating subsequent blocks. This trait is due to the nature of hash functions, which are deterministic and random. This system gives Bitcoin immutability. For example, if a transaction in Block #400 is altered, the hash of Block #400 will change, invalidating the Proof-of-Work for Block #400, but also making Block #401 invalid, because Block #401’s “previous hash” parameter no longer matches the hash of Block #400. This change will ripple forward, disconnecting all blocks after Block #400. This feature ensures that once a block is added to the blockchain neither it nor any transactions included within it can be altered.|2,100 sats  |
|<a id="block_explorer"></a>ブロックエクスプローラ|Block Explorer|A block explorer is a service that allows anyone to browse and query the blockchain. Bitcoin’s blockchain is publicly accessible to all. Tens of thousands of nodes maintain full copies of the exact same blockchain, allowing them to verify any transaction or block and prove their Bitcoin balances. A block explorer allows those who do not run a node to do the same and in a simpler way. These benefits come at the cost of potential loss of privacy and the need to trust a third party. Most block explorers exist as websites, which may collect data linking your IP address, physical location, and the Bitcoin addresses you queried. Some block explorers allow users to use their service locally with their own node, bypassing the aforementioned privacy leaks. Try out Blockstream's Explorer to browse a complete list of Bitcoin blocks and transactions. You should avoid looking up your own addresses in order to preserve your privacy.|2,100 sats  |
|<a id="block_size"></a>ブロックサイズ|Block Size|The block size describes the amount of data which a block is allowed to take up, measured in bytes. Miners are not allowed to create a block with more data than the block size limit allows for, limiting the number of transactions miners can fit in each block. This limit is in place to ensure the blockchain does not grow too rapidly in size, which would prevent average individuals from being able to maintain and query the blockchain. The block size limit is also the reason miners collect transaction fees based on the data size of the transaction. Miners are attempting to maximize the total fees they can collect per block. Before SegWit activation, Bitcoin blocks were strictly limited to being at most 1MB. After SegWit, blocks are measured by weight rather than size. The maximum possible size of a block post-SegWit is now 4 MB.|2,100 sats  |
|<a id="block_height"></a>ブロック高|Block Height|A blockchain is a collection of blocks linked together in an immutable, chronological order. Beginning at zero with the Genesis block, all blocks are numbered in ascending order. This number is known as a block’s height. The current block height is simply the number of blocks in the blockchain minus one. Block height can be used as a reference to a point in time within a blockchain. For example, Bitcoin halvings occur at specific block heights (every 210,000 blocks). Additionally, special Bitcoin transactions can be timelocked until a certain block height.|2,100 sats  |
|<a id="blockchain"></a>ブロックチェーン|Blockchain|A blockchain is the foundational data structure behind Bitcoin. As its name suggests, a blockchain is a list of blocks. Each of these blocks contains data. In Bitcoin’s case, each block contains transactions created when one party sends bitcoin to another. The blockchain can be thought of as a digital ledger that keeps track of every account on the network. The entire blockchain is the book that stores the record of every transaction that has ever taken place on the network. Each block, then, is like a new page added to the ledger to update the state of accounts on the network. Bitcoin’s blockchain is public, and thousands of nodes store identical copies of it, making it a decentralized ledger. One special property of a blockchain is that it is immutable. Once a block is added to the blockchain, it is difficult to alter it. As more and more blocks are added on top, changing the original block becomes ever more difficult until it is practically impossible.|2,100 sats  |
|<a id="block_subsidy"></a>ブロック報酬|Block Subsidy|The block subsidy is the amount of new bitcoin minted in each block. Each block that is produced and added to the blockchain allows the creator of the block to mint a certain amount of new bitcoin. This amount is strictly determined by an algorithm in Bitcoin’s source code: the subsidy started at 50 BTC per block, and is cut in half every 210,000 blocks or roughly 4 years. The block subsidy is how new bitcoin enters into circulation, but it also incentivizes miners to remain honest and submit valid blocks. The block subsidy is paid out in the coinbase transaction of each block. This special transaction is the first transaction in every block, and it has no inputs. The output of a coinbase transaction cannot be spent for 100 blocks, so miners can only spend their block subsidy after a 100 block cooldown. Each block contains many transactions, each with fees attached to incentivize their confirmation. The sum of the block subsidy and cumulative transaction fees in a block yield the block reward. Because the block subsidy falls by half every four years, transaction fees will slowly begin to make up most and then all of the block reward.|2,100 sats  |
|<a id="immutability"></a>不変性|Immutability|Bitcoin maintains a high level of immutability on two levels. Firstly, Bitcoin’s consensus protocol is resistant to change, and the core aspects of the protocol, most importantly Bitcoin’s strict monetary policy, can never be changed. This immutability is enforced by the tens of thousands of Bitcoin nodes who independently run the same code and agree to the same ruleset. No single party, neither miners, nor governments, is able to change Bitcoin’s consensus rules without convincing these tens of thousands of nodes to agree to their proposed changes. This immutability gives institutional and retail investors faith in Bitcoin’s scarcity and longevity. Secondly, Bitcoin’s blockchain is immutable in the sense that its history cannot be easily rewritten. This allows merchants to trust Bitcoin payments more easily than fiat payments. Bitcoin’s blockchain is append-only, meaning that once a block is embedded in the chain, it is practically infeasible to remove or alter it. This makes Bitcoin’s history immutable. This property is enforced by the SHA-256 hash function. When a miner hashes a block hoping to find a valid hash, the hash of the previous block is included in that block. Thanks to the properties of a hash function, if the hash of the previous block changes, this will change the current block’s hash, invalidating the Proof-of-Work and thus the entire block. For example, if the blockchain has 500 blocks, Block #400’s hash will include Block #399’s hash. If a single piece of Block #399 is altered, Block #399’s hash will change, causing Block #400’s hash to change and so on, all the way until Block #500. Every block after #399 will be invalidated. This trait prevents anyone from altering a block once it is part of the blockchain without completely rebuilding the blockchain. Bitcoin’s immutability is neither absolute nor unassailable. If an attacker were to control a majority of all computing power on the bitcoin network, they could alter past blocks in what is called a 51% attack. It is imperative that Bitcoin maintain a significant and decentralized hash rate in order to keep the cost of such an attack beyond the means of any entity.|2,100 sats  |
|<a id="protocol"></a>プロトコル|Protocol|A protocol is governed by a set of rules which define the behavior of a network. The Bitcoin protocol has many rules dictating its use, similar to a constitution. Rather than relying on a central entity like a Supreme Court or a CEO, all nodes in the Bitcoin network enforce the entire ruleset. The Bitcoin protocol uses a blockchain based on Proof-of-Work and a token (bitcoin) in order to establish a peer-to-peer monetary network.|2,100 sats  |
|<a id="fiat_currency"></a>法定通貨|Fiat Currency|Fiat currency is money that is declared to have value despite a lack of intrinsic value. An item has intrinsic value if it still has value if it isn’t being used as a form of money. Creating a fiat currency requires a central authority to control the currency and maintain its supply. Most modern governments use fiat currency as the primary money of their economy. An alternative to fiat currency is commodity money. Commodity money is an asset with intrinsic value that is also used as a form of currency. This is commonly an asset that can be consumed or used for construction. However, commodity money is generally harder to transact with due to inferior portability, divisibility, or durability. Finally, a currency could be representative money. Representative money does not have intrinsic value on its own, but it can be exchanged for something that does. For example, a currency that can be exchanged for barley would be representative money.|2,100 sats  |
|<a id="fork"></a>フォーク|Fork|A fork is a change to a protocol or a piece of code. Forks are usually introduced to upgrade a project. In the open source community, forks exist because many individuals choose to download and run the same software at different times and do not always update. If two users download and run version 1 of a software, and only one user upgrades when version 2 is released, the user who updated is running a fork of version 1. This could become a problem in a system like Bitcoin, where consensus is critical to knowing how much money one has. If nodes run different software with different rulesets, some nodes may approve of some transactions or blocks while other nodes do not. The network would fracture, and the ultimate truth upon which the Bitcoin network agrees, the decentralized ledger, would be destroyed. This is why Bitcoin development must remain cautious and conservative. There are essentially two types of forks: soft forks and hard forks. Soft forks do not break compatibility between the old version and the new version and thus do not require all nodes to upgrade; they are backwards compatible. Hard forks are not backwards compatible and thus require all nodes to upgrade. Hard forks are avoided at all costs within the Bitcoin community, while soft forks are strongly preferred. When a project experiences a hard fork, and many members choose to follow the fork while many others do not, a network can split in two. This has occurred several times as projects have attempted to branch off from Bitcoin and change consensus rules. These rogue projects are called forks, but they are no longer a part of the original Bitcoin project or network. While forks cause social friction and confusion, they do not harm the Bitcoin network on a protocol level.|2,100 sats  |
|<a id="hot_wallet"></a>ホットウォレット|Hot Wallet|The term hot describes a device with external connections, especially to the internet. A hot wallet is a Bitcoin wallet which connects to the internet. These wallets are more convenient for day-to-day spending, but are not as secure as cold storage options because they interact with the internet. Anything which interacts with the internet may be targeted by malware from the internet. For large stacks of bitcoin, it is safer to keep your wallet disconnected from the internet for as much time as possible.|2,100 sats  |
|<a id="bolt"></a>ボルト (BOLT)|Basis of Lightning Technology (BOLT)|The Basis of Lightning Technology (BOLT) are specifications that describe the consensus rules and standards of the Lightning Network. The standards established by the BOLTs allow different Lightning implementations such as LND and c-lightning to integrate and form a network. As the Lightning Network continues to develop, the BOLTs are adapted and improved.|2,100 sats  |
|<a id="whitepaper"></a>ホワイトペーパー|Whitepaper|A whitepaper introduces a new idea or topic for discussion. The Bitcoin whitepaper introduced Bitcoin as a “Peer-to-peer electronic cash system” which “required no trusted third parties”. Satoshi Nakamoto released the whitepaper on October 31, 2008 to an email list of cryptographers and cypherpunks. You can read the full whitepaper here.|2,100 sats  |

---
コンテンツの著作権は [River Financial](https://river.com/) に帰属します。二次利用の可否は権利者にご確認ください。 / All rights reserved to River Financial.