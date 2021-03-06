![](https://miro.medium.com/max/1400/0*aFRIsO9uaCaeRdTK)

# Assignment on Hyperledger Fabric [CS4262-Distributed Systems] 

 Transaction called "DuplicateAsset" was added to the smart contract [here](src/main/java/org/hyperledger/fabric/samples/assettransfer/AssetTransfer.java). 
 
 This transaction will take an asset id and an owner, duplicate the asset and assign the duplicate to the new owner while keeping the original asset with the previous original owner.

| ![](https://www.researchgate.net/profile/Olivia-Choudhury-3/publication/323973240/figure/fig1/AS:608593283915776@1522111354176/Outline-of-transaction-flow-in-Hyperledger-Fabric-It-depicts-a-use-case-where-1-A.png) | 
|:--:| 
| *Hyperledger Fabric Workflow* |

 ## Concepts that I learnt about blockchains 

 1. **Permissioned and Permissionless Blockchains** - A permissioned blockchain needs **prior approval** for joining whereas a permissionless blockchain holds no restraints as such and allows anyoen to participate. Both these follow the same principles as a blockchain i.e. they are both **distributed ledgers** and **immutable**. Hyperledger Fabric used in this assignment is an example of the permissionless variant.

 2. **Smart Contracts** - Smart contracts are programs that run on a blockchain when certain criteria are met. They control the **transaction logic** of the chain. Within a smart contract, rules regarding how transactions should occur are defined. Moreover they also include a framework in which how disuptes can be resolved. The **chaincode** deployed in Hyperledger Fabric is the smart contract of this distributed ledger.

