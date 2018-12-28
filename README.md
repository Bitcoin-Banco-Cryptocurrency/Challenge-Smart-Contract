<p align="center">
  <a href="https://www.btc-banco.com">
      <img src="https://s3.amazonaws.com/assinaturas-de-emails/btc.png" alt="Grupo Bitcoin Banco"/>
  </a>
</p>

## Challenge for Smart Contract Developer

A client needs to create an new smart contract to generate lunch simple ICO

Based on ERC20 Standard 

```
// ----------------------------------------------------------------------------
// ERC Token Standard #20 Interface
// https://github.com/ethereum/EIPs/blob/master/EIPS/eip-20.md
// ----------------------------------------------------------------------------
contract ERC20Interface {
    function totalSupply() public view returns (uint);
    function balanceOf(address tokenOwner) public view returns (uint balance);
    function allowance(address tokenOwner, address spender) public view returns (uint remaining);
    function transfer(address to, uint tokens) public returns (bool success);
    function approve(address spender, uint tokens) public returns (bool success);
    function transferFrom(address from, address to, uint tokens) public returns (bool success);

    event Transfer(address indexed from, address indexed to, uint tokens);
    event Approval(address indexed tokenOwner, address indexed spender, uint tokens);
}
```

you will need to develop:

- a simple smart contract implementing all interface functions available on ERC20;
- it should be possible to search your contract on Rinkeby Network;
- it should be possible to use any your contract functions trough metamask, web3...;

The test should be done in solidity and we do like if you avoid older versions. 

Remember that at the time of the evaluation we will look at:

- Code organization;
- Maintenance;
- Version control knowledge;
- Design Pattern ( Plus );

To send us your code, you must:

Make a fork of this repository, and send us a pull-request.
