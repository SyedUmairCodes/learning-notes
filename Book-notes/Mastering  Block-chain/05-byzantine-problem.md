# Mastering Block-chain
- **Author:** Imran Bashir
- **Genre:** Block-chain, Web-3, Crypto

# Byzantine generals problem

The inconsistent behavior of Byzantine nodes can be intentionally malicious, which is detrimental to the operation of the network.

Any unexpected behavior by a node on the network, whether malicious or not, can be categorized as Byzantine. The Byzantine Generals problem In 1982, a thought experiment was proposed by Lamport et al in their research paper, The Byzantine Generals Problem, which is available [here]( https://www.microsoft.com/en-us/research/publication/ byzantine-generals-problem/) 

In this problem, a group of army generals who lead different parts of the Byzantine army is planning to attack or retreat from a city. The only way of communicating among them is via a messenger. They need to agree to strike at the same time in order to win. The issue is that one or more generals might be traitors who could send a misleading message. 

Therefore, there is a need for a viable mechanism that allows for agreement among the generals, even in the presence of the treacherous ones, so that the attack can still take place at the same time.

As an analogy for distributed systems, the generals can be considered honest nodes, the traitors as Byzantine nodes (that is, nodes with arbitrary behavior), and the messenger can be thought of as a channel of communication among the generals. 

This problem was solved in 1999 by Castro and Liskov who presented the Practical Byzantine Fault Tolerance (PBFT) algorithm, which solves the consensus problem in the presence of Byzantine faults in asynchronous networks by utilizing the state machine replication protocol. PBFT goes through a number of rounds to eventually reach an agreement between nodes on the proposed value.

#Block-chain #Web3 #Panaverse #Books #mastering-block-chain 