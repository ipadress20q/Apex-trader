APEX TRADER — Testnet prototype

This is an experimental, non-custodial frontend for Base Sepolia only.
It can connect to an injected EVM wallet, show native ETH balance, display/copy the wallet address, import ERC-20 token addresses, and request user-approved ETH/ERC-20 transfers.

IMPORTANT LIMITS
- Base Sepolia testnet only. Test assets have no real value. Never use this prototype with real funds.
- The Swap UI is intentionally disabled. It is not an exchange yet. Enabling swaps requires explicitly selected test tokens, verified liquidity/pools, integration testing, and an independent security review.
- Only the connected wallet can sign transactions. This app never requests or stores seed phrases/private keys.
- The source and Pages site are public if deployed from a free public GitHub repository. Wallet balances/addresses may be public on-chain; imported token list and activity history are stored in this browser only.
- No audit, legal review, company authorization, cross-chain transfers, fiat on/off-ramps, or automated notifications are included.
- On iPhone, use a compatible wallet's in-app browser for injected wallet access. Do not paste secret recovery phrases into any website.

Base Sepolia configuration (official docs): chain ID 84532, RPC https://sepolia.base.org, explorer https://sepolia.basescan.org.
