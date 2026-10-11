# Repolex Knowledge Graph of agronholm/asyncfusion

RDF knowledge graph data for [agronholm/asyncfusion](https://github.com/agronholm/asyncfusion), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/asyncfusion
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8697a789912e2c73779b924ba7e687a7f157fffe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8697a789912e2c73779b924ba7e687a7f157fffe
│           └── chunk-001.nq.gz
├── blob
│   ├── 104eebf5a3002fccdaceef3a4cb936173c1c2035.nq.gz
│   ├── 14f59061cf44d8b91e71b902e4e49b5576f899ae.nq.gz
│   ├── 166f5948e93f4b73bba8cacdb77688ce48e47ade.nq.gz
│   ├── 17562d5c13456cf8bdfbbf1a1ac743c8969e8d73.nq.gz
│   ├── 1963f91c8922fe0c7997a37dd1b5bda84649cd77.nq.gz
│   ├── 1b5ea8d950ecc9280b7800454efc54afa0993071.nq.gz
│   ├── 28618d3a30201574ac05f3e4d4e9ce4f54c0d833.nq.gz
│   ├── 2be591d0b282c0d9a338f010920de58b9b3ffc28.nq.gz
│   ├── 3d0262a24550153fb9d1f538f5b141dc4415f8e6.nq.gz
│   ├── 45a2f73673edab66a13ab5de206142341e996f10.nq.gz
│   ├── 48ac4e1dc57fc0d2d6718a8fab56c98bfdff35d3.nq.gz
│   ├── 51c4f7a06a9af6dd68db7534df820dbcbfbb30a9.nq.gz
│   ├── 54fde9e3df150efa35c383a6e97979b0d828516a.nq.gz
│   ├── 5c920dd9b2b83bcadbf080ef99cd14d02d84676b.nq.gz
│   ├── 626c81c604840207a860a34020d721f720900e04.nq.gz
│   ├── 6291bdc3a157976e6a07d10432238680e1700671.nq.gz
│   ├── 668be52fab866497e74aab7299df509091c873ed.nq.gz
│   ├── 6a51ba301cb71da78279f9a56e4b55b5ff5a536a.nq.gz
│   ├── 6da5555508bc1d515bf324a476afe0fbae41b56d.nq.gz
│   ├── 724c3763839e9ba272172dc8417573d40ee27b3c.nq.gz
│   ├── 7351aadbdbc8939fa621700163bbd7d92132c494.nq.gz
│   ├── 73b06eb22992b6e42d101677cbeaa4a8f62cecf6.nq.gz
│   ├── 77912ed42f9f18a9bacedfc3a32944092ab96468.nq.gz
│   ├── 7ca8184e9f41ff2429897e766f9bff11231f9721.nq.gz
│   ├── 7d9691ed25addc5c23a78263114e2bc81702a33a.nq.gz
│   ├── 7f2501c0657ae9c38f5f3e7938f3c06f10675733.nq.gz
│   ├── 813649f91158aee565dab8f2a0e48020c46106ed.nq.gz
│   ├── 86a1892c8a849721436aa8d1c9437d22c148d3c3.nq.gz
│   ├── 8a0ebe5105c8138af6b3a2486213aaebae2665e1.nq.gz
│   ├── 94e079454ba8dea24273b90a488d8f9ac820f800.nq.gz
│   ├── 9745ae74d4b2c9997af81c19d9f1ea8a43b3c6db.nq.gz
│   ├── 98eff18db04a2aae498156323a4b4e6efc6c8361.nq.gz
│   ├── a67c4fdfa36cdad643f910246cc7988598db8478.nq.gz
│   ├── b33e39c738266dc7377ffa7f41cdb5abbcc9b810.nq.gz
│   ├── b86938fd59d6836fdbbb416e0ae1de7220f9eed7.nq.gz
│   ├── bf09c81841a4f5f5b01fbc357c749c60904fae9f.nq.gz
│   ├── ce538f555698bf0021a21b00c5c6506b8f9a3dcf.nq.gz
│   ├── cf52dbc06edb53d0e76a38952a13600ca2a7d8ae.nq.gz
│   ├── d4256b16d189012f4fe83313c587599c22b47f43.nq.gz
│   ├── e13b6022e43ec65a1e98c5da71b025757f375653.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea100cc7ff2cff34b4822aaf75f8e30d72c34c98.nq.gz
│   ├── ec1d6756695039999e173a6ca467b2172ea9bbd6.nq.gz
│   ├── ed06cd4231161413d520f18b3810985207dd4eac.nq.gz
│   ├── edaf5bbed3a82e3a10c12990c064aaff19189dc1.nq.gz
│   └── fb0a464b93175e48940f31927e49c2ec1869717a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8697a789912e2c73779b924ba7e687a7f157fffe.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 53 files
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

[agronholm/asyncfusion](https://github.com/agronholm/asyncfusion)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
