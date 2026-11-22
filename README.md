# Repolex Knowledge Graph of tafia/quick-xml

RDF knowledge graph data for [tafia/quick-xml](https://github.com/tafia/quick-xml), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download tafia/quick-xml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5611c894f6b9fd5301c266167a6d3a7ef005dedd
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 5611c894f6b9fd5301c266167a6d3a7ef005dedd.nq.gz
│   └── repolex
│       └── 5611c894f6b9fd5301c266167a6d3a7ef005dedd
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ea373bca33aa54893cde8c2b4a87451534e4bb.nq.gz
│   ├── 045172906cb79ebed246a38ce8f11360eb31f3da.nq.gz
│   ├── 068c2b5e528b3ee4e24adbeceda0f9c822880a31.nq.gz
│   ├── 09f820a38c8e02bb2ecff6bf2e84955864bce741.nq.gz
│   ├── 0bd7cb2be8660a513c518b52f4a016c76321721d.nq.gz
│   ├── 0d7b145ab14db6d2395b148588489691217b804f.nq.gz
│   ├── 0ffdb29f14b6c16af2cd3012a638b0df76aa4988.nq.gz
│   ├── 15ce8eaf60a15ac5cffd6c7bf395137bcb665548.nq.gz
│   ├── 16a30bcb7493efb21c2cf5a80df1c0208a5307d9.nq.gz
│   ├── 185659c91cc5fa5f2b0dcf029eb1c020c4592b55.nq.gz
│   ├── 18c248041e235c8330bbd65220ad883203f9a2eb.nq.gz
│   ├── 197775823597193f9f54ca0dd7ffdd6fd0dd54f5.nq.gz
│   ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
│   ├── 1f76a06b72c75c74cfb217e8b8640d571706beed.nq.gz
│   ├── 23672cb16dc7aab48bb8386c0ff45941d6d8df98.nq.gz
│   ├── 23cc15ecda7cf9086d2cb11872e64f969ac03abd.nq.gz
│   ├── 24aed68eb2c885b1ea1e6fab704bfab864aadc3f.nq.gz
│   ├── 265563e7f2e133490e474f1259dfa9b9824c183b.nq.gz
│   ├── 2690ae39fc54b49f4bbb216b421cec4b0397ed69.nq.gz
│   ├── 28c69dfe27d1fa65880265dc9fb63c13deb25be5.nq.gz
│   ├── 2953e412e2a30f71f1cb9182abf3d35b52fed9d6.nq.gz
│   ├── 2a27a8667c6b49ce1c49f2405811ca48c115302b.nq.gz
│   ├── 2b1d56b999ea9c1c5da5cb645afb9d10b6c8501a.nq.gz
│   ├── 30f132b3927eb27c74307962985a3a92c50b1685.nq.gz
│   ├── 33eb429f485859f22eaf2ee917be9153b39a6fa4.nq.gz
│   ├── 382ac855f6ae2f96ff9b05f08f122fc8f8f7bf4f.nq.gz
│   ├── 38ce06ca8eb0e980cc290c8898577745b8b7274f.nq.gz
│   ├── 3980ddd1445c840827df1dfd72bbda42baf7d063.nq.gz
│   ├── 3a26366d4da66e27c821e462eed5ef057a896684.nq.gz
│   ├── 3ab2613436babf2775df6b59c887a802a14948d3.nq.gz
│   ├── 3c1111686af0a016ca7036622a97e35c8e00bf0f.nq.gz
│   ├── 3d5f9ad400166141448721763eb61a360cb3c5fc.nq.gz
│   ├── 3dc5df63e1885c6170b4ca6fb4bb7c10673591e8.nq.gz
│   ├── 4442f5480054e9e0356aa4a6b103734fe7e70aad.nq.gz
│   ├── 4cc96667fabef249c6b1494fcbcb87288f421b57.nq.gz
│   ├── 4db9e605fb011af9e2997347c537bf5a5d79efc5.nq.gz
│   ├── 4e23bbc68889fc36bb5e7fc4c61c562e2b21212a.nq.gz
│   ├── 4f1c79a6a6e1f822551a62718282ddd95d7ce3b1.nq.gz
│   ├── 50a5f90d8debad26318fa47669bbceda54172937.nq.gz
│   ├── 521034c22a9ff7ad5c01822c18ac9386305a6040.nq.gz
│   ├── 5333f7a446b17cf133a3ff477c1d018b6fd6d8a6.nq.gz
│   ├── 53683fdc2a18ba5ab44469c4221bc99b441a605e.nq.gz
│   ├── 58b4271a71ffe84cd6d407d16cda84f20bd55aa5.nq.gz
│   ├── 5a30229a73b1ceca4d80c5589c99cb6a87e1fccf.nq.gz
│   ├── 5a5105241094958c62bc8f5240f8f8972f4cb245.nq.gz
│   ├── 5c2fca178612483aac18c6bb9d16972c13d50189.nq.gz
│   ├── 5d9ba047802b643d76ad3802b95935f7115712a5.nq.gz
│   ├── 5e569a6c363892d40b7b82aa771e9d130ae131fc.nq.gz
│   ├── 5e615f14433cba1d07c332fbd6351d8792f8ddc9.nq.gz
│   ├── 5efc0117ccf5224b2cef6ab9e34fa472343390dd.nq.gz
│   ├── 600e521a161ff3cde4524b5635fc8cb23240b6d1.nq.gz
│   ├── 62b97fbd654759820d165958cd1c69619ed9290e.nq.gz
│   ├── 63110b8217635f4f9b8b24d5b0ef89015891d19c.nq.gz
│   ├── 631e78d32347e5245da06805b00311b10295f15f.nq.gz
│   ├── 631fc0c68f1ae1e72993bb5bc9842ccd5af908a5.nq.gz
│   ├── 637e732bf03272826722427a40a198a49a3fb906.nq.gz
│   ├── 6432cb952f4e2b8fae8c78c5f8dc52394848dd8b.nq.gz
│   ├── 6484c6e1bd220cd3477286891d22363813770edf.nq.gz
│   ├── 68a930718af647b4510fa6a3e48a47d01c1e9804.nq.gz
│   ├── 695b226e1c02b889cd200c4b8f557a15b68509d0.nq.gz
│   ├── 6e91823d787bcb1bb39faf39ee5c47c65a95cba2.nq.gz
│   ├── 6f5539e2a1c2d9910d01125b7d1d1a085a5b93c4.nq.gz
│   ├── 6f83dc3f5dc6fa6de7395e8cdfcf4305476c29c0.nq.gz
│   ├── 6ff4fef212b6e416450d7c3890c33c17964e5bff.nq.gz
│   ├── 70768ee8ee0bf9845b7456b652960e7fe7cc43a1.nq.gz
│   ├── 74e6e127f821d06ffcb71eaf4936258ae7dbd502.nq.gz
│   ├── 75b82239a473e497ccc2f8f842e0ebfaf334168c.nq.gz
│   ├── 77197b3edb5854a7ae2dd5740d91826bb7392585.nq.gz
│   ├── 7ae179de0f2de4a191e85b7440011d73a931886b.nq.gz
│   ├── 7b3a7ae32074ebdd8878b461c7d8bc7737d08b1b.nq.gz
│   ├── 7d9f951fda5211460646aa66ff3a3e81e67a3677.nq.gz
│   ├── 7e4cca1c1d4c0178f5b3547802f3c61c66584857.nq.gz
│   ├── 8304874e1f65703965a418b9f3a1482953fe9063.nq.gz
│   ├── 8708885c1fbcd1c18b750f154b00da2a5d83e09e.nq.gz
│   ├── 8824610c511611b64d70418e359f8747d8e36e2d.nq.gz
│   ├── 894c97c20620ccf1a3311746a9e8fb52e4ad6267.nq.gz
│   ├── 8d51b22aed039d7a64525e68f864bf65c7b2c761.nq.gz
│   ├── 8f8118f3e10e2726f4a261592f0c150a4089389d.nq.gz
│   ├── 911baaee8242fed326921731da0802aff2160886.nq.gz
│   ├── 92a1e89fa1d0355e9c4f6f68ad72684043d741ae.nq.gz
│   ├── 92c8c319e4025069cddc9433a3d0f177988625f4.nq.gz
│   ├── 94003c0c3992896ccc201dbb2998424b376cd63b.nq.gz
│   ├── 95ef0978077e9e7ff8a04caede98628584d30c15.nq.gz
│   ├── 962bd2000657573a3d4492863494095687c0d9e6.nq.gz
│   ├── 98cbf2b3af576e8158d0ed5e4f757be9d4e67483.nq.gz
│   ├── 99496c934a47f52778bef6521e9e4c2f0473faba.nq.gz
│   ├── 9a529ca6b4264a5822e6d887455f73b70433301a.nq.gz
│   ├── 9d5c04421f777b04496985a1ae3ae2d2e6fafa21.nq.gz
│   ├── 9db14f385841b8f77c970662a7cccffd9aa2cfbb.nq.gz
│   ├── 9ee16eefa17b9c2894c486a39812c8fb43ea9af0.nq.gz
│   ├── 9fb4ee79e34b8de9a0377516dc18e5f55c8ccba5.nq.gz
│   ├── a0ee3b963394bd6f0ebd8a2e3f8904a72f9ee8d2.nq.gz
│   ├── a0fc6a38483d68e047e42a902ab712f54c750402.nq.gz
│   ├── a3978c70797d291cbcbba10aeff12f8017c9c0a8.nq.gz
│   ├── a69f36405ee1596049da80b137257f37a0bb722e.nq.gz
│   ├── a6ccde3d0bacc3688ffa3d5d323df0f46095fe0c.nq.gz
│   ├── a6f5e03556bc2d10c0de44a99a0f8ddfe3217c14.nq.gz
│   ├── a7e3e698a0bb0bb44d4a71ca408ca96f8314cd54.nq.gz
│   ├── ab3afb2a73389103f30dad81dcb35a7c2f635e97.nq.gz
│   ├── b0f3456e2a18d63581e6d6298eccc455a6c60ad2.nq.gz
│   ├── b4d744a46380df1386ada3fb4d8ac7c30853c76d.nq.gz
│   ├── b58a0095e8386d97896ba96814eabba122b4f387.nq.gz
│   ├── b6fb04235316a552d21ac99b2d67ad96a7d2ba57.nq.gz
│   ├── b8a569b2f4dc1f9a24b10cb005ef0b47309d53f2.nq.gz
│   ├── b93c788a918d4fc711e453bf629856009ba622da.nq.gz
│   ├── bcf51350a3f95de5a8a29fd3568dbfe2db14ba66.nq.gz
│   ├── be9d11ea5ec65495d143ae5e2b72a6789b866508.nq.gz
│   ├── be9fbc1552d133a3740afb853277b9e0377cfcf7.nq.gz
│   ├── becbba69b4349adc75d338458a49b734d4e08514.nq.gz
│   ├── c262ba6d0c7c7b8c39c99ac5e38cec131bdfc3bb.nq.gz
│   ├── c56c2fca1e4c380d75d6b46e42a1a586f85643a4.nq.gz
│   ├── c626cf3a247c21cd414d81eb8cd6b29aed06588e.nq.gz
│   ├── c992696b878261509362aead1f1f509555309612.nq.gz
│   ├── c99e6f64d7fd1d6e433e5b2e71b1520589a1ee4e.nq.gz
│   ├── ca2f1beda04cc0e40823ca22a3e59b9bb1b680e6.nq.gz
│   ├── ca9139b5253f10bec1d45890d04c33708b2922e8.nq.gz
│   ├── cb8371da1fb68e821fc5e475d50b64258f935af6.nq.gz
│   ├── ce7bf853fa9b516670f9ba43d55f50440591c8af.nq.gz
│   ├── cfa0bca899dd515937f88de1b2246de116d87ae1.nq.gz
│   ├── d1a1aed39eb6e961f62e43a7f0f1f67a093f4776.nq.gz
│   ├── d2a8bf16361bd9a69d77915e007e08d196094704.nq.gz
│   ├── d3c4e4485cc7c2d504dea7e149fe0445bb9301f4.nq.gz
│   ├── d483afd011118dfddd50bc68763e7cd0f418a488.nq.gz
│   ├── d5e4cb4aafae48bb6334915c6d9018cf8e1220f7.nq.gz
│   ├── d8287ba696265de17032466228705e5c9fdaab7a.nq.gz
│   ├── d894f9501a9975217b254d81219e8a58a7e26848.nq.gz
│   ├── db99111f500b04177ef8dfdbb3ca8b0ca0c67832.nq.gz
│   ├── dbadfe2f2b0188a2dc12431b7393f8413a6cc41f.nq.gz
│   ├── dc5e969683ac84885f49275c36cd908d31a26687.nq.gz
│   ├── de0a5b43f08ac71bb42fbb3550e062aa71218b88.nq.gz
│   ├── e00a17585a0e18d206b3e7a00db7340d4bb9e56d.nq.gz
│   ├── e0b78cfdecc062c67276b47679d9880e2812a93d.nq.gz
│   ├── e29339ce509ceb40600ddd6bbc9032fa9f989dbf.nq.gz
│   ├── e4d8c07f0eb17a95ab6481049f42f4dd13968c70.nq.gz
│   ├── e64e29f858a93a126c1066c7b3946c9bab8714a8.nq.gz
│   ├── e7157c431eb2717991f48012aa21002e77fc2625.nq.gz
│   ├── e7304afde1702bb580c882dd061e8a6d8f089725.nq.gz
│   ├── ee418eb5d6cae8000081e2a85decc03a3704ea94.nq.gz
│   ├── f02f0dfe2dab487202466aacdd813d3954a485a6.nq.gz
│   ├── f0c73d2a166b85a8f62085a400f10f86d4fff825.nq.gz
│   ├── f225d0d6b903b02d52466c2700175b8e71a430c3.nq.gz
│   ├── f3264ef329d5718bdf5a98b94f7b09b56d41da23.nq.gz
│   ├── f546332c0a304145bd243bbd6522d4524739c15e.nq.gz
│   ├── f6af550f3e3b9112939cfad19b7b9e21c04e7ba0.nq.gz
│   ├── f75a894fce8764759596b3aaacac624f58faefac.nq.gz
│   ├── f7944de1f6dc074a6196142a6c9413e96588fb09.nq.gz
│   ├── f98f076579008857f2977ebc4cd26669c6ebc05f.nq.gz
│   ├── fa9ce6cfd8c23d867e217107bb72b1704b28ca97.nq.gz
│   ├── fb2c8672bb020e20058868d3cf159c96d2eda4a9.nq.gz
│   └── fe8bb0826652fea445624dccf6b84164d3de9d3e.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 5611c894f6b9fd5301c266167a6d3a7ef005dedd.nq.gz
├── filetree
│   └── 5611c894f6b9fd5301c266167a6d3a7ef005dedd.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 160 files
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
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[tafia/quick-xml](https://github.com/tafia/quick-xml)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
