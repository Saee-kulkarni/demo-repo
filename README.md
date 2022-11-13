  hello this is my first file
pragma solidity ^ 0.7.0;
contract Banckcontract{
    uint banckbalance=5000;
    function deposit(uint x)public{
        banckbalance=banckbalance+x;
    }
    function withdraw(uint x)public{
        banckbalance=banckbalance-x;
    }
    function showbanckbalance ()public view returns (uint){
        return banckbalance;
    }
}
