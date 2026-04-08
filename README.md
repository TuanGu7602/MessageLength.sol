# MessageLength.sol
MessageLength.sol5
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MessageLength {
    string public message;
    function length() public view returns(uint){
        return bytes(message).length;
    }
}
Add event logging contracts
Enhance security validation
Simplify function logic
Update contract version
