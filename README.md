# Coinnu.com | Sui Mint tool

With this online tool you can

- mint your own currency on Sui network;
- mint tokens of your currency;
- update metadata of your currency.

# Development

To install dependencies:

```bash
yarn
```

To start a local dev server:

```bash
npm run start
```

# Notes

Publishing a package requires a Move bytecode.
To avoid bundling a compiler with the package, we use a precompiled bytecode.
User can select from different symbols which are used as module (snake_case) and witness (UPPER_CASE) names.
Additionally, in the same publish tx we want to set the metadata of the currency.
