## Requirements

The following are the requirements to run this library:

- Rust
- Cargo

To install the required tools, I recommend using [rustup](https://rustup.rs/).
There, you will find this instruction:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Cloning the repository

To clone the repository, you can use the following command:

```bash
git clone https://github.com/tridims/cryptocurrency-wallet.git --recurse-submodules
```

## Folder Structure

The repository is structured as follows:

- `crypto-wallet`: The main library containing the wallet implementation.
- `mnemonic-vault`: A library to store and encrypt mnemonics.
- `speck-cipher`: A library to encrypt and decrypt data using the Speck cipher.
