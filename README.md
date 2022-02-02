# Mirror-Clone

Welcome to the Mirror Clone tutorial! The goal of this tutorial is to introduce the Web 3 development process in the context of a full stack decentralized application. Specifically, we’ll be bridging you from Web 2 to Web 3 by building a blog similar to Mirror using a Web 3 stack.
Mirror is a powerful Web 3 platform for publishing content. It allows writers to publish in a decentralized, censorship-resistant way while retaining full ownership of their content. It also enables functionality like tipping writers, splitting proceeds with co-writers and contributors, and crowdfunding projects.

By the time you're done, you'll have a blog similar to Mirror. Users will be able to write entries, publish them, mint NFTs for each entry, and transfer those NFTs to other public addresses.

The entries will be saved on [Arweave](https://www.arweave.org/),  a decentralized storage solution for immutable data storage, and the NFTs will be **ERC-721** tokens on **Polygon**, a protocol for scalable Ethereum dApps.

**Step 1**  will walk you through some basic set up and configuration. This will include cloning a template repo, so you don't have to write code you're already familiar with (i.e. NextJS). It will also include setting up a few environment variables you'll need in later steps.

In **Step 2**, we'll introduce the **ethers.js** library and learn how to connect a user's MetaMask wallet to the dApp.

Then we'll introduce Arweave - a decentralized, censorship resistant storage solution - in **Step 3**. We'll write an endpoint to create blog entries and finish a form to submit them. In **Step 4** we'll learn how to fetch them and in **Step 5** we'll write code to display a list of the latest entries

**Step 6** will be a brief introduction to smart contracts including inheriting from standard libraries, writing functions, testing them and deploying the smart contract to the Polygon testnet. We'll be minting an NFT for each entry so authors can own their entries.

Finally, **Step 7 ** will implement functionality that allows authors to transfer NFTs. This sets up the application for expansion into a marketplace for blog entry ownership.

## Prerequisites
  - Node.js
  - 