# Starknet Basecamp NearX

## Config

> [Config](https://www.youtube.com/watch?v=UzRHehWDdow)
>
> [Doc](https://docs.google.com/document/d/17hMrdu_0tbsj86R7evSeb6WXEuQEKINby2w5B3Wl-3c/edit)
>
> wallet BasecampNearX
>
> > _Sepolia_`0x017C6A6427d78A4A9891Fe28E2310Fb7130083fc3DF239F86152647d788A8fAB`
> >
> > _Mainet_ `0x06cbB71892BDe5d50AB0F2b373335820376Ed4cBAe697f8cfe89cd52C1B40ecF`

## Day 1

> [2024-08-26](https://www.youtube.com/watch?v=zMVXM-dpYzY)
>
> ```sh
>  #starknet-devnet --seed 2148813889
>  starknet-devnet --seed 2525635640
>  starkli signer keystore from-key .c-wallets/account0_keystore.json
>  starkli account fetch 0x72ffeb1cfb9b00f4df13b26f393ad923b3a3bdfe1ca293dc871fbb3114355a9 --rpc http://0.0.0.0:5050 --output .c-wallets/account0_account.json
>  starkli declare target/dev/counter_CounterContract.compiled_contract_class.json --rpc http://0.0.0.0:5050 --account .c-wallets/account0_account.json --keystore .c-wallets/account0_keystore.json
> ```

```
| Account address |  0x72ffeb1cfb9b00f4df13b26f393ad923b3a3bdfe1ca293dc871fbb3114355a9
| Private key     |  0xba489462e093e740187771f23ea83db
| Public key      |  0x5afff160be71e265edbca9da1acbad7996f2661174eb3c2a4f4f0711d2cf12c
```

## Day 2

> [2024-08-28](-)

## Day 3

> [2024-08-30](-)

```

```
