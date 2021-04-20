# OpenSourceBlockchain


What is blockchain?

Essentially, blockchain technology acts as a structure that stores transactional records (block) in several databases (chain) in a network connected with nodes and hence, the name "blockchain." It is a system of recording information that makes it difficult or even impossible to edit, hack, or duplicate. This is done so through decentralization and cryptographic hashing.

An easy way of thinking about this is by comparing it to a Google Doc. When creating a google document, you can distribute it to others without having to make a copy or transferring access to the doc. This acts as a decentralized chain as everyone has access to the document at the same time. All modifications to the document are being recorded live-time and it is transparent. On the other hand, a word document would not suffice with this analogy. For a word document, you will need to save the file and transfer it to another party and then the other party will have their own copy. 

A blockchain is a database that stores encrypted blocks of data then chains them together to form a chronological single-source-of-truth for the data
Digital assets are distributed instead of copied or transferred, creating an immutable record of an asset
The asset is decentralized, allowing full real-time access and transparency to the public
A transparent ledger of changes preserves integrity of the document, which creates trust in the asset.
Blockchain’s inherent security measures and public ledger make it a prime technology for almost every single sector

3 concepts: Blocks, Nodes, Miners

Blocks: Each chain consists of many blocks and each block consists of data, nonce, and a hash. A nonce is a 32-bit whole number that is randomly generated once a block is created and as a result, it generates a block header hash. This hash is a 256-bit number that is attached to the nonce and must start with many zeroes (VERY small number)

Nodes: Since no one computer can create a chain, it has to be distributed and the nodes are what connects the chain. It maintains copies of blockchain and keeps it functioning. Every node has a copy of entire blockchain and the network algorithmically approves new blocks that are then updated and trusted. 

Miners: This is what creates new blocks on the chain. Since every block has its own unique nonce and hash but also references hash of previous block in chain, mining becomes very hard, especially in large chains. To solve these complex mathematical problems, softwares such as Sisense and Alteryx come into play and they are tools that help find a nonce that generates an accepted hash. To put it into perspective, there are 4 billion possible nonce-hash combinaotrs and when the right one is found, it is called the "golden nonce" and the block is added to the chain. To add the block to the chain successfully, it requires re-mining not just the block with the change but all of the blocks that come after. 

Use cases of blockchain:
  Voting mechanisms (voting fraud issue)
  Advertising Insights
  Cryptocurrency Exchange
  Music royalties tracking
  Personal identity security


What is hyperledger fabric?

Hyperledger Fabric was initiated by IBM and Digital Asset but currently hosted by Linux Foundation. 

One type of blockchain framework includes Hyperledger fabric. It is a modular blockchain framework that is a foundation for developing products, solutions, and application components for private enterprises. Since Hyperledger Fabric is private and requires permission to access, businesses can extract information and transactions can be sped up as # of nodes in network is reduced. 

The point of Hyperledger fabric is to support private transactions and confidential contracts which traditional blockchain networks cannot do. This supports memberships based on permission and as a result, all network participants have a known identity.

Participants on network have 3 distinct roles:
  Endorser: Transactional proposal submitted to endorser 
  Committer: After sufficient endorsements by endorser, blocks of transaction are delivered to committer where they validate endorsement policy was followed and there are no conflicting transactions.
  Consenter: Once both checks are made, the transactions are committed to consenter
  
Modular Architecture of Hyperledger Fabric:
  Smart Contracts (Chaincode): distributed logic processing and agreement of system
  Transaction Ordering
  Transaction Validation/Commitment

Use cases of hyperledger fabric

Many business sectors, such as healthcare and finance, are bound by data protection regulations that mandate maintaining data about the various participants and their respective access to various data points. Fabric supports such permission-based membership.

Real-Life Scenario: Suppose there's a manufacturer that wants to ship chocolates to a specific retailer or market of retailers (i.e., all US retailers) at a specific price but does not want to reveal that price in other markets (i.e., Chinese retailers).

Since the movement of the product may involve other parties, like customs, a shipping company, and a financing bank, the private price may be revealed to all involved parties if a basic version of blockchain technology is used to support this transaction.

Hyperledger Fabric addresses this issue by keeping private transactions private on the network; only participants who need to know are aware of the necessary details. Data partitioning on the blockchain allows specific data points to be accessible only to the parties who need to know.

What is carbon credits?

A rather overloaded term, “carbon credits” can refer to both government-issued credits traded on regulated markets, and voluntary carbon offsetting where credits can help remove emissions via projects that plant trees, for instance. Blockchain technology has been touted as a way to prevent the double counting (or double spending) of carbon credits in all areas and markets.

Each blockchain-based UPCO2 token represents a certified measure of carbon dioxide.
Today, the retail market for voluntary carbon credits – via sites like TerraPass or Cool Effect – allow access, but not holding or trading, which is the important distinction, said Thieriot.
There are currently two types of carbon credits: (1) voluntary emissions reduction (VER): a carbon offset exchanged in the over-the-counter or voluntary market for credits, (2) certified emissions reduction (CER): emission units (or credits) created through a regulatory framework with the purpose of offsetting a project's emissions.
The foundations for Blockchain are rooted in the ability to achieve a consensus of distributed parties
Recently, free automated market makers (AMMs) have been developed on blockchains allowing for the trading of digitized assets directly on the Blockchain without intermediary and minimal algorithmic fees.


