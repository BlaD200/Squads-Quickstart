https://docs.squads.so/main/v/development/introduction/quickstart

### Install solana
`sh -c "$(curl -sSfL https://release.solana.com/v1.18.12/install)"`

### [Install Node.js](https://nodejs.org/en/download/package-manager)

### Install yarn
`npm install --global yarn`

### Download packages
`yarn install`

### Create wallet
```mkdir ~/my-solana-wallet
solana-keygen new --outfile ~/my-solana-wallet/my-keypair.json
solana config set --keypair ~/my-solana-wallet/my-keypair.json
solana airdrop 1
```

### Start localnet
`sh ./runlocalnet.sh`

### Run test
`npm test`

