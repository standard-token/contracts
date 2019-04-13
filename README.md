### A Standard Token for a new Token Standard.
### ---------------------------------------------------------------------------------------

## Main components:

### 1. Standard Token (STT): 

Standard Tokens are provided with a liquidity mechanism that ensures they are fully convertible into other tokens in the network. 
Each Standard Token is balanced in response to a connected token, e.g. STT holds ETH.


### 2. Standard Converter:

The Standard Network Tokens are smart contracts which enable a decentralized exchange mechanism of ERC20 
tokens on the Ethereum blockchain to solve the problem of centralized exchanges. All transactions, purchasing and 
selling, are completed through the smart contract on the Ethereum blockchain. So the Standard Token will minimized 
the trading risk to zero.

Unlike an exchange, the Standard Network has no order book. The price of the Standard Token will be calculated by the reserve balance. 
Thanks to the Standard Network, users perform token conversions against smart contracts (Converter). Users can buy and sell the Standard Token 
without a need for corresponding bid and buy orders.

### 3. Token Connector Contract:

A Connector Token  is an ERC20 compliant Standard token, enabling conversions between STT and a connected token (e.g. STT-eBTC Connector). 
Owner of the Connector Contract is a new Standard Converter, holding STT and a further Token  (e.g. eBTC).

Using an on-chain transaction, STT can be converted in any connected token in the network and vice-a-versa. 
The new Standard Converter holds two balances, each of them has 50 % weight.

General example: The converter holds 100.000 eBTC (price: USD 0.10) and 200.000 Standard Token (price: USD 0.05). 
If a user now would like to buy 1 eBTC from this Token Connector Contract, the user has to send the Converter 2 STT.

After this transaction, the Converter holds 99.999 eBTC and 200.002 STT.

Thus, the transaction has definitely changed the conversion rate between the two token.



