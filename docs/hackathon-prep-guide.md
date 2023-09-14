---
sidebar_position: 4
---

# Hackathon Prep Guide

Welcome to the inaugural ETH Chicago Hackathon. 
To help you make the most of this experience, we've put together a brief Hackathon Preparation Guide. 

First, a link to [The Hackathon Method by OpenUX](https://mirror.xyz/openux.eth/Z9CkF5Np4usTAt393Snq-fLN6BfZQkj-5_o6dy-XGoE).

This piece contains detailed data-driven advice for hackers participating in hackathons. 
We believe there's value for hackers of every experience level and recommend reading the report before the event.

Next, we present tips that have been honed over five years of hosting and participating in hackathons. 
While they may not answer every question you have, they're sure to make your time here more productive and enjoyable. 
Happy hacking!

## Before the Hackathon

### Understand the Theme and Rules

Make sure to familiarize yourself with our event's theme, [schedule](https://taikai.network/ethchicago/hackathons/ETHChicagoHackathon2023/timeline), and [guidelines](https://taikai.network/ethchicago/hackathons/ETHChicagoHackathon2023/rules). 
Many of our sponsors provide valuable perks such as free credits, bounties, or grants for using their services, so don't miss out on these opportunities. 
Additionally, having a clear understanding of the event's timeline will enable you to manage your time more effectively.

### Form Initial Teams & Ideas

Start brainstorming ideas ahead of the event but be open to change.

Assembling your team before the hackathon. 
If possible, meet up with your team ahead of time to discuss ideas, roles, and the skills each member brings.

### Repo setup

Create a shared folder or repository where you can quickly access useful resources, code snippets, or other essential files.

## During the Hackathon

**Pick A Chain**

Every chain has its own tooling, ecosystem, and tech stack. 
For example, switching from Ethereum to Starknet or Solana to Sui is not trivial.

If you're a beginner our suggestion is to start with Ethereum.

**Programming Languages**

Each chain uses its own set of programming languages. Common languages include:

* EVM compatible: Solidity, Vyper, Huff, Yul 

* Rust compatible: Rust, Move (Rust based), Cairo (Rust Inspired)

* Haskell: Cardano

Check out this guide about [web3 programming languages](https://www.alchemy.com/overviews/web3-programming-languages#8-haskell).

**Tech Stack**

Web3 development involves blockchains (as the server) and clients:

* An essential part of web3 development is deploying to a chain, and then ensuring it operates as expected.

* The second part is to call service from a client.

The chain is now the server, while the client remains the client.

On the “server” side, you’ll need

* A Virtual Machine (VM) to run code. 
In Ethereum it's known as the EVM or Ethereum Virtual Machine.

* Various tools to write, compile, and test your code. 
Using Solidity as an example, you may use an online IDE such as Remix or ChainIDE. An online IDE can be a great place to begin for simple contract deployment. 
            
* A Local Framework such as Truffle, Hardhat, or Brownie.
Any of these options satisfy serious web3 development. 
Frameworks often require terminal installation but are powerful.

* A wallet to interact with the blockchain and deploy your contract. 
All wallets require tokens. 
Popular wallets include:
    - MetaMask
    - Trust Wallet
    - Coinbase Wallet

On the “client” side, you’ll need:
    
* A node. Nodes are the connecting point of the blockchain. You need to connect to a node to query and update the data in the blockchain. Popular nodes include: 
    * EVM: Infura, Alchemy, QuikNode

    * Near Protocol: NEAR Nodes
    
    * Solana: Helius, QuickNode

* APIs are your friend. Some libraries simplify the node communication process to one line of code. For example, to talk to an Ethereum node, you may use 
        
    * Web3.js or Ether.js for [JavaScript](https://ethereum.org/en/developers/docs/apis/javascript/#available-libraries)

    * Web3.py, Go, or Geth for Python

* An App such as Uniswap, Aave, Compound, or OpenSea to access and update on-chain data, which is connected through a wallet. 
        
    
    [Ethereum Stack](https://ethereum.org/en/developers/docs/ethereum-stack/)

### Be Realistic and Strategize

Be mindful that the hackathon is only for a few hours. 
You don’t have time for a perfect product; so build an MVP. 
Narrow the scope of your product. 
Focus on building one core function of your product. 
Understand the hackathon timeline, form your team, and roughly plan the hours ahead. 
Break down tasks and assign them based on skill sets. 
Keep an eye on the clock! 
Allocate time for testing, debugging, and submitting the project! (It can take an hour or more).

### Use Your Resources

**Network:** 

Take time to visit the booths and meet other participants. 
You never know what you could learn, or who you could meet.

**Meet the Mentors:** 

Many hackathons have experienced mentors on hand. 
Say hello and don't hesitate to ask for help or guidance.

### Pitch your Project

It's crucial to be well-organized and direct given that you have 4 to 5 minutes for your pitch.
Get straight to the point. 
Crafting an effective pitch can be as important as the project itself. 
A well-told story can make your presentation compelling and memorable. 
Based on our past experience, a successful pitch typically includes:

1. **A Hook (30s)**: Grab your audience's attention with a startling fact, statistic, or question that pertains to the problem you're solving.

2. **Set the Scene (30s)**: Provide context for the problem you’re solving. 
Use human stories or scenarios to make it relatable.

3. **Conflict and Resolution (30s)**: Describe the problem as a conflict that needs resolving. 
Then, introduce your project as the solution to this conflict.

4. **Climax (60s)**: Build up to a key point or major reveal that resolves the initial conflict you set up.

5. **Show, Don't Just Tell (90s)**: Show a live demo of your product to prove that you have solved the conflict. 

6. **Closing (30s)**: End with a strong takeaway message, which could be a call to action, and a memorable quote or a powerful restatement of the problem and your solution.

### How to DEMO your product?

Typically, you'll be expected to incorporate a product demo into your pitch, often with a time limit of around 2 minutes. 
So, how can you execute this demo in a way that most effectively compliments your pitch?

1. **Plan the Flow**: Plan how your demo integrates into your pitch. 
Should it come at the beginning to grab attention, or as the climax after you've set the stage?

2. **Keep It Short**: You'll usually have limited time so get to the point. 
Only show the most important and impressive features.

3. **Walk Through a Scenario**: Use a real-world scenario to demonstrate how your product solves a problem. 
This helps in making the application of your project relatable.

4. **Explain as You Go**: Don't just show—tell. 
Explain what you're doing and why it's important as you go through the demo.

5. **Data and Feedback**: If you’ve been able to collect any user data or feedback, share this to show that you've validated your solution to some extent.

6. **Fallback Plan**: Always have a backup plan in case the demo doesn't go as planned. 
This may include screenshots, videos, or even well-prepared slides to save the day.

## After the Hackathon

### Keep Building

Hackathons can be the birthplace of fantastic new ideas and projects. 
Don't let it end there; continue to build and improve upon your project.

### Stay Connected

Stay in touch with the people you've met, the organizers, and mentors. 
You never know when these connections may come in handy.

### Have a Great Time

Most importantly, have a blast!
Hackathons are fast and furious.
They can be stressful by their very nature.
Keep a positive attitude and remain flexible to changes in the initial plan.

Let us know if you found this guide helpful, and share any tactics you've used to create a meaningful hackathon experience.