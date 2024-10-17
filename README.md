# Mitosis

Mitosis is an Ecosystem-Owned Liquidity (EOL) blockchain that empowers newly created modular blockchains to capture Total Value Locked (TVL) and attract users through its governance process.

## About the repository

The `mitosis-public` repository exposes certain parts of code (particularly interfaces) during active development. \
All code is copied from the [protocol repository](https://github.com/mitosis-org/protocol), which is currently private.

Check [Developer Docs](https://docs.mitosis.org/docs/developers/overview) for more guides.

## Getting Started

### Prerequisites

- Git
- Yarn
- Solc
- Foundry (for `forge` and `cast` commands)

### Installation

1. Clone the repository and its submodules:

   ```bash
   git clone https://github.com/mitosis-org/protocol-public --recursive
   cd protocol-public
   ```

2. Install dependencies:

   ```bash
   yarn install
   ```

3. Install dependencies via soldeer:

   ```bash
   forge soldeer install
   ```

4. Build the project:

   ```bash
   forge build
   ```

### Documentation

```bash
forge doc --build --serve
```

## License

MIT
