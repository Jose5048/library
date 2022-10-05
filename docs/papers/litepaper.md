---
id: litepaper
title: Smart NFT (DripVerse v1.0.0)
sidebar_label: Litepaper
hide_table_of_contents: false
category:
  - Litepaper
tag:
  - Litepaper
  - NFT
  - SmartNFT
  - DripVerse
---
Author: [Kumar Anirudha](https://twitter.com/kranirudha)

### _SuperCharge your NFTs_

## Abstract
NFTs are awesome but it's incomplete as it is right now. PFP NFTs can only be used in so many cases. The future lies in adding utility to NFTs. In this paper we will discuss the limitations of current NFT ecosystem and how our platform can add power to your current NFTs as well as make it easier to develop, integrate and use NFTs as integrations to various platforms.

## Introduction
In recent years, we've seen an enormous increase in NFTs and the creator communities built around it. The usual idea of an NFT would come from creating a digital twin of a physical object or artwork that can be uniquely identified and marked ownership of in a decentralised ecosystem. The value of an NFT lies in the uniqueness and rarity of it as well as how the market values it.
Some projects have tried incorporating NFTs in their regular usage to add "utility" over these NFTs to provide actionable value to the end user. However, these are either utility as a service model or specific industries just waking up to the new value found in utility usage of NFTs.

# Summary of Problem
The lack of value beyond what the market determines for PGP(Pretty Good Privacy) NFTs is a dead end. Presently, the only reason anybody would mint NFT would be, to place it on a market and trade it so they can earn out of it. For any new artists, this means large scale marketing and promotional activities. But once someone acquire such NFTs, there is not much that can be done with it other than hoping that the value of it rises over time given the rarity of it and hopefully re-list at a later stage on some marketplace. Even when we have some NFTs on our wallet. There's really not much to do with it. So, what is the added value to it apart from any other fungible tokens?

# The Solution
Here we should get aquainted with what DripVerse is all about. However, to grasp the depth to it, we need to be able to define what we are solving with it as well.

## Adding Utility to NFTs
We are starting to see some artists and celebrities coming up with their own NFTs, which provides access to exclusive content, events and deals in respect to the artist who's NFT we might have acquired. This is a great step towards adding utility over PGP NFTs and in turn adds additional value to it. Of course, these can still be traded over any marketplaces. There is also real world objects which are connecting with digital twins using NFTs which provides access to the same digital object in a Metaverse. Even some events and concerts have started adding NFT tickets, which adds further actionable value to the NFT. There are various industries pushing added value to the NFT which is brings us to the next upgrade over NFT, also sometimes called as NFT2.0 or Smart NFTs.

## Smart NFT
Smart NFTs is the next step in the evolution of NFTs which creates and distributes NFTs with programmable and actionable utility.
We provide an SDK and other dev tools to ease the process of creating Smart NFTs. Our custom variation of ERC721 and ERC1155 as well as ERC4907 provides embedded utility inside the smart contract itself, which is linked back to additional private information readable by our SDKs and client libraries to support on various platforms, like mobile (Android, iOS), desktop(Linux, Mac, Windows) and web(Browser).

## Interoperable Assets
Just adding more value to existing NFTs is not enough if it's limited to a single network. We also need to support multiple networks as well as be able to move the assets seemlessly across chains. We're creating our own custom NFT Bridge to support not only Layer 1 networks like Ethereum, Polkadot, Cosmos, Solana, but also Layer 2 networks like Polygon, Starknet, ZkSync, and many more. We'll also integrate external bridges like Router Protocol to add further support for token bridging and provide more options to the users.

## Open Web Protocol
We are only focusing on creating the building blocks, not just for us but also for our builder community. Going forward, we would encourage builders and developers to integrate and build their own utilities and make it available to the large community. The entire DripVerse ecosystem is an open ecosystem where community made plugins is going to be the corner stone for new upcoming projects. A good analogy can come from Wordpress Community made plugins and add-ons or the Figma Design Community Plugins. The main Drip SDK is essentially an open web protocol with encouraging innovation at the core.

### Plugins
Any developer or builder should be able to easily build their own plugins and custom utilities and list them on our plugin marketplace to earn by per-use model in realtime transaction basis. These plugins can also be made in various access types such as private, protected and public modes. The plugins currently supports javascript and python libraries and we will be working further on supporting more libraries going forward. We will also support any wrapped libraries built over our libraries and will support most major package managers like npm, pypi, etc.

## SDK
The SDK (Software Development Kit) holds the key to all our products. The SDK is written in rust and will run over CLI and support various other programming languages via Web Assembly language bindings. We are starting with support for EVM based networks and solidity as smart contract language, but in upcoming versions we will cover non-EVM chains as well. 

## CLI Tool
The CLI tool is the first step for our SDK to attempt for a general purpose use-case. Currently supporting Ubuntu and Arch Linux and Mac distributions via majorly used package managers. We are also integrating all NFT functionalities like minting, transfer, withdraw and moving assets cross-chain seemlessly. However, while using CLI tool, users will need to enter their private keys manually. We'll be embedding a secret manager as well, thereby simplifying the usage. The advantage of CLI tool is that, it can run practically anywhere, including very resource deprived hardwares like Raspberry Pi and Arduino Uno.

### Smart Contract Programming Support
We are creating our own Smart Contract standard, which means any other custom smart contract can easily import our library and use it in their own smart contract like OpenZepplin Smart Contracts right now. These custom Smart Contracts can also be turned into utilities and listed on the platform as well. Control Access around it and make it a usable plugin.

### Custom Token Support
Every project has their own token and might not always use the native token of the network. We are integrating various token bridges and wallets supporting them which will allow using a wide number of tokens to be used. We will also have an easy no-code tool to link your tokens to our partner wallets so that you can use your tokens in a private dev environment as well.

# Drip Token
We will have our own token to support various activities across platforms as well to support the SDK via a native token utility. More about DRIP token soon on our tokenomics paper.

# Multi-Chain Explorer
A lot of assets moving cross-chain does make sense only if we've more visibility over it. This will include tracking the assets from the source network to destination network including any transitions they might have been done in between. We will eventually also open the APIs to the same for adding Dune like platforms to create analytics over it.

# High Level Architecture
![High Level Architecture of Smart NFT Tooling](https://i.imgur.com/Z7lHIY7.png "Smart NFT Tooling Block Architecture")

# Who can use DripVerse
There is two major aspects of DripVerse which combines to form the supportive tools for Smart NFTs. The **buidling** aspect and the **using** aspect. The builders are Token gated communities, Brands, Metaverses, Digital Events and other service providers using NFTs in their own products for their users. The users are the users of said platforms who would be motivated to use more of it if given additional benefits and use-cases over that they're currently receiving.
Nurturing both is equally important.

## Builders
DripVerse enables builders to reduce their building time and resource usage by almost 1/10<sup>th</sup>, while maintaining a greater control over the utility to be integrated. Thereby also reducing the time and cost to the project not just while development but also while maintaining as it'd be a click away to upgrade. Using the no-code UI provided, builders who are also non-programmers can take advantage of the integration and be done within minutes from what would have been an development process of weeks.

## Explorers
While the advantages are greater for the builders, the users or explorers will also get the benefit and freedom to move the assets freely and seamlessly across chain and multiple networks. Supporting multiple wallets and a wide range of supported marketplaces, bridges and options to choose from. Since the custom Smart NFT contract will reduce the number of transactions required and lower fee by moving most excruciating tasks to Layer 2 network, thereby saving in millions throughout.

# Conclusion
Smart NFTs are the undoubtedly future of NFTs. And DripVerse Tools are here to nurture and grow the ecosystem.
