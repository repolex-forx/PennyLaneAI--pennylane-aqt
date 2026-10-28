# Repolex Knowledge Graph of PennyLaneAI/pennylane-aqt

RDF knowledge graph data for [PennyLaneAI/pennylane-aqt](https://github.com/PennyLaneAI/pennylane-aqt), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane-aqt
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 54951cad65f717792b2c4dd43ca78628edebf144
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 54951cad65f717792b2c4dd43ca78628edebf144
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bb9552796d5cf6635e326bbb4124220d591e63.nq.gz
│   ├── 037ce6dbf34b7c41a090b4dfbead6133054a4d15.nq.gz
│   ├── 10c4717018e0dd8ae5399e5c89551a45e16f9bc5.nq.gz
│   ├── 1400757309c6c6b4648213bf4bc23ffd8c6bb057.nq.gz
│   ├── 14d650c20b1d63e729b71214287dbfa044c2125d.nq.gz
│   ├── 18b28256af3a92aca6cc59b3114ced1c93d7ed17.nq.gz
│   ├── 2001f3e2567cd1d7790d2f45fc7fc67e96cdc49d.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 2c42946a120a09dcfa99dbc4e6a19e810a4168db.nq.gz
│   ├── 3449fd99f379dac6918709e4bbdff0881f50c5ac.nq.gz
│   ├── 3461a2bd2df9173430e357eae1b1736a144937c7.nq.gz
│   ├── 3484eec8f977c6497f6dc77dab89dcb7d31fbcf7.nq.gz
│   ├── 37b9385b55b761d0ed1a5b45f0f4bd048f59cc50.nq.gz
│   ├── 442ccda50d8215eee470bf5cbff435955347544c.nq.gz
│   ├── 4adeaf7f937b4b5db8adb199cd10f9cb42174cec.nq.gz
│   ├── 56255a6292f125eff97a9c3a17163abf08253af4.nq.gz
│   ├── 6042159d7605f6be2b283951ad10489ff896af69.nq.gz
│   ├── 63cb40579950cd506d39592ca070d05637a557f4.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 7a15f1c395ea81c2d83167fbd47f38d2730d6893.nq.gz
│   ├── 7aff14565ff49c4c938b841d5ba937deba93016b.nq.gz
│   ├── 86e24b7e5f0480beeecf9d3928065c6288f4b0c4.nq.gz
│   ├── 9691438755057e29301be482f36975f1f774224d.nq.gz
│   ├── a3d5e1af4c3024cf56348f45fa6e8b8b8530131e.nq.gz
│   ├── b0fbdf0e313d3fd3138974eabdc3c6f91a78ae25.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── c07defcc7b6d099e17e7776fe28e7e6ae393608b.nq.gz
│   ├── c1abf5ce880a2cf740a44abc033326098d8524f3.nq.gz
│   ├── c51b21f94ad40933b6a7ae315ac80dd9853b347d.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── cf8f14a20d31ebe1b002f73515a642fd90859e96.nq.gz
│   ├── d754975309270c66254a9808e2a3fde47cf35d1f.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── e230702f148a152448c9b8de032c5be2ee93ad90.nq.gz
│   ├── e46f64e04b0fd5417f8ea1b5435f9740b8c74dbd.nq.gz
│   ├── ee3ab8497e7503c6b09f026ab84a3f1fca74163a.nq.gz
│   ├── f1d8321d6a5f3c033f035b31f2b1bf4594f12838.nq.gz
│   ├── f5da2156afc1ca8c4aeb16ae33a96a36e9d7d0bc.nq.gz
│   ├── f67bec815653a41d9d6bb7cda75b00f728640fe0.nq.gz
│   ├── f9fc1fc0364b50da74fd3b547c811c730acaee58.nq.gz
│   └── fa05d801a9fc8aa287fb6f6f40e9cdc78702cf0a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 54951cad65f717792b2c4dd43ca78628edebf144.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[PennyLaneAI/pennylane-aqt](https://github.com/PennyLaneAI/pennylane-aqt)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
