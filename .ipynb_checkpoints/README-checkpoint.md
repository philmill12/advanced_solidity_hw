# Advanced Solidity Homework

## PupperCoin 

This contract creates an ERC20Mintable token named PupperCoin, symbol "PUP", with an initial supply of 1,000,000 tokens. See screenshot below.

![remix_deployed_contract](screenshots/puppercoin_deployed_contract.png)

## PupperCoin Crowdsale

In order to deploy a contract that creates a crowdsale, I imported several OpenZeppelin contracts (crowdsale, mintedcrowdsale, cappedcrowdsale, timedcrowdsale, refundablepostdeliverycrowdsale).

Similar to the PupperCoin token creation, this contract sets the name and symbol. Additionally, this contract creates a crowd sale of PupperCoin (PUP) which you can estblish a fundraising goal, and a sale period that is open for 24 weeks.

![puppercoin_crowdsale_deployed_contract](screenshots/puppercoin_crowdsale_deployed_contract.png)
![puppercoin_crowdsale_deployed_contract_success](screenshots/puppercoin_crowdsale_deployed_contract_success.png)