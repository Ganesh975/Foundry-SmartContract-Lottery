# LotterySmartContract

## Project Overview
LotterySmartContract is a blockchain-based smart contract project developed using Solidity and deployed on the Ethereum Sephola test network. It provides a decentralized solution for conducting transparent and secure lotteries, ensuring fairness and trust among participants.

## Functionality
- **Ticket Purchase**: Users can buy lottery tickets by interacting with the smart contract.
- **Random Selection**: The smart contract autonomously selects a random winner from the pool of participants at predefined intervals.
- **Prize Distribution**: Upon selecting a winner, the smart contract transfers the prize money to the winner's account automatically.
- **Continuous Operation**: The process of ticket purchase, selection, and prize distribution repeats automatically for each lottery cycle.

## Need
- **Transparency**: Blockchain technology ensures transparency by recording all transactions on a decentralized ledger, preventing any manipulation of lottery results.
- **Security**: The immutability of blockchain ensures that once recorded, lottery results cannot be altered, providing a secure environment for participants.
- **Trust**: The automated selection process eliminates human biases and ensures fairness for all participants, fostering trust in the lottery system.

## Technologies Used
- **Solidity**: Solidity is used for developing smart contracts on the Ethereum blockchain, providing the logic for ticket purchase, selection, and prize distribution.
- **HTML/CSS**: HTML and CSS are used for developing the frontend user interface, allowing participants to interact with the lottery system.
- **VRFConsumerBaseV2 and VRFCoordinatorV2Interface**: These contracts are utilized for generating random numbers securely, ensuring the randomness and fairness of the lottery selection process.

