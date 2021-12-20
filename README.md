# Dchat
decentralized chat app

- i wrote a smart contract for group chat where can user write a message in any room and everybody who joins that room  can receive a message
- you can test smart contract functions  on https://remix.ethereum.org

- solidity does not provide any method for encryption 
so we can implement end-to-end security by ECDH with. etheriam uses "secp521r1" ECDH crave for generating private and public key, we can establish a connection by sharing shard key which is made of user private key and receiver public key. and send an encrypted message with this key so only receiver can decrypt that message by his private key
