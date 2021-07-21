# HW 21 - Advanced Solidity- In this homework, I will create a ERC 20 token that minted through Crowsale contact. I am useing OpenZepppelin Solidity library to leverage the contract. I am using the two starter codes: Crowesdale.sol and PupperCoin.sol. 


## Smart contract code written in Remix 

![crowdsale_code](Image/crowdsale.png)

## Compile the contract 

![compile](Image/compile.png)

## Deploy the contract. 

    1.Change the enviroment to Injected Web3.
    2.Connect to Metamask (connct to one of the Ganache account,I have the banlance of 87.92 ethers).
    3.Click on Contract and choose "PupperCoinSaleDeployer-PupperCoin".
    4.Click on Deploy dropdown and fill in the name, Symbol, wallet and Goal(300ether in wei). then click the transact. 
    5.Open the deployed Contracts (Puppercoinsaledeployer) Copy the token_sale_address and paste it to PupperCoinSale - PuperCoinCrowdsale.osl contract "add address"copy
    6.Copy the token_address and paste it to PupperCoin-PupperCoin.sol contract "add address".
    
![deploy](Image/deploy.png)

![add_sale_address](Image/token_sale_address.png)   ![add_sale_address](Image/token_sale.png)

![add_token_address](Image/token_address.png)   ![add_sale_address](Image/token.png)  


## Using 10 Ether to buy 10 Puppcoin
![buy_token](Image/buy_token.png)

![buy_token](Image/metamask.png)


## My account balance is dropped from 87.92 down to 77.73 Ether 

![Account_balance](Image/balance.png)

