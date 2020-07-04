# Raspberry-Pi-DApp
A Static Decentralised File uploading application running on a Raspberry Pi Network

1. Intialized IPFS nodes
2. Edit IPFS config file with their peer Identifications
3. Set CalcDifficulty function to 1, in the consensus.go file of Ethereum
4. Initialize IPFS daemon in the crontab, such that it can automatically start the peer on boot.
5. Upload the src folder and contracts to IPFS

Published paper DOI : 10.36548/jitdw.2020.1.003

Link : https://www.irojournals.com/itdw/V2/I1/03.pdf

Dependencies

Geth v1.8.14-stable

Go vgo1.11

ipfs v0.4.18

Metamask v7.2.0

Node v10.12.0

Solidity v0.5.12 (solc-js)

Truffle v5.1.5 (core: 5.1.5)

Web3.js v1.2.1
