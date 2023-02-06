# Blockchain-Ledger
This code implements a smart contract in Solidity, a language for writing smart contracts for the Ethereum blockchain. The contract has a state variable for energy, carbon credits, and renewable energy certificates, and two functions: validateAndPackage and sell.

The validateAndPackage function takes in inputs for energy, carbon credits, and renewable energy certificates, validates them to make sure they're greater than 0, and updates the state variables with the validated inputs. It also emits a NewValidation event with the updated energy, carbon credits, and renewable energy certificates.

The sell function takes in inputs for energy, carbon credits, and renewable energy certificates, validates them to make sure they're less than or equal to the packaged quantities, and updates the state variables with the sold quantities.
