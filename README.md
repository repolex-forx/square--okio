# Repolex Knowledge Graph of square/okio

RDF knowledge graph data for [square/okio](https://github.com/square/okio), parsed by [repolex](https://repolex.ai).

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
lexq download square/okio
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 7663819ae58a1b49320fc5c8d729896daf99d633.nq.gz
│   │   ├── 8b870e8eaacecb1c1ceffbbb47246112604a1f92.nq.gz
│   │   └── e906faf9b6bdca38a90f96c34db22e8978e114cf.nq.gz
│   ├── dataflow
│   │   ├── 7663819ae58a1b49320fc5c8d729896daf99d633.nq.gz
│   │   ├── 8b870e8eaacecb1c1ceffbbb47246112604a1f92.nq.gz
│   │   └── e906faf9b6bdca38a90f96c34db22e8978e114cf.nq.gz
│   ├── lsp
│   │   ├── 7663819ae58a1b49320fc5c8d729896daf99d633.nq.gz
│   │   ├── 8b870e8eaacecb1c1ceffbbb47246112604a1f92.nq.gz
│   │   └── e906faf9b6bdca38a90f96c34db22e8978e114cf.nq.gz
│   └── repolex
│       ├── 7663819ae58a1b49320fc5c8d729896daf99d633.nq.gz
│       ├── 8b870e8eaacecb1c1ceffbbb47246112604a1f92.nq.gz
│       └── e906faf9b6bdca38a90f96c34db22e8978e114cf.nq.gz
└── blob
    ├── 0067d4488ef241744e319976a9652b80dfbfbf10.nq.gz
    ├── 00aba1a2738a858ab25dfd89229bbc78ff78ea79.nq.gz
    ├── 010319ef48670a778699a2a6f354b6f2ffac2afc.nq.gz
    ├── 016430108f3dcad9ffe5478234e70085eea5982b.nq.gz
    ├── 01666d176795f4a623ee6d0400ee9ff6b4623706.nq.gz
    ├── 021ffb4cbb5e484b99139cc4dcd9ce3d88dd3a49.nq.gz
    ├── 0263aabdb2c6cfb7cb60229e6135c3d56d6ca432.nq.gz
    ├── 029b93d2973f3e9b6c1ae5b37017f318b9b98ddf.nq.gz
    ├── 0390eca24e35fc2134c14bf3da2e174c3a60515b.nq.gz
    ├── 03997d301bbb1090e3619a15e3c27cd059a42c74.nq.gz
    ├── 03a6cfd3f7f9467270a46897ec6ffea2d7fed7e1.nq.gz
    ├── 04350d157a4bdf1965f435d0aac2740cfdd4e2e6.nq.gz
    ├── 04572169e8c58be0c29c2eb0492b5f116af95912.nq.gz
    ├── 0483999b20ae2a39058bd0737727bc786ef325cc.nq.gz
    ├── 0509e4e5a2610247205b90c162516584cd25b335.nq.gz
    ├── 051c9a14bd58ad947dd5c75d0e8971c27e3e8536.nq.gz
    ├── 05cdd6d39216d5337d0c07e7198315c4fe72bf92.nq.gz
    ├── 060aa4ceb81be5966c278b2189b2e5e03d91ec44.nq.gz
    ├── 0700270842916f96f1c18bb0526e9998bb7653fc.nq.gz
    ├── 07409255edd55e33b9f964e0377813effb0ba84f.nq.gz
    ├── 07943c4b3d01d5be6f0f3f50084c414c46bf6f82.nq.gz
    ├── 07b8b7086edf53acc0b66c61d314fc48797e5122.nq.gz
    ├── 07dfad8d9e11ce68f1d8670b1ddb6caa06443542.nq.gz
    ├── 08a13d2a25e20b22ccca678c5987429a56aea2d0.nq.gz
    ├── 090387529ed28a5037c80628fc151fe42d82b3d3.nq.gz
    ├── 09b036f8f74fe84124be2545b499f44d52ce6161.nq.gz
    ├── 0a6af54ab7eb4c4580687b4036d73ca0ed272aa6.nq.gz
    ├── 0af5344254da32a9c63447a3d7bedfd1adc9982c.nq.gz
    ├── 0b151794d862fd2cf9188f1c005520c3b79c3688.nq.gz
    ├── 0b3e9f6aa70c1b74ef0b90856eb490200de8cf0a.nq.gz
    ├── 0b50b0054da9844f0915de7fbc34eea26cb53e06.nq.gz
    ├── 0bc7e4dafb9ac4c936bb85f9d8314a25fbcacc9e.nq.gz
    ├── 0c1065156eae1357a7da833bcb25303b0691a35e.nq.gz
    ├── 0c17992c849598c084c41b3b31e8ccb4f1e2f5ae.nq.gz
    ├── 0c61696a1aec3fa2ac9b69e1d870fd430f194150.nq.gz
    ├── 0ce9e2945af7f186200cb41d896ee8d4e848ab97.nq.gz
    ├── 0d4a9516871afd710a9d84d89e31ba77745607bd.nq.gz
    ├── 0dbaf02146ff137da5db1e901d4fc6d8101ec5d7.nq.gz
    ├── 0e0ecedc66a8f1dca9428b0c3f4ad7552849eca5.nq.gz
    ├── 0e3bd6ead43d2de0c1ff94851415152be266f65c.nq.gz
    ├── 0e600e061fbf52affea38e2dd7fa541970fed57c.nq.gz
    ├── 0e6ce90627f8b0390babff0a0131f380f1ea5020.nq.gz
    ├── 0e9c04b7d049d476c29981eb39c0addfa7e9509c.nq.gz
    ├── 0f92b61d8fe20e6b15cbf34f16e8bc2f9d2d5b12.nq.gz
    ├── 101a075b114ce287eea29318ae3f4312620734bf.nq.gz
    ├── 10290eac740d85eae59a500dc749f073506c98bd.nq.gz
    ├── 1048c3dbc82ec4f864ef0b326cacf3ab3d49c5eb.nq.gz
    ├── 109ef1402e69fabc29c5edc1083ddb8c5e2428c7.nq.gz
    ├── 1108a3b0dd70a4d5d333e404cf11c2191bca6ccd.nq.gz
    ├── 11cdabdefaa508cac557aaf9c115fce35a5f75ac.nq.gz
    ├── 124569694959bd24b1f9658f1fcc45f2330b95ae.nq.gz
    ├── 131dffb7b42f2325afd85dc556520fa25ac0d55c.nq.gz
    ├── 13c63158ac2b3e37f91f511c54df955814ae257d.nq.gz
    ├── 150793cc400917c15f58caccbe08d8a4baae3263.nq.gz
    ├── 1584d8b416e74ffc0f94d6ead41edf5b59f95b41.nq.gz
    ├── 15cb0ecb3e219d1701294bfdf0fe3f5cb5d208e7.nq.gz
    ├── 16328afa7887ee231d7b7cf6f6fa40e36b6f34d6.nq.gz
    ├── 167753501d16fe43fef9ed73c614917b8c784897.nq.gz
    ├── 168d0ddc1183d1e7c0adc192bb84ce256e2b463c.nq.gz
    ├── 16e564822939c9276b326949d180d4cb98a448be.nq.gz
    ├── 173bb84113131045ee3e679b128d59709b16767d.nq.gz
    ├── 18370b9d23b7893454436fae1060951e1a9e09e8.nq.gz
    ├── 18744831a43b8e89f019bf1a3d03aa582e3d4707.nq.gz
    ├── 18c5d2ed52c8d03846de6c44c2fca15f81318e8d.nq.gz
    ├── 199b22fa6e6bb4bbe944299dc00248e89c769689.nq.gz
    ├── 19a01eea3d1b87e58ba41e07917b3ffb672ae34a.nq.gz
    ├── 1a2efbb44c7ee9069ff720755b457193f5b14216.nq.gz
    ├── 1a32a260af723000a3a3c774c3a323cc33774ba2.nq.gz
    ├── 1a6c99bc4022e672890eef8c23f19e82093d75b6.nq.gz
    ├── 1aa94a4269074199e6ed2c37e8db3e0826030965.nq.gz
    ├── 1abcc031b4a2e571c89512c0f3b3f7c6ef4b92d4.nq.gz
    ├── 1ad75961157bd8627afb7a4cd22b65c4e88ae2ed.nq.gz
    ├── 1b75eba576a2f815eb54b6d154def35c4a695acb.nq.gz
    ├── 1c7f19a3a9ea8ae58f46474c04a042185d6739f9.nq.gz
    ├── 1d319e4340c5d93a7efa30944b2a7fb9773b0ed0.nq.gz
    ├── 1eb5628e05e30b760971f93bad9d70c76902a6a8.nq.gz
    ├── 203404989fc8de68977d266346d2bef7c726649b.nq.gz
    ├── 2152a91b0c90637d94d5984d653d9d78ac9436ea.nq.gz
    ├── 2173bd64fb8357bfa762d76533afca9bbbba10f9.nq.gz
    ├── 21dd41a07a63c8879401e89a7820f392abf467d0.nq.gz
    ├── 223485a63413473536bcfa07c906f9a54d310228.nq.gz
    ├── 223fd5205ab0f02d2542c76bc1a32bc78a059f44.nq.gz
    ├── 2270fc1dccd0669e242368e6cb1afa50d808362d.nq.gz
    ├── 22a73a27f3a924c953bddf6850bc3187c7546b26.nq.gz
    ├── 24467a141f791695fc1009c78d913b2c849d1412.nq.gz
    ├── 24b1138e9643b08212ae8b069ae79cd042f38299.nq.gz
    ├── 25d9e1c3a53535fc099ddaee9e02dcd572ea0543.nq.gz
    ├── 2667de1ea5599e9260cdb4d06e93d7d3cd3a318f.nq.gz
    ├── 27630d6775b6b4715ac35b4eb41f0f66c6a65301.nq.gz
    ├── 27b65d407bc2ecbb13ce5dcb92e74fad374cc586.nq.gz
    ├── 27fc7c2960688da71cf9ed71a369f692ee42c7f2.nq.gz
    ├── 2958eea225948cde8479753f653c0e19bccecf86.nq.gz
    ├── 29e8ca4fec469294c1cfecb17104bd46acc916c2.nq.gz
    ├── 2a00b3ee431e4aa7d6604cf22bfacb44fa729a60.nq.gz
    ├── 2a51635a4f55d1f77eb949482c0090ce11560605.nq.gz
    ├── 2b698343775db6e613380a7c1b4c6b92f0c4e97f.nq.gz
    ├── 2c7cf41821c9f476c8803462c6450190d5f4a2fb.nq.gz
    ├── 2cd7614cb6492701b93b8a91f48f65f57ab3a704.nq.gz
    ├── 2d5c7989d9d9175963d7533d6668d60a94612417.nq.gz
    ├── 2e65efe2a145dda7ee51d1741299f848e5bf752e.nq.gz
    ├── 2ee271a3c3659b3c660b8e7d5b8334b413a1eae1.nq.gz
    ├── 2fcdac384852236935574d6a603aba545ecfd476.nq.gz
    ├── 2fe5cd4f0625afe0996d51be20bd828a26581539.nq.gz
    ├── 303e12a9070a2a256b063d59030397fdf023e3c4.nq.gz
    ├── 311c17e57b4baee51b08cd87d15d094fa9ef376e.nq.gz
    ├── 31ec6cba83a2366373ad035039aa010d062421df.nq.gz
    ├── 337abac7abeb98e38957cc6958dd3f4e693122e6.nq.gz
    ├── 337fe83ac674442a933d3b5b6c0d7785069330aa.nq.gz
    ├── 33a861cdc5a19f4a7c2cb63bb48a97bb58b20bfa.nq.gz
    ├── 33cc2186e37ee91fc931c5f88291481a52b49e56.nq.gz
    ├── 353fa8080ccfd350af485583be2502fca28415bd.nq.gz
    ├── 35e11ceb57753810c931ed55994034e25013a9c7.nq.gz
    ├── 3657f1363152511c96ef9d17539c3e44dde3888a.nq.gz
    ├── 36dd9461115782d821368dc81b2a36548e856f91.nq.gz
    ├── 36e2689f52c5961de45bd04ec4f63c5c583b7dea.nq.gz
    ├── 3704a08150b1b04be02f44dc5abb020a1a16383c.nq.gz
    ├── 378ae5c8b703ff1a1fd28f820e3c87aaa59bc74d.nq.gz
    ├── 37922adfed6ec7d733cbed155b699931e671205f.nq.gz
    ├── 3909af66e254d6b95515b5f07d6cf64648eea47d.nq.gz
    ├── 394c2142a79a9e86cc2fbc5b54c8ff44d315edc4.nq.gz
    ├── 3981f721052302eba01076c4dab50dc69fa80f08.nq.gz
    ├── 3a34c59f1b4f6dd367b493857df3c0bb09f58f8a.nq.gz
    ├── 3a9cac7caf7c9fcc71761e8619bac2f20fee73ef.nq.gz
    ├── 3afc3ed62f0f208cf3207285667dc4fc4215b68f.nq.gz
    ├── 3b20295f7fda74f9e2bc5a15411ec0e34a28f2ec.nq.gz
    ├── 3bb3f8d7a8bfd91cdcc974496df8a0b0c9cb1b95.nq.gz
    ├── 3bc8193c14bec421d2e71643de602e3123a8eadf.nq.gz
    ├── 3c4ecbaee8ed21eac254935b4fb9b72472e3901d.nq.gz
    ├── 3cf713b390408425a68b1863026b3899dad53303.nq.gz
    ├── 3dc99a551a3d83316718c75e218b8dc6447b3586.nq.gz
    ├── 3e409ef2932b455557019d5c491bd4053a542c1a.nq.gz
    ├── 3e5e9547298b21dc6f098d368af7a7df297ec53a.nq.gz
    ├── 3efeb7641d50b370d6b08b96b83376a9f1aa4fc9.nq.gz
    ├── 3f123c8ee0fb63aea02391a2a8388dadba09043a.nq.gz
    ├── 3f2b0bb2327a9a20fc0c575082a59ceb60f2f6c3.nq.gz
    ├── 3f31e2bc4fda43715f00a3be20232a0a61989662.nq.gz
    ├── 3f8c0afae4dc6ce08c9093621997d52b822bd6c4.nq.gz
    ├── 3fa8f862f753336d4fabfd607678a7a2317e8a06.nq.gz
    ├── 4050b9188a5715b7ed4ace35bc8ebb89dd20cb59.nq.gz
    ├── 40938ea2f8559349b8ab803579860a17453c75c7.nq.gz
    ├── 40c26585c8813ba87f4a977cbccc73846757852e.nq.gz
    ├── 40e4a628393b4fdd7e04a2ae366d84534257df37.nq.gz
    ├── 4110f91ab42ded03c0a5ec3c79e3f46c992683df.nq.gz
    ├── 412d10334d42e81d257ef90eb607fc57e9dcf749.nq.gz
    ├── 4160ce1c0138c5d03242f3bb7114b7a7325af113.nq.gz
    ├── 430dfabc5c448ab59153f3e08af753f2af964813.nq.gz
    ├── 43a216ccc70a5870204728464e66dc549b41e44a.nq.gz
    ├── 4432ce4f93f2a016b86b048badee801b02c5cc01.nq.gz
    ├── 4441d5ec14d84f4a60da9e6fa1128ea4fa8e5fa7.nq.gz
    ├── 44622233c20c802fc03f6eff4584605f136b6631.nq.gz
    ├── 44a046f261277c447e63f012d43c8a2d572f9272.nq.gz
    ├── 44c6bbfd8f2f8c28e8ec467f17197690909f172e.nq.gz
    ├── 4516a51dd81e2e65fe104f5dbf8ec4e20ffd7520.nq.gz
    ├── 45536fc0f1b1e66a08fdc36f418399443e626071.nq.gz
    ├── 4561240f1555772d42acf0b206ebf5a9a47c4778.nq.gz
    ├── 45e6688a4d0f605fe2965411c8309bb57229df4a.nq.gz
    ├── 465a4abf76793476d70a03e0d8928bdfdfb1b407.nq.gz
    ├── 466f7aadf303d0910b5e75dd54625feb11a9607a.nq.gz
    ├── 46edcc10e917c85c769c9c2694a474898298e614.nq.gz
    ├── 46f5bca40cbb752340fe580bdfca28c52f8c5a5b.nq.gz
    ├── 47d387fe38223e34744073a3581435c654cf6049.nq.gz
    ├── 47de8766f06f9df0f60924d0b3ad558658712391.nq.gz
    ├── 480f41a453ea5ddb1f1be9c3b6c03dae0a7e33a7.nq.gz
    ├── 48136b7efc71d57e44caa2615551394ca763daa3.nq.gz
    ├── 48271943dd059d001893cbc9d219cef64fbd448e.nq.gz
    ├── 4847b76cbc30eef3230d3fb74e853d1697057bd7.nq.gz
    ├── 485d834ec4725fe145b62f0e6e2dbdc73fa5cd67.nq.gz
    ├── 490eb425864c988d88bb08020a8a7c7c3560a9e5.nq.gz
    ├── 49207d9feb4454435013f906a2f5239d63419d14.nq.gz
    ├── 494be846f8e127aeca31a9d7f12503a1ad4cc6fb.nq.gz
    ├── 49b0c4d75599d41806d03f5754e7ebbc2a70f9c2.nq.gz
    ├── 4a05478c6b9d368c7e4330b51e004f5c33ff3c56.nq.gz
    ├── 4a874ec826524d741cc7fbc33c1af77f5ab31e8b.nq.gz
    ├── 4abe072336bad8c549579d7b1c7b62a5ebd4e31a.nq.gz
    ├── 4b40d41b0f46cce570d84f5b496b373410ea8cef.nq.gz
    ├── 4b5142678b20a6f43a683c16b7f672307796366f.nq.gz
    ├── 4bc047e00002a6138fed0dedd3c45fb2b190eb12.nq.gz
    ├── 4c44d9dcb3b3d424161657682a4c071f1be60548.nq.gz
    ├── 4cac2a42ff40fdf44d148ddb6eeda4a881b8e589.nq.gz
    ├── 4cad858a74319421f3c3388e580c7624b11cb913.nq.gz
    ├── 4cc1fb6481ba0dd04b3b53554d4619b8b5a762a2.nq.gz
    ├── 4ceb828cccf1d28cc479b5f5fbe61c4cf8de886d.nq.gz
    ├── 4cfb5ae59bebe8f2b3add174bb7757596c8d15cd.nq.gz
    ├── 4d2b77835f410d103c6295b203260531179e8800.nq.gz
    ├── 4e528827015797c5632600b89c95edbeb9f26246.nq.gz
    ├── 4eb27221e5f11d41dc996b3ad81d950da216016f.nq.gz
    ├── 4f242017f25e8b441ee2a9b45963fc93ba866a19.nq.gz
    └── 4f4a0229e56520a39819d5b1435e5db02b73de74.nq.gz

7 directories, 200 files
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

[square/okio](https://github.com/square/okio)

---
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
