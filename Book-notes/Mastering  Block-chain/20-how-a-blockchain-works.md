# Mastering Block-chain
- **Author:** Imran Bashir
- **Genre:** Block-chain, Web-3, Crypto

# How a block-chain works
Nodes are either miners who create new blocks and mint cryptocurrency (coins) or block signers who validate and digitally sign the transactions.

A critical decision that every block-chain network has to make is to figure out which node will append the next block to the block-chain and this is done through a consensus who's steps are as follows:
-  **Transaction is initiated:** A node starts a transaction by first creating it and then digitally signing it with its private key. A transaction can represent various actions in a block-chain. Most commonly, this is a data structure that represents the transfer of value between users on the block-chain network.

	Transactions are usually either a cryptocurrency transfer (transfer of value) or smart contract invocation that can perform any desired operation.

-  **Transaction is validated and broadcast:** A transaction is propagated (broadcast) usually by using data-dissemination protocols, such as Gossip protocol, to other peers that validate the transaction based on preset validity criteria. Before a transaction is propagated, it is also verified to ensure that it is valid.
- **Find new block:**  When the transaction is received and validated by special participants called miners on the block-chain network, it is included in a block, and the process of mining starts.
- **New block found:** Once a miner solves a mathematical puzzle , the block is considered "found" and finalized. At this point, the transaction is considered confirmed. 

	Usually, in cryptocurrency block-chains such as Bitcoin, the miner who solves the mathematical puzzle is also rewarded with a certain number of coins as an incentive for their effort and the resources they spent in the mining process.

- **Add new block to the block-chain:** The newly created block is validated, transactions or smart contracts within it are executed, and it is propagated to other peers. Peers also validate and execute the block. It now becomes part of the block-chain (ledger), and the next block links itself crypto-graphically back to this block. This link is called a hash pointer.

#Block-chain #Web3 #Panaverse #Books #mastering-block-chain 