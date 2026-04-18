# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`d2826cca`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`253ad594`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`253ad594`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`e9f5d128`)
  
