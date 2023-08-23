# Challenge-21
create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

# Deploy the KaseiCoinCrowdsale smart contract
For the purpose of crowdsale, a deployer contract KaseiCoinCrowdsaleDeployer was defined in the file named KaseiCoinCrowdsale.sol. The same file also contains the KaseiCoinCrowdsale contract. The deployer contract deploys KaseiCoin contract, which is the minter contract, and KaseiCoinCrowdsale contract - the crowdsale contract. The minting rights are passed on to KaseiCoinCrowdsale contract so that tokens can be purchased and minted at the same time.

The contracts are deployed using Remix IDE.


**Screenshots of contract steps**

![Image 4](https://github.com/Willykman/Challenge-21/blob/main/Image%204.png?raw=true)
![Image 5](https://github.com/Willykman/Challenge-21/blob/main/Image%205.png?raw=true)
![Image 6](https://github.com/Willykman/Challenge-21/blob/main/Image%206.png?raw=true)
![Image 6](https://github.com/Willykman/Challenge-21/blob/main/Image%207.png?raw=true)
# Technologies
The application is developed using:

Language: Solidity
Development Metamask, Ganache, Remix

# Contributors
William Korman with the help of the starter code, TA's and the weekly module
