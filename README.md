# Repolex Knowledge Graph of Cognition-Labs/synapse-bridge

RDF knowledge graph data for [Cognition-Labs/synapse-bridge](https://github.com/Cognition-Labs/synapse-bridge), parsed by [repolex](https://repolex.ai).

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
rlex download Cognition-Labs/synapse-bridge
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a4f41856ed59945e1a71122a3919cad38e49660f
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a4f41856ed59945e1a71122a3919cad38e49660f.nq.gz
│   └── repolex
│       └── a4f41856ed59945e1a71122a3919cad38e49660f
│           └── chunk-001.nq.gz
├── blob
│   ├── 029bf11c1d2dee8e85d38db3825bdc89967bc556.nq.gz
│   ├── 0d5b035e6b64e528a0d77884433730689db91c37.nq.gz
│   ├── 197ef04f54fd9f6fe5643cc19913dce744856b96.nq.gz
│   ├── 281d1b2aceca7a84a0a1b109399765050e60926d.nq.gz
│   ├── 2b66dafb5cfec6d2409b3ff0a6f8970cf2a48718.nq.gz
│   ├── 2b831535752b68dcd3f17dda65c9934ce064ba55.nq.gz
│   ├── 2c2f69c1e8b13622dedfb669b5f7597eb201519c.nq.gz
│   ├── 30e803757b8e2f9722bc65b2347727f2f7a646fa.nq.gz
│   ├── 4b072fa20ba2523584973b8885d977520e60e8d7.nq.gz
│   ├── 515590bfe63f602e324d33d4d7e7e81b88e8a132.nq.gz
│   ├── 5326e2b0b0ac6fb6615c26b7f91a23148b7aa590.nq.gz
│   ├── 5539400d960b46a104b2e3a3bbd92fd74dd14927.nq.gz
│   ├── 5cec962221ef36823ba201067f399ab2d83a6c1b.nq.gz
│   ├── 604237f4b61a4ef74238b0f1156e9e5b7de1b005.nq.gz
│   ├── 65c51243309aa8da37e8365b167f73e11572feda.nq.gz
│   ├── 6c71ee4c59fe69d0cb1ffd49488be7f646fa1594.nq.gz
│   ├── 6cbfffbd92b354c2a5e6555877116326ca13ffa5.nq.gz
│   ├── 6ece64b29c92eb05d060c852f302fbb92e75a397.nq.gz
│   ├── 7045b97c1dd8ea04bea3856d0c0b85b7b71783c6.nq.gz
│   ├── 709d45e0910d85908b23987b4a6d177eb2234965.nq.gz
│   ├── 713e1b028260f9c43d3eecd5e650c38ae6c38407.nq.gz
│   ├── 722c5ead98addb70d150a535dd03d059760a6c4b.nq.gz
│   ├── 743b1d9a69cb8762e8e95c39127e6ef13e28f711.nq.gz
│   ├── 7dca98e66735e63efb60c120915d147ad1f84d4d.nq.gz
│   ├── 845287af02fedeb85bfb02d48151d12626c3077c.nq.gz
│   ├── 84f2e324a98a2ae836ed66398081681a56ca3899.nq.gz
│   ├── 8a57dede77060aa159836686f7e8eff9fb0f5899.nq.gz
│   ├── 8c95c1e717064fc98c4346805e022344facfca68.nq.gz
│   ├── 94f480de94e1d767531580401cbf13844868e82b.nq.gz
│   ├── 9b4fa441ac228c853f3dd79e435dc67b9e9c3ff3.nq.gz
│   ├── 9f5571134afae954145c9d42e8e5ab34f5cdb073.nq.gz
│   ├── ac02e62b371423d499ce12b788eec9993649f145.nq.gz
│   ├── ae6b862be6869d4907877758f2464bdea696fbeb.nq.gz
│   ├── b870252622d3b3206fcef779a672b361c85a6318.nq.gz
│   ├── be8f47d17e5c3b94187370ab46b0d37b56e4ddf0.nq.gz
│   ├── c0e457b94d7ec9a6267c6b1c027f6a6bbbf48f94.nq.gz
│   ├── c1a766eec145e65354ba53a3f9f82cb7a7353efd.nq.gz
│   ├── d26c77ffa417ede07eec2bab8aa91421ec38c896.nq.gz
│   ├── dbbe3558157f5861bff35dcb37b328b679b0ccfd.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── ef4aa68cc85d39bec863b82d6f2233e1f1b59bed.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a4f41856ed59945e1a71122a3919cad38e49660f.nq.gz
├── filetree
│   └── a4f41856ed59945e1a71122a3919cad38e49660f.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[Cognition-Labs/synapse-bridge](https://github.com/Cognition-Labs/synapse-bridge)

---
*Parsed on 2026-09-30 by [repolex](https://repolex.ai)*
