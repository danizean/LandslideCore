# LandslideCore: The IBC Bridge to Avalanche

![Landslide Logo](https://media.publit.io/file/Landslide/Github/Github.png "Landslide")

## Version Information

LandslideCore is based on [Tendermint 0.34.19](https://github.com/tendermint/tendermint/blob/v0.34.19/CHANGELOG.md#v0.34.19), released on April 8, 2022.

## Introduction

Landslide is a game-changing IBC bridge to Avalanche, designed to enable seamless interoperability between Avalanche, Cosmos, and other IBC-enabled chains. Our core mission is to bring forth a new era of cross-chain DeFi operations, scalability, and user experience.

---

## Table of Contents
1. [Overview](#overview)
2. [Benefits](#benefits)
3. [The Most Secure Interoperability](#the-most-secure-interoperability)
4. [Motivation](#motivation)
5. [Architecture](#architecture)
6. [Goals](#goals)
7. [Run Local Network](#run-local-network)

---

## Overview

By implementing the necessary ABCI calls, Landslide Core enables developers to connect their existing Cosmos dApps to the Avalanche network. This opens doors to faster finality times and IBC compatibility.

---

## Benefits

Avalanche's consensus protocol offers a slew of benefits:

- **Improved User Experience**: Faster finality times enable quick trades and seamless interactions.
- **Increased Liquidity**: Landslide can process more transactions per second, contributing to a more robust market.
- **Reduced Risk of Liquidations**: Quick finality minimizes cascading liquidations during market volatility.
- **Enhanced Arbitrage Opportunities**: Faster transactions enable efficient cross-chain arbitrage.

Deploying an outpost on Avalanche is a strategic move that not only improves user experience but also contributes to the overall growth and success of Cosmos.

---

## The Most Secure Interoperability

The IBC protocol offers seamless interoperability, enabling Avalanche to interact securely and efficiently with Cosmos and other IBC-enabled chains. This enables:
- Cross-chain DeFi operations
- Smooth asset and data transfers

---

## Motivation

Cosmos's scalability is limited by its consensus algorithm, Tendermint. Although rollups could solve throughput issues, they introduce security compromises. Avalanche and CosmosSDK together unlock scalable solutions in various applications, including metaverse and gaming.

---

## Goals

The Landslide Network aims to:

- **Connect Natively to IBC**: Enable native transfers of all IBC-connected tokens.
- **Decrease Transaction Finality**: Reduce transaction finality time to under 1 second.
- **Leverage Trading Opportunities**: Capitalize on fast-paced trading environments.
- **CosmosSDK Compatibility**: 100% compatible with Cosmos-based SDK.

---

## Run Local Network

To run a local Landslide network, follow these steps:

1. Use [avalanche-cli](https://github.com/ava-labs/avalanche-cli#avalanche-cli) to set up an instance of Subnet-EVM on a local Avalanche network.
  
  - [Official Subnet-EVM Release](https://docs.avax.network/subnets/build-first-subnet)
  - [Locally Built Subnet-EVM](https://docs.avax.network/subnets/create-custom-subnet)

