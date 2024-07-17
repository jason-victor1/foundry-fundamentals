# Foundry Fundamentals

I acquired the skills needed to start developing my smart contracts and protocols using the best web3 development tools and frameworks like Chainlink, Alchemy, and Foundry.

## Overview of Foundry
Foundry is a smart contract development framework known for its efficiency and modularity. It manages your dependencies, compiles your project, runs tests, deploys, and lets you interact with the blockchain from the command-line and via Solidity scripts. 

## Advantages of Foundry
- **Rust Compilation**: Leverages Rust for compilation by offering significantly faster build times compared to frameworks like Hardhat or Brownie.
- **Solidity-Based**: Entirely Solidity-based  by eliminating the need to learn other programming languages.
- **Comprehensive Documentation**: Provides extensive documentation by making it easier to understand and use.

## Development Tools
I used Visual Studio Code to write, test, deploy, and interact with smart contracts. Visual Studio Code is a versatile code editor that integrates well with Foundry and other web3 development tools.

By utilizing these tools and frameworks, I am able to efficiently develop and manage smart contracts and protocols.

## Setting Up the Development Environment with VS Code on Mac OS

### VS Code Development Environment
The VS Code development environment was set up using Mac OS. 

### VS Code Built-in Terminal Emulator
- **Command-Line Interface**: The built-in terminal emulator in VS Code provides a command-line interface (CLI) environment by allowing interaction with Mac OS.
- **Tools and Utilities**: This terminal enabled the running of various tools and utilities directly within VS Code.

### Git Installation and Update
- **Updating Git**: I updated the version of Git on my Mac OS to ensure compatibility and access to the latest features.

## Installing Foundry

Terminal has been set up.

### Steps to Install Foundry
1. Navigate to the [Foundry website](https://foundry.paradigm.xyz).
2. From the installation tab, fetch the command to install Foundry. The command will look something like this:
   ```zsh
   curl -L https://foundry.paradigm.xyz | zsh
   ```
3. Hit Enter after pasting this in your terminal.

### Verifying Your Installation
After running the curl command, an output will appear at the bottom of your terminal indicating the detected shell and that Foundry has been added to your Path. For instance, the output can be something like this:
```
Detected your preferred shell is bashrc and added Foundry to Path.
Run: source /home/user/.bashrc
Start a new terminal session to use Foundry.
```

### Updating and Installing Foundry Components
1. Type `foundryup` and hit Enter to install and update Foundry to the latest version. Whenever you want to install an update for Foundry, simply run `foundryup` again.
2. This will install four components: `forge`, `cast`, `anvil`, and `chisel`.

### Confirming Installation
To confirm the successful installation, run:
```bash
forge --version
```
You should get an output indicating the Forge version, as shown below:
```
Forge version x.x.x
```
