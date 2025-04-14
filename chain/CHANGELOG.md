# Changelog

## [2.5.0](https://github.com/mateuszjasiuk/namada-indexer/compare/chain-v2.4.4...chain-v2.5.0) (2025-04-14)


### Features

* add block proposer to addresses_with_balance_change ([7cf71cf](https://github.com/mateuszjasiuk/namada-indexer/commit/7cf71cf5edca9354cb800a0c8c69af8e4af141cd))
* add block proposer to addresses_with_balance_change ([fb31083](https://github.com/mateuszjasiuk/namada-indexer/commit/fb3108398e8ca1888b27ede07e684df3b0024208))
* add json logging with LOG_FORMAT option ([#173](https://github.com/mateuszjasiuk/namada-indexer/issues/173)) ([838301d](https://github.com/mateuszjasiuk/namada-indexer/commit/838301dc7e85900ba02ec192320482da2d6b4fa4))
* add redelegation info ([2f5f8de](https://github.com/mateuszjasiuk/namada-indexer/commit/2f5f8de974db7b4ce71b2d00e32b848c54deda9d))
* add redelegation info ([ab1e143](https://github.com/mateuszjasiuk/namada-indexer/commit/ab1e14358b10df6eb28a74d64cb94d825d7f0a92))
* add total reward for epoch for each user ([a8e87b1](https://github.com/mateuszjasiuk/namada-indexer/commit/a8e87b101ea6ae17e93889aaee3a90d70deae865))
* apr native token and other things ([#52](https://github.com/mateuszjasiuk/namada-indexer/issues/52)) ([092ae2e](https://github.com/mateuszjasiuk/namada-indexer/commit/092ae2e079d080a839f7bced331c7787e55e2399))
* bonds start date ([#64](https://github.com/mateuszjasiuk/namada-indexer/issues/64)) ([5c84c52](https://github.com/mateuszjasiuk/namada-indexer/commit/5c84c52ef2e870ed9746fc034508b7770af8666b))
* check if chain service can backfill ([9478130](https://github.com/mateuszjasiuk/namada-indexer/commit/9478130e02104dae5d7a008b434676265ca9a745))
* check if chain service can backfill ([4f7d6d3](https://github.com/mateuszjasiuk/namada-indexer/commit/4f7d6d3f84681f103f474c622f422677b0c30094))
* crawlers states ([#73](https://github.com/mateuszjasiuk/namada-indexer/issues/73)) ([0aa9369](https://github.com/mateuszjasiuk/namada-indexer/commit/0aa93694bf583064ea974823134ebb62abce2cc2))
* ibc transparent balance ([#117](https://github.com/mateuszjasiuk/namada-indexer/issues/117)) ([3d82460](https://github.com/mateuszjasiuk/namada-indexer/commit/3d824600a2e23fe4640c22fafbd6c879fc998db2))
* insert votes in chunks ([2b8fcf5](https://github.com/mateuszjasiuk/namada-indexer/commit/2b8fcf5d644b6ea8a354ef3b5fcc808ca145faad))
* insert votes in chunks ([#180](https://github.com/mateuszjasiuk/namada-indexer/issues/180)) ([cc30098](https://github.com/mateuszjasiuk/namada-indexer/commit/cc30098ef7ab454089c65510fefc4a5a2d2cca9a))
* one native token constraint and namada bump ([#138](https://github.com/mateuszjasiuk/namada-indexer/issues/138)) ([9ba6ea9](https://github.com/mateuszjasiuk/namada-indexer/commit/9ba6ea9296912b1eaf82440e11e6639454a0683b))
* reduce chain crawler interval ([#118](https://github.com/mateuszjasiuk/namada-indexer/issues/118)) ([a502d82](https://github.com/mateuszjasiuk/namada-indexer/commit/a502d82d00719e9670938ad710cf0443f7c81f4d))
* remove path parameter from gas endpoint + prepare gas limits for 0.45.1 ([#140](https://github.com/mateuszjasiuk/namada-indexer/issues/140)) ([a62af3d](https://github.com/mateuszjasiuk/namada-indexer/commit/a62af3d2a168b05a24a1651cf19b225ae5f73973))
* return blocks by timestamp or height ([001e1e0](https://github.com/mateuszjasiuk/namada-indexer/commit/001e1e05628fff832294cc814817369594543f0e))
* return correct earliest redelegation epoch ([8efb8c3](https://github.com/mateuszjasiuk/namada-indexer/commit/8efb8c3e69ebac77bcd7ad98e76a3e21c7e063ad))
* return proper redelegation info ([21591e5](https://github.com/mateuszjasiuk/namada-indexer/commit/21591e550fa98009bc680feab71dad3709b744d4))
* return raw amounts ([#166](https://github.com/mateuszjasiuk/namada-indexer/issues/166)) ([8e4a385](https://github.com/mateuszjasiuk/namada-indexer/commit/8e4a385bd69c440d2f19fefcb824c04268dd88c8))
* run rewards  service every epoch ([#116](https://github.com/mateuszjasiuk/namada-indexer/issues/116)) ([9f85ffb](https://github.com/mateuszjasiuk/namada-indexer/commit/9f85ffb2a0665a56a1b1927b3a7bb93849861dab))
* some fixes after test session ([#94](https://github.com/mateuszjasiuk/namada-indexer/issues/94)) ([7615344](https://github.com/mateuszjasiuk/namada-indexer/commit/76153440657293a8f07ad02a678b29f4da0cd0bc))
* store first block in epoch ([#83](https://github.com/mateuszjasiuk/namada-indexer/issues/83)) ([d72152c](https://github.com/mateuszjasiuk/namada-indexer/commit/d72152ccabcf6b92d0c23f55e2e0f7a8891dfcb6))
* swagger and axum updates ([#46](https://github.com/mateuszjasiuk/namada-indexer/issues/46)) ([3d12fe4](https://github.com/mateuszjasiuk/namada-indexer/commit/3d12fe4d3aac6b1c8489202b2c16be19444bf31c))
* tokens and ibc tokens tables ([#124](https://github.com/mateuszjasiuk/namada-indexer/issues/124)) ([03a8619](https://github.com/mateuszjasiuk/namada-indexer/commit/03a8619efb66dd2cfe2d42303b7a4db3a2b80d5a))
* unbonds withdraws improvements ([#66](https://github.com/mateuszjasiuk/namada-indexer/issues/66)) ([f9a4d2f](https://github.com/mateuszjasiuk/namada-indexer/commit/f9a4d2f9cd1311f89b14146ab2886fce1c44aea6))
* validator rank ([#113](https://github.com/mateuszjasiuk/namada-indexer/issues/113)) ([69b3e89](https://github.com/mateuszjasiuk/namada-indexer/commit/69b3e895c6acd2225eac6cdd6fd87bc5b2f1a0c1))


### Bug Fixes

* add name for validator metadata upsert ([#146](https://github.com/mateuszjasiuk/namada-indexer/issues/146)) ([5d5902e](https://github.com/mateuszjasiuk/namada-indexer/commit/5d5902e534749e33ae11905cf0e5b626a2d44ad3))
* add new validators on initial query and becomde validator tx ([#130](https://github.com/mateuszjasiuk/namada-indexer/issues/130)) ([667abcf](https://github.com/mateuszjasiuk/namada-indexer/commit/667abcf81156eae63f5b4ddef2828a8c4556c42e))
* delete rewards by both source and validator ([#164](https://github.com/mateuszjasiuk/namada-indexer/issues/164)) ([4f70851](https://github.com/mateuszjasiuk/namada-indexer/commit/4f708510194b01b332f3ace3c6ad474d87cdadb5))
* duplicate bonds and unbonds addresses ([#93](https://github.com/mateuszjasiuk/namada-indexer/issues/93)) ([4cc06bf](https://github.com/mateuszjasiuk/namada-indexer/commit/4cc06bfe3334b26d11fc1fa897fac25a55836734))
* duplicate votes for same voter ([7e1e5cc](https://github.com/mateuszjasiuk/namada-indexer/commit/7e1e5cc7460039837eb75b38c04f393757f1a0c0))
* insert bonds and unbonds in chunks ([#178](https://github.com/mateuszjasiuk/namada-indexer/issues/178)) ([f706116](https://github.com/mateuszjasiuk/namada-indexer/commit/f7061168b56fbe0f92ca33f06cdb29d601976229))
* merge ([c393c22](https://github.com/mateuszjasiuk/namada-indexer/commit/c393c221f14f6b5fce9c8caef6d40949db2b167c))
* minor fixes ([#85](https://github.com/mateuszjasiuk/namada-indexer/issues/85)) ([ff40594](https://github.com/mateuszjasiuk/namada-indexer/commit/ff4059499d7591c7a2d2521d85913a27cd9c3e0e))
* negative precvious epoch ([7455dbe](https://github.com/mateuszjasiuk/namada-indexer/commit/7455dbe48b9a517ec73ddb0966c394aba8ad3ab0))
* negative previous epoch ([853a135](https://github.com/mateuszjasiuk/namada-indexer/commit/853a135d85ff426e412d26d99d21c8dae873818e))
* propagate error messages for redelegations ([89189c1](https://github.com/mateuszjasiuk/namada-indexer/commit/89189c1a375d21be6fd0167f08ba2adc18a5078a))
* redelegations after rebase ([04f7cf7](https://github.com/mateuszjasiuk/namada-indexer/commit/04f7cf7a362b4fe4dfddba9b2735bdbd04518e1a))
* update rewards deletion ([f2aade5](https://github.com/mateuszjasiuk/namada-indexer/commit/f2aade57b2a0295b696c724770dc098457450cd0))
* validators balance ([604b60a](https://github.com/mateuszjasiuk/namada-indexer/commit/604b60a3778df520d2f2f311cb1496b5603f5f58))
