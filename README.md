# MY TOKEN SMART CONTRACT SOLIDITY
The MyToken contract is a simple implementation of a custom token on the Ethereum blockchain. It allows for the creation and destruction of tokens through minting and burning functions, respectively. 
Below are the key components and functionalities of the contract:

Public Variables:

tokenName: A string representing the name of the token (e.g., "MyToken").
tokenSymbol: A string representing the symbol of the token (e.g., "MTK").
tokenSupply: A uint256 variable tracking the total supply of the tokens, initialized to 0.
Mapping:

addressBalances: A public mapping that associates each address with its token balance, allowing anyone to check the balance of any address.
Mint Function:

mint(address _to, uint256 _amount): A function to create new tokens.
Increases tokenSupply by _amount.
Increases the balance of _to address by _amount.
Burn Function:

burn(address _from, uint256 _amount): A function to destroy tokens.
Checks if _from address has at least _amount tokens.
Decreases tokenSupply by _amount if the balance is sufficient.
Decreases the balance of _from address by _amount.



Acknowledgements:
*Ethereum Community: For the continuous development and support of the Ethereum platform and its related technologies.
*Solidity Documentation: For providing comprehensive guides and references that were instrumental in developing this contract.
*OpenZeppelin: For their open-source libraries and educational resources on smart contract development.
*Online Tutorials and Courses: Various online resources and educators who have created tutorials and courses on Solidity and smart contract development.






