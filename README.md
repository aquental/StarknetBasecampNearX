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

[Code](https://github.com/aquental/counter)

[Homework](homework.md)

## Day 2

> [2024-08-28](https://www.youtube.com/watch?v=0v58mtt9ae4)

### Cairo

> [Demystifying Cairo White Paper — Part I](https://medium.com/@pban/demystifying-cairo-white-paper-part-i-b71976ad0108)
>
> [Demystifying Cairo White Paper — Part II](https://medium.com/@pban/demystifying-cairo-white-paper-part-ii-9f9dc51886e9)
>
> 📖[Cairo Book](https://book.cairo-lang.org/)
>
> 📖[Starknet Book](https://book.starknet.io/title-page.html)
>
> - [x] [Starklings](https://starklings.app/) :white_check_mark:
>
> - [x] [Rustlings](https://github.com/rust-lang/rustlings) :white_check_mark:
>
> - [ ] [OnlyDust](https://www.onlydust.com/)
>
> [Starknet Basecamp Hub](https://starknet.notion.site/Starknet-Basecamp-Hub-1541b3c1f49f439da872d3d71647d834)
>
> [Introduction to Cairo language](https://www.certik.com/resources/blog/fQfJVKgF4GAQdpIXgwrOb-an-introduction-to-the-cairo-programming-language)

## Day 3

> [2024-08-30](https://www.youtube.com/watch?v=Zee4fmm-aBw)

### Project

> [erc20](https://github.com/aquental/token-sender-erc20-basecamp2)
>
> [frontend](https://github.com/aquental/starknet-workshop-frontend-basecamp2)

### Previous Basecamp

[Basecamp 9](https://www.youtube.com/watch?v=bZd-WUvNH5Q&list=PLMXIoXErTTYWyWg4AQVJP1N-7ZoYh4g1y)

[Starknet Kampala Basecamp](https://www.youtube.com/playlist?list=PLOYP_hXwmI9_WsY4oJQHHdn4yjnqJlM1e)

[StarkNet Basecamp - Cohort 1](https://www.youtube.com/watch?v=7p60e7RzuMs&list=PLcIyXLwiPilVhgOKl2uNawwBA6KV9NLYn)

[Starknet ERC20](https://github.com/starknet-edu/starknet-erc20)

> Argent X
> 
> [Writing and deploying your first ERC20 token on Starknet](https://www.argent.xyz/blog/writing-and-deploying-your-first-erc20-token-on-starknet)
> 
> [repo](https://github.com/argentlabs/min-starknet/blob/new_syntax/src/min_erc20/ERC20.cairo)

- [ ] [Starknet Basecamp Self Serve](https://www.youtube.com/playlist?list=PLMXIoXErTTYWjJGmSMgORC7O8tKffBhfU)
