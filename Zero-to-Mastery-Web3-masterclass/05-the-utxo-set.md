# The UTXO set

A block-chain is a perfect example of an distributed ledger. Each block in the block-chain only stores the amount of money that was transferred or received. It doesn't keep track of the total amount of money a person has.

The program that allows us to compute the ledger and everyone's balance in bitcoin is called the **unspent transaction output set** or the **UTXO** for short. The UTXO is an extra set of data that lives alongside the block-chain and tells us that who own what at the current moment. It does this by keeping track of the unspent bitcoins users have in thier wallets.

The UTXO set is also maintained by the same computers that represent the bitcoin block-chain.

The UTXO set is used by bitcoin and other block-chains that are based on bitcoin or are similar. Meanwhile, Ethereum uses a different approach.

Ethereum uses a state database. This database is similar to the UTXO set but is more simpler and flexible but doesn't provide that much privacy as much as the UTXO set.
