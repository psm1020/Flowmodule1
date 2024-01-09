
# MyContract Smart Contract


This is a simple smart contract written in the blockchain programming language called Cadence.


## Description

This smart contract defines a Person struct and a dictionary called people that maps String keys to Person values. The smart contract also includes two functions: addPerson and getPerson.

The Person struct has two fields: name, which is a String representing the name of the person, and age, which is a UInt32 representing a unique identifier for the person.

The addPerson function takes two arguments: _name, a String representing the name of the person to add, and _age, a UInt32 representing a unique identifier for the person. The function creates a new Person instance with the specified name and number, and adds it to the people dictionary.

The getPerson function takes a single argument: _name, a String representing the name of the person to retrieve. The function retrieves the Person instance from the people dictionary with the specified name, and returns it.

The smart contract includes an init function that initializes the people dictionary to an empty dictionary.
 

## Requirements

To run this code, you will need the following:

1)A Flow account with sufficient FLOW tokens to pay for the transaction fees

2)The Flow CLI tool installed on your machine

3)A code editor or IDE for modifying the code
## Usage

To use this smart contract, you will need to have access to a blockchain environment that supports Cadence smart contracts. One example of such an environment is the Flow Playground, which allows you to write and test Cadence code in a web-based IDE.

To deploy the smart contract to the blockchain, you can use the flow project deploy command provided by the Flow CLI. Once the smart contract is deployed, you can interact with it using the addPerson and getPerson functions.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This code was inspired by the Flow NFT Tutorial on the Flow documentation website. Special thanks to the Flow team for creating such a powerful and developer-friendly blockchain platform!
