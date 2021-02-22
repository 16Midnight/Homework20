# Homework20

Background
Your new startup has created its own Ethereum-compatible blockchain to help connect financial institutions, and the team wants to build smart contracts to automate some company finances to make everyone's lives easier, increase transparency, and to make accounting and auditing practically automatic!
Fortunately, you've been learning how to program smart contracts with Solidity! What you will be doing this assignment is creating 3 ProfitSplitter contracts. These contracts will do several things:


Pay your Associate-level employees quickly and easily.


Distribute profits to different tiers of employees.


Distribute company shares for employees in a "deferred equity incentive plan" automatically.

In order to do that we need to create 3 contracts, we are going to use  Solidiy leguage to create them and  deploy them in Remix IDE browser, Ganach and Metamask to simulate some transactions, after that we are going to  test all of them in the Testnet using Kovan network.

 1-First Contract objective

AssociateProfitSplitter contract. This will accept Ether into the contract and divide the Ether evenly among the associate level employees. This will allow the Human Resources department to pay employees quickly and efficiently.

The program contains a deposit  function that are going o distribute the same amount of ether between 3 employees.

The only requirements to run this program is to input the Wallet addresses of the employees in our case we use the one provide by ganache and Transact.

 Description slides  1 to 6  of the powerpoint
 
 2-Second contract objective
 
 TieredProfitSplitter in this one  will distribute different percentages of incoming Ether to employees at different tiers/levels. For example, the CEO gets paid 60%, CTO 25%, and Bob gets 15%. And if anything remaind is going back to the the employee with the higher percentage.
 
 Requirements are the same  of the first contract.
 
 Description slides 7 to 12 of the presentation
 
 3-Third contract objective
 
 Is a DeferredEquityPlan that models traditional company stock plans. This contract will automatically manage 1000 shares with an annual distribution of 250 over 4 years for a single employee.
 
 In this contract  we establish limitation buy time and amount of shares to distribute if the employee fulfill the requirements,  for that we were using  unlocks and require statements and  we tested it using the fastfoward function with a fakenow variable in order to do it properly.
 
 Description slides 13 to 17 
 
 On the slide 18 I copied  the contract addresses after tested them with Tesnet.
 
 




 
 
 
 
 


