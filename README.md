# erc20-token-TXP

A simple Smart Contract for a Standard, Capped, Mintable, Burnable, Payable ERC20 Token.

Token has a Role Based Access Control so you can add the `MINTER` permission to users or Smart Contracts.

Token has a `trasferEnabled` property. Nobody can transfer tokens until the property will be enabled or you can define users as `OPERATOR` allowed to transfer also if not enabled.

Token has the ERC1363 behaviors. [ERC1363](https://eips.ethereum.org/EIPS/eip-1363) is an ERC20 compatible token that can make a callback on the receiver contract to notify token transfers or token approvals.

## License

Code released under the [MIT License].
