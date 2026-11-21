# Repolex Knowledge Graph of tokio-rs/valuable

RDF knowledge graph data for [tokio-rs/valuable](https://github.com/tokio-rs/valuable), parsed by [repolex](https://repolex.ai).

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
rlex download tokio-rs/valuable
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9efc29b6e58cef28f6566a47aa7e142a55fead77
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 9efc29b6e58cef28f6566a47aa7e142a55fead77.nq.gz
│   └── repolex
│       └── 9efc29b6e58cef28f6566a47aa7e142a55fead77
│           └── chunk-001.nq.gz
├── blob
│   ├── 02f8354b1d6bc6fb0e6e24c396eed428b17f5917.nq.gz
│   ├── 091246b52b25e1816c40ea16d4b4deebc65af410.nq.gz
│   ├── 0ac84ec8bc8236c01e47387e1a8d0c015ab88080.nq.gz
│   ├── 1b41acdd9f07bbf1aa62496d0127dc1eaf415f27.nq.gz
│   ├── 255ee5a73d7ef14877c0e3ee100a74b7b38b8d13.nq.gz
│   ├── 2b4a88d873e03924bed90eb91523afadec6b910c.nq.gz
│   ├── 2d41c1460675139d307354e6386fb627e4db04db.nq.gz
│   ├── 3161f19f0dafca6dd6ce542f16fb684cc71c4711.nq.gz
│   ├── 35c381f5f405b88a59937aea9e915b12169d2897.nq.gz
│   ├── 38013cedaebbfa589103ed3245f423f6fcca387c.nq.gz
│   ├── 3c15e8ab8a29f99c1c54e636031870571b000669.nq.gz
│   ├── 3d00cd754e57fb0c3e394ed53b4bbd616c41de86.nq.gz
│   ├── 45a0e0b93f308db9882214ca13f955bdc331866a.nq.gz
│   ├── 4ca822a5cb54142a14070f5be388e60497781615.nq.gz
│   ├── 4e005cb5bf523bf489003f7f7e5ffe8634704291.nq.gz
│   ├── 4e731039ae20bfc78e2834aeed9640fda6cdb6a6.nq.gz
│   ├── 4f436522a243d8449ff1974fa87bcbae7ce4a0fa.nq.gz
│   ├── 5a8fe67e6e9ef892d1661f9585f7f9ee3341b4d6.nq.gz
│   ├── 5fee0ef1b7cadc60dd400969a3a07158610eb8c4.nq.gz
│   ├── 60c91c180d66ce08d1e19fd08f04d058f606f9a9.nq.gz
│   ├── 611a7e58b5f96c8efe373ae72f25d6a2a56fa9f2.nq.gz
│   ├── 66d54cd4bbac32d345987e990f3ab57eae9b0c7c.nq.gz
│   ├── 6a16e3f0cd052d860b50098b9eda9fc6531f5ca7.nq.gz
│   ├── 6b5393000ddd4658357799fffe21b9c8e36d24ca.nq.gz
│   ├── 704d989474f699bb89c7e6fb3c88661e0b4b6b35.nq.gz
│   ├── 7515a7820d5c7f1c34e3532cfb23e6c25a0ecf48.nq.gz
│   ├── 77a8645960a30b2027b8b13999c2dc7a269bed10.nq.gz
│   ├── 7c3d173f0f5ace60ecf5e0c0c87cac8f22da3e53.nq.gz
│   ├── 7da12571130bba4fe1fac5caa301113f5715a662.nq.gz
│   ├── 7fe879d50fbedd3914e92875175e9735d0e15037.nq.gz
│   ├── 838ecd5908167174b0918d0f1f0013bddbf972d0.nq.gz
│   ├── 8a9f056657dc4d7ad510578a1807f9072a702105.nq.gz
│   ├── 8c7169ff255477e36efb2c91cdc76346998d0940.nq.gz
│   ├── 9182c518f6bdc2019b7a0de9c0e8e5b2a97568d4.nq.gz
│   ├── 92cffaf7a636ebcb2da3762dea660b5410d4b44a.nq.gz
│   ├── 93c37acb38ae2085704f8f60d1fca6c016ba8d4a.nq.gz
│   ├── 96ef6c0b944e24fc22f51f18136cd62ffd5b0b8f.nq.gz
│   ├── 996881be2062189cf5e872f1ef2c7009fd4271db.nq.gz
│   ├── a26ad5b0a552b906efe5aef18107dd332ef19a1b.nq.gz
│   ├── a5d83a0a964d9923b4fa2381d65a2c42578a2139.nq.gz
│   ├── a6ada6e6796631b7843bccf10d08f0d5507d9e07.nq.gz
│   ├── b67aaf3a71e78bb0a95b625ecaf229f421365cd1.nq.gz
│   ├── b6998d37ac6128ef33651ea11c4ff063b3288ff1.nq.gz
│   ├── b79317f9c37e8645844f7939df7c69842b9d76ff.nq.gz
│   ├── c97856d39af96713e36eda1f4c8169260b390a3a.nq.gz
│   ├── d0ada87362b0b6ee9d53cefeba8e371f7c5d68af.nq.gz
│   ├── d21a1718acfffb749a43503278ca673c988189ad.nq.gz
│   ├── d6fe7f89f009b47b7855c6ad666d8081a7d57c32.nq.gz
│   ├── e3a027014d3ef0e9c88562109b84076abb90b951.nq.gz
│   ├── e8fa5ddcf026e00ac7f40534b695617af4b8c3ac.nq.gz
│   ├── f14dfeb5e9f0056af81e8fdf478e097a41a3daf0.nq.gz
│   ├── f14ea7703924b795fbca6f42b74561af77114671.nq.gz
│   ├── f91a04cadba4c4ebb07335076ef5bb76651c2775.nq.gz
│   └── faa00f420e3347bad31595f79701f77a69f75ed1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 9efc29b6e58cef28f6566a47aa7e142a55fead77.nq.gz
├── filetree
│   └── 9efc29b6e58cef28f6566a47aa7e142a55fead77.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 64 files
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

[tokio-rs/valuable](https://github.com/tokio-rs/valuable)

---
*Parsed on 2026-11-21 by [repolex](https://repolex.ai)*
