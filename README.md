#### My Uniswap ####
## Architecture ##
- `swap`
- `modifyPosition`
- `donate`
- `take`
- `settle`
- `mint`

## Repository Structure ##
contracts/
----interfaces/
    | IPoolManager.sol
    | ...
----libraries/
    | Position.sol
    | Pool.sol
    | ...
----test
...
PoolManager.sol
test/
----foundry-tests/