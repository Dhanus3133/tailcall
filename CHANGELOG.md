# Changelog

## [0.19.0](https://github.com/Dhanus3133/tailcall/compare/v0.18.0...v0.19.0) (2024-01-15)


### Features

* add an io Abstraction to fupport file and http/network ([#914](https://github.com/Dhanus3133/tailcall/issues/914)) ([cfaaf49](https://github.com/Dhanus3133/tailcall/commit/cfaaf49b810b9f2ce04864cd1e3154455c10a656))
* add cli `compose` command ([#853](https://github.com/Dhanus3133/tailcall/issues/853)) ([b04ced1](https://github.com/Dhanus3133/tailcall/commit/b04ced11e1ffbaa05886faa4e39b8c30a123dda0))
* add encoding option in [@http](https://github.com/http) ([#896](https://github.com/Dhanus3133/tailcall/issues/896)) ([ab3d972](https://github.com/Dhanus3133/tailcall/commit/ab3d972416970df7c8255fa639aa13f41859e91a))
* add tailcall timelines ([#900](https://github.com/Dhanus3133/tailcall/issues/900)) ([2780074](https://github.com/Dhanus3133/tailcall/commit/2780074a239f07c3e5d4aed0526b49ef800ecefd))
* add wasm compatibility to tailcall/core ([#892](https://github.com/Dhanus3133/tailcall/issues/892)) ([2fcc41b](https://github.com/Dhanus3133/tailcall/commit/2fcc41b6a82f3d6453e63dad1cdbede8a395cedd))
* add`[@omit](https://github.com/omit)` operator ([#935](https://github.com/Dhanus3133/tailcall/issues/935)) ([a5b5ecd](https://github.com/Dhanus3133/tailcall/commit/a5b5ecdc271a6e1f6c700631c3ba2509475a8217))
* auto release ([7eee217](https://github.com/Dhanus3133/tailcall/commit/7eee217bdc155df3f3a73765470977a52a71ad18))
* gh actions label ([#848](https://github.com/Dhanus3133/tailcall/issues/848)) ([04c526f](https://github.com/Dhanus3133/tailcall/commit/04c526f6d90a51a3e54083a6f25db14d57f13246))
* gh release ([b9186ce](https://github.com/Dhanus3133/tailcall/commit/b9186ce6f67d498ef60631ad5a11e177f755b6b6))
* if-expressions for resolvers ([#862](https://github.com/Dhanus3133/tailcall/issues/862)) ([6328120](https://github.com/Dhanus3133/tailcall/commit/632812042abd30d55c93d694737949cb5c88d953))
* implment FileIO for Cloudflare ([#926](https://github.com/Dhanus3133/tailcall/issues/926)) ([adab633](https://github.com/Dhanus3133/tailcall/commit/adab63347519f0976ce2eaf1a22686bf3afe7a19))
* push tag ([b5b8512](https://github.com/Dhanus3133/tailcall/commit/b5b8512dd497844f98e00e1e7c7b6df90e0431cb))
* support for reading environment variables ([#823](https://github.com/Dhanus3133/tailcall/issues/823)) ([a10347f](https://github.com/Dhanus3133/tailcall/commit/a10347fd4a94f887922b748345337e0bcfe2f419))


### Bug Fixes

* **cli/init:** handle some edge cases for init command ([#908](https://github.com/Dhanus3133/tailcall/issues/908)) ([6183d22](https://github.com/Dhanus3133/tailcall/commit/6183d22de636963909aa33aa049d8b723f50d3fe))
* **deps:** update rust crate anyhow to 1.0.78 ([6bea61d](https://github.com/Dhanus3133/tailcall/commit/6bea61dd745a575cf5bb7aa67e4ba5e7fb29464d))
* **deps:** update rust crate anyhow to 1.0.79 ([fefd5aa](https://github.com/Dhanus3133/tailcall/commit/fefd5aafe8bcb232925068c86169577d73d33188))
* **deps:** update rust crate async-graphql-value to v7 ([#903](https://github.com/Dhanus3133/tailcall/issues/903)) ([402d6d1](https://github.com/Dhanus3133/tailcall/commit/402d6d1406be0c13fa9979c3bdc5cf3be133d4df))
* **deps:** update rust crate async-trait to 0.1.76 ([e605739](https://github.com/Dhanus3133/tailcall/commit/e605739f40bf2aed448df5236e17aa113ea11071))
* **deps:** update rust crate async-trait to 0.1.77 ([0abc733](https://github.com/Dhanus3133/tailcall/commit/0abc73389ae5713a5db056eaa743402b6300dea6))
* **deps:** update rust crate clap to 4.4.12 ([7768339](https://github.com/Dhanus3133/tailcall/commit/776833900a24f5b829f03e2c987005e1009fdee2))
* **deps:** update rust crate clap to 4.4.13 ([f2f2594](https://github.com/Dhanus3133/tailcall/commit/f2f2594e56980060496f92c7b3cbc78899dd7934))
* **deps:** update rust crate clap to 4.4.14 ([b5442ea](https://github.com/Dhanus3133/tailcall/commit/b5442eae7a3c009b3fc1e79fcf5b1ba71ca901e2))
* **deps:** update rust crate clap to 4.4.15 ([6da3c27](https://github.com/Dhanus3133/tailcall/commit/6da3c27b83eb6752ddd29408d190c5a99caff3c4))
* **deps:** update rust crate clap to 4.4.16 ([22591a1](https://github.com/Dhanus3133/tailcall/commit/22591a18442056f41e598c68dd33bd6d530ae2fd))
* **deps:** update rust crate moka to 0.12.2 ([4134100](https://github.com/Dhanus3133/tailcall/commit/41341007bd1bafd208c0edb1cb2d8c490e5ffa46))
* **deps:** update rust crate moka to 0.12.3 ([383621c](https://github.com/Dhanus3133/tailcall/commit/383621c181be17f4699ffce90d25f8e164df7de8))
* **deps:** update rust crate serde_path_to_error to 0.1.15 ([e67f16a](https://github.com/Dhanus3133/tailcall/commit/e67f16a89dce8897a2692915ca00134e5656932f))
* **deps:** update rust crate thiserror to 1.0.53 ([87a3512](https://github.com/Dhanus3133/tailcall/commit/87a35127fd630c85b3d940fa8de3cc8027196065))
* **deps:** update rust crate thiserror to 1.0.56 ([5421f6c](https://github.com/Dhanus3133/tailcall/commit/5421f6c74a2be7e10eaccfa91346c374f31c3eae))
* **deps:** update rust crate thiserror to 1.0.56 ([#907](https://github.com/Dhanus3133/tailcall/issues/907)) ([0e7a5a0](https://github.com/Dhanus3133/tailcall/commit/0e7a5a0b1e0ff1492d680cd090554f696ad94c3d))
* disable batching by default ([#840](https://github.com/Dhanus3133/tailcall/issues/840)) ([6a88ebf](https://github.com/Dhanus3133/tailcall/commit/6a88ebffa31b05e311cbdff060153cd27f0ea28f))
* remove the run tests failed step ([bd3b583](https://github.com/Dhanus3133/tailcall/commit/bd3b58341c20e33a93dfa2def596d5a164075cdc))
* show log info instead of error ([#817](https://github.com/Dhanus3133/tailcall/issues/817)) ([d771b03](https://github.com/Dhanus3133/tailcall/commit/d771b0376a7b501f165c2e3be6bc98ea957add85))
* try_fold multiple calls for the same handler ([#915](https://github.com/Dhanus3133/tailcall/issues/915)) ([9aaa958](https://github.com/Dhanus3133/tailcall/commit/9aaa958799a3ca599c9dfba3e114b71bc4299104))
* validation error printing multiple times ([#910](https://github.com/Dhanus3133/tailcall/issues/910)) ([2fcbead](https://github.com/Dhanus3133/tailcall/commit/2fcbeadb2d2aba81bc7cb07dc194f9a401d07096))
