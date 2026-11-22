# Repolex Knowledge Graph of dtolnay/ref-cast

RDF knowledge graph data for [dtolnay/ref-cast](https://github.com/dtolnay/ref-cast), parsed by [repolex](https://repolex.ai).

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
rlex download dtolnay/ref-cast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8cea9d561e44ec4ebaf4de1ba64bedfdf2944138
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8cea9d561e44ec4ebaf4de1ba64bedfdf2944138.nq.gz
│   └── repolex
│       └── 8cea9d561e44ec4ebaf4de1ba64bedfdf2944138
│           └── chunk-001.nq.gz
├── blob
│   ├── 0f837b4b54f988495c418d9a6e433824491e7fcc.nq.gz
│   ├── 116b197c6bb9706d610a6e5a257d71742d87d78f.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 278b5d5f8454fcd93597ffef2980cfc2f83845de.nq.gz
│   ├── 292f282cf146c268a45cd4ea17b0b9dc6d66b0fe.nq.gz
│   ├── 3161d334a6e3857b2698e26968f96e7f08b16eb2.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 3b4ff4ae775277e534aaad58a53bf945fae634f4.nq.gz
│   ├── 3fcc2d2ecbc9e1ca8c94fa1585b1dec8ea00f613.nq.gz
│   ├── 4676d50d4950aa4ecb6c11144d8dc9448e1047cc.nq.gz
│   ├── 4c222a072cd9d4ea39dd2d020f97c30e15f003cc.nq.gz
│   ├── 5188ba109c12e888352075d773c4e9b1250ee9e4.nq.gz
│   ├── 55f91f8c322595375f528a19a8a7798cdb98a655.nq.gz
│   ├── 589bf5cf0a9c3e360a95068bc4a84deae17e5baa.nq.gz
│   ├── 5da54d7955d605b6bb92218a66dcf6ada2759e4a.nq.gz
│   ├── 64e388a326e2cb562a2c52e78213f8391ceca332.nq.gz
│   ├── 65398da0ae1df8a58452fcb8f608de4d8effc141.nq.gz
│   ├── 6e9459f3cc97a32448e25290f8eb5b1f077dd196.nq.gz
│   ├── 732b31c5b49fe3f106b968d95c089e82911743b0.nq.gz
│   ├── 7368b3d0017c1c95748c2ec35bbc73fef8c67c55.nq.gz
│   ├── 7368d56d095320d2bb60ad1514404859d52d52c7.nq.gz
│   ├── 73d9bd69958b1e40c1a0f7211f5f40d68422c9bd.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 76725bcf776c30fdba1fba8a5ef2beaf605561e5.nq.gz
│   ├── 7de06292f349b6d68f79bd8499a793ab80a37ba9.nq.gz
│   ├── 83783c39509b4e8815c419ad153e73925d5e3877.nq.gz
│   ├── 89cef9de87f1ca699822338eb4f2e13e476aa289.nq.gz
│   ├── 8b1cb543d6dae24a202556e5fdf06a5899939dff.nq.gz
│   ├── 8f124bef02e66c5506e82a36721b8214eb771b6a.nq.gz
│   ├── 915044a85f64f1c06f614343a0b6710f697eed30.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 9983cdc9344392d14b58208470e4f7438f57ab23.nq.gz
│   ├── a23eff2bf2d3d44d01fdf65f2b1455770d343e2f.nq.gz
│   ├── ae5f2c15205d87ce714dac31aac8d23d7877dede.nq.gz
│   ├── b3e6d0d7b7a0bdbd424e727786958c526e4c69d9.nq.gz
│   ├── c5ec85ae208cd5ab6ed8a48ae2f5cf3479f48645.nq.gz
│   ├── dc61f2dfa5170277b489e1a2ca4803b193d14fef.nq.gz
│   ├── df294f5423dd95aa7200174022f39c62c301472d.nq.gz
│   ├── e22076a6d8c049b65533e843a9ffdd6090515cd6.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── ee3777b438b1890d93b4e46a329cd27f721d5ae6.nq.gz
│   ├── f5e8d4e9badcb6e68bece345f8e1cf302a49c72f.nq.gz
│   ├── f74e0dc287bb1130decb301d53a779835f5b7d5e.nq.gz
│   └── fd8cc5252a9fd16e3b5f9e5d3ce98973e5f1fe92.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 8cea9d561e44ec4ebaf4de1ba64bedfdf2944138.nq.gz
├── filetree
│   └── 8cea9d561e44ec4ebaf4de1ba64bedfdf2944138.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 56 files
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

[dtolnay/ref-cast](https://github.com/dtolnay/ref-cast)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
