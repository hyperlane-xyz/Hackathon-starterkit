# Hyperlane Hackathon Starterkit
![Twitter Banner](https://user-images.githubusercontent.com/44020788/223877593-66e6e885-9914-46a9-b50f-38811b220b56.png)


This is your Hackathon Guide to help you deploy your app Interchain, using our Permissionless Interoperability tools to help you expand your ideas on how to make your app more chain rich. 

Check out or [docs](https://docs.hyperlane.xyz/docs/introduction/getting-started) to get more complex ideas.

# Hacker Resources

## ⚙️ Pre-requirement tools

To interact with Hyperlane contracts you can use any of the following libraries: 

- [EtherJS](https://docs.ethers.org/v5/)
- [Wagmi](https://wagmi.sh/)
- [Hardhat](https://hardhat.org/)
- [Foundry](https://getfoundry.sh/)

These tools can be used to not only interact with Hyperlane contracts but to interact with any Web3 app.

## 🖥️ Quickstart

Looking to send cross-chain message. Use our [Quickstart tutorial](https://github.com/hyperlane-xyz/hyperlane-quickstart) to help you deploy simple send and receiver contract on any chains.

## 🧰 Hyperlane tools which you can use in your project

We have a set of helpful tools which you can easily integrate into your app and integrate it in your project: 

[Accounts API](https://docs.hyperlane.xyz/docs/apis/accounts)

- You can use the accounts API to have an account make function calls on another chain, like a DAO can own assets on other chains
- You could build a EIP-5164 implementation, Safe integration, Tally integration

[Queries API](https://docs.hyperlane.xyz/docs/apis/query)

- You can use the queries API to read state from a remote chain, for example read a price feed on Ethereum from BSC

[Message API](https://docs.hyperlane.xyz/docs/apis/messaging-api)

- Anything that doesn't fit in the above, you can use Hyperlane messaging to send and receive arbitrary bytes between your contracts on different chains.

[Warp Routes API](https://docs.hyperlane.xyz/docs/apis/warp-api)

- Looking to have a representation of a token from one chain, on another? Use Warp routes to quickly create a bridge without writing any code

[Permissionless Deployment](https://docs.hyperlane.xyz/docs/deploy/deploy-hyperlane)

- Looking to do any of the above, but Hyperlane is not on there? You can use PD to deploy Hyperlane to that chain and then use that to have your app do stuff on there

## 🏆 Hyperlane Bounties

Available on behalf of Hyperlane supported Hackathons. Join our [Discord](https://discord.com/invite/hyperlane) to get more information if there's ongoing or upcoming hackathon for submitting your project and get a chance to win one of our Bounties!

**Best use of Permissionless Interoperability**

- To qualify you simply need to deploy Hyperlane on a new blockchain or rollup.
- How you utilize your newfound interoperability capabilities will dictate how likely you are to win the grand prize.
- Examples would include deploying to your own rollup created via Celestia, Optimism, Polygon, or any rollup toolkit you’d like to use.
- Permissionless Interoperability related submissions will be eligible for the other Hyperlane prizes

**Best use of Hyperlane Warp Routes**

- Warp Routes are Hyperlane’s unique take on token bridging. Each Warp Route has its own security model, using Hyperlane’s Interchain Security Modules. Most importantly, Warp Routes are completely permissionless. You can now bring any asset to any chain.
- To qualify for this prize you simply need to use Warp Routes in your submission.
- Here are some ideas about what you could do:
- Create the first bridge on a new chain! This would also make you eligible for the grand prize.
- Leverage Warp Route’d assets in an app of your design
- Use Warp Routes to create interchain NFTs or bridge existing collections

**Write new Interchain Security Modules (ISMs)**
- Hyperlane’s Modular Security Stack is premised on a variety of available Interchain Security Modules that developers can use to secure how applications can communicate between chains. While a few ISM’s are already available, and more are in the works, the hackathon is a great opportunity to build new ones. Some suggestions for ISMs Hyperlane developers would like to see:
- An Optimistic ISM; this would implement an ISM that secures messages with an Optimistic system, in the mold of the Optics protocol, one that allows for a challenge period of some time, during which a fraud proof can be submitted by anyone. A successful submission will include the ISM itself, and any necessary offchain agent software such as the Watchtower and any Relayer changes.
- A Telepathy ISM; the newly released Telepathy client allows for interchain messaging from Ethereum secured by ZK-SNARKs. A Telepathy ISM would use the Telepathy client to secure outbound messages from Ethereum. A successful submission will include the ISM itself, and any necessary changes to the Relayer.
- A Native/Rollup Bridge ISM; this ISM would leverage the native bridge for a rollup, i.e. the native Optimism or Arbitrum bridges, to secure messaging. A successful submission will include the ISM itself, and any necessary changes to the Relayer.

## 🧑‍💻First time at Hackathon?

Check out this amazing Survival guide by [Francesco](https://twitter.com/francescoswiss) to prepare yourself and set expectations for any Hackathon
[Ultimate Hackathon Survival Guide for 2023](https://dev.to/andreolf/ultimate-ethereum-hackathon-survival-guide-for-2023-149i)

Starting with Ethereum development? Check out [Speed Run Ethereum](https://speedrunethereum.com/) to help you kickstart the Ethereum journey 

Looking for diving into Crypto ecosystem ? Look no further, we compiled list for you [Crypto READ.ME](https://github.com/anettrolikova/Crypto/blob/master/README.md)

## 💬 Still stuck? Reach out to us!

We are online on our Discord ready to respond to your questions! Let us know if you need any help [Discord](https://discord.com/invite/hyperlane)
