# Repolex Knowledge Graph of scrapinghub/pastebin

RDF knowledge graph data for [scrapinghub/pastebin](https://github.com/scrapinghub/pastebin), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/pastebin
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a712e60367fc41c42e341c4821cfb07b5ac80c50
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a712e60367fc41c42e341c4821cfb07b5ac80c50
│           └── chunk-001.nq.gz
├── blob
│   ├── 014951529c315d6042e72febc310a4d2db5b4a82.nq.gz
│   ├── 05a774b89c82457ac3157bcbbac40052e71a2d88.nq.gz
│   ├── 06283ceea22348dc41894c9267bdfff05dc5485c.nq.gz
│   ├── 0b30ddf632ceaac39252c9bcff0a8d399cdf7230.nq.gz
│   ├── 105d5fa86524470608e361ca5ac667661e3c7de6.nq.gz
│   ├── 139f0b4311ad2e0369a347b3be6c46e6c2b730d5.nq.gz
│   ├── 13b2fb6482b323bfbadf349632a8f55191cdc1fa.nq.gz
│   ├── 1459fc8845a8c8a06032f039808704de5ddb798b.nq.gz
│   ├── 162ec36756a1fda6efff4f554c6e38935ced21b6.nq.gz
│   ├── 1d4525238f7ea20615c98a36d5aa809f22f215a3.nq.gz
│   ├── 1e1ee437da82d053d49ed52b093857f2ec8f4b4a.nq.gz
│   ├── 216268f7bea124b840688662fae977a873568095.nq.gz
│   ├── 24049248569555995b6a4e45d1ec62d87d53bac0.nq.gz
│   ├── 241a43f5bcb29df7e07afaf43f87c6ee64fbff07.nq.gz
│   ├── 256936e45872610e3866c62acebd09359f7e2cd6.nq.gz
│   ├── 26bf9da837febd20d0bcd762d7a0474087d9fffb.nq.gz
│   ├── 2840d4c6f98be03be2d957a4eb7353acd2775427.nq.gz
│   ├── 2ab019b73ec11a485fa09378f3a0e155194f6a5d.nq.gz
│   ├── 2da49c9fb98b4f5b9ab3f9e2c29c90e3f67ebe35.nq.gz
│   ├── 3845b2518af077fe9fb16a4376f5240b03e73434.nq.gz
│   ├── 3869d843d3b12c1b62d746e1db442362abd5817f.nq.gz
│   ├── 38c38335d0919ceb7b0dd09e88a86be90a966ef3.nq.gz
│   ├── 3a0c4069ea808b4f21c191bc14f8cfdc65e536b3.nq.gz
│   ├── 3a40ddd564fe0ea0a8e0f7e103afa2bd01040ac5.nq.gz
│   ├── 3e451c8cfe6aac6c0e4753ebdf5b3381a0dddbf1.nq.gz
│   ├── 3e9548447e462bdcc1c193d391a9c345216f11bb.nq.gz
│   ├── 3fa716ab5c2ca329aa72e6b6e4488ee4bf2b8fb4.nq.gz
│   ├── 40693fb241e0b7df699f86a1b6a790b8bbf43f76.nq.gz
│   ├── 43ed0d0b37030029a1e611d02cfbecdc50866731.nq.gz
│   ├── 4443fdc1a156babad4336f004eaf5ca5dfa0f9ab.nq.gz
│   ├── 47acaadd737478ddb090f47f618810712163317b.nq.gz
│   ├── 4b4ecc66671e45e9dac162aa85dab558cebc191c.nq.gz
│   ├── 4c40986cde4c25994434c700d57095db433c990b.nq.gz
│   ├── 4f3faf8aa8b1054ef1b18b80ab58f670b406a794.nq.gz
│   ├── 51d6111d722981a86766cc99c53f1956e5c0a229.nq.gz
│   ├── 5254838eaa0b3689c3da8bc5471c6e7d25cb28ab.nq.gz
│   ├── 57e74a6510dd6a4b29668db181cb94727d1eb4b7.nq.gz
│   ├── 58cd6b5e61eff273e920942e28041f8ddcf1e1b5.nq.gz
│   ├── 5af21573dd4252300415632c2a2b3895ecdcf17b.nq.gz
│   ├── 5b5dab2ab7b1c50dea9cfe73dc5a269a92d2d4b4.nq.gz
│   ├── 629424047a49e46cc5277cd90800fbee34d1f763.nq.gz
│   ├── 636d4a0ab4a7b6d21f516a497508402d2a1ad4d0.nq.gz
│   ├── 672bf761fe9ebf408371373f84d7203358766854.nq.gz
│   ├── 686392ce13a9764a3348aec19a9537a19d06d30e.nq.gz
│   ├── 6a5fe686df0aa31c44e2be5f3e0829c8300fb891.nq.gz
│   ├── 6ad6e1266faff2824dd3cef235e1c833875c2121.nq.gz
│   ├── 6ba7fed9c34b160277492ee3741b75caa0f501de.nq.gz
│   ├── 6f4bd87c041453ef037c4a9a1a698f0105d02eba.nq.gz
│   ├── 6f611fcded04e789f5dc46a8e15330d49f1494c2.nq.gz
│   ├── 734201bed16677bc6494af52a15b4c842bb60184.nq.gz
│   ├── 7473e1fe616530b3d2a00420b8d5e716d5a04f59.nq.gz
│   ├── 7686843d2ccb20a87f405de7eb325b65c874301a.nq.gz
│   ├── 76bf892d40c9283e0cbce51b602aa5a2b73aaa4e.nq.gz
│   ├── 7792ddbfdc8f049df5118916c26221793df6b8ed.nq.gz
│   ├── 78625024d94a74eb1aceb327f45059faf439fece.nq.gz
│   ├── 7d4e877ad04da75e8b11e39a9007224fe89a726f.nq.gz
│   ├── 7e2164308cffac007edc4b8d9a07d0e0919b1812.nq.gz
│   ├── 7fd2534a23e6268f408779e7c40fc2f48bdd15d4.nq.gz
│   ├── 7fe87ae414569f5d8c68fbbcc540c74dbb5b2731.nq.gz
│   ├── 80a901ca54c7c59762450dfa8e4bfd66cd47b7c2.nq.gz
│   ├── 81ae596d6da716245c31cd3670371b5311cdc851.nq.gz
│   ├── 81ecc362d50ef5abbc0420aacd5345822f1f6098.nq.gz
│   ├── 8332c4ec23c853944c29b02d7b32a88033f48a71.nq.gz
│   ├── 84defe6e8ab878a83d7ed145c4734e5e1117cf0f.nq.gz
│   ├── 8624542ed208db88b2d1e99bcce1e1acc7e6c28b.nq.gz
│   ├── 8651ade7cbe030e85efc811a844d8f366c97a50c.nq.gz
│   ├── 87fbcc8e6b33b1b1ecc3d91302920a3d45c61ffc.nq.gz
│   ├── 88eefb1c21b94352ca1494790b205572d403f4be.nq.gz
│   ├── 89692f74f051cd43503744c3dab65c8ba773b7e2.nq.gz
│   ├── 89c1711113b1f29cde4cfb0773524f08cb2d0867.nq.gz
│   ├── 8a3b012135ab56508a018d20b9c850875c8a359c.nq.gz
│   ├── 8ab8dc89ee5185b894004e8f8441c2e4fc44cb80.nq.gz
│   ├── 8d323b7e853eeb75be21299922cfe5bba5c64f44.nq.gz
│   ├── 9762683ece45d0df8b6d96b37f8ac2665863e690.nq.gz
│   ├── 9829625bf864afcec01c49eaa09b291d529f56b9.nq.gz
│   ├── 9af10057e4b6ddb040342dcbf920a088b303b2ee.nq.gz
│   ├── 9b028268a44f2cc8b4e88a51acb1df2264095d17.nq.gz
│   ├── 9be6547ed61cbea68f354fc49651bc3645c822fa.nq.gz
│   ├── 9c5cbe9f69b613a3154edfb47102920dbd1f662b.nq.gz
│   ├── 9f3eafaab0f048da81e1e072c3091282742c4980.nq.gz
│   ├── 9fb564f8d0a117f17aa6b844490309dadbd94821.nq.gz
│   ├── a49f0600b0416ef695b2ab036bbb2a36defb4ca8.nq.gz
│   ├── a6dc1c0891b28670981c600ce613e6956afe67c2.nq.gz
│   ├── ac4a977362738ca7daa20784717f10f9617136b4.nq.gz
│   ├── ad2dc6f9dbeeabbda9ae6917659b6df07817ec35.nq.gz
│   ├── ae3c529aba57651dd177bf5019c1f1411544e51d.nq.gz
│   ├── b03e4a6031501497fca02d1a21fd7a6a62c69128.nq.gz
│   ├── b55eee397ee4c3a502f33a0e6ff708101f59fe9c.nq.gz
│   ├── b57f798fb63c88f7190b35f56dae043e72c9acea.nq.gz
│   ├── bafce519822194da596ef3ea6eeba91d0af643e1.nq.gz
│   ├── bb4052f37829745073f6218f35993d6e099930f0.nq.gz
│   ├── bd2cf079add1ca236adeb509698adabbffb08acb.nq.gz
│   ├── c2de2d7111e3cb59cf6511dd2ab045e824bdb43e.nq.gz
│   ├── c47fd20beac01131ebfe7f6b927344056487c77a.nq.gz
│   ├── c4b09218288e0e66609b782b0ee635ba93d0eff1.nq.gz
│   ├── c7072a7abab64fdaf0915f6c8cbc4b050cf5c179.nq.gz
│   ├── c89ecfb1061efe588705664ce5a98ff89b2ca75d.nq.gz
│   ├── c957b0eb28dc482bca358405db9c40bb579f89a9.nq.gz
│   ├── c99a1d94cae40a3a80b971f2aa60a181e74d6e4a.nq.gz
│   ├── d200b83e8bfc732e1fdbb4a3b29a658a8b53aa87.nq.gz
│   ├── d742bbaee463b4179be57b9d59b4ef7305c4853d.nq.gz
│   ├── d788627097eca24818dd8f119ac1325aca9bf5a3.nq.gz
│   ├── d82725635a879e7033c305107ebe523a3fe8bd87.nq.gz
│   ├── daa8ad8cccd5fde8f9271939afa438f9f302b316.nq.gz
│   ├── db87076952d35ec04af6010ad2f6549c9472135e.nq.gz
│   ├── db91380f80f6e8cd335b3ce2324239842a9a09ef.nq.gz
│   ├── dee2f9381da4ab71d692ced4f8e620db4c5b158f.nq.gz
│   ├── e059ad5d8b9e8ef7d3ce9947bc33ae8e66858603.nq.gz
│   ├── e4bacf5291f0550f534e12a555e26d2eb5d2bfdd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e95cb4dd01bbccfae40cd187123dac984b1f2896.nq.gz
│   ├── ea7220df88eb21bac0fc65681ab9f8b3e9d27d3f.nq.gz
│   ├── ec45addbf7f08fc02235c19b309d3ea3dfca11ca.nq.gz
│   ├── ed185b99cb5f0fa85de0c49faf36280330b26694.nq.gz
│   ├── ed5d6d514fba2333c33c1bb28ca7b894a64c4376.nq.gz
│   ├── f20cc7c11fc8046d6e3336b52de92f7c6f2520f6.nq.gz
│   ├── f28b6c841ebffae4b08487ad088b3ec069d03f8d.nq.gz
│   ├── f565d47cc738c53b1297f9e25a284ab84bf8c046.nq.gz
│   ├── f7a3e16787d828751479829e6eed755d48da00ff.nq.gz
│   ├── f7b8f8a02d1810ba447f5175a5750d3dcfd9edef.nq.gz
│   ├── f9342b9e7c4de5cc79b994d21142a26ece6d3b02.nq.gz
│   ├── fc35f239ea0459d809a5430a61920f22217932a1.nq.gz
│   ├── fea3b2f080dca6cf549dedf0fb4c29ef69047e0a.nq.gz
│   └── ff701e19f6d2c0658fb23b1d94124cba4ce60851.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a712e60367fc41c42e341c4821cfb07b5ac80c50.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 131 files
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

[scrapinghub/pastebin](https://github.com/scrapinghub/pastebin)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
