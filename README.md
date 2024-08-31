7EmpestToken

O 7EmpestToken é um contrato inteligente ERC-20 implementado na rede blockchain Sepolia Testnet. 
Este contrato cria e gerencia um token chamado "7Empest Coin" com o símbolo "7Empest" e 2 casas decimais.

Características:

Total Supply: 30.000.000 tokens.
Funções Principais:
transfer: Transfere tokens entre endereços.
approve: Aprova um endereço para gastar tokens em nome do proprietário.
transferFrom: Permite que um endereço transfira tokens de outro endereço.
approveAndCall: Aprova e chama uma função em um contrato de callback.a rede Ethereum desejada (Mainnet, Testnet como Sepolia, ou uma rede local).
Interagir com o Contrato:

Implementação:

**Endereço do Contrato na Sepolia Testnet:**
- [Ver Contrato no Etherscan](https://sepolia.etherscan.io/address/0x4474b9605f7ea6b35e623d7d03c75a17329837a6)
Código do Contrato: Disponível no arquivo token.sol.

Exemplos de Uso
Transferência de Tokens:
solidity
function transfer(address to, uint tokens) public returns (bool success);

Aprovação e Transferência de Tokens:

function approve(address spender, uint tokens) public returns (bool success);
function transferFrom(address from, address to, uint tokens) public returns (bool success);

Aprovação e Chamada:

function approveAndCall(address spender, uint tokens, bytes data) public returns (bool success);

Links Úteis:
https://metamask.io/​ 
https://rpc.info/   
https://remix.ethereum.org/
https://faucets.chain.link/sepolia
https://sepolia.etherscan.io/



