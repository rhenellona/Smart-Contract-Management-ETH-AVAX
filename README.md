# Smart Contract Management

A simple contract which values of the functions are shown i the frontend of the application. 

## Description

This project is a simple fund manager contract, which allows the owner/user to deposit, withdraw fund from the account. 

## Source
Used the SCM-Starter template of Sir Chris from Metacrafters. 
[SCM-Starter Files](https://github.com/MetacrafterChris/SCM-Starter.git)

## Usage/Features

1. Allows secured management of funds, wherein the owner is the one allowed to deposit and withdraw funds.
2. It Provides essential functionalities, such as providing security and transparency. 
3. It utilizes custom error handling, by preventing data modifications providing error messages if certain conditions are not met. This ensures that the funds withdrawn is from an authorized access. 

### What to do before executing program?

* Create and organize your codes in your desired source-code editor.
* Activate/Login to your Metamask Wallet.
* Create your own network.
  
### Executing Program 
* After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/

Once you are in [here](http://localhost:3000/) following the ff steps:

1. Connect your Metamask wallet to your contract.
2. Make sure youre connected to the correct network and account.
3. Feel free to withdraw and deposit!

### Additional Files / File requirements

* GitBash
* Node.js

## Authors

Rhene F. Llona
email : 8213812@ntc.edu.ph


## License

Unlicensed.
