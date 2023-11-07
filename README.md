# NoobChain 
A simple Java blockchain with transactions, for a  simple crypto-currency “NoobCoin” because why not.
- Allows users to create wallets with ‘new Wallet();’
- Provides wallets with public and private keys using Elliptic-Curve cryptography.
- Secures the transfer of funds, by using a digital signature algorithm to prove ownership.
- And finally allow users to make transactions on your blockchain with eg.‘Block.addTransaction(walletA.sendFunds( walletB.publicKey, 20));’

# Dependencies: You will need to import Both Bouncy castle and GSON:
- bouncy castle [bcprov-jdk15on-159.jar ](https://www.bouncycastle.org/download/bcprov-jdk15on-159.jar)
- gson [gson-2.8.2.jar](http://central.maven.org/maven2/com/google/code/gson/gson/2.8.2/gson-2.8.2.jar)

# Java Version:
- *JDK1.8.0_77*


