Every line of code represents an ethical and moral decision
Grady Booch, at QConSF 2018 (attributed by Martin Charette, @cinq, 6 Nov 2018)

It's important to know the performance cost of the data structures you use. For example, insertion into a regular linked list has a cost of O(1). But add a cryptographic hash to every link, and an insertion can cost 1 MWh. #blockchain #Bitcoin
Kevlin Henney, https://twitter.com/KevlinHenney/status/1036998948177801218

## A Blockchain ...
  ... is a digital ledger in which transactions are recorded chronologically (and publically)
  ... is an immutable, sequential chain of records. They're chained together using hashes
  ... is a (public) database where new data is stored in blocks, where each block also encodes information about the previous block. The blocks are, therefore, chained together - hence blockchain.
In the cryptocurrency case, the data is transactions moving coins between addresses, but the data can be anything. 
Blobs of data joined together one to the next is that hoary old interview canard, the linked list. 
The transaction data is, typically, stored in a merkle tree. 

## Merkle Tree
A tree in which every leaf node is labelled with the hash of a data block and every non-leaf node is labelled with the cryptographic hash of the labels of its child nodes. Hash trees allow efficient and secure verification of the contents of large data structures. A Merkle tree is recursively defined as a binary tree of hash lists where the parent node is the hash of its children, and the leaf nodes are hashes of the original data blocks. 


## Proof of work
The goal of PoW is to discover a number which solves some problem. The number must be **difficult to find but easy to verify** (computationally speaking) by anyone on the network. 

_Mining: computers shouting random numbers at each other until one of them guesses today’s secret number. That’s numberwang!_ https://singletrackworld.com/forum/topic/can-someone-explain-crypto-mining/ Singletrack is a cycling website

_Even now, really, almost no one understands how this freewheeling digital toy based on computers shouting random numbers at each other actually works._
https://www.ft.com/content/a9e0f3fa-f47f-11e8-ae55-df4bf40f9d0d
