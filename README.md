#Ethereum Access Control for multi-dapps platform

Many multi-contract platforms are using a 'on contract' access model, or some strategies for multi-access inside the contract itself.

The issue occurs when you need to change access inside dapps one by one.

This model creates an access manager, with 3 levels (p. ex. Administrator, Manager and User) for using with dapps. Thus you can easily mantain and manage the access control for your dapps, since for people accessing functions or contracts that access another contracts to execute functions.

## Files:

- OriginalMyAccessControl.sol:
  - Levels: SuperUser, Manager and User
  - Just add the addresses from users or contracts for any level
- testAccess.sol:
  - An example for testing access levels. If you own any of the addresses registered, you can test the access level.   
