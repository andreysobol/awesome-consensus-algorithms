# Awesome Consensus Algorithms

## Problems

- [Byzantine generals problem](https://en.wikipedia.org/wiki/Byzantine_fault), [The real Byzantine Generals](https://www.researchgate.net/publication/4122503_The_real_Byzantine_Generals)
- [Fault tolerance](https://en.wikipedia.org/wiki/Fault_tolerance)

## Limitations:
- [A Simple Bivalency Proof that t-Resilient Consensus Requires t + 1 Rounds](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.22.402&rep=rep1&type=pdf)

## Synchrony models

- [Synchrony, Asynchrony and Partial synchrony](https://decentralizedthoughts.github.io/2019-06-01-2019-5-31-models/)

## Algorithms

### The Byzantine Generals Problem
- [The Byzantine Generals Problem](https://dl.acm.org/doi/pdf/10.1145/357172.357176)

### Completely Asynchronous Agreement Protocols
- [Another Advantage of Free Choice: Completely Asynchronous Agreement Protocols](https://allquantor.at/blockchainbib/pdf/ben1983another.pdf)

### An Efficient Algorithm for Byzantine Agreement without Authentication
- [An Efficient Algorithm for Byzantine Agreement without Authentication](https://groups.csail.mit.edu/tds/papers/Lynch/dffls-ic.pdf)

### The Part-Time Parliament
- [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)

### Raft

### An Optimal Probabilistic Algorithm for Byzantine Agreement
- [An Optimal Probabilistic Algorithm for Byzantine Agreement](http://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Distributed%20Computation/An%20Optimal%20Probabilistic%20Algorithm%20for%20Byzantine%20Agreement.pdf)

### PBFT
- [PBFT](https://pmg.csail.mit.edu/papers/osdi99.pdf)
- [Practical Byzantine Fault Tolerance and Proactive Recovery](https://pmg.csail.mit.edu/papers/bft-tocs.pdf)

### Q/U protocol
- [Fault-Scalable Byzantine Fault-Tolerant Services](https://www.pdl.cmu.edu/PDL-FTP/PASIS/sosp05.pdf)

### Uniform consensus
- [Uniform consensus is harder than consensus](https://infoscience.epfl.ch/record/88273)

### Trusted Timely Computing Base
- [The Design of a COTS Real-Time Distributed Security Kernel](https://navigators.di.fc.ul.pt/archive/ttcb-edcc.pdf)
- [How to Tolerate Half Less One Byzantine Nodes in Practical Distributed Systems](https://www.gsd.inesc-id.pt/~mpc/pubs/correia_m_sma.pdf)

### On Expected Constant-Round Protocols for Byzantine Agreement
- [On Expected Constant-Round Protocols for Byzantine Agreement](https://eprint.iacr.org/2006/065.pdf)

### Efficient Synchronous Byzantine Consensus
- [Efficient Synchronous Byzantine Consensus](https://arxiv.org/pdf/1704.02397.pdf)

### Nakamoto Consensus 
- [Bitcoin: A Peer-to-Peer Electronic Cash System](https://bitcoin.org/bitcoin.pdf)
- [The Bitcoin Backbone Protocol: Analysis and Applications](https://eprint.iacr.org/2014/765.pdf)
- [The Bitcoin Backbone Protocol with Chains of Variable Difficulty](https://eprint.iacr.org/2016/1048.pdf)
- [Analysis of Nakamoto Consensus](https://eprint.iacr.org/2019/943.pdf)
- [But Why Does it Work? A Rational Protocol Design Treatment of Bitcoin](https://eprint.iacr.org/2018/138.pdf)
- [Analysis of the Blockchain Protocol in Asynchronous Networks](https://eprint.iacr.org/2016/454.pdf)

### Honey Badger BFT

- [The Honey Badger of BFT Protocols](https://eprint.iacr.org/2016/199.pdf)

### Byzantine Agreement, Made Trivial
- [Byzantine Agreement, Made Trivial](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Distributed%20Computation/BYZANTYNE%20AGREEMENT%20MADE%20TRIVIAL.pdf)

### BABE/GRANDPA

### HotStuff and Libra
- [HotStuff: BFT Consensus in the Lens of Blockchain](https://arxiv.org/abs/1803.05069)
- [State Machine Replication in the Libra Blockchain](https://cryptorating.eu/whitepapers/Libra/libra-consensus-state-machine-replication-in-the-libra-blockchain.pdf)
- [DiemBFT v4: State Machine Replication in the Diem Blockchain](https://developers.diem.com/papers/diem-consensus-state-machine-replication-in-the-diem-blockchain/2021-08-17.pdf)

### Ouroboros family
- [Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol](https://eprint.iacr.org/2016/889.pdf)
- [Ouroboros-BFT: A Simple Byzantine Fault Tolerant Consensus Protocol](https://eprint.iacr.org/2018/1049.pdf)
- [Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake blockchain](https://eprint.iacr.org/2017/573.pdf)

### Hashgraph
- [The Swirlds hashgraph consensus algorithm: Fair, fast, byzantine tolerance](https://www.researchhub.com/paper/337/the-swirlds-hashgraph-consensus-algorithm-fair-fast-byzantine-fault-tolerance)
- [Verifying the Hashgraph Consensus Algorithm](https://arxiv.org/pdf/2102.01167.pdf)

### Avalanche
- [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV)
- [Scalable and Probabilistic Leaderless BFT Consensus through Metastability](https://assets.website-files.com/5d80307810123f5ffbb34d6e/6009805681b416f34dcae012_Avalanche%20Consensus%20Whitepaper.pdf)

### DAGs

## Distributed randomness

### Classics
- [Coin Flipping by Telephone](http://users.cms.caltech.edu/~vidick/teaching/101_crypto/Blum81_CoinFlipping.pdf)
- [An Optimally Fair Coin Toss](https://eprint.iacr.org/2009/214.pdf)

### Commit reveal
- [Randao](https://github.com/randao/randao)
- [Economically Viable Randomness](https://arxiv.org/pdf/2007.03531.pdf)

### Shamir's Secret Sharing
### Threshold cryptography
### VRF:
 - [Wikipedia](https://en.wikipedia.org/wiki/Verifiable_random_function)
 - [Micali, Rabin, Vadham (1999)](https://dash.harvard.edu/bitstream/handle/1/5028196/Vadhan_VerifRandomFunction.pdf)
 - [A verifiable random function with short proofs and keys](https://eprint.iacr.org/2004/310.pdf)
 - [Verifiable Random Functions from
Standard Assumptions](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.738.9975&rep=rep1&type=pdf)
 - [Derandomization in Cryptography](https://dash.harvard.edu/bitstream/handle/1/41467486/86374%2010.1.1.91.2701.pdf)
 - [Verifiable Random Functions from Non-interactive Witness-Indistinguishable Proofs](https://link.springer.com/article/10.1007/s00145-019-09331-1)
### VDF
 - https://vdfresearch.org/
### PoW
 - http://hashcash.org/
 - https://bitcoin.org/bitcoin.pdf
 - (add diffreent hashes)

## All possible selection approach
- PoW
- PoS
- DPoS
- Proof Of Space

## Attacks
- Long range attacks: [A Survey on Long-Range Attacks for Proof of Stake Protocols](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8653269)
- Selfish mining: [Majority is not Enough: Bitcoin Mining is Vulnerable](https://arxiv.org/abs/1311.0243)
- [Why buy when you can rent? Bribery attacks on Bitcoin-style consensus](https://jbonneau.com/doc/BFGKN14-bitcoin_bribery.pdf)
- [On Stake and Consensus](https://download.wpsoftware.net/bitcoin/pos.pdf)
- [Distributed Consensus from Proof of Stake is Impossible](https://download.wpsoftware.net/bitcoin/old-pos.pdf)