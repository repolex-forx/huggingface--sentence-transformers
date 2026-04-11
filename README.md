# Repolex Knowledge Graph of huggingface/sentence-transformers

RDF knowledge graph data for [huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download huggingface/sentence-transformers
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fe9361218c10b2ee18f497d73863788a6b592210
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── fe9361218c10b2ee18f497d73863788a6b592210.nq.gz
│   └── repolex
│       └── fe9361218c10b2ee18f497d73863788a6b592210
│           └── chunk-001.nq.gz
└── blob
    ├── 00b7be018704555482c4bd0526fc2d05ebf27601.nq.gz
    ├── 016e8beada88d42c6e2637252eb8709210a64ce1.nq.gz
    ├── 029d30208a6338b8ae10e93d07e53783ab30568d.nq.gz
    ├── 0300652f72309a4743ed053a2d7d3728ba0351a7.nq.gz
    ├── 030e7f4d6d1fce384ec61caf08779be0db045f40.nq.gz
    ├── 035462e8887f81eed11e65b4b21f28a031e4e822.nq.gz
    ├── 03983d615716615333d7bf3450b5b43b6b876480.nq.gz
    ├── 03b26a5a51716a0de4aa4b67620fca21a9174ee3.nq.gz
    ├── 03cbd30c74d6cfb512f9fe839e4304f1771a2b44.nq.gz
    ├── 03e210f91961f04283f757cc00a5f27c492be849.nq.gz
    ├── 04224d2eea7f1340a36ee042e3cae6facd8d6f29.nq.gz
    ├── 047b0a2199c59ea26f77a9218c023a277b5a67e1.nq.gz
    ├── 0550dc15330338db32f2a62b66c53c61ecce78d8.nq.gz
    ├── 058a5c644c69f92bfee1aa3b1f165383b7098c57.nq.gz
    ├── 05b01f7b77edb8666aef63841eb642b4f989aec2.nq.gz
    ├── 05b5c8fe43776d6dac7a0bad7c833ce78603a834.nq.gz
    ├── 05ccd468cf63450597b82093cf313c7f0cb4e94e.nq.gz
    ├── 0609192cb10b7c9309bbf4ab1b8a73c95870de01.nq.gz
    ├── 07128e9e414302e1ea2e34763a7f05b4202d01b8.nq.gz
    ├── 07393527a0b04a45fbf17a53d335fdf54b8a8581.nq.gz
    ├── 082683886b6b894067f085fd134440a818098296.nq.gz
    ├── 095e2ed587fb403ff4c33a1039d4bddbce67e341.nq.gz
    ├── 099b960a54c2803bb394fae6794f5d6d9554c996.nq.gz
    ├── 0ab7cd39a6eaedfb4d87ff3d73e3845e6b0481e1.nq.gz
    ├── 0b0f3b27d4af1cd97355b09d323029a3a4ef78ab.nq.gz
    ├── 0b13a6f514265bb86ef0100d1591e8de455340d3.nq.gz
    ├── 0b2379e785a10c4f42c904258d2c816699ac9c84.nq.gz
    ├── 0b736ae271f64c20ead4dc1af3b39404113c6095.nq.gz
    ├── 0bd7d846fd17824a011e46572c4c124af2da64ba.nq.gz
    ├── 0c1dbfa5efd19b568c0fa29c1260d5b6a42293c7.nq.gz
    ├── 0cd74fc2242e814ce0a33b871d8f1ae148ef7df8.nq.gz
    ├── 0d0ecf5e166f8c0a4ff53e171531db2754e62cc4.nq.gz
    ├── 0d74a92b00de45e58ea975f7619b7fb6aa134be2.nq.gz
    ├── 0d85b0187a18cfedc283009bb5af91dabaaaa84b.nq.gz
    ├── 0d8688e1905fcf9b6e6a9e2a43e063ee269b362e.nq.gz
    ├── 0dc9322bc4b8851823fc964e0b59346b697dadb8.nq.gz
    ├── 0ddc05a1cf9283a77e9b871c09749a8432e95b35.nq.gz
    ├── 0dedffd18fc61c78afa9917752800e98817dc58b.nq.gz
    ├── 0e401099f999484d2c368263a9383191d7aca8e3.nq.gz
    ├── 0eb54bec08d7e7a0cbb91d630d84f243636b2aca.nq.gz
    ├── 0f18740ffa01d666bea97fef11e7fc3de2502e4b.nq.gz
    ├── 0f509328041bcaeddec920726979dbf5a7fe62dc.nq.gz
    ├── 0fc0c335147f5ba4feedc31235c66714aab742d3.nq.gz
    ├── 10701477d1e43db6ba5294992437e171603058b8.nq.gz
    ├── 1096784bf5bb9bd071b2105499b4c6d10813ef37.nq.gz
    ├── 112ef3e833ad6cff6dc77725e30c74a1464c16ea.nq.gz
    ├── 11be946d7a0f84d76d4b8b136c441f0ec6aafc1f.nq.gz
    ├── 11c61b874514dfbeffa116e86f54c8c419eb3f7e.nq.gz
    ├── 11d3d4e541e77751fc4eb39522426bbafe6ccd0d.nq.gz
    ├── 1225f0523829ff4fe51a3803d2f2f2d761a2ee1f.nq.gz
    ├── 126cd589f0bc87c6a17f965e3d250111359e080e.nq.gz
    ├── 1370ae38dd556fe8a995a851e27ce0317188eb72.nq.gz
    ├── 1381e21d728e1f047fc3277cf2deb872a1951164.nq.gz
    ├── 144f3d75bfd7983c976c985b52bb86f8ad2bdcb1.nq.gz
    ├── 15a968ced05cbadf4bb8a5076946d9d3a812dd75.nq.gz
    ├── 15e7b5bc2de8791a7cd278862bea5451c978c87b.nq.gz
    ├── 1607c9b32fe23e9ba250b2363e9ee8b07c0714e4.nq.gz
    ├── 16092b6648984d01e4ce475af1f9abb9edc83334.nq.gz
    ├── 16a1835d3de541c33205460eb4f9f0dddf4d3913.nq.gz
    ├── 16eba858a142609beee806fe0595ec55f2d73e23.nq.gz
    ├── 16ef4146f05eea16cc5de8666aeb15299075daea.nq.gz
    ├── 1793cee937e2fa169189297afca3c21d33a80eb4.nq.gz
    ├── 18797de4f9c0389cb77c78f53ba83403b5609bab.nq.gz
    ├── 192e3847f6038cbcb03deb43a3e3eb614fdd093e.nq.gz
    ├── 1a592bb91ec00f6b55be1ff264d72d21ba6461c3.nq.gz
    ├── 1b5d3cce184752573cdeb532963b0bdbeebc8c41.nq.gz
    ├── 1bf2f22f629c71ddd997a34d675f55238d731fee.nq.gz
    ├── 1c5a06179176e3a290f809d43b289357422c6168.nq.gz
    ├── 1c8a70b7d7f717715bc9b660104920cc55e38c7c.nq.gz
    ├── 1cbb796f9c928e28d71d1f0d6c8b48f9f248765a.nq.gz
    ├── 1d404e8ac4bae0f51a52c6e4000bf2513dbdd54d.nq.gz
    ├── 1db33091c826b8b920d60e23676776441e5f96fb.nq.gz
    ├── 1ddaab8943c34fdd8a5fa9e14988cb86cab608c0.nq.gz
    ├── 1e1457d3762952aa17ad315534217c1701d47b84.nq.gz
    ├── 1e41109905a21fc7695b2a994d1054b88e318083.nq.gz
    ├── 1e560ef2aed647100adc473ff32c20e370e65cd8.nq.gz
    ├── 1e65e0a2d277b56594b0aba7065574edd8ae0261.nq.gz
    ├── 1e8eb191a915fecfcf25e1939ba1bcd48105dee9.nq.gz
    ├── 1ebfd2a65de7f5b87f063e2fcc97bc9f8767f9bd.nq.gz
    ├── 1f7484614ea22b33ea753d6164c2362bff33981d.nq.gz
    ├── 1fada3db9617444b48296e75c85795ad96a6f54b.nq.gz
    ├── 1ffefe6bc93df7291871d77eab9eb6083c37ca65.nq.gz
    ├── 20ca2b1b3c93bf0fe539882871fe7cc4a2a4cd8f.nq.gz
    ├── 20dc6abb28aeb04cd9e275f41dc5b19547979b99.nq.gz
    ├── 211a83cd0934c826f60772b968413b5d4ce2f48f.nq.gz
    ├── 21fa416662a19a811eb5447b9953b222daee6930.nq.gz
    ├── 2244b7bbca4783d1703be14de2b9c2dc453eda40.nq.gz
    ├── 226e500ea5b64362491360ab278d472cd850391d.nq.gz
    ├── 241f455ebd0e717b6fdae36e4c7cc7b99a1ccba7.nq.gz
    ├── 244f576b9ab547adf9bb0820df0d50f7c601c744.nq.gz
    ├── 26120c522785502c222e657f3ca590564ac63812.nq.gz
    ├── 2666acf02d51a059bce670de4c87d292893d0d13.nq.gz
    ├── 266a28f96adf987269d1998dc6f5a298cebf2dd1.nq.gz
    ├── 2689a19c407ee560598fa1e229b7d283a34c1278.nq.gz
    ├── 269d54b91c996bad2badbb7e238ca3d87e3b4535.nq.gz
    ├── 270948cdabebc8a5ceec9c3b04407cb2932d4e49.nq.gz
    ├── 272865cb537e8e9675dc547dd74210d7e6b0612b.nq.gz
    ├── 273926a8c9daf2aec8a5203444763302a332e23f.nq.gz
    ├── 2929058e6ac4589b2e16a0d1d3c001c052a11176.nq.gz
    ├── 295696c6bcabd5fea6fd77154ddaf9171e567773.nq.gz
    ├── 2997c18f290ded578693b453b0a1c91ffb0518d8.nq.gz
    ├── 29b787a1c956256f82d82bd35303d9a0113baa3b.nq.gz
    ├── 29f2ac54aba3206591ef5aadb5be2ddbdab858ea.nq.gz
    ├── 2bb06cbef00b3de89b8c1531fcb7686390dccbb7.nq.gz
    ├── 2c0fd5d04216a8c469643557f384f737e53f3ec2.nq.gz
    ├── 2c287d4b54952486a570ca7b29b5af1fb6195586.nq.gz
    ├── 2d208525ae6dc5cfa32ea1436d35995f970a8bca.nq.gz
    ├── 2d317ef6d166c712d6cc3c26ee59eb5023e5a982.nq.gz
    ├── 2d35664e982e33049229d47db7e457fdcb170098.nq.gz
    ├── 2d6e1ab36db279d962a8ddba25ee2afcdd3f4e18.nq.gz
    ├── 2d9344506d18b556919a20b91aa1fe14252426e4.nq.gz
    ├── 2da8d2e1c8a8f0c3b709f6a6af728507690a3271.nq.gz
    ├── 2de6f62fcb80f89e2e9e3f0e24c689e9f4a144b4.nq.gz
    ├── 2ea8dc4d051a43efdaac4fa897c4bc008b0a71a9.nq.gz
    ├── 2f5054f21370947b9c44548f480cf1bec95b8bd2.nq.gz
    ├── 2f5ae2d969ba1ce0f49352e263a71328152e1b91.nq.gz
    ├── 2fc23071175175141529fcba0e53a132f676b6a0.nq.gz
    ├── 2fcdc1cf94de67744c5795c6b1f87a22af736656.nq.gz
    ├── 2ff69f640b57e6f221df22c53af42233d847ce28.nq.gz
    ├── 30215330397d8ccbc15ca29536d86cf79dfa6ecd.nq.gz
    ├── 3132d27759a73fb0fdc8f79ab7d018db9c223145.nq.gz
    ├── 3151f1a0b9976f8e410836ab6dee0fb68cd13799.nq.gz
    ├── 316a1f40148ee9d52bd82332107b165a06110b86.nq.gz
    ├── 317904291cff90ef064be53a3a67e15882e52c53.nq.gz
    ├── 31a3e863599e7e13e651993fec727108214c21a6.nq.gz
    ├── 31aa824c9ec22ee32b3202df619ab6801b301f0f.nq.gz
    ├── 32189ec43f65d45d7fd1df779482567e409ccbe6.nq.gz
    ├── 3229ddeb58c5d8875d482a9e76259fe765a4378a.nq.gz
    ├── 3278e9a5ef0d888fe647c8bd08db8096c4fd4b88.nq.gz
    ├── 3294f8ab33d772cb8aabf0c5c3fc3909318f3121.nq.gz
    ├── 32c15eb0f8505ccf3abcffd5ff1388dcfb8f6943.nq.gz
    ├── 33cc4419dd0edd85af8c82e7d1b072537b44d5fe.nq.gz
    ├── 33d5bf9337056edee90c988263c404c476873422.nq.gz
    ├── 344901c869af82b9f894e957dbe8c82ec90009c0.nq.gz
    ├── 3479e2e9ed5c7cf19dbde75e4e2f853318c0f5d2.nq.gz
    ├── 34ecbf9068799da556a94cda3c3f03212fb2983d.nq.gz
    ├── 353759315de6ca7ea347aba860b9a14ba3012e39.nq.gz
    ├── 35d9c96d0a562b252cf6816e3d3e0ecdbcc5b516.nq.gz
    ├── 366ef1224cc8666f1cdf7c4d88afad58ff6fc399.nq.gz
    ├── 36fadbd1ff2d63f1487285392a2bb89a42998e73.nq.gz
    ├── 370fac24f6c70ac1722bae29e8b28666cafd11f6.nq.gz
    ├── 3794ec35cb2d5f4cc8067b4a590a5a9453123961.nq.gz
    ├── 37ae7365a094ff2dd610f1d1599512ab99b11e10.nq.gz
    ├── 37ff06d5f2bbbde5f3b304c402d12388c7c1a59f.nq.gz
    ├── 380e3a39938326c063e06fcec79c2f29f4763db0.nq.gz
    ├── 3855ae4f313b74998b3ed06c1da341cffe0f483e.nq.gz
    ├── 39eec91352a7a39074b40326d1a339c869871c97.nq.gz
    ├── 3a954c3b3daa592e724fb80e1e77489deb02a65f.nq.gz
    ├── 3b2093e30f9caef5d23268ab9c2d2e7f5f7e0903.nq.gz
    ├── 3b315f19c5d1d497d44846b295b3c8bbac004970.nq.gz
    ├── 3b541353f8262aab61aeb4ecdc9f5516b9d298d1.nq.gz
    ├── 3cc189eb8cf02cdd437f80a7900aefff42b84cc1.nq.gz
    ├── 3cd251204acea6eb47ecfc24b5f2924b3e2b38e4.nq.gz
    ├── 3dc66a3cab84c85273cfa71a9f65ab53b532e44a.nq.gz
    ├── 3eab8a85a8f66d54b044bc719b04d0c871501223.nq.gz
    ├── 3eaed8d99b3b6557bde9c4b53d1ec83a41b5c480.nq.gz
    ├── 3edb36f322f1202b0f55d53e668c3dc1ffa533a6.nq.gz
    ├── 3eee575d9d3fd977e92707b340a55079118aca67.nq.gz
    ├── 3fb2a039152645864335bdc140be82e0791a19a2.nq.gz
    ├── 400f1b89f7eb07d3174a85ffce5ddb363c9391ae.nq.gz
    ├── 40539046414e2d47106874d5d01729804e42c1b0.nq.gz
    ├── 4059bbd9da8eaa66a0cad75d7e2f21fc0d74b5a0.nq.gz
    ├── 408b6852a8c653aa60d1c4836f4d62f70952e697.nq.gz
    ├── 40ed70ed7b08c3e9b3687bd8d6237110c40d08dd.nq.gz
    ├── 4215fdda6af1a3b056fe460cda6c2fe514365812.nq.gz
    ├── 427b2379063c53364060299f8b9325913d12ba84.nq.gz
    ├── 42c5fad4374873d9cc034ebdfa563302c826cb0b.nq.gz
    ├── 432088a98eb657a4201939af36d21599e587533c.nq.gz
    ├── 43743376e9a7fbc78d0e9a325e5b3ae13b59d308.nq.gz
    ├── 441162be3215d4f570d958fbaa1e37a31b623b10.nq.gz
    ├── 447d6562103bf47892c625aa0e74a9614bd944f0.nq.gz
    ├── 44cf7d9477c9f22e748a0df996ba75dcf1fe0266.nq.gz
    ├── 456d77bcc9e761c1c7b1356cff13d82a3a93e1a1.nq.gz
    ├── 456f2856b73adf06aaca64415cdc810f01484b4c.nq.gz
    ├── 464aafedc564e93591fbf2a7337722f434666cc2.nq.gz
    ├── 47baacd623ad1a6498eee96c5441f1e93afffb67.nq.gz
    ├── 481c4f905d85acb3f2d02ecaf48b12972b9a4d07.nq.gz
    ├── 48d2369f000e86c3e77d53494cbab2369bfe5d20.nq.gz
    ├── 494d5506ea9421ad0f8b17c73baa2683f844a64d.nq.gz
    ├── 497d8a9a3414235b5e21a43a58ffe8704d049b2b.nq.gz
    ├── 499d3e992c7a19778105d816175b78c55075cfde.nq.gz
    ├── 4a1739fd9aefa0402627f9e12438d3556be85c4d.nq.gz
    ├── 4a73828f2b09fb8c249c6cb8e4404ef6b8de7294.nq.gz
    ├── 4ae5d626f6bb5e772b790456c45bfb142c60deb6.nq.gz
    ├── 4b62684cf0c8089f942f0847977e8fab91d9a1df.nq.gz
    ├── 4c8e3bd88555b4a075ea33d32bbb8d58e0537df6.nq.gz
    ├── 4cfd29d9f100305f18226654870a2788ad368109.nq.gz
    ├── 4d2a771dec61b4894241e21c776e0df8ffb6b1a6.nq.gz
    ├── 4d41c5dcf53342d591d5b2435770fbe0cf894459.nq.gz
    ├── 4e14a9695bb7cd6519799a052108e5b1d880e2bd.nq.gz
    ├── 4ea27ebb6bed8a8d75bced6444d5ba51e194e71a.nq.gz
    ├── 4f39a1e514240296a66f0d1e39a259a37060c0e7.nq.gz
    ├── 4f6a05369077105dad737e2e652317fd6c06a871.nq.gz
    ├── 4f9ebe7c81ff3380b465150e9c41c574a523541f.nq.gz
    ├── 4fa82909144d77dfb0b6a85867987bf9d5a177aa.nq.gz
    ├── 5064f99fa034051b6306abb1e35f4bc14ee92f2f.nq.gz
    └── 509a7dad769d9ee203bf18d3d0cfa6e6845a7aab.nq.gz

8 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |

## Source repository

[huggingface/sentence-transformers](https://github.com/huggingface/sentence-transformers)

---
*Parsed on 2026-04-11 by [repolex](https://repolex.ai)*
