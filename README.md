# Repolex Knowledge Graph of Pylons/pyramid_zcml

RDF knowledge graph data for [Pylons/pyramid_zcml](https://github.com/Pylons/pyramid_zcml), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/pyramid_zcml
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b7740dc319482ab83de874e3bc371c25a4563e19
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b7740dc319482ab83de874e3bc371c25a4563e19
│           └── chunk-001.nq.gz
├── blob
│   ├── 01fc2c2232e0bd0def4d8365b025547285b1d774.nq.gz
│   ├── 032c55584deb02ad62b3f430a937a26cb94451be.nq.gz
│   ├── 0341802e5111ad58a05ef6e93e59bfa6e5d3d1a6.nq.gz
│   ├── 049da4a809581bdbc4a9ff13766139c5294a4159.nq.gz
│   ├── 057f1650489157131171c700ca5b9d30ec1a95a5.nq.gz
│   ├── 0596f2020327efd97a4467c3025691844bb703d5.nq.gz
│   ├── 06dd4e2b1164e3d04dde4dd4dbb2ee843874fa72.nq.gz
│   ├── 0ba791d8eef5f0802d4d45a5238d18d8b84ac99d.nq.gz
│   ├── 0da5f4eaebcdbf972c908c8d6dbc26bbe256f3eb.nq.gz
│   ├── 0ddebfc3e5f4cb6babad8d965cc4d31e2dc2f343.nq.gz
│   ├── 11907ce31bb3a828d41476959c0f2464ebd8a7e9.nq.gz
│   ├── 12ed8832d818778811997bc6a08cf47a7553062a.nq.gz
│   ├── 1341dfb83e7c5655fa7b2535ff254482982ab741.nq.gz
│   ├── 135ef82903df2ca17192d937c6144ee8bfc4828b.nq.gz
│   ├── 142b6ca357fee89f09803fc9ad7ff676500c37cf.nq.gz
│   ├── 178e49f67b79e740fbd6916b4434a922df97a9a1.nq.gz
│   ├── 17f87bc198f6c51ccfc2d4d633849b82f26a1257.nq.gz
│   ├── 18e574a2f6cc888ae4f64964ba1ce0445344488b.nq.gz
│   ├── 1a35cdb4aa12a6dd730ed371ee25522957273dc9.nq.gz
│   ├── 1e15edaf13577552426dc36a44fbbe162d30b488.nq.gz
│   ├── 1e3f3ec26f9fc36b6869330c7bb5da96586cc99c.nq.gz
│   ├── 1f01de1e487c48d4367d6973608b71cd96cfdd43.nq.gz
│   ├── 1fbc873daa930207b3a5a07a4d34a9478241d67e.nq.gz
│   ├── 213930e9350b45a4e0d677b7c9bc970b4f1f240e.nq.gz
│   ├── 2369cfb7da3e5052c2ad4932a6d56240c92654c7.nq.gz
│   ├── 2924a5eb504d425c769b8aa3847f512c23832663.nq.gz
│   ├── 2ba3e3b75a81ac1b8c3d8cd54a03936ec430bb10.nq.gz
│   ├── 32cfb9ee741491bf7633b9b95289ef8cde70a542.nq.gz
│   ├── 33b97671ee748a33a464e1a30872e7d970164396.nq.gz
│   ├── 33f8c50b49620af1ff733b6540f452c5d1b80375.nq.gz
│   ├── 347e0554962610340ca1fa8e527261fcabe21763.nq.gz
│   ├── 35a34f33241b3255e30ce34cd0efed3b534f9171.nq.gz
│   ├── 3d811895c66fc969f9b97ead47c143026d3ffb9e.nq.gz
│   ├── 3d84d552a4feac213d71f783b4049e1e6760d9ee.nq.gz
│   ├── 491eb38d5330777aa33f12d8f244727212956126.nq.gz
│   ├── 4a6939ac2c8d2fd800ca0ba516789d2c03cff328.nq.gz
│   ├── 4df5d15e7e0736f2fa12232372788f2eee7948d2.nq.gz
│   ├── 4df7964ec1d4aced8496bf257ae0826c0a1aab75.nq.gz
│   ├── 4f6cb23622c91e4e461956782ac99f90f318996d.nq.gz
│   ├── 52ee910b0199393ffe2dfca6cb0d0ca62ca0e96c.nq.gz
│   ├── 546616b2c6075897fce0b115716a338b4346d856.nq.gz
│   ├── 54e720ea6c4f5d0c934c8c4c96579013684405bc.nq.gz
│   ├── 56e73ee7a62090cf754b8b0d9ac5ed4270f167d6.nq.gz
│   ├── 5ad506a6f181cc167ad255cc1b48a69b41fd142f.nq.gz
│   ├── 5bb534f795ae0f566ba9f57c31944d8c6f45284c.nq.gz
│   ├── 5bec29823c231e340806e4bf4854a9797ba653df.nq.gz
│   ├── 5cf615d269479fb7df47e27322c87dd98fa27388.nq.gz
│   ├── 6099077742bc09011a4536696676e9f963913c36.nq.gz
│   ├── 6a2f701b6ef92245ac1193a2e106363b93fec926.nq.gz
│   ├── 6e0fce3dbf79606c971a21c9f7d070b4e7adde90.nq.gz
│   ├── 6f2c47e7cc7f3186096cb11abecba39fae5e1201.nq.gz
│   ├── 6ffb2b6c442b6d1a35d91372a848611514b1f75e.nq.gz
│   ├── 71f837c9e27a57cc290a775b8260241d456582e9.nq.gz
│   ├── 788bed3643e106bfc86fd4acbc21d9f2ba690296.nq.gz
│   ├── 7f1e43809c146fef9810d3ab896088a7a897008d.nq.gz
│   ├── 81d2161ec55168793fe3706fd630ea31d3fec113.nq.gz
│   ├── 82a189b9eac9b50587ca7edd092274629db0fa73.nq.gz
│   ├── 8351c4a2b3a08064a23993e0bc1d3e54c77f2b5d.nq.gz
│   ├── 83cce0c391186fb48dd07451584ac6749f3febad.nq.gz
│   ├── 89bc6c3d789e27c2cb66f620719d2d4948ea7aec.nq.gz
│   ├── 8ddd5640698d9aa2cffd3c5cbe8fc5578d478096.nq.gz
│   ├── 8e45b972a723e6a6c98f70d756c47ec8cfb4d51f.nq.gz
│   ├── 90531a4b3ed18b20c9d5b952b61cbb935e0e50a2.nq.gz
│   ├── 909cf6a3bb7b60a09a1838b0f066aedd90899334.nq.gz
│   ├── 9256e52e5afb72c7a738da472438cd4db6e4da07.nq.gz
│   ├── 92dedcb76f52fd8a38d3399dab0ba9055916c4d9.nq.gz
│   ├── 96b832576f3530b763a2b871450d74a3a3813d0c.nq.gz
│   ├── 9d2d483b707216a9abfa3e7f7d988baf3ed207e4.nq.gz
│   ├── a5bc0ade71d3da5eab67391e840ff20448c42cd6.nq.gz
│   ├── ad66a09be13670a2b7cff92ef66a3266fa729c4c.nq.gz
│   ├── af7a6db9449bfdf30646519c090e0e7fb173a5eb.nq.gz
│   ├── b0df795c633fd7443c78da26d288b4634bd9e845.nq.gz
│   ├── b0e3f6be211d08e574667fe3883a230441256f45.nq.gz
│   ├── b10501110637980a16f6a2476044717a2ef1595a.nq.gz
│   ├── b23fbc6cfb26252db338e1ac102324ac5f49cbcb.nq.gz
│   ├── b7c8493d8f9df3834d3804e9da431a30943783f6.nq.gz
│   ├── b948510995c63b231a5436c4fd9336c08b535598.nq.gz
│   ├── b96226d0e5d4b5dd2c2597fb9f349ccf65116e7d.nq.gz
│   ├── bb381fc539bf51f49a755277508637223b538f4e.nq.gz
│   ├── be22d2c3de5cb30e8c4774a5f539cb0690739b04.nq.gz
│   ├── c35cbd16fc2d255a8cbd156bd18679b117c62d6d.nq.gz
│   ├── c69260fffd1a97053f075bce6d06206719ff5d48.nq.gz
│   ├── c7beead323eca922f21a39c19b2e8972ab1b5673.nq.gz
│   ├── c7f949ab81241a9d6bdbbae2ce26acce7a502e24.nq.gz
│   ├── c83713a257ce066c8b47fa5a466a90b1d273c37a.nq.gz
│   ├── c90e649f62058bdb99f44960d4bb1107132069eb.nq.gz
│   ├── cbb53e5667f619a89887eb5292c0b1af45b1401e.nq.gz
│   ├── d16d9f28c61fec53d6bb4951072156c4dc6e09ef.nq.gz
│   ├── d2e178c9337f1b64a4dc40f11041c01ba9ffc186.nq.gz
│   ├── d3173e6360a3eeeeffd356895771a31de79dad1d.nq.gz
│   ├── d80d14bb3ecb398656ea763c8de1db9b2893cfdb.nq.gz
│   ├── dba0b6b6f61c56476a16cf82eda53b5eb8e484d6.nq.gz
│   ├── de9e90dc26958d2d08433dbf7e7122fe776ac6f4.nq.gz
│   ├── e3fa39f28214855cf71180da3dbaa7d05605f251.nq.gz
│   ├── e5261747b2347d058585f65300fdc100b7b48dd3.nq.gz
│   ├── ee8f9c94fe3590f30837d354606d965166716c99.nq.gz
│   ├── ef5fe8b125103c4046c18fd1f0e8d0bfa581b8de.nq.gz
│   ├── f09531415dd536ad362c57249a12c48751b6d2d2.nq.gz
│   ├── f095436f42e8316a604512cd0441cf7d1c0e610d.nq.gz
│   ├── f3b2a874ef5e4d3fc9cd103e94433165f441be1f.nq.gz
│   ├── f55caa07c2f5c2a363913f79ccebb019b9006965.nq.gz
│   ├── f805b88c9dfaed9ea11b49810efde421152aebbb.nq.gz
│   ├── f833ad04fcf4bc3b227b32a4ecb729ebd6d717f2.nq.gz
│   ├── fd1914d8d023c35b04fbd5768bc10b5303dd9be9.nq.gz
│   ├── fe407badcb724660c513fc9e98b25badde12adb3.nq.gz
│   └── ff5c3b7112eba3b76bf9b6fc5b37817d4b77feb7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b7740dc319482ab83de874e3bc371c25a4563e19.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 114 files
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

[Pylons/pyramid_zcml](https://github.com/Pylons/pyramid_zcml)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
