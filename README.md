# EVM-Subnet-using-Avalnche-cli

Welcome to the GitHub repository for our Avalanche DeFi Kingdoms Clone! This project is a blockchain-based game where players can collect, build, and earn rewards through various game activities. The game is deployed on the Avalanche blockchain, specifically utilizing a custom EVM subnet to provide a unique and scalable gaming experience.

## Overview

This game clone is inspired by the popular DeFi Kingdoms game but adapted for the Avalanche ecosystem. Players will interact with the game through a series of smart contracts which allow them to mint and trade digital assets, participate in quests, and earn rewards.

## Tools Used

To participate in or contribute to this project, you will need the following tools:

- Unix Computer (MacOS or Linux)
- Solidity (for smart contract development)
- Remix (IDE for Solidity)
- Metamask (cryptocurrency wallet)
- Web Browser (Chrome, Firefox, etc.)

## Project Setup: Step by Step

Follow these steps to set up the project on your local environment and begin interaction:

### Step 1: Deploy Your EVM Subnet Using Avalanche CLI

First, ensure you have the Avalanche CLI installed. Deploy your own EVM subnet:

```bash
avalanche subnet create --name mysubnet
```

### Step 2: Add Your Subnet to Metamask

Add the new subnet information to Metamask:

- Open Metamask and navigate to Networks.
- Select "Custom RPC".
- Enter the details of your deployed subnet.

### Step 3: Make Sure It Is Your Selected Network in Metamask

Ensure that your newly added subnet is selected as the active network in Metamask.

### Step 4: Connect Remix to Your Metamask

To deploy your smart contracts:

- Go to [Remix](https://remix.ethereum.org).
- Connect Remix to Metamask using the "Injected Provider" option.

### Step 5: Deploy the Smart Contracts

In Remix, load your Solidity smart contracts and deploy them to your subnet.

### Step 6: Test Your Application

Now that your contracts are deployed, interact with them directly from Remix or through a frontend interface to test the game functionalities. Make sure to deploy tokens, pools, and more to see how they function within the game.

## Testing

Ensure to test all aspects of your application thoroughly. Testing can include:

- Minting and trading assets.
- Reward mechanisms.
- Interaction with different pools.

## Contributing

Contributions are welcome! Please read the CONTRIBUTING.md file for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to clone, star, and contribute to this repository to make the Avalanche DeFi Kingdoms Clone even better! Enjoy building and enhancing your version of a blockchain-based game!
