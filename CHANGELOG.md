# Changelog

## 0.1.0-alpha.1 (2025-01-24)

Full Changelog: [v0.0.1-alpha.0...v0.1.0-alpha.1](https://github.com/meorphis-test/test-repo-18/compare/v0.0.1-alpha.0...v0.1.0-alpha.1)

### Features

* **client:** add `retry_count` to raw response class ([#7](https://github.com/meorphis-test/test-repo-18/issues/7)) ([f66d453](https://github.com/meorphis-test/test-repo-18/commit/f66d4539e652d9f44f1a8e3349b46b79dd6b566d))


### Bug Fixes

* **client:** compat with new httpx 0.28.0 release ([#19](https://github.com/meorphis-test/test-repo-18/issues/19)) ([ec407c1](https://github.com/meorphis-test/test-repo-18/commit/ec407c12f1c7002e47e46b3f1c5af10e51c64369))
* correctly handle deserialising `cls` fields ([#37](https://github.com/meorphis-test/test-repo-18/issues/37)) ([37ceb96](https://github.com/meorphis-test/test-repo-18/commit/37ceb96a5e2db7f7ad85697261fd5f326c922919))
* **tests:** make test_get_platform less flaky ([#40](https://github.com/meorphis-test/test-repo-18/issues/40)) ([b6a0e36](https://github.com/meorphis-test/test-repo-18/commit/b6a0e36f18986542c69c9d478d119465bede9af3))


### Chores

* add missing isclass check ([#33](https://github.com/meorphis-test/test-repo-18/issues/33)) ([b11a737](https://github.com/meorphis-test/test-repo-18/commit/b11a7377f62cb49cdf7f37be5b5bdfbea3f1170d))
* go live ([#1](https://github.com/meorphis-test/test-repo-18/issues/1)) ([1608d6a](https://github.com/meorphis-test/test-repo-18/commit/1608d6a16377a52e15c5c91a002b231ac73d8c03))
* **internal:** add support for TypeAliasType ([#26](https://github.com/meorphis-test/test-repo-18/issues/26)) ([f2922b8](https://github.com/meorphis-test/test-repo-18/commit/f2922b81f5676c411d2ee2437e14b41f3c13a7db))
* **internal:** avoid pytest-asyncio deprecation warning ([#41](https://github.com/meorphis-test/test-repo-18/issues/41)) ([5d72fbb](https://github.com/meorphis-test/test-repo-18/commit/5d72fbb3148a6c28924783860f8b95acf19c2e9f))
* **internal:** bump pydantic dependency ([#22](https://github.com/meorphis-test/test-repo-18/issues/22)) ([f9a1a81](https://github.com/meorphis-test/test-repo-18/commit/f9a1a8173fdd2353b0ca9c8e02df229251f6d204))
* **internal:** bump pyright ([#20](https://github.com/meorphis-test/test-repo-18/issues/20)) ([72031ff](https://github.com/meorphis-test/test-repo-18/commit/72031fff83de0ba7cdfefa06b2c8e0db67908630))
* **internal:** bump pyright ([#25](https://github.com/meorphis-test/test-repo-18/issues/25)) ([9945afb](https://github.com/meorphis-test/test-repo-18/commit/9945afb961d9e3dd4674088e74d82e07bc8bef7c))
* **internal:** bump pyright ([#6](https://github.com/meorphis-test/test-repo-18/issues/6)) ([b1482d8](https://github.com/meorphis-test/test-repo-18/commit/b1482d87ee05771089afdf860532aec26a848d6e))
* **internal:** codegen related update ([#24](https://github.com/meorphis-test/test-repo-18/issues/24)) ([7816109](https://github.com/meorphis-test/test-repo-18/commit/78161094c6b549c904d178970f3eff13c63a45e8))
* **internal:** codegen related update ([#27](https://github.com/meorphis-test/test-repo-18/issues/27)) ([1efc127](https://github.com/meorphis-test/test-repo-18/commit/1efc1273fa0693f6a9df5b9f6fee89b6d7bac50f))
* **internal:** codegen related update ([#28](https://github.com/meorphis-test/test-repo-18/issues/28)) ([229bdc9](https://github.com/meorphis-test/test-repo-18/commit/229bdc92277b5bde5daa7e60383c971689eadbc7))
* **internal:** codegen related update ([#29](https://github.com/meorphis-test/test-repo-18/issues/29)) ([0feb423](https://github.com/meorphis-test/test-repo-18/commit/0feb423f6e6d6ff5a3a16da265454ba0746a9e4f))
* **internal:** codegen related update ([#32](https://github.com/meorphis-test/test-repo-18/issues/32)) ([a8cf3c4](https://github.com/meorphis-test/test-repo-18/commit/a8cf3c4d181e20f334e19f6dd0721505f5469470))
* **internal:** codegen related update ([#34](https://github.com/meorphis-test/test-repo-18/issues/34)) ([a9d428e](https://github.com/meorphis-test/test-repo-18/commit/a9d428e9d15f17a3284e34335529f79a84a6b2c9))
* **internal:** codegen related update ([#36](https://github.com/meorphis-test/test-repo-18/issues/36)) ([f9d17bc](https://github.com/meorphis-test/test-repo-18/commit/f9d17bc1a888f6d7d110726fc05e9231212c5a45))
* **internal:** codegen related update ([#38](https://github.com/meorphis-test/test-repo-18/issues/38)) ([3e7b7c2](https://github.com/meorphis-test/test-repo-18/commit/3e7b7c23204da2526620b99569d878fcf13b0c01))
* **internal:** exclude mypy from running on tests ([#18](https://github.com/meorphis-test/test-repo-18/issues/18)) ([40be3b3](https://github.com/meorphis-test/test-repo-18/commit/40be3b339f99f89244b146aa553736141b762569))
* **internal:** fix compat model_dump method when warnings are passed ([#15](https://github.com/meorphis-test/test-repo-18/issues/15)) ([86e2edb](https://github.com/meorphis-test/test-repo-18/commit/86e2edb81ca22f4f09335e12a03d3a3b8614b7a8))
* **internal:** fix some typos ([#31](https://github.com/meorphis-test/test-repo-18/issues/31)) ([ef54c9b](https://github.com/meorphis-test/test-repo-18/commit/ef54c9b8fb6ef3eff9e1fc142d881ad49b8cfa74))
* **internal:** minor formatting changes ([#43](https://github.com/meorphis-test/test-repo-18/issues/43)) ([a153d97](https://github.com/meorphis-test/test-repo-18/commit/a153d9765305db75ee64267edad0f75c403f94f7))
* **internal:** minor style changes ([#42](https://github.com/meorphis-test/test-repo-18/issues/42)) ([9e84ff9](https://github.com/meorphis-test/test-repo-18/commit/9e84ff96122c8039451dd7c646d9e38291bdd25b))
* **internal:** test updates ([#8](https://github.com/meorphis-test/test-repo-18/issues/8)) ([820f243](https://github.com/meorphis-test/test-repo-18/commit/820f243d2e6f11ebdadebd2973014784937d003a))
* **internal:** use `TypeAlias` marker for type assignments ([#5](https://github.com/meorphis-test/test-repo-18/issues/5)) ([587c484](https://github.com/meorphis-test/test-repo-18/commit/587c48408577f2e38c52d14ae6e980b4e4b52fa5))
* make the `Omit` type public ([#21](https://github.com/meorphis-test/test-repo-18/issues/21)) ([fd7103a](https://github.com/meorphis-test/test-repo-18/commit/fd7103a9fc7b931b76bf58e8eef320059f32ceb8))
* rebuild project due to codegen change ([#10](https://github.com/meorphis-test/test-repo-18/issues/10)) ([30ade4c](https://github.com/meorphis-test/test-repo-18/commit/30ade4c232c0fe85319c8b14b4e6e122613b02da))
* rebuild project due to codegen change ([#11](https://github.com/meorphis-test/test-repo-18/issues/11)) ([6bba3d7](https://github.com/meorphis-test/test-repo-18/commit/6bba3d7c4bed9c5530c9f1476edb0ccc7f0d2e52))
* rebuild project due to codegen change ([#12](https://github.com/meorphis-test/test-repo-18/issues/12)) ([c009e6e](https://github.com/meorphis-test/test-repo-18/commit/c009e6e422ff90a873c3c559f282647453dde40f))
* rebuild project due to codegen change ([#13](https://github.com/meorphis-test/test-repo-18/issues/13)) ([38040fa](https://github.com/meorphis-test/test-repo-18/commit/38040fa324f182b43897f5e7b7b7233e0274b0f3))
* rebuild project due to codegen change ([#14](https://github.com/meorphis-test/test-repo-18/issues/14)) ([bc8da31](https://github.com/meorphis-test/test-repo-18/commit/bc8da31d41774c3e6a895b84dddd42df78876603))
* rebuild project due to codegen change ([#9](https://github.com/meorphis-test/test-repo-18/issues/9)) ([256689d](https://github.com/meorphis-test/test-repo-18/commit/256689d6a356468dca9e9aaae00d2e8ea60c0a33))
* remove now unused `cached-property` dep ([#17](https://github.com/meorphis-test/test-repo-18/issues/17)) ([f39bf53](https://github.com/meorphis-test/test-repo-18/commit/f39bf53b8baae6fd55f1e764f52a2703b5d80d9f))
* update SDK settings ([#3](https://github.com/meorphis-test/test-repo-18/issues/3)) ([dccb85d](https://github.com/meorphis-test/test-repo-18/commit/dccb85d7421491ca5f4b8043fae97a0c034ee237))


### Documentation

* add info log level to readme ([#16](https://github.com/meorphis-test/test-repo-18/issues/16)) ([1f196a7](https://github.com/meorphis-test/test-repo-18/commit/1f196a738318e1ddb387e204ae6a77a06268a193))
* fix typos ([#35](https://github.com/meorphis-test/test-repo-18/issues/35)) ([662028a](https://github.com/meorphis-test/test-repo-18/commit/662028ad5480e1ce6af55bd3406f38448002cf8b))
* **raw responses:** fix duplicate `the` ([#39](https://github.com/meorphis-test/test-repo-18/issues/39)) ([0ad3309](https://github.com/meorphis-test/test-repo-18/commit/0ad33093ef19a5e795077ba874f0cdb1d26c9bb5))
* **readme:** example snippet for client context manager ([#30](https://github.com/meorphis-test/test-repo-18/issues/30)) ([abf7dca](https://github.com/meorphis-test/test-repo-18/commit/abf7dcade29a7fed288e0fcbaf9bafc4801ae309))
* **readme:** fix http client proxies example ([#23](https://github.com/meorphis-test/test-repo-18/issues/23)) ([957258e](https://github.com/meorphis-test/test-repo-18/commit/957258e7c68541b08006090784aa0d5d6d834bdd))
