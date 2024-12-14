# Crypto Clash

A decentralized Rock Paper Scissors game built with Solidity, Web3.js, and an ERC-20 token called MemeCoin. Players can join, make moves, and win rewards in MemeCoins. The game is interactive and styled for an engaging experience.

---

## Features

- **Claim Initial Tokens**: Players can claim 100 MemeCoins for free.
- **Join Game**: Two players can join the game by paying an entry fee in MemeCoins.
- **Make a Move**: Players can choose Rock, Paper, or Scissors to compete.
- **Determine Winner**: The smart contract determines the winner and transfers rewards.
- **Reset Game**: Players can reset the game for a fresh start.
- **Live Updates**: Player and balance information can be refreshed dynamically.

---

## Smart Contract Details

- **RockPaperScissors Contract**: Manages the gameplay, player states, and rewards.
- **MemeCoin Contract**: Handles the ERC-20 token used for payments and rewards.

### Contract Features

1. Players join by paying an entry fee in MemeCoins.
2. The game resolves based on the standard Rock-Paper-Scissors rules.
3. Winner receives the pot and additional rewards.

---

## Contract Details

- **Contract Address**: `0x401fF791402AcBCD4D6B96F74088Da4DfA671251`
- **Network**: Mantle Sepolia Testnet
## Deployment

- **Contract Address**: [View on Explorer](https://sepolia.mantlescan.xyz/address/0x401ff791402acbcd4d6b96f74088da4dfa671251)
- **Coin Used**: MNT

## User Interface

The frontend is designed for simplicity and engagement:

- **Responsive Design**: Fully responsive, optimized for both desktop and mobile.
- **Custom Buttons**: Interactive buttons styled with vibrant colors and hover effects.
- **Game Moves**: Rock, Paper, Scissors moves are represented with images.
- **Live Player Tracking**: View player addresses and refresh player status dynamically.

### Key Sections

1. **Balance**: Displays the user's MemeCoin balance.
2. **Players Joined**: Shows current players in the game with a refresh button.
3. **Game Controls**: Includes buttons for joining, making moves, determining the winner, and resetting the game.

---

## How It Works

1. **Claim Tokens**: Users can claim 100 MemeCoins to get started.
2. **Join Game**: Two players join by transferring an entry fee in MemeCoins.
3. **Make Moves**: Players select Rock, Paper, or Scissors.
4. **Determine Winner**: The contract evaluates the moves and transfers rewards.
5. **Reset Game**: Allows a fresh start for a new game.

---

## Technologies Used

- **Solidity**: For the smart contract logic.
- **Web3.js**: To interact with the Ethereum blockchain.
- **HTML, CSS, JavaScript**: For the user interface.
- **ERC-20 Standard**: Used for MemeCoin.

---

## Game Rules

- **Rock beats Scissors**.
- **Scissors beat Paper**.
- **Paper beats Rock**.
- If both players choose the same move, the game is a draw, and their stakes are refunded.

---

## Screenshots

<img width="1440" alt="Screenshot 2024-12-13 at 1 56 15 AM" src="https://github.com/user-attachments/assets/e1ce0526-087b-4706-80d0-619a69ac4980" />

<img width="1440" alt="Screenshot 2024-12-13 at 1 56 26 AM" src="https://github.com/user-attachments/assets/9c9417af-d485-4bb7-9928-e77f3b3dd1e1" />

<img width="1427" alt="Screenshot 2024-12-14 at 4 36 43 PM" src="https://github.com/user-attachments/assets/99c674e5-007b-41a2-b6cc-4d4495cf1bbd" />








