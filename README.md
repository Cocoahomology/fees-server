# Fees and Revenue

### Guide
There is a guide for how to add a fee adapter listed [here](https://docs.llama.fi/list-your-project/how-to-add-a-fee-adapter).

### Cloning
Clone this repo with `git clone --recursive`. If you have already cloned it use `git submodule update --init`

### Protocol ids

Taken from `protocols/data` matching category or `protocols/chains`

### Adding a new adapter

To add a new adapter
- write adapter to `src/adaptors`, helpful to reference existing ones
- add adapter path to `src/adaptors/index`, and `utils/adaptors`
- test using `npm run test-fees uniswap` with protocol id
