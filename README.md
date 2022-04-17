pragma solidity ^0.8.0;

import "https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol";

contract WILLSMACK IS ERC209 {
    constructor(uint256 initialsupply) public ERC20 ("WILLSMACK", "WILLS")
_mint(msg.sender,initiualsupply); }
{
