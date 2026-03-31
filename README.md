# Repolex Knowledge Graph of rtfd/commonmark.py

RDF knowledge graph data for [rtfd/commonmark.py](https://github.com/rtfd/commonmark.py), parsed by [repolex](https://repolex.ai).

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
lexq download rtfd/commonmark.py
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   │   ├── 568dffc45be82abd0f8365939f04bcd8fca4cc28.nq.gz
│   │   ├── 637197fd371357e4736d1be2b6eee0d7e45c5e51.nq.gz
│   │   ├── 8b99773deb7ecfd1fcf7f1761da492fabdaa3c04.nq.gz
│   │   ├── 90029807faab27bf163ab79c8639922756684f95.nq.gz
│   │   ├── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│   │   ├── bc19b3b1d7290b62310cc1200384abb5dda208d0.nq.gz
│   │   ├── bd196fe6ac37757e9d5ec181e0a2342f6ccb81bb.nq.gz
│   │   ├── bd4338f55389951e5b6b607e3ae8a7693273d8e8.nq.gz
│   │   ├── c800fa628f2679ea7346499e9ee7c5c24e2cc34a.nq.gz
│   │   ├── e6bcb0d5a13e806f74f53195e9a56a1d1769ac2f.nq.gz
│   │   └── ebf011ea5d781bc0f2d1ed1d0c15da5bb3941071.nq.gz
│   ├── lsp
│   │   ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│   │   ├── 568dffc45be82abd0f8365939f04bcd8fca4cc28.nq.gz
│   │   ├── 637197fd371357e4736d1be2b6eee0d7e45c5e51.nq.gz
│   │   ├── 8b99773deb7ecfd1fcf7f1761da492fabdaa3c04.nq.gz
│   │   ├── 90029807faab27bf163ab79c8639922756684f95.nq.gz
│   │   ├── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│   │   ├── bc19b3b1d7290b62310cc1200384abb5dda208d0.nq.gz
│   │   ├── bd196fe6ac37757e9d5ec181e0a2342f6ccb81bb.nq.gz
│   │   ├── bd4338f55389951e5b6b607e3ae8a7693273d8e8.nq.gz
│   │   ├── c800fa628f2679ea7346499e9ee7c5c24e2cc34a.nq.gz
│   │   ├── e6bcb0d5a13e806f74f53195e9a56a1d1769ac2f.nq.gz
│   │   └── ebf011ea5d781bc0f2d1ed1d0c15da5bb3941071.nq.gz
│   └── repolex
│       ├── 277044484c0a37a5060891c1bdececcf2e82f209.nq.gz
│       ├── 568dffc45be82abd0f8365939f04bcd8fca4cc28.nq.gz
│       ├── 637197fd371357e4736d1be2b6eee0d7e45c5e51.nq.gz
│       ├── 8b99773deb7ecfd1fcf7f1761da492fabdaa3c04.nq.gz
│       ├── 90029807faab27bf163ab79c8639922756684f95.nq.gz
│       ├── ae4cb27cd4da4d0b87bff19d2f480eecd96290a1.nq.gz
│       ├── bc19b3b1d7290b62310cc1200384abb5dda208d0.nq.gz
│       ├── bd196fe6ac37757e9d5ec181e0a2342f6ccb81bb.nq.gz
│       ├── bd4338f55389951e5b6b607e3ae8a7693273d8e8.nq.gz
│       ├── c800fa628f2679ea7346499e9ee7c5c24e2cc34a.nq.gz
│       ├── e6bcb0d5a13e806f74f53195e9a56a1d1769ac2f.nq.gz
│       └── ebf011ea5d781bc0f2d1ed1d0c15da5bb3941071.nq.gz
└── blob
    ├── 00fa4ae35603c45230ff002796e3fa8e65f07c5b.nq.gz
    ├── 0572481cc2499da0d2c86f71fcea986280f136d5.nq.gz
    ├── 058f86bb2b6ffd9715201c066d19cf1569fef8f6.nq.gz
    ├── 073864b48e7d7ea01823c17230ba4902db8f7500.nq.gz
    ├── 07c752b533a3249a0d3e801eb77ef250a176653d.nq.gz
    ├── 09db05efac8b1d2d6a040958071cb0ffc4016975.nq.gz
    ├── 0c01829dbeab9587c04f44505c2e619d172ddf70.nq.gz
    ├── 102670063eb6b9c221af90d7ba9b39278a4586d3.nq.gz
    ├── 11215b5d422884765816dc7f37b4d9d53be517b8.nq.gz
    ├── 122bafb456ee68e3f18e5097cf24ade3a373e2ff.nq.gz
    ├── 1389962bff23b20677d0193d36438b65f964a064.nq.gz
    ├── 15b893cb5de23738929f6764108ece81ce267345.nq.gz
    ├── 15ce8bcdce0d141a057580334338ed84a1e36fbe.nq.gz
    ├── 179cbf5b410058522d88e254b51298e9839e955b.nq.gz
    ├── 1a7e37fa0671ff7c23c8e968f6d0fe1de3b7c4b9.nq.gz
    ├── 1b388b45fcf0474ca466a5c6cbfbe0376b18bb8f.nq.gz
    ├── 1bbf8168d82f725a0b7b4061e106b6d1deb054d1.nq.gz
    ├── 1c2193c5d6c13ad1eb3c356881f709a32e0b8571.nq.gz
    ├── 1e840dcef2bad35cd51df2ef21ee296abd44a585.nq.gz
    ├── 1f2612b6934b6871a30eebaea08020cedaf2e603.nq.gz
    ├── 1f37015906a8e6e0435bc1c36dd595b5e88895f6.nq.gz
    ├── 21e0e1360bb387574233ed5503120b3f07cc0cfd.nq.gz
    ├── 232f3e9cce22897fd6d6f4379ee732f1e12e6dce.nq.gz
    ├── 23344ab05ca0b0d311b188deb98e3fa483e7079d.nq.gz
    ├── 26c3d885900b999c599b5a03f7bc0a6f7bd93566.nq.gz
    ├── 2d98de1883eb634a91521aed6c9ead367e836c0d.nq.gz
    ├── 3245066f56d15c5ba65ec9fd76412097f3f4d0f2.nq.gz
    ├── 346e46fbbc944c03d0afc14113119c0963d71251.nq.gz
    ├── 34fa367929139b5c9d55d0387cc52c756d726a91.nq.gz
    ├── 372c2df5a3cb3e357169d2f78d698653d50a47e1.nq.gz
    ├── 392ca6c17622124dacb42d061c54da848c06271b.nq.gz
    ├── 398272fa897082a5eb2c1afb5064ee91db2f9e81.nq.gz
    ├── 39e26b523a619da15daca456b86197e2b923b0e7.nq.gz
    ├── 3a301c6be58fcced7a10a4b09b5100df36541439.nq.gz
    ├── 3a9e6ab501043b6845eb0185f43611dd57fdb2df.nq.gz
    ├── 3cb90db577020aa8ae7f645f40e6a48d5c9cbb3d.nq.gz
    ├── 3cdd50e884a75e8d507b8f2c307c903452c0486a.nq.gz
    ├── 3d05d68abe65db89acb22a475232dcceffab6bad.nq.gz
    ├── 3e1f047316eaf0b98c9ebd746445db94737e8780.nq.gz
    ├── 3ff021c400d82eb94dbc414fb110935d80bd6a83.nq.gz
    ├── 400b9d5ed6e5da3b406be6e6c835783d4d5a613a.nq.gz
    ├── 426f7c79e1fe91fed2f9f92f9b941b883ceb0566.nq.gz
    ├── 446fd91f53f5d3dffd5549dd79c5e3dfa8af5149.nq.gz
    ├── 45c7336d8fd32becb469cc5bab7d835ce01b08ec.nq.gz
    ├── 4911c7b59726a1f230af1a85cd40d26bb2646325.nq.gz
    ├── 49d44b5ddf33d2fb5171e9371b8fc5d675acf002.nq.gz
    ├── 49f156b7a7884fa3f7850b1c81230df2ca946144.nq.gz
    ├── 4b5fdf53975a29825e97fdff7c035cd7d50fe98e.nq.gz
    ├── 4c550fb007be9232dec6a7692dc358df0476683b.nq.gz
    ├── 4de6536a5638abb52b0769636d2c5a4c2e58b06d.nq.gz
    ├── 4eee387c062b2f8dad11d8c1a3b115c4df250bb2.nq.gz
    ├── 5155e560d63731cdac27efd0200ebe34f894fdeb.nq.gz
    ├── 5339e03cf3ec398c1d4e355f9872b9292b5ca8e5.nq.gz
    ├── 54a927b96ff5dcdfc09c4158849c1292f7aa7620.nq.gz
    ├── 54af6e5e58e3796d563a3b6a5d0797230b24dccb.nq.gz
    ├── 54cba24ea8387987636d1abd159555f5d19319e0.nq.gz
    ├── 5b1a1d090c82b048833ed97204ec0a6e87c3bad5.nq.gz
    ├── 5ca112327bbbd4784a210113ab048fae7ead88b1.nq.gz
    ├── 5fbbf987484bc18d27c869842332ca4f766f15b9.nq.gz
    ├── 60095698a7b73269014b34cb3a4e8875451de306.nq.gz
    ├── 6011b61858fafb33dbe53788a7d101879dd9f441.nq.gz
    ├── 60d024bfe5a0ba9b78e79880883d9d440b115b2a.nq.gz
    ├── 64153c6a989bc3520dce109229fadd0baf7b1902.nq.gz
    ├── 65edd4ea7724d49350abdf1fefe326c4cf3c1694.nq.gz
    ├── 6645843ec5885a2d9095c33794d8535509973af5.nq.gz
    ├── 66612f761d5eeb2ffea1f598b2ab143f0e420d99.nq.gz
    ├── 66e2ef982656c92c1f014648d9b1bba99d4f785c.nq.gz
    ├── 66ec2a733f3d686d83c98174f28c16c995410250.nq.gz
    ├── 6771b2c4c045b83e8d94bb234d64f04bdb76b2f6.nq.gz
    ├── 67d578e9179ec8b47867ef072d6ab230b9e70b01.nq.gz
    ├── 69a4eaa02b7ca4b25ebe9847d05859cd4a1294db.nq.gz
    ├── 6a1885ecb7685b0a80d74fdad42360fab22e8d81.nq.gz
    ├── 6b3b95df29e2d94a333e83588d8e029c11c5c290.nq.gz
    ├── 70c7ed45c43ef323db3a375c82e63a7dca33ddc0.nq.gz
    ├── 71c8025bd52b2cc9fdc2e14421eb0a8e51dfdcfa.nq.gz
    ├── 74375bf837ad3e5a01b58da833cee3df9ace4fee.nq.gz
    ├── 74694888384de1b28dbafddf4e3e4d471c7ad698.nq.gz
    ├── 748bc2c2213c3369fa4292c36f5e3d95f50d2441.nq.gz
    ├── 7aedcfea3e60bb0580cba2f53ae859376058cbb8.nq.gz
    ├── 7b3f5cd5468110552f776a78e6d502252d62cc68.nq.gz
    ├── 7b7b3341bcc9a28508345c7d5f116998ed9cf32c.nq.gz
    ├── 7be9b0c87a55e338f246c390393f8bc23181602d.nq.gz
    ├── 7c5cf94e1e0944fcc2282894f834af30a81bef36.nq.gz
    ├── 7ea2584a4d5809f7891db0b16df9279002bd2296.nq.gz
    ├── 7eb9c0ebc595ae41c60cf99c6cb20a5f78b075c1.nq.gz
    ├── 7f23ac40a524c22c9e4830a40c1f7b9c4dde5ee6.nq.gz
    ├── 811df054197011400ad9760cef0d20a1a2eb7cb7.nq.gz
    ├── 82487fc6e353f17167de7a99a16d8d78c6f1068d.nq.gz
    ├── 85a4d1cd0cda1ae02388985e452947604af22e9d.nq.gz
    ├── 8690fd05a3a1cd0a599b82e770adefccfac4244f.nq.gz
    ├── 8dc95bcd3346c235165fbb892271a79d107f8634.nq.gz
    ├── 8dfd6d560de6a9853ce339210f1f08c6188fe8b7.nq.gz
    ├── 8f36457781adee4a66e41e718bb24c7f2266f3b2.nq.gz
    ├── 8ff5501d0e617005d9b6a22d24512979f574cde4.nq.gz
    ├── 91255580e6359c62d6dc646ae369372810067312.nq.gz
    ├── 9156d8848dfd3e18e9d79950cc2ce01740138a7d.nq.gz
    ├── 9161612f7aa74accfd8371b67c104ee1860154a0.nq.gz
    ├── 9274ced4aa33707b59ae600c564688abc30bc585.nq.gz
    ├── 946749aa9aa071ef8b76265ed2a40a0dc68142ce.nq.gz
    ├── 97514ec61f70a73a1139ece76b207a56486b4d5c.nq.gz
    ├── 9b569de425c83f741b635fe5196f94852ae2ec9f.nq.gz
    ├── 9da2d7f8f2bebf7bbfe5b0cfbcecdbc01648039e.nq.gz
    ├── 9ebb4b04215fa429d1b48c5bcb1f03ae80b1d38f.nq.gz
    ├── 9f73b8a31b86ddaa5ab305280590d568b7ea9563.nq.gz
    ├── 9fd58413973a6543687e0dd0590cb13fd2ba0812.nq.gz
    ├── a037385a4fbf280b71a511a4326e6adb7d47d08c.nq.gz
    ├── a06ea846f261cff6bb961d928f903e089625d96b.nq.gz
    ├── a12586f420c2ffcb59c9ec190303a2d0d30a3a54.nq.gz
    ├── a18f7b233428d19d6ea2fc8f1d3a6a301ed92ac1.nq.gz
    ├── a2e81f4ed497659386fa843fc8e9d7370139024d.nq.gz
    ├── a4c652f98df37d300a0e46c730b092def56cd34e.nq.gz
    ├── a70d2e133b8cecf504987553af6735b521343a8f.nq.gz
    ├── a7535d7ca2c08b28940c0d49f1c240feab6bdb2e.nq.gz
    ├── a8332d02977959d36c2a8f3b47331634eb0125c6.nq.gz
    ├── a8e20cf28ade08edbf93fe61d6ad804b6789da2c.nq.gz
    ├── aa80d23fbd7bb22522608842a8301a793bb53d11.nq.gz
    ├── ad06fc8b85f03dcc6c3ef37600c00a7a361b05c5.nq.gz
    ├── ad4ff09ba6f7e479e27dad956e2c1944db375b28.nq.gz
    ├── ae998afa14c1dd02891fd69fa5d3648dccedb882.nq.gz
    ├── aebcfbb71c5b512e515a4f3904e8b0c37b38b3c5.nq.gz
    ├── aecbcdc4b9ed444ffda8ed48b29be47cfd6b83c0.nq.gz
    ├── aeecffa3def87168510995450ece47672f736f4f.nq.gz
    ├── b2215809160ad01810201bbd446c7270496e7d30.nq.gz
    ├── b56c9961095bddb0febf208e87221d54e19eed5e.nq.gz
    ├── b5815d67a55bd19d913a93ad59e000b2b5feabdb.nq.gz
    ├── b5b972670b82c37a9f99eea8a2021230098f0f5e.nq.gz
    ├── b8fa890091577f511f9d0d899a3f0fd547e14a29.nq.gz
    ├── b9746db3da94efa99bb0a9062c19116b4ff615f7.nq.gz
    ├── b9c107f8484de37144a4945272da9bdd646b66ad.nq.gz
    ├── bb4b59188329db8b4a44acfff5bd4862f43fe015.nq.gz
    ├── bbeaf57fd7cd7d6b26b1c63a33d3c62fa880db94.nq.gz
    ├── bc75a52a0ca9c606dcc0bfc71fe1667775ae8e67.nq.gz
    ├── bc917c4abd846923542ad2ea2246b175b101be91.nq.gz
    ├── bd5295893162b94bb364c90bf289aedde85c28e8.nq.gz
    ├── bdaed436dd9e20ae200ea1e49be4b10c679c730f.nq.gz
    ├── bf3e57a6df55b3ead0ec93d45ccfbe5329d08700.nq.gz
    ├── c0148d6c9112a69d5c2404b1a218e14fac465c8e.nq.gz
    ├── c49e85b39f2e7248cd1cc68eadb8e928c4583239.nq.gz
    ├── c682ba2c6c1603151f170437b607be804defa2b8.nq.gz
    ├── c6bd438a93fff47ef45253343ab5cd53cd851cf6.nq.gz
    ├── c6e9c7931db4d22b56c51edbf363d1956b8b6328.nq.gz
    ├── c7055a94c55de83f63d1ca178a987b3f1b5736fd.nq.gz
    ├── c71df18636427d3c11652ce91fe4d8a16fc0c302.nq.gz
    ├── c8190d87d02c103014e7f25d394513095794339e.nq.gz
    ├── c861ba29c69ff8b15e3c0bddcc4b851eb3da3df8.nq.gz
    ├── cf3a92ddf8ca5dfcdb8950ad8d62f675e71a8ea8.nq.gz
    ├── cffe63c3675a8ef582e92a5d2831d5faa5ba38af.nq.gz
    ├── d3076c4611d34e8d550bb89990d71d037ce994d9.nq.gz
    ├── d52eab3abf4f9c2dbcc0eb1cd6077371883e666e.nq.gz
    ├── d5ca11fed744904bc74053f8a541345ebdbf95ec.nq.gz
    ├── d83f259e7164e8837dd3a63701129cb5ff4f2bf4.nq.gz
    ├── d93a527ae245dcb0abdfa5848ea80f21cf13248b.nq.gz
    ├── db7b77f137bf3d90ba1dd7f74239d67ca4b4c6e4.nq.gz
    ├── dca4039eb21da98840ac626a7d9b5e687642e5ea.nq.gz
    ├── dee0be392b8f518fd8b49970867b431f580d331c.nq.gz
    ├── e0014871dd5ae84f38f88b2433bdf2dbf7bab01f.nq.gz
    ├── e0982a1a64707802880f44bb4fd34eede1633aeb.nq.gz
    ├── e2b6834d82a4879af5869b17c29c4ee88eefb5e5.nq.gz
    ├── e339fa0c3b0126081cb03e114a2bf0c67a9c8055.nq.gz
    ├── e3aada7cd38c922b4363454d49a741cc21dedeaf.nq.gz
    ├── e57339a4b10c22ba6da65f26fed776a8c7200e54.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e7ede9fedde58a1e810ebf93ae439d01cca0221a.nq.gz
    └── e9542a2cb06bef3ddb8a4a793c3d508ef6757e68.nq.gz

6 directories, 200 files
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

[rtfd/commonmark.py](https://github.com/rtfd/commonmark.py)

---
*Parsed on 2026-03-31 by [repolex](https://repolex.ai)*
