#  Complete-blockchain-nanodegree-program 
These are the resources that helped me to understand the core concept of block chain
https://anders.com
#Hashvalue-It is a digital fingerprint for information
#Hashing function-Maps a group of data to a unique hash value
Data-Hashing functiion-Hash
Blockchain-Shared digital ledger that records a list of transactions.
Transactions---->Blocks
Blockheader-
Previous 
Blocks Hash
Time(
Merkle Root 
Nonce
BlockData + Nonce =Hash value
These are the two papers that will help you to know about blockchain
bitcoin.org/bitcoin.pdf
A hash is a digital fingerprint for information
Hashing function-Maps a group of data to a unique hash value




Data --->Hashing function-->Hash
           (SHA256)
           SHA is the hashing algorithm while 256 is the outcome

Blockchain framework:-

Transaction-Wallet-Signature-Mempool-Network-Concsensus-Hashing-Block-Blockchain
  `


Block is a container that holds a list of transactions to be added to the blockchain
Shared digital ledger that records a list of transactions


Transactions
-
-
-
-
-
-
-
-


Transactions    Blocks
__    -------->  []
__    -------->  []
__    ---------> []
__    ---------> []

Blockheader:
*Previous Block hash//It stores the value of the previous hash
*Time//Stores time 
*Merkle Root//Transactions in the forms of hashes are paired and they are again  merged till they get a single value
*Nonce
Block data+Nonce=Hash value

Blockchain 

It is a digital ledger that contains the entire history of transactions made on the network






Block chain
[] <> [] <> [] <> [] <> [] <> [] <> [] <> [] <> [] <> []
#     #     #     #     #     #     #     #     #     #




Valid block(Blue)


Invalid block (Red)
(Change Data)

Blockchain is a distributed network that allows information to be spread out across many users


Centralized             Decentralized                  Distributed                 
    \       /        \     /       \     /          .____._____.______. 
.     \     /         \   /         \    /          |     \     \      \
      \   /          \  /           \  /            |._____\_._____\__.___\.   
       \./            \.-------------.              |       \       \      \
       / \            /  \           /\             |._______\.______\_.____\.      .    .    .
      /   \          /    \         /  \
     /      \       /      \       /    \
    /        \     /        \     /      \
   /          \   /          \   /         \
  /            \

Mempool
Waiting place for all unconfirmed Transactions before they are added to the blockchain

Consensus 
How the network reaches agreement about which transactions are most trustworthy.
Proof of work
Proof of stake 
DBFT
Pooled mining
A mining approach wherre multipleminers combine resources to mine a block and then 
split the block reward.
Proof of Stake 
It seeks to achieve consensus by giving votes to those with stake in the system.


Who is using it?
Etherum
-Switching from POW to POS in the casper project
DASH
-A pioneer of POS
-Built from the  core bitcoin platform with added features 
for privacy and tx speed

LISK
-Focused on creating Decentralised apps 
-Uses Delegate Proof of Stake 


Delegate Byzantine Fault Tolerance 
Consensus algorithm based on assigning roles to nodes to help coordinate consensus

It has two nodes ordinary node and consensus nodes

It has delegates and a speaker

Private ----->Public Key----->Public key------>Bitcoin wallet  
Key                             Hash             Address
       (Eliptical    Ripemd 
        Curve         (SHAH 256())        Base 58   
      Multiplication )                    (Check)
        One-way
        
 Wallet Address 
 A unique identifier for your wallet
 Private Key(Secret Key)
 A secret number that allows you to spend bitcoin from your wallet
 Public key
 Publicly  sharable key that cannot be used to spend bitcoin.
 Wallet 
 Non-Deterministic 
 Sequential determinstic 
 Hierarchical deterministic
 
 
Wallet type     Non                     Sequential          Hierarchial 
               deterministic           deterministic      deterministic wallet
                wallet                   wallet
 
 
 
 Description   Randomly generated       Derived sequentially
               private key              from a single seed
                                        and can be traced 
 How to get      Private key             back to the seed
 a new private   =randomly generated    private key=
 key?             between 1 and 2^256    sha256(seed+n),
                                        where seed=128
                                        purely random bits
 
 
 
 
 
 







