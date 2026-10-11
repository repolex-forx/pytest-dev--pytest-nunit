# Repolex Knowledge Graph of pytest-dev/pytest-nunit

RDF knowledge graph data for [pytest-dev/pytest-nunit](https://github.com/pytest-dev/pytest-nunit), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-nunit
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3890ee8ed438794e3ab153bd08c8b0c52c4e5dc0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3890ee8ed438794e3ab153bd08c8b0c52c4e5dc0
│           └── chunk-001.nq.gz
├── blob
│   ├── 026496213eb1452da8f5d9f6b51fa04cb8543577.nq.gz
│   ├── 1ade348bb74d5b25edb2813cc00395dfc3e6c53f.nq.gz
│   ├── 1f869b509ce4760bf46f6487fd2813c92d0740e2.nq.gz
│   ├── 222d751306fed1584ca52e504980b0ca44f20e0c.nq.gz
│   ├── 22407e0c698153b7bed46f0fda7c1976658bb490.nq.gz
│   ├── 2737ce2e4520006c08dd45ef3f7a1bb0d311a5f2.nq.gz
│   ├── 2f19e58fe80eebe18574c87be89b57741b75d9c6.nq.gz
│   ├── 2f2e9633122bea8bbfc70df4261e0bcb208f7426.nq.gz
│   ├── 37b2b6e86d175e9e23d5a845a74c94e4c5922a9b.nq.gz
│   ├── 499f7a40c232260fee707d1d999c8873310b9ee3.nq.gz
│   ├── 4b4acae70d84b864714d59bc3901432a0bf3dc56.nq.gz
│   ├── 52f5ad90b04f74aa428c174b4d080ac71a473f00.nq.gz
│   ├── 59ed8c815815bd22a97c06987fe2d5385beda8b6.nq.gz
│   ├── 67fe8c61ada4cc30b0b00647a0a8c8c8ad05faed.nq.gz
│   ├── 692c5853d007abcd9030df7ffac687d878eee57f.nq.gz
│   ├── 694d7d58d440c236ea8ddcfece9eb605427f7be9.nq.gz
│   ├── 6b92e196b1f6d5afdec5a98b603372496e8751b7.nq.gz
│   ├── 72c7ff8c67fe0a898ffbc7f81ab9695dfcac398d.nq.gz
│   ├── 73e517fc9f972a999520cc27e18a6e8cd368b886.nq.gz
│   ├── 77d44f7ab602e6959b07d37dcb08c41acbdb9105.nq.gz
│   ├── 7994f6870f87c9d44542e90924989e08df2d4594.nq.gz
│   ├── 7f3d2a85053e6bd0ecfcb2afca8c95b226ffbf43.nq.gz
│   ├── 82bccdf20f047a5f5fd3dfc9fcd43d9773259041.nq.gz
│   ├── 83dc7fb700344317f06a5cf2df81dba86569fee7.nq.gz
│   ├── 850c2a92e88864efb7a84b2aa8fe179a9e8d9601.nq.gz
│   ├── 9534b018135ed7d5caed6298980c55e8b1d2ec82.nq.gz
│   ├── 9829cd7940ac3cb8085289ce979475e04a81b110.nq.gz
│   ├── 9d1a3c134fc88a15aa3391aa606691ff05bff231.nq.gz
│   ├── 9e604c040e9608e9b3df2d2c39ed6dfab67677d1.nq.gz
│   ├── a9b47778182c423d1bfb609de4c214f82bf088ee.nq.gz
│   ├── ad1de8671c65bb531f89e9eec80eeecdb7a9603c.nq.gz
│   ├── adf5c34eeafd88367666e2b57cf9df7dde5380b0.nq.gz
│   ├── b825cbb707354c1325462ccf6e09333bbee554a8.nq.gz
│   ├── ba345157477981313941ba8d34c146ba83d88481.nq.gz
│   ├── bcb17304a40516dd9ba364e651a526c15c57c46c.nq.gz
│   ├── cac4a23bebc6ceea0f4f17d754f777ef78b42283.nq.gz
│   ├── d0417fb87f1c0dcf5b111d3439c4a80b77bed7b4.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── daaa2013457cdf0099f61de13bdffe6efcc27ced.nq.gz
│   ├── e59d9fc31ec4745a4f860b4761b1ebed6684af13.nq.gz
│   ├── e60a0f7301a40fbeb83ed0c4726f90aca260cbe1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e734b5347c9f62ab53095bff7a068a2c632f0a6c.nq.gz
│   ├── ec870a2e89d2a31b0d7a6ee26a88cfb7800929aa.nq.gz
│   ├── f3fb9d35ba39fa66f5d3b0b20149f9c84dffe273.nq.gz
│   ├── f47b2b928c702b753be65d6efde76fef16e4fe97.nq.gz
│   ├── f4abf0b38cf77fabff2444e17741cb07a65a0bbd.nq.gz
│   └── fe1f816f36186a73fa655e0ebbda54c9ad80c718.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3890ee8ed438794e3ab153bd08c8b0c52c4e5dc0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[pytest-dev/pytest-nunit](https://github.com/pytest-dev/pytest-nunit)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
