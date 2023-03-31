---
id: overview
title: Current challenges
tags: [build, quickstart, developer, dapps]
---

Cartesi Rollups are an innovative and dynamic product that constantly evolves to meet the needs of our users. As we strive for excellence, we recognize that there may be ongoing challenges that need to be addressed. On this page, you'll find a comprehensive list of these challenges, along with the strategies and solutions we're working on to overcome them.

- [Transaction scalability](#transaction-scalability)
- [Disputes](#disputes)
- [Large data as input](#large-data-as-input)
- [Composability](#composability)
- [Convenience layer: Frontend](#convenience-layer-frontend)
- [Design for upgradability](#design-for-upgradability)

## Transaction scalability

### Challenge

In contrast to the majority of rollups, which primarily focus on enhancing transaction throughput and minimizing fees (essentially facilitating more transactions at a lower cost), our current **0.9** release is dedicated to expanding computational capacity within the rollup framework, ensuring more efficient and optimized performance.

### Solution strategy

Achieving transaction scalability is directly related to the implementation of *Aggregator*. This key component will streamline the process, enhancing the overall efficiency and capacity of our rollup solution.

## Disputes

### Challenge

The initial **0.9** release lacks support for dispute resolution.

### Solution strategy

Our team has recognized this limitation and has already begun developing dispute resolution features to enhance this functionality in future releases.

## Large data as input

### Challenge

The current Cartesi Machine does not support obtaining large data (from logger or IPFS), limiting DApps based on Cartesi Rollups to rely solely on on-chain data.

### Solution strategy

We are currently researching methods to expand the Cartesi Machine's capabilities.

## Composability

### Challenge

The current **0.9** release lacks composability, which is the ability to effectively integrate and interact with multiple DApps, enabling seamless communication and data exchange between them. This feature also allows users to easily move tokens and transfer them to different addresses on Cartesi Rollups. 

### Solution strategy

After the initial **0.9** release, we plan to prioritize the development of composability features, expanding the functionality and interoperability of DApps within the Cartesi Rollups ecosystem. This enhancement will further improve the user experience and promote the growth of the DApps network.

## Convenience layer: Frontend

### Challenge

The current **0.9** release features an HTTP API but does not yet include a frontend convenience layer that would minimize the amount of code necessary for developers to send inputs, query the DApp state in the rollups, and execute outputs. Convenience in SDK usage often involves multiple layers, with each layer designed to simplify and streamline the process further. However, the current release's lack of such layers could lead to increased effort for developers when interacting with our rollups solution.

### Solution strategy

To improve the user experience for developers, we are examining the potential integration of various convenience layers, including a frontend layer that would make it simpler and easier to use the SDK. Our present focus lies in conducting research and exploring potential approaches, without committing to a specific implementation plan at this stage.

## Design for upgradability

### Challenge

The current **0.9** release does not currently account for the evolution of our solution or the DApps built on it. This includes the ability to modify smart contract behaviors related to validator operations, dispute strategies, and other aspects. Additionally, the The current **0.9** release does not consider the possibility of updating the code running inside the Cartesi Machine or establishing a clear governance model to manage upgradability decisions.

### Solution strategy

We are researching methods to address these challenges, which involve incorporating the Diamonds design pattern for smart contract upgradability and exploring options for updating the code inside the Cartesi Machine. Furthermore, we recognize the importance of a robust governance model to guide decisions related to validators, dispute approaches, and other aspects of the platform. At this stage, we are primarily focused on researching these potential solutions.