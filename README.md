# Raspberry-Pi-DApp
A Static Decentralised File uploading application running on a Raspberry Pi Network

1. Intialized IPFS nodes
2. Edit IPFS config file with their peer Identifications
3. Set CalcDifficulty function to 1, in the consensus.go file of Ethereum
4. Initialize IPFS daemon in the crontab, such that it can automatically start the peer on boot.
5. Upload the src folder and contracts to IPFS
