# LandslideCore: The IBC Bridge to Avalanche

![picture alt](https://media.publit.io/file/Landslide/Landslide-Background.png "Landslide")

Landslide is a game-changing IBC bridge to Avalanche, enabling seamless interoperability between Avalanche, Cosmos, and other IBC-enabled chains. It ushers in a new era of cross-chain DeFi operations, scalability, and streamlined user experience by enabling any CosmWasm-based dapp to run natively on the Avalanche network. Through Landslide, we're fostering a more interconnected, robust blockchain ecosystem, enhancing liquidity, diversifying applications and assets, and attracting a broader user base to blockchain.

## The Most Secure Interoperability
Firstly, the IBC protocol allows for seamless interoperability between different blockchains. In the context of Avalanche, an IBC bridge means that Avalanche can securely and efficiently interact with Cosmos and any other IBC-enabled chains (Polkadot being the most recent), facilitating asset and data transfer between these networks. This opens up a new world of possibilities, such as cross-chain DeFi operations, where a user on one network can utilize financial products on another network, enhancing overall accessibility and utility.

## Motivation
The large scale adoption of Tendermint is entirely dependent on Tendermint consensus. While rollups do present a potential soluiton to TPS, they present centralized security risks.
With a Tendermint module and Avalanche consensus, now the Cosmos and Terra ecosystems will be able to build entire realm of metaverse, gaming, and trading applications that were formerly impossible to scale.

## Architecture
![picture alt](https://media.publit.io/file/Landslide/Landslide-Design.png "Landslide Architecture")


## Goals
*The Landslide Network aims to address some of the challenges faced by existing blockchain networks such as slow transaction finality, scalability issues, and limited interoperability. The following are the main goals of the Landslide Network:
*Connect natively to IBC: The Landslide Network enables native transfers of all IBC-connected tokens. This allows for seamless transfer of assets between the Landslide Network and other IBC-enabled chains.
*Decrease transaction finality: The Landslide Network aims to reduce the finality time of transactions on Tendermint from 7-22 seconds to under 1 second, making it one of the fastest networks in the blockchain ecosystem.
*Take advantage of trading opportunities: With faster finality times, the Landslide Network can take advantage of trading opportunities that arise in fast-paced environments, making it an attractive platform for high-frequency traders.
*100% compatibility with CosmosSDK: The Landslide Network is designed to be highly compatible with the native Cosmos-based SDK, enabling developers to easily port their existing dApps to the Landslide Network.
*Collaboration between Avalanche, Cosmos, and other IBC-enabled chains: The Landslide Network aims to create closer collaboration between the three ecosystems of Avalanche, Cosmos, and other IBC-enabled chains, creating a stronger, more interconnected blockchain ecosystem.

## Run Local Network

To run a local network, it is recommended to use the [avalanche-cli](https://github.com/ava-labs/avalanche-cli#avalanche-cli) to set up an instance of Subnet-EVM on an local Avalanche Network.

There are two options when using the Avalanche-CLI:

1. Use an official Subnet-EVM release: https://docs.avax.network/subnets/build-first-subnet
2. Build and deploy a locally built (and optionally modified) version of Subnet-EVM: https://docs.avax.network/subnets/create-custom-subnet
