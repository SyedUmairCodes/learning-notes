# Mastering Block-chain
- **Author:** Imran Bashir
- **Genre:** Block-chain, Web-3, Crypto

# Generic elements of a block-chain
Elements of a generic block-chain are many and are described here one by one.

-  **Address:** Addresses are unique identifiers used in a block-chain transaction to denote senders and recipients. An address is usually a public key or derived from a public key.
- **Transaction:** A transaction is the fundamental unit of a block-chain. A transaction represents a transfer of value from one address to another.
- **Block:** A block is composed of multiple transactions and other elements, such as the previous block hash (hash pointer), timestamp, and nonce. Blocks are composed of a block header and a selection of transactions bundled together and organized logically. A block contains several elements, which we introduce as follows
	 
	 A reference to a previous block is also included in the block unless it is a genesis block. This reference is the hash of the header of the previous block.
	- A **Genesis** block is the first block in the block-chain that is hard coded at the time the block-chain was first started. The structure of a block is also dependent on the type and design of a block-chain.
	- A **Nonce** is a number that is generated and used only once. A nonce is used extensively in many cryptographic operations to provide replay protection, authentication, and encryption. In block-chain, it's used in proof-of-work consensus algorithms and for transaction replay protection. A block also includes the nonce value. 
	- A **Timestamp** is the creation time of the block.
	- **Merkle root** is a hash of all of the nodes of a Merkle tree. In a block-chain block, it is the combined hash of the transactions in the block. Merkle trees are widely used to validate large data structures securely and efficiently. 
	   Merkle root in a block-chain is present in the block header section of a block, which is the hash of all transactions in a block. This means that verifying only the Merkle root is required to verify all transactions present in the Merkle tree instead of verifying all transactions one by one. 
	   
	- In addition to the block header, the block contains transactions that make up the block body. A transaction is a record of an event, A block contains transactions and its size varies depending on the type and design of the block-chain.

- **Peer-to-peer network:** As the name implies, a peer-to-peer network is a network topology wherein all peers can communicate with each other and send and receive messages. 

- **The scripting or programming language:** Scripts or programs perform various operations on a transaction in order to facilitate various functions. 
  
  Think of the scripting language as a calculator that only supports standard pre-programmed arithmetic operations. As such, the Bitcoin Script language cannot be called "Turing complete."

- **Virtual machine:** This is an extension of the transaction script. A virtual machine allows Turing complete code to be run on a block-chain (as smart contracts); whereas a transaction script is limited in its operation. However, virtual machines are not available on all block-chains. 

    Various block-chains use virtual machines to run programs such as Ethereum Virtual Machine (EVM) and Chain Virtual Machine (CVM).
	EVM is used in the Ethereum block-chain, while CVM is a virtual machine developed for and used in an enterprise-grade block-chain called "Chain Core." 

- **State machine:** A block-chain can be viewed as a state transition mechanism whereby a state is modified from its initial form to the next one by nodes on the block-chain network as a result of transaction execution.

- **Smart contracts:** These programs run on top of the block-chain and encapsulate the business logic to be executed when certain conditions are met. 
	
	These programs are enforceable and automatically executable. The smart contract feature is not available on all block-chain platforms, but it is now becoming a very desirable feature due to the flexibility and power that it provides to block-chain applications.
	
	 Smart contracts have many use cases, including but not limited to identity management, capital markets, trade finance, record management, insurance, and e-governance.

- **Node:** A node in a block-chain network performs various functions depending on the role that it takes on.
	A node can propose and validate transactions and perform mining to facilitate consensus and secure the block-chain.  Nodes can also perform other functions such as simple payment verification (lightweight nodes), validation, and many other functions depending on the type of the block-chain used and the role assigned to the node.
	
	Nodes also perform a transaction signing function. Transactions are first created by nodes and then also digitally signed by nodes using private keys as proof that they are the legitimate owner of the asset that they wish to transfer to someone else on the block-chain network.
	
	This asset is usually a token or virtual currency, such as Bitcoin, but it can also be any real-world asset represented on the block-chain by using tokens.
	
	There are also now standards related to tokens; for example, on Ethereum, there are ERC20, ERC721, and a few others. 

#Block-chain #Web3 #Panaverse #Books #mastering-block-chain 