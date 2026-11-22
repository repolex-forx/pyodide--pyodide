# Repolex Knowledge Graph of pyodide/pyodide

RDF knowledge graph data for [pyodide/pyodide](https://github.com/pyodide/pyodide), parsed by [repolex](https://repolex.ai).

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
rlex download pyodide/pyodide
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 276aff3ecadb34681a065fe8cadb178b58f5aa4a
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 276aff3ecadb34681a065fe8cadb178b58f5aa4a.nq.gz
│   └── repolex
│       └── 276aff3ecadb34681a065fe8cadb178b58f5aa4a
│           └── chunk-001.nq.gz
├── blob
│   ├── 022873e82406e1d03faa1e35a0f368bc821b9b8d.nq.gz
│   ├── 022fb04ab3dc99f4731ccbe504e1de4ec9fcd0c2.nq.gz
│   ├── 032fa4f6571750e427ba4e538c27199b3f7a0eec.nq.gz
│   ├── 04be3412738fb744385f24e42912b39720eb3da9.nq.gz
│   ├── 083d7fda4aed736999fdc53785ce05e8c20ed82a.nq.gz
│   ├── 08479b9c15bbe75d6aefee9cdcef68a3d4bd9e5a.nq.gz
│   ├── 08eb7acb4fd0e9b6c871c869946ea17a028b1f4b.nq.gz
│   ├── 095644925dc3b294d4eb271dcba957cfcf1523f3.nq.gz
│   ├── 0ac1a20fadb1fff356b8f551fe1f8a4a860e7ba2.nq.gz
│   ├── 0ada785149125b5bbbc8ecec4d9141a37432e498.nq.gz
│   ├── 0c076ac819a5b8e23b8ed5422c729467edd78341.nq.gz
│   ├── 0cb70deaba052aaca73dafef756646dba9033a30.nq.gz
│   ├── 0d2ae6e8ab6eecb6d05c552011c102d570242065.nq.gz
│   ├── 0e81a65a4b6042d68c7825e291ed0992d2a09f4c.nq.gz
│   ├── 103320d72bf6d825ce3aa186ed3ba07716902cec.nq.gz
│   ├── 11c1b0b752178540d00e20abb76e53036c9cc2bc.nq.gz
│   ├── 12442d3ce6b01d2d4b4dd4a84fbed21d1753d1b9.nq.gz
│   ├── 12ce3539f28ef11ce46965b99535e0ff2e896aa1.nq.gz
│   ├── 153de8622b884c435ebd21eb9cadd929961c5c21.nq.gz
│   ├── 154ddef3d755ed30eb0ae75e07a57a22f5b086a2.nq.gz
│   ├── 157e943fe21f3d3cb28a4eceac0850c1df8b223b.nq.gz
│   ├── 175d510f4963da2be6c4d46fd7166551f96900f4.nq.gz
│   ├── 1ab28fd424ac58f2260f1830a2ed77bcbed7516a.nq.gz
│   ├── 1e2a1d45721bbb7f83f33304c544994d4175800b.nq.gz
│   ├── 1f53b53d52032fb4bfe105448361d09fc63bc7c0.nq.gz
│   ├── 2002bd77f7bcf7e8c3f382cf9c6e42ea0085a1ae.nq.gz
│   ├── 201821f0bd918eb72b9a719885cda26eecf8a29b.nq.gz
│   ├── 2058c13f2cdf84cd7ce67d13cc6e733a94e0235e.nq.gz
│   ├── 2229dfb6121508a35a8cd089f1b4f32689d3d652.nq.gz
│   ├── 22482306ebb6b6db885348757202147f6d70f3a9.nq.gz
│   ├── 22c48b2f74fb4bce7b1a57ab8990f217d850f309.nq.gz
│   ├── 244f39198dc55d9141c08048f196bbbb0ebafcae.nq.gz
│   ├── 257e37a7c80b0e6146a9c8a433cda65357a66810.nq.gz
│   ├── 277c109f21f7a9f35a34689428eddafb108591fd.nq.gz
│   ├── 27c033fee39176c1d376244a363f6ab436cc1195.nq.gz
│   ├── 29150270ee4b006fd7d60285bd04eca598f17504.nq.gz
│   ├── 2a4d05b6f1bc1108416b4070f3b89e25f0b39626.nq.gz
│   ├── 2d2262eae0784c2afb98155d6e8edb311c0a7be3.nq.gz
│   ├── 2fe1198b65aab0f3caadb313192e2ce34b826c1c.nq.gz
│   ├── 33594baf71a5522338f1cc09e4340e9ec16c85fc.nq.gz
│   ├── 34dd3f5ea8f601160e19e1a65b0d9b6d1f7d16d6.nq.gz
│   ├── 368f41714dda8b23d57655c025f8c6feb23c54d4.nq.gz
│   ├── 380d2e82e54723978c458790a4f3c00adcb6a04d.nq.gz
│   ├── 392b81b5b7e7555cac992a80e1a385430be92b49.nq.gz
│   ├── 395fdf15c9fd7ed1b858e5f560815a33d2e89e65.nq.gz
│   ├── 3974a3e11513ede3d46fd4efca1ea443b97020a4.nq.gz
│   ├── 39fb3ea474a4ff1deb547e4a20008c32a46f373a.nq.gz
│   ├── 3b6c025a2724476ddc80277761a61dcf049efc4a.nq.gz
│   ├── 3dc5eec20fc064f2795daa1d495c0596168e3cbc.nq.gz
│   ├── 40fe2bd40105f7a6dea0a49fba382c37991bcad9.nq.gz
│   ├── 4113aac0b7f3abfcb6be81ffbdbb758b9e831ab5.nq.gz
│   ├── 414c365582cbea2adc8ce800f760035c727eac3c.nq.gz
│   ├── 43fd6b61a11a24a16d925c39c53e64398d3cd2c2.nq.gz
│   ├── 4698f4b5e4fe1b580062cabb3f138207761685b5.nq.gz
│   ├── 476d8bbb906166a49c86c7b73137da5b91bdb96b.nq.gz
│   ├── 477419de91071f14a23f4ee0982f81422a0e74e4.nq.gz
│   ├── 4c4425bff943c138d99483a68ff589ff37eb559e.nq.gz
│   ├── 4dda010ece52607706bd6c5c9c20439c78d22d42.nq.gz
│   ├── 4e5354bbbb182db5100786889107e60549b3df56.nq.gz
│   ├── 508a28b9619de8775b6d98fc5a1f827d83cb1b6b.nq.gz
│   ├── 508e8345b9177ecf7d3ca8bc6b8a4b4dcff57b8c.nq.gz
│   ├── 52c77f4bfe838a9d02673b247112779b107b7a92.nq.gz
│   ├── 5370f5ff6d049331063d163eaf44a2c8e8f33978.nq.gz
│   ├── 53a8df18083e7864d82325f0a172bdf5ea5d915a.nq.gz
│   ├── 544d050bdb1d49fbc75dd47e4460b81022e56508.nq.gz
│   ├── 5565cc9ac02e4d93faf171e6c38eff4b25ac8070.nq.gz
│   ├── 5613d0e1810e22177c9052b30ece9365da825412.nq.gz
│   ├── 57f59a1678662e3bae5f4173f2aa5ab139d9e2a2.nq.gz
│   ├── 59f73f883e19cfe4f090f71d5ddcbe105ad16f0d.nq.gz
│   ├── 5a93551cc9419066a4998c2bb1c94d0ff4286cce.nq.gz
│   ├── 5b9cf013d7bf4268d6ae1abf9b7120dd7fb3f422.nq.gz
│   ├── 606d383b4a0e2ca480a4c430ea9a32dce065e9a7.nq.gz
│   ├── 653c925c948cd65e43fc4aa8e7ac40b598cef6f1.nq.gz
│   ├── 671c786efb9883f2b6ec1a0cab6d53fb34fdcefd.nq.gz
│   ├── 678d7d0fd3f3cab90d74fc4d01b85d249c83cc4f.nq.gz
│   ├── 683173a836c45b530ac4525aaec81b7212755110.nq.gz
│   ├── 6838cbc7b1c8cd2c55a351a2acf63faf26fe9d57.nq.gz
│   ├── 6e9e53b36759ebe2c51f8cf153a6ea781c0c1262.nq.gz
│   ├── 6f5626f4bb3386172696d75228b099bedff3c6c4.nq.gz
│   ├── 70def0bead5e9e6b2418a3e9510fb56c3106ed55.nq.gz
│   ├── 750132cfe8c67c7643bd16a716e82b14cc092d6a.nq.gz
│   ├── 7503badc6b45cda421c5a7d3475c5e6ceeb30b30.nq.gz
│   ├── 7bfdde512c8b6ed430d8803706f32a9a8d16c8ea.nq.gz
│   ├── 7d95435ba5393dab5b1457e902eb4d3a5306540e.nq.gz
│   ├── 84b2fecf372a2ce08d39b3bdd88827779e3d8760.nq.gz
│   ├── 867132ed9fb3a72ff0185d1735adba9b8b1761ff.nq.gz
│   ├── 87670cafe20b84be87ec0be1241a7fe33bb393cf.nq.gz
│   ├── 88c926cab5853f2168912011243cff90f1b5c3df.nq.gz
│   ├── 89abf173a7611221755d5fc3b1327d7c752f2297.nq.gz
│   ├── 8bf971d385d533c5f5c4330f61c21700a13f58bc.nq.gz
│   ├── 8c152b525be176c179e8bc01eb86ec0a22e98b11.nq.gz
│   ├── 8c54554255b19864fe0f26b137f8bc6f3a7750b9.nq.gz
│   ├── 8dc18e14c1d33bb0dafb71130bd7ec6b75c44325.nq.gz
│   ├── 8eb546392420498b04dc05ae13b1c2f741dd2e83.nq.gz
│   ├── 8f56cb85703200908e9edfe283e8c5c9a332096c.nq.gz
│   ├── 907f42e0ce183d28aed37f435cd489f38f5b653d.nq.gz
│   ├── 94f62891f0189ac05b49279c33ab0a321a7bfed2.nq.gz
│   ├── 96da9f07ea72e852b0a770e73ea585db05391f19.nq.gz
│   ├── 9aa3b626d3e27a7fffbe59e28ae450a0f2b66a33.nq.gz
│   ├── 9be98cafb8ca21b8075a9613d6b710043e8d0ee6.nq.gz
│   ├── 9cd212cb087e3e542efea837ff69374bf193e4a9.nq.gz
│   ├── 9fbddc7c80951488e20f700fd3acc873a9accfae.nq.gz
│   ├── a0ec1346501b83d0dc23c1145a717387649f0616.nq.gz
│   ├── a2e9a4721c62e72b4675abd429d2d6cc8ad7ff57.nq.gz
│   ├── a418c2cd78b8cc410da328a4e6ac5f53c5c4c32b.nq.gz
│   ├── a55201b4f0a5271b61ce896dbb063a70ad867c37.nq.gz
│   ├── a612ad9813b006ce81d1ee438dd784da99a54007.nq.gz
│   ├── a759c9cd0d06f65c402085ee14ea1c3391154803.nq.gz
│   ├── a8a6f26f362a25cd208ecf7c5d1f263da1230cf2.nq.gz
│   ├── a8a997662a75e0b9919d3ac5691524b4caf35ad8.nq.gz
│   ├── a959b908189e4391d028bfe9a2214ee5c12b5b3c.nq.gz
│   ├── a9635a542ff9a22087871e896d3d0b63b329241b.nq.gz
│   ├── a9f79bc4f4906b7b437fe1ff7d0cdd31940491bf.nq.gz
│   ├── ab61e131f65e4d719381b51df4fdccbbbc53ec3f.nq.gz
│   ├── ac2065e525554b8a17513e63bf25e04b5ee0fb0e.nq.gz
│   ├── ac7809ad519e2df8c048bab8b6290fc7c1c26ff0.nq.gz
│   ├── ad5c7eb754d8a8fa5bb4ae7431c368c400619418.nq.gz
│   ├── adfebf6a08a72cffcf4b0ba2c5c9642b334b2f96.nq.gz
│   ├── aea7f15414707e29b8fa7ecb5226524a399f1c06.nq.gz
│   ├── b02796aa365e4c3db2089f76fb01551caae800fc.nq.gz
│   ├── b2d2a5cb3f39082632f772f6772950066e6342c6.nq.gz
│   ├── b4217f134e49e0f3bc491f94575cab9a1e0859ad.nq.gz
│   ├── b461c9a3293fe04e2129a7e9b89e933fec64ce3f.nq.gz
│   ├── b4a97314868c03b1d5bc00b3cf66c49a66492450.nq.gz
│   ├── b5889b601461202c75f3ae88f88a0fcc8ad7bd13.nq.gz
│   ├── b686a8c00e2ad90e6dc43509caf4605d266d27c2.nq.gz
│   ├── b794fd409a5e3b3b65ad76a43d6a01a318877640.nq.gz
│   ├── b91b9dab0ec42ed9b319c793b63c2bb6a2a498cd.nq.gz
│   ├── b9bd7370300e6b18bbeae60378938c9a43b87f25.nq.gz
│   ├── b9e930e8467e79afb50de0da6477c9cf1336fed2.nq.gz
│   ├── bd492c6ca7081a0965443728c7e0119dd0a81f8d.nq.gz
│   ├── bee738225c45d4ed3f13ebfa6565a2cfb206a63c.nq.gz
│   ├── c0afb3d135539edfc50fd4858c9cf5e8d205c6ff.nq.gz
│   ├── c3de4aca46b97242164b787c16cda14667076655.nq.gz
│   ├── c5f3f93d1ff73fb238ade8d7232dcb8166c87960.nq.gz
│   ├── c9462a3a8f58656e018c4863d0e82b781cb4659d.nq.gz
│   ├── c9850fede7c7dcef8d733da330fbebfbc65cf200.nq.gz
│   ├── c9b2cf8775c2f1894b6b5a710c8a43605a5761f4.nq.gz
│   ├── ca2f741a05457b345e875c30f509cdad2ae99472.nq.gz
│   ├── ca8484b3a2e2ef98cc7c50fbe8ab9f01f27256bf.nq.gz
│   ├── cb8d073146c72844a9aba0aeb149a86318f554eb.nq.gz
│   ├── cbb4c6b263ebf6076626021050f2901405d01ffa.nq.gz
│   ├── ccd5ba9582f53587bf96bc59ca5c2cbfe1ec9521.nq.gz
│   ├── cce1da6896e100d98309f30a31f3ee08ec0fddc3.nq.gz
│   ├── cd6e7431473e97b7621573ba590c4549a5aa0d95.nq.gz
│   ├── ce6dd488d28b9bab62bf8b31b05ba02dfa88fd2d.nq.gz
│   ├── d3d28f6d441acf63e8e9cb5a539c33212d8a030f.nq.gz
│   ├── d5608b1b5c91f50f1beda379be99e679de4d483f.nq.gz
│   ├── d64dafc1b24ace24a00f43e233822d3fac9972ba.nq.gz
│   ├── d92e0ff979402ffe5d02d6219a014bbc930b26a5.nq.gz
│   ├── d9f3cf1cedc44865aad0f778661b0e01b8a9e4f6.nq.gz
│   ├── db5bdd80caa67d8089ab985e8529886d72b4051d.nq.gz
│   ├── dd02dfb920116af54ffff5765c28f8eb5fd74ae1.nq.gz
│   ├── e237e497365f7cfe606940dba4dadb7bb1607bed.nq.gz
│   ├── e2d02a37142aa3f1ea95b7333777a6e8844e9b41.nq.gz
│   ├── e30bc4f3cee4f767a9db185401e741ccfd685bb1.nq.gz
│   ├── e427984d4a2c1904681f2e2ee5980f37640d353f.nq.gz
│   ├── e437119bdb0684bbef914a82f177d8590d99a8e1.nq.gz
│   ├── e511e10d2fd9d3c2a729af5bbebe342300e2b24b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e80534ae4f6cea02a9dd779bf6e3d4ce55dcb822.nq.gz
│   ├── e9d89fcf63a715c7d91b741c4e83a525d83e1fc2.nq.gz
│   ├── ead44870dca2834a20eea93143d72f867b6cc9af.nq.gz
│   ├── ec4f84d76e4d9cede4d920becd79736893f1cc76.nq.gz
│   ├── ee870a33ed3fd5cad2fe25ec751165ad15fd18a8.nq.gz
│   ├── eee632e29a3fe75e8c4cedc91bd4350eeb1fc5cd.nq.gz
│   ├── ef5dc1ddc872a720f0c088d576d5359b8ce4f1bd.nq.gz
│   ├── efc601ccea8bbff0d961c6caee9b8cac0465dc5e.nq.gz
│   ├── f009a7d91ce4e462d09b30a21fcbcebf48b5ce8b.nq.gz
│   ├── f2cdc4287fb8ee6634c1a0076d56078932f5a423.nq.gz
│   ├── f42e9cceb5c0ee7d5a874c12492db32ed12763f7.nq.gz
│   ├── f4c1ed12cb26c1ef010664263c5bfb398d73bb5c.nq.gz
│   ├── f4f08092077cd050c9a56c457b30dffd7a0124fa.nq.gz
│   ├── f54c288ff90929af85ea26968f0792f2c97f628f.nq.gz
│   ├── f5d04f37660b6208833576adbfb0c4435ce49b8e.nq.gz
│   ├── f8412a228c9a0e8d0ea5c8f77d1e38a956fa7707.nq.gz
│   ├── fbed37cb152464d5e558a5f0b64e6cacfbed97ff.nq.gz
│   ├── feb40dc8b01e7ba47eda8b6fe37068178e635524.nq.gz
│   ├── fecfe7b051f00b713c4032e666070dabfa30c561.nq.gz
│   └── ff110187dea0d774edabc55ff564a5013a6ba941.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 276aff3ecadb34681a065fe8cadb178b58f5aa4a.nq.gz
├── filetree
│   └── 276aff3ecadb34681a065fe8cadb178b58f5aa4a.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 190 files
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

[pyodide/pyodide](https://github.com/pyodide/pyodide)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
