# Masternodes

### **Does Viction have Masternodes? How do they work?**

Yes, Viction has a maximum of 150 Masternodes with Proof of Stake Voting (POSV) consensus that enable low transaction fees, and instant transaction confirmation. Masternodes create, verify and validate new blocks one the Viction blockchain.

* **Masternode Candidates:** Any account can deposit 50,000 VIC using [VicMaster](https://vicmaster.xyz/) to become a Masternode candidate. A candidate can resign, but the tokens will be locked for the next 30 days (1,296,000 blocks) after the resignation.
* **Becoming a Masternode:** A Candidate becomes a Masternode when he/she belongs to the top 150 most voted Candidates in each epoch. A Masternode can resign, but the tokens will be locked for the next 30 days after the resignation.
* **Rewards:** The rewards a Masternode receives in each epoch is proportional to the number of signatures it signs.

Viction Masternodes started signing blocks and receiving block rewards when the Mainnet released in December 14th, 2018.

### **What is a Masternode in the Viction ecosystem?**

A Viction Masternode is a server which uses its computing power to contribute to the network. Its job is to create and sign blocks. For this contribution to the network, Masternodes receive rewards in the form of VIC.

Masternodes are elected using the PoSV consensus via our governance Dapp [VicMaster](https://vicmaster.xyz/)

### **What are the incentives to run a Masternode?**

Masternodes contribute to the network and for this work they receive significant block rewards, which will likely exceed the cost for running the infrastructure. However, Masternode owners need to invest in Viction by depositing at least 50,000 VIC, and stake them over the long term.

After the initial deposit, if the account does not become a Masternode (has less votes than the top 150 most voted candidates), it will not receive rewards. Therefore, Candidates are incentivised to do as much as they can to signal their capability to support Viction to get into top 150 most voted Candidates.

### **How did you decide on 150 Masternodes? Why did you decide to increase this from the initial 99?**

The reason came from considering both decentralization and scalability. In terms of decentralization, 150 is better than 99. The more important consideration was scalability. We also increased the number of Masternodes to better suit a future sharding solution.

Also 150 is [Dunbar’s Number](https://en.wikipedia.org/wiki/Dunbar's\_number).

### **Where will the Masternode rewards come from? Will they be from the DEX?**

The block rewards will come from a 17 million VIC reserve for 8 years - this was decided since the genesis block. Our [Economics paper ](https://docs.google.com/document/d/197Cu57A6OYPoEQbrUVr067qNVEzP\_FEwaDCFff7hnlM/edit)lays out the number in detail.

### **When are Masternode rewards paid out?**

Masternode operators and Voters will receive rewards every epoch. An epoch is represented as 900-blocks of 2-second block time (\~30 minutes).

### **How can I check my rewards?**

You can check your Masternode/staking rewards using Viction Wallet. Alternatively you can use VicMaster or VicScan.

### **What rewards do Masternodes receive?**

Each epoch consists of 900 blocks, which will reward a total of 250 VIC in the first two years. This amount of 250 VIC is divided across all of the Masternodes proportionally to the number of signatures they sign during the epoch.

Example: With only 25 Masternodes with equal performance, every Masternode would be rewarded with 10 VIC. With 125 Masternodes, each one would receive 2 VIC per epoch.

Please, refer to our [Economics paper](https://docs.google.com/document/d/197Cu57A6OYPoEQbrUVr067qNVEzP\_FEwaDCFff7hnlM/edit) for more details about the Masternode rewards.

### **How much of the Masternode reward will go to the Masternode infrastructure (node owner) and to voters?**

There is a reward sharing ratio among token holders and the Masternodes which have been elected to be supported by the token holders. The rewards achieved by each Masternode will be divided into three portions:

* **Infrastructure Reward:** The first portion of 40% called Infrastructure Reward goes to the Masternode operator.
* **Staking Reward:** The second portion of 50% called Staking Reward goes to the pool of all voters for that Masternode which is shared proportionally based on the token stake. The Masternode also gets proportional rewards for his 50K VIC initial deposit.
* **Foundation Reward:** The last portion of 10% called Foundation Reward goes to a special account controlled by the Masternode Foundation, which is run by the Viction company initially.

### **What is the expected ROI for Masternodes and Stakers?**

The rewards for every Masternode will be dynamic and depend on multiple factors like: number of Masternodes in the network, the efficiency signing blocks, the total number of votes on each Masternode.

Please, refer to our [Economics paper ](https://docs.google.com/document/d/197Cu57A6OYPoEQbrUVr067qNVEzP\_FEwaDCFff7hnlM/edit)for more details about the Masternodes reward. We discuss 3 possible scenarios with 50, 100 and 150 Masternodes; and different number of total votes.

One example is outlined below.

**Scenario**: 150 Masternodes, 12.5 million tokens voting (a total of 20 million token locked).

Reward achieved per epoch (900 blocks):

* `By a Masternode = 0.6667 VIC`
* `By a Voter with 1K VIC staked = 0.00625 VIC`

Approximate reward achieved per week:

* `By a Masternode = 224 VIC`
* `By a Voter with 1K VIC staked = 2.1 VIC`

Approximate reward achieved per year:

* `By a Masternode = 11,680 VIC`
* `By a Voter with 1K VIC staked = 109.5 VIC (10.95% annually)`
* `By a Voter with 50K VIC staked = 5,475 VIC`
* `Total reward for a Masternode with a 50K VIC deposit: 11,680 + 5,475 = 17,155 VIC (34.31% annually)`

## Masternode Candidate

### **What is a Masternode Candidate? What is the difference between Masternode Candidate and Masternode?**

A Masternode Candidate is any node owner who deposits 50,000 VIC to be listed on [VicMaster](https://vicmaster.xyz/).

A Candidate only becomes a Masternode when it is in the top-150 most-voted Masternode Candidates in an epoch. Only these elected Masternodes will be able to sign blocks and receive block rewards.

### **How can I become a Masternode?**

The first step to become a Masternode, is becoming a Masternode Candidate. To become a Masternode Candidate you need:

* to run Viction software in a machine with a certain minimal hardware requirements
* to deposit 50,000 VIC in a smart contract via VicMaster

The list of Masternode Candidates will be available on the governance Dapp, [VicMaster](https://vicmaster.xyz/). The next step is to be elected as one of the top 150 most voted Candidates.

### **Do I need to use my own computer to run a node?**

We recommend using an IaaS ("cloud") provider of your choice (like Amazon AWS, Digital Ocean, Google Cloud GCE, Vultr, etc). The machine must be directly internet facing (public IP, no NAT) and have 100% uptime.

If you have another production grade environment other than cloud a provider at your disposal, please tell us more about it on our[ Github.](https://github.com/BuildOnViction)

### **What are the hardware requirements to run a node?**

Processing transactions is mostly CPU bound. Therefore we recommend running CPU optimized servers.

* Directly facing internet (public IP, no NAT)
* 16 cores CPU
* 32GB of RAM
* SSD storage

We recommend using popular cloud providers as their reliability and uptime are close to 100%. Those servers would be a good starting point:

* **DigitalOcean:** CPU optimized droplet 32GB/16CPU
* **Amazon EC2:** C5 instance
* **Google Cloud Engine:** n1-highcpu-16

Setting up a masternode candidate on a weaker machine might result in poor performances, significantly impacting the owner's rewards and the chain performance.

**Note:** If you are running a node in Testnet, 2CPU/8GB of RAM is sufficient.

### **How do Masternode Candidates become Masternodes?**

Once you are a Masternode Candidate, you need the support of the Viction community in the form of votes. The top 150 most voted Candidates every period, called an epoch (900 blocks of 2-second block-time), will be promoted to Masternodes. This list will change dynamically every epoch. Only the 150 Masternodes elected will be able to sign blocks and will receive rewards in the form of VIC.

### **Where can I find the latest Masternode guide or the instructions for setting up a Masternode?**

Find more details about tmn [here](../../masternode/run-a-full-node/create-a-viction-masternode.md)

### **What is the command to start a fullnode with 'tmn'?**

`tmn start --name node_name --net mainnet --pkey your_private_key`

### **What I can do when tmn is installed but just not in your path.**

See [here](../../masternode/run-a-full-node/tmn.md)

### **I tried stopping the node using 'tmn stop', but after that I ran 'tmn status' it still says running.**

You can run `tmn --debug stop` and send the log to us. We will help you to investigate the issue.

### **Do I need two wallets to run a Masternode?**

It is recommended for security reasons. You can create your wallet from wherever you want, the only rule being that you need two of them. One for your Masternode, and one to make the 50K deposit (this account will receive the rewards).

### **What is the 'coinbase address'?**

'Coinbase address' is the public address used to run your node and register it to the system.

We recommend using two addresses when running your nodes. The public address or 'coinbase address' will only receive transaction fees. The private address is from where you make the initial 50K VIC deposit and where the block rewards will be collected.

{% hint style="info" %}
In short, we need to have 2 wallet addresses. **The Wallet address A** is used for signing the block in the full node which had been already set up. **The Wallet address B** contains 50k VIC to login to **VIC Master** & stake that amount to propose the full node to become master node. We will input the **wallet address A** to the **coinbase address** field in the "**Become a candidate"** pop-up
{% endhint %}



### **I noticed that we need another wallet for the Masternode with a different mnemonic. Assume we use a hardware wallet, we would need another hardware wallet with a different mnemonic?**

It is recommended to use a separate empty account for your Masternode as it only receives transactions fees - what we call public or 'coinbase address' on the documentation.

The block rewards are sent to the account connected to VicMaster who make the initial deposit - the 'private' address.

### **Can I use the same address pair (tmn public address + initial deposit address) for all my nodes? Or I have to transfer tokens to another wallet and start the second node?**

No. You must use different public 'coinbase' addresses. But you can use the same initial deposit ('private') address, then all rewards will be transferred to only one address.

### **I have finished all steps of setting up a node. Why I don't see my node on VicMaster?**

You must apply to become a Masternode Candidate on [VicMaster](https://vicmaster.xyz/)

### **Do I need to deposit the 50K VIC before or after running 'tmn' in VPS?**

After. Your node must be fully synced before applying.

### **How do I check the blockchain sync status from the node?**

You can watch the logs, but it is easier from the [VICStats](https://stats.viction.xyz/) website or its eth.blockNumber API call.

### **If the Masternode owner deposits 60K VIC instead of 50K on its own node, can it later on unstake the excess 10K?**

Yes, it can.

### **How can I change my node's name?**

You can do it on VicMaster. Go to your Masternode page on VicMaster, if you are logged in to VicMaster with the owner account, you can click next to the Mastenode name to edit info.

### **My node status is 'Proposed', will it change status with the next checkpoint?**

Yes, if you are in the top-150 most voted Masternodes.

### **Why is a node flagged as 'Slashed'?**

With Slashing v2.0, a Masternode that does not create any block within an epoch, and therefore delays the network by 10 seconds at each of its turns will be penalized (no rewards) for the next five epochs.

Note: a slashed Masternode can still sign transactions if its online but will receive no rewards for doing so.

After being slashed for 5 epochs, the Masternode is analysed for re-entry. If the slashed Masternode has signed any transaction during the last epoch (meaning that it's up and working again) it will come back to its Masternode status and receive rewards normally. Otherwise it will be slashed for a new round of 5 epochs. This can happen for as long as the node isn't back up or kicked out of the top 150.

Some reasons for being Slashed might be that the Masternode does not have the correct Viction software, lack of memory or the Masternode crashed due to lack of e-maintenance and operation by the Masternode owner.

### **How do I update my Masternode to the newest version?**

Run this command: `pip3 install -U tmn && tmn update && tmn start`

### **How many nodes am I allowed to run?**

As many as you can.

### **How can I resign as a Masternode?**

If you no longer want to be a Masternode, you can resign on VicMaster. Your Masternode will stop generating rewards and your funds will be locked for 30 days (1,296,000 blocks). After the lockup period you will be able to withdraw your 50,000 VIC deposit.

### **Can I close the node entirely, then start a new one with a totally separate coinbase address without being penalized?**

No. Your old node will be penalized (50K initial deposit 30-day lockup) and your new node has to apply again.

### **Is it possible to move a Masternode later, like backup and start it from another IP address?**

Yes.

### **What if I do not have enough VIC for a Masternode? Can I stake my VIC?**

Yes. Token holders can stake VIC and receive rewards.

To stake VIC you need to vote for Masternode Candidates by sending VIC to each candidates specific voting-address using the official governance Dapp VicMaster. The top-150 most voted will become Masternodes. Token holders can also un-vote Candidates, but the tokens will be locked for the next 96 epochs / 8,640 blocks (approx. 48 hours) after the un-voting.

Masternode token deposits and all tokens used to vote for Masternodes will enter the staking program, and earn block rewards in each epoch, plus any fees. Tokens used to vote for candidates that do not become Masternodes will not earn staking rewards.
