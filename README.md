// SPDX-License-Identifier: MIT

pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract Davewin is ERC20 {
    constructor() ERC20("Davewin", "DAVE") {
        // supply = 2million
        _mint(msg.sender, 2000000000000000000000000);
    }
}
