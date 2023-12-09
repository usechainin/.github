# ChainIn ⛓️

**Authenticity-Driven**, **Privacy-Focused** Business & Employment Aggregator dApp. Fostering genuine connections between employers and job seekers using [Chainlink CCIP](https://chain.link/cross-chain), [Polygon ID](https://polygonid.com/), [The Graph](https://thegraph.com/) and [Tableland](https://tableland.xyz/).

<div align="center">
<img 
  src="https://github.com/usechainin/.github/blob/main/assets/chainin-logo.png" 
  style="width:40%; height:40%;"
/>
</div>

## 🛑 Problem

The Web2 version of **LinkedIn** we have today contains several critical concerns:

1. **User Privacy** - Users have to provide extensive personal information for e.g. in order to "complete" setting up a user profile, the user has to add in their birthday, which is completely unnecessary.
2. **Authenticity** - LinkedIn struggles with fake profiles and inflated credentials, impacting trust and authenticity when viewing a user's profile, for e.g. users can easily endorse each other, leading to inflated profiles.
3. **Inconsistency** - Job application process has also been criticized for its inconsistency, causing a cumbersome experience for users seeking to apply for positions.

## 💫 Solution

ChainIn is a **secure and transparent** space for businesses and job seekers, prioritizing **user authenticity** through **verifications** and **proof of experience**. 🌟

Part of Chainlink Lab's team? 😱 Obtain verified proof showcasing your association with Chainlink Labs on **ChainIn**! 🫡

Picture a world where employers can **trust an applicant's past job experiences**, and job seekers can verify credentials **without compromising all their data**. That's the beauty of **ChainIn** ❗️

With a commitment to **authenticity**, **ChainIn** employs web3 innovative technologies to **verify** and **validate** user credentials, ensuring a **secure** and **transparent** environment for both businesses and job seekers alike. 🙌🏻

Experience the future of job searching and building connections with our **privacy-focused**, **authenticity-driven** dApp at **<a href="https://chainin.netlify.app/">ChainIn</a> 🚀**

### ⛑️ How it works

1. **Connect your wallet** through our built-in wallet provider, [RainbowKit](https://www.rainbowkit.com/).
2. Set up your profile.
3. Voila! It's done. Your info stays on-chain, safe from leaks.

## ✨ Features

1. 😌 **Simple UI/UX**: Users can personalize their profile with just a few pieces of information.

2. 🔥 **Permissionless NFTs**: Creating an organization page will permissionlessly deploy an NFT smart contract that is unique to your organization.

3. 🧑🏻‍💻 **Seamless Listings**: Creator of the organization can seamlessly create job listings for users to browse.

4. 📲 **Effortless Applications**: Users can apply for jobs with the chosen organization with just a few clicks.

5. 🧾 **Proof-of-Experience**: Users can add an organization to their profile and verify their authenticity through Polygon ID.

6. 😉 **Cross-chain Minting**: Users upon proving their identity, can choose to mint their proof of experience on their selected destination chain.

7. ⛽ **Gasless**: Gas and most on-chain operations are abstracted from the user, prioritizing UI/UX.

## 🏛️ Architecture

![chainin-architecture](https://github.com/usechainin/.github/assets/42776950/89deccdb-b375-46e4-8cf3-88c051cbf7b3)

## 🧑🏻‍💻 Software

- **Chainlink CCIP**: We used Chainlink's CCIP to allow users to mint their proof-of-experience NFT on their selected destination chain. This provides versatility and enhanced UX for the user.
  
- **Polygon ID**: We implemented Polygon ID to let users verify their credentials through ZK proofs from their wallet so that we can airdrop the user a verified NFT that can be used to verify their authenticity before minting an organization's proof-of-experience NFT to their wallet.
  
- **The Graph**: We created a Subgraph to fetch the job applicant's data from the emitted event when a Job Application NFT has been minted. This allows job applicants to get confirmation of their successful application while providing the applicant's information to the employers.

- **Tableland**: We wanted a permissionless SQL-like on-chain database. We used their Studio & Console clients, SDK, and CLI to create, store, test, and manage tables & queries. Tables are hosted on Polygon Mumbai.

## 🛠️ Improvements

- **Feature Enhancements**:
  - **Social Posts, Comments & Likes**: Implement ChainIn's social network aspect to increase user engagement.
  - **User Portfolio Enhancements**: Add in features to the user profile page e.g. resume uploads, video introduction & showcase of user's verified NFTs.
  - **Resume File Uploads in Subgraph**: Include links to resume for employers to easily view job applicant's details.
  - **Cross-chain Minting Choices**: Increase DevOps to allow more network choices for cross-chain minting.
  - **Additional Tools**: Improve organization management tools to allow organization creators to better manage their organization page.

- **Latency Improvements**:
    - **Server-Side Optimization**: Improve server response times to reduce front-end load.
    - **Client-Side Efficiency**: Improve UX and UI performance.
    - **Framework Selection**: Evaluate more efficient frameworks and technology stacks.
    - **Caching with CDN**
    - **Micro API Optimization**

- **Gasless Transactions**: Gasless on-chain storing of data but at the cost of security.

## ⛔️ Limitations 

- **Team Dynamics**: We had to rework our team  and find a new member mid-hackathon due to the inactivity and lack of participation of our previous front-end developer.

- **Team Constraints**: Team of 3, each with full-time jobs, dedicating weekends and nights. We had to carefully plan for MVP and sacrifice certain requirements deemed secondary.

## 📬 Open Source

We welcome any feedback, improvements, and amendments to these repositories 🙌 

- [Frontend](https://github.com/usechainin/chainin-dapp) - A NextJS frontend dApp.
- [Smart Contracts](https://github.com/usechainin/smart-contract) - Smart Contracts for CCIP, Polygon ID.
- [Subgraph](https://github.com/usechainin/Subgraph) - Subgraph query endpoint.
- [Backend](https://github.com/usechainin/chainin-server) - A Server API connecting to the Tableland on-chain DB.
- [API Documentation](https://documenter.getpostman.com/view/31443216/2s9YkgCjsv) - Backend API Documentaton.

