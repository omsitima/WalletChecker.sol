# WalletChecker.sol
How to deploy a contract on Base Chain WalletChecker.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract WalletChecker {
    function checkBalance(address _addr) public view returns (uint) {
        return _addr.balance;
    }
}
