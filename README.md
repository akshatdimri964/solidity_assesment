DESCRIPTION 
For this assesment we have created a contract on solidity in order fulfil multiple rquirements like:-
public variables to store details of coin, ie-Token Name,Token Abbreviation,Token Supply
mapping of addresses to balances 
a mint function which takes two parameters: an address and value then increases the total supply by that number and increases the balance of the address by that amount.
a burn function that destroys tokens by taking an address and value just like the mint functions then deduct the value from the total supply and from the balance of the address.
Lastly, the burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

EXECUTION
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
The details of coins is stored
