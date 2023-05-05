# Anchor

## Version

```bash
# rustup default 1.60

# solana
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
# solana-install init 1.14.16

# anchor (latest anchor may not be compatible with stable solana)
cargo install --git https://github.com/project-serum/anchor avm --locked --force
avm install latest
avm use latest
# avm install 0.27.0
# avm use 0.27.0
```