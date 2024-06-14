# Coordinate : Bitcoin Layer 2 Sidechain

## Introduction
Coordinate is a UTXO-based Bitcoin sidechain forked from the Bitcoin Core v.26 codebase. It is backwards compatible with Bitcoin Script and contains additional transaction versions and RPC calls. These transaction types are engineered to provide increased flexibility and functionality to the native features of bitcoin. Coordinate supports native UTXO-based digital assets and tokens, modeled after the BitAssets architecture by Paul Sztorc.   
## Assets
Assets on coordinate are transferred natively and enforced by consensus via Script and support optionally prunable on-chain data blobs. Consensus is achieved by a hybrid Proof-of-Work and Proof-of-Authority mechanism, which directly pays mainchain Bitcoin SHA-256 merged-miners in Coordinate’s native bitcoin-pegged asset. Coordinate offers the option of premium transacting; which allows users to avoid fee bumps, pay only the minimum required for inclusion into a block, receive 2-minute certainty over success or failure, and benefit from MEV resistance.  
## Usage
To interact with Coordinate, users peg in (deposit) TBTC (Testnet bitcoin) with the Collective, a consortium of entities recruited to administer peg ins and peg outs to Anduro sidechains. Deposits are secured by a super majority of the Collective. Users are credited CBTC (Coordinate bitcoin) that is redeemable via the Collective at a 1:1 ratio for TBTC.  
## Pegin (_fuding_)
CBTC(s) allow users to perform Bitcoin-like transactions on the Coordinate sidechain: P2PK, P2MS, P2PKH, P2SH, P2WPKH, P2WSH, P2TR, among others. This is useful for users who desire more frequent settlement with average lower fees than what Bitcoin’s mainchain can offer. Coordinate implements version 10 transactions which facilitate the creation of on-chain assets. 
## Disclaimer
*All Anduro sidechains remain in a closed beta. Registrants of this hackathon will be receiving exclusive pre-launch access and are among the first to innovate on the Anduro ecosystem*

## Links
[Coordinate Sidechain Node (SRC)](https://github.com/AnduroHackathon/coordinate-node)
[Coordinate Wallet (chrome)](https://chromewebstore.google.com/detail/anduro-wallet/khebhoaoppjeidmdkpdglmlhghnooijn?pli=1)
[CBTC Faucet](https://faucet.coordiscan.io)
[Paul Sztorc - Bit Assets](https://www.truthcoin.info/blog/bit-assets/))
