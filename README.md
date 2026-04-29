# BoolToUint.sol
BoolToUint.sol
pragma solidity ^0.8.20;
contract BoolToUint {
    function convert(bool x) public pure returns(uint){
        return x ? 1 : 0;
    }
}
