# BlockBase Project

## Project Overview
BlockBase is a blockchain-based expense tracking and debt management application mentored by FEC. This project implements smart contract functionality to register users, track expenses, and manage financial interactions between users on the Ethereum blockchain.
![Alt-Text](https://github.com/vivek16-mdev/Expense_Tracker_FECIITG/blob/main/Screenshot%202025-04-20%20221225.png)
## Feature Implemented
-Get total number of registered people
``` 
function isUserRegistered(address _addr) public view returns (bool) {
     return people[_addr].walletAddress != address(0);
 }
```
### Solidity Features
- **Get User Name**: Users can retrieve their registered name using their wallet address
- **Update User Name**: Functionality for users to update their registered name

### JavaScript Features
- **Display Connected Wallet Address**: Shows the currently connected Ethereum wallet address
- **Show User's Name**: Displays the current user's registered name from the blockchain

## Technologies Used
- Solidity (Smart Contracts)
- JavaScript/React (Frontend)
- Web3.js (Blockchain interaction)
- MetaMask (Wallet connection)
