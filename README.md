# first_dApp
Basics of creating a Truffle project and deploying a smart contract to a blockchain with Ganache Environment

# Create a new directory for your Truffle project:

mkdir MetaCoin
cd MetaCoin

# Download ("unbox") the MetaCoin box:

truffle unbox metacoin

# On a terminal, run the Solidity test:

truffle test ./test/TestMetacoin.sol

# Run the JavaScript test:

truffle test ./test/metacoin.js

# Compile the smart contracts:

truffle compile

# Download and install Ganache.

# Open truffle.js in a text editor. Replace the content with the following:

module.exports = {
  networks: {
    development: {
      host: "127.0.0.1",
      port: 7545,
      network_id: "*"
    }
  }
};




