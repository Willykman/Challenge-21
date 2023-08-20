# Challenge-21
create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

# Deploy the KaseiCoinCrowdsale smart contract
For the purpose of crowdsale, a deployer contract KaseiCoinCrowdsaleDeployer was defined in the file named KaseiCoinCrowdsale.sol. The same file also contains the KaseiCoinCrowdsale contract. The deployer contract deploys KaseiCoin contract, which is the minter contract, and KaseiCoinCrowdsale contract - the crowdsale contract. The minting rights are passed on to KaseiCoinCrowdsale contract so that tokens can be purchased and minted at the same time.

The contracts are deployed using Remix IDE.

Invoke Remix IDE - https://remix.ethereum.org/.
Open Files in the File section to navigate to and select KaseiCoinCrowdsale.sol
Click on compile icon to compile the contract
Deploy by clicking on the icon below the Compile icon.
Now click to the Metmask (fox) sign and select the account for deployment
Click on the Contract list to select the deployer contract
Fill the deployer fields
Get the wallet address from Ganache.
Click on Transact to Deploy
Now, deploy the crowdsale contract to Remix by following
click on crowdsale from the Deployed Contracts, and copy the address
select the crowdsale contract from the list of contracts
paste the address copied above at field next to At Address and click on At Address
Follow the same procedure as last 3 steps for the token contract
select KaseiCoin token
copy and paste the contract address and click At Address
You can see that now all the functions in both the contracts are visible now - KaseiCoinCrowdsale Contract, KaseiCoin
From here on you can run the various functions to purchase and track the tokens etc. See the Contract Deployment and Evaluation Evidence section above for the sample tests.

# Technologies
The application is developed using:

Language: Solidity
Development Metamask, Ganache, Remix

# Contributors
William Korman with the help of the starter code and the weekly module
