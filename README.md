# CyberBanknotes
Make cryptocurrencies highly decentralized without POW.

The goal is to solve all problems caused by POW and POS. POS causes bad decentralization. While POW has disadvantages such as below:

    Bad scalability.
    Huge amount of electricity waste.
    51% attacks.
    After the miners became centralized, the decentralization is no longer good enough.

Let’s solve these problems by ownership blockchains.
## Ownership blockchains

Start with a simple blockchain. Just put the data of the current block and the hash value of the previous block together, calculate and get the hash value of the current block. In this way link the blocks to a chain. Everyone can verify the data in the entire blockchain through the final hash value.

Ownership blockchains are based on these simple blockchains. Each ownership blockchain is private. It has an owner. Only the owner has the right to add a block. Others can only read.

The owner of the blockchain can be changed by adding blocks. For example, there is an ownership blockchain X, Alice is its owner. She can add a block at the end of X, in which she writes: I would give this blockchain to Bob. After the block broadcast, Bob becomes the new owner of X. Now, he is the only one who has the right to add the next block to give X to others.

Consider only the blocks used to change the ownership. Each block is added by the receiver defined in the previous block. In all the blocks, we can read all the ownerships of the blockchain in its whole life. The history of ownerships are most important.

In this way, the blockchain can travel in the crowd. For each step or position, only one person can add the block. So there is no need of competition or consensus. There is no POW, POS nor 51% attacks.

Consider many ownership blockchains like X. They are travelling in the crowd without interfering with each other. Such an ownership blockchain group is a simple superposition of a single blockchain case. Every person owns some ownership blockchains and may give them to others without power wasting or 51% attacks.

Although each ownership blockchain has an owner, the ownership blockchain group is highly decentralized. Everyone can join freely and every user has exactly the same rights. They can decide who they want to give their blockchains to, cannot participate the decisions of others.

To increase the scalability, just add the number of the blockchains. There is no upper limit on scalability.

We achieved the original goals. The ownership blockchain group runs in high decentralization, good scalability, less power consumption, no 51% attacks. For each ownership blockchain, they are private. But for the group, it has better decentralization than the public blockchains. It can replace the public blockchains at least in the usage of cryptocurrencies.
## For cryptocurrency

For the usage of cryptocurrency, just regard each ownership blockchain as a BANKNOTE. Like the paper banknotes we are familiar with, each banknote has a fixed denomination, which is the basic unit of payment. Each payment is carried by the transfer of ownership of several banknotes. Both for paper banknotes and ownership blockchain banknotes, the payer selects a few from his banknotes, makes up the amount to be paid, transfers the ownership of the banknotes to the payee, and the payment is completed.

We got the perfect cryptocurrency.

Someone may ask how to transfer some money from one blockchain to another without consensus. There is no such action. Pay attention that each ownership blockchain is a banknote rather than an account. You can not transfer some money from one banknote to another. For a banknote, all what may change is its ownership. The denomination won’t change.
For bitcoin

The ownership blockchain banknotes can also work for other cryptocurrencyies such as bitcoin. If the bitcoin miners stop mining because their income is too low, bitcoin would die. We may save it with banknotes in the follow steps.

    Create a banknote, get its id.
    Transfer some bitcoin to the address equals to the id in step 1.
    Add the second block to the banknote, in the block write the UTXO id in step 2.

So we get a banknote of bitcoin. The part of bitcoin carried by the banknote could be paid with performance and power saving from now on. Though it may still get 51% attacks in the phase of the public blockchain of bitcoin.

We can create many such banknotes for the whole bitcoin amount, make bitcoin running without mining.

Until the bitcoin team adds new features, we couldn’t transfer this part of bitcoin back to the public blockchain of bitcoin.
Security

For each position of the ownership blockchain, only one person can add the block and he can only add one. If everyone does this compliantly, the ownership blockchain won’t fork. If someone added more blocks at the same position, the blockchain forks, the users can easily locate and punish the offender. For the forked blockchain, the users can identify which fork is valid by the time of broadcasting of the root blocks of the forks. And the users can finally fix the forked blockchains.

We never make decisions by voting to avoid Sybil Attacks.
## Q&A for details

Q1. Alice added one block to give an ownership blockchain banknote to Bob at her position. Then, she added another block to give it to Charlie at the same position. She made a double spend attack.

A1. Everyone can see the two conflict blocks from broadcasting. They will block Alice because of both of the conflict blocks are signed by her. Bob and Charlie can refuse the payment.

Q2. In Q1 case. Charlie is an accomplice. None of Alice or Charlie broadcast the second block. Others won’t know about the block.

A2. When Charlie or another accomplice pays the ownership blockchain banknote to another user who is not an accomplice, the block will be broadcast. The payee will refuse.

Q3. In Q1 case. In a decentralized network, to be blocked is nothing. Alice can register another account freely.

A3. We can set some rules to make accounts expensive. For example, every new account must pay some money for activating. Or, when spending some banknotes, the user must mortgage enough other banknotes to ensure the payment security.

Q4. In Q1 case. After the blockchain forked, how can we know which fork is true?

A4. Consider the typical time of broadcasting, if we received the block not too late from its create time, we can trust it. If Alice broadcast the conflict blocks at almost the same time, None of Bob and Charlie would accept.

Q5. In Q4 case. If a user was offline at the fork time, how can he choose the forks?

A5. Users should try to stay online. If he can’t, he may refuse all the forked banknotes.

Q6. In Q5 case. After a long time, the number of forked banknote increases. To refuse all the forked banknotes may cause trouble.

A6. We can fix the forked banknotes. For example as Q1, Alice forked a $10 banknote, gave the forks to Bob and Charlie. The fork block for Bob is broadcast in time. Bob contacts Charlie, suggests to buy Charlie’s fork with $1. Charlie agrees. Bob gets the two forks, adds a new block follow to both the two forks. The banknote gets fixed.

In this case, Bob deficitted $1 to buy Charlie’s fork. The system should return him some benefit. One of the ways is to regard the fixing block as a lottery ticket. Bob may get some money by chance. So fixing a banknote becomes a game.

## Scalability

We have to broadcast every block immediately for security. When the network grows very big, there may be some performance issues. We can solve it by grouping.

Randomly divide banknotes into multiple groups. Each user may join some groups. New blocks only broadcast to the users in its group. The number of broadcasts is reduced. If Alice and Bob have frequent economic transactions, they should join a group together and pay by the banknotes in this public group for both security and performance.

## Thanks
Feedback is highly appreciated.

If you could read the Chinese document, you may get more detail information.

http://www.guideep.com/read?guide=5700866052980736
