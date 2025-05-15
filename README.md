# 🧠 Web3 Smart Contracts with Solidity

This repository contains my personal learning journey in Web3 development using **Solidity**.  
Each folder or file represents a smart contract created while exploring different topics, use cases, and best practices.

---

## 🚀 About

This is a growing collection of smart contracts developed using [Solidity](https://docs.soliditylang.org/) and tested in environments like [Remix IDE](https://remix.ethereum.org/) and [Hardhat](https://hardhat.org/) (coming soon).

The goal is to improve my understanding of:

- Ethereum and EVM-based development
- Smart contract design and architecture
- Common patterns like storage, modifiers, inheritance, events, etc.
- Real use cases such as tokens, voting, NFTs, and more

---

## 📁 Project Structure

```
/contracts
├── SimpleStorage.sol       # A basic contract to store and read values
├── Primitives.sol          # Demonstrates basic Solidity types and defaults
├── RegistroConAcceso.sol     # Access-controlled data storage with events
├── [More files coming soon...]
```

---

## 🧪 Tools Used

- Remix IDE (initial development)
- Visual Studio Code + Solidity extension
- Git and GitHub for version control
- (Planned) Hardhat for local testing and deployment

---

## ✅ Completed Contracts

- **SimpleStorage.sol**  
  Stores a single `uint256` value. Includes a constructor, set and get functions.
- **Primitives.sol**
  Demonstrates Solidity's primitive types like bool, uint, int, address, and bytes.
  Shows default values and common sizes (uint8, uint256, int8, int256, etc.). Useful for understanding low-level data types in Solidity.
- **RegistroConAcceso.sol**
  Access-controlled data registry that allows only the owner to update the stored data.
  Includes:
  - A modifier to restrict actions to the contract owner.
  - An event that logs old and new values when data changes.
  - A counter to track how many times the data was updated.
  - A function to transfer ownership.
    This contract helps practice modifiers, events, and basic role-based access control in Solidity.

More contracts will be added as I progress 📚

---

## 📌 How to Use

1. Clone the repository
2. Open any `.sol` file in VS Code (with Solidity extension installed)
3. Deploy and test in Remix or your preferred environment
4. Contributions and suggestions are welcome!

---

## 📜 License

MIT License — feel free to use and adapt the code.
