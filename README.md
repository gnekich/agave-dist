# agave-dist

If you are looking for a missing build `solana-release-aarch64-unknown-linux-gnu.tar` when running official solana install script, you are on the right spot.

There is issue [1734](https://github.com/anza-xyz/agave/issues/1734) still open for agave.

This repository is here to resolve this issue for now. It does not include anything other than build pipeline using Github actions...

## Misc

```bash
wget https://github.com/gnekich/agave-dist/releases/download/{{version}}/solana-release-aarch64-unknown-linux-gnu.tar.bz2
tar xjf solana-release-aarch64-unknown-linux-gnu.tar.bz2
cd ./solana-release/bin
./solana --version
```

## Special thanks

Thanks to [mindrunner](https://github.com/mindrunner)
