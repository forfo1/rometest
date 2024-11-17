// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract RomeToken is ERC20 {
    constructor(
        string memory name,     // 토큰 이름 (e.g., "Changki, Aeithr")
        string memory symbol    // 토큰 심볼 (e.g., "Queen, ATH")
    ) ERC20(name, symbol) {
        _mint(msg.sender, 100000 * 10 ** decimals());
        
    }
}
