# Solana Program

- [See front-end](https://github.com/KevinFiorentino/angular-solana-chat)

### Deploy program

- `anchor build`
- `solana address -k target/deploy/solana_nft-keypair.json`
- Replace Program ID in `lib.rs` and `Anchor.toml`
- `anchor build` (again)
- `anchor deploy`

### Test

- `anchor test --provider.cluster localnet`
- `anchor test --skip-build --skip-deploy`
