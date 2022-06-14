<p align="center"><img src="https://github.com/HydroBlockchain/brand-kit/blob/main/hydroswap-logo.png?raw=true">

## HydroSwap Smartcontracts

## Deployment of HydroRouter.sol

Start with deploying the PancakeFactory contract.

Constructor Arguments:

```Arg0: Address to PancakeFactory```

```Arg1: Address to WBNB (0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c)```

Then set the init code hash. Get the value from the INIT_CODE_PAIR_HASH variable in the PancakeFactory contract.

Use optimized enabled with 500 runs (or else it might exceed the smart contract size limit).
