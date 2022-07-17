# Mastering Block-chain
- **Author:** Imran Bashir
- **Genre:** Block-chain, Web-3, Crypto

# Types of consensus mechanisms
All consensus mechanisms are developed to deal with faults in a distributed system and to allow distributed systems to reach a final state of agreement. 

There are two general categories of consensus mechanisms. These categories deal with all types of faults . These common types of consensus mechanisms are as follows:

- **Proof-based consensus mechanisms:** This arrangement requires nodes to compete in a leader-election lottery, and the node that wins proposes the final value.

	The algorithm works on the principle of providing proof of some work and the possession of some authority or tokens to win the right of proposing the next block. 

- **Traditional fault tolerance-based:** With no compute-intensive operations, such as partial hash inversion, this type of consensus mechanism relies on a simple scheme of nodes that publish and verify signed messages in a number of phases. Eventually, when a certain number of messages are received over a period of rounds, then an agreement is reached

- **Fail-stop faults:** This type of fault occurs when a node merely has crashed. Fail-stop faults are the easier ones to deal with of the two fault types.

	Paxos or the RAFT protocol, introduced earlier in this chapter, are normally used to deal with this type of fault. These faults are simpler to deal with.

- **Byzantine faults:** The second type of fault is one where the faulty node exhibits malicious or inconsistent behavior arbitrarily. This type is difficult to handle since it can create confusion due to misleading information. This can be a result of an attack by adversaries, a software bug, or data corruption.

#Block-chain #Web3 #Panaverse #Books #mastering-block-chain 