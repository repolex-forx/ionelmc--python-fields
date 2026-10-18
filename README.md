# Repolex Knowledge Graph of ionelmc/python-fields

RDF knowledge graph data for [ionelmc/python-fields](https://github.com/ionelmc/python-fields), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/python-fields
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cb473d126b926621c4423ecf59387da9f0f26563
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cb473d126b926621c4423ecf59387da9f0f26563
│           └── chunk-001.nq.gz
├── blob
│   ├── 0160103b8766163458075561874008235bf73793.nq.gz
│   ├── 023e9440290f7acb88945db49db403eb72356672.nq.gz
│   ├── 14e41affbdeca0dc41ad2e4e20123167f2420ac0.nq.gz
│   ├── 17cc9e501af58a2daa46273eb03b3c7da387f39c.nq.gz
│   ├── 1a1c1ca7cab47a4f75b4434559dcf536efa3894a.nq.gz
│   ├── 1dd5342070a683dab0f891a83dc68978cee86f97.nq.gz
│   ├── 2261e19dd1d33bfed60c60c35f96330ad4346254.nq.gz
│   ├── 260e25a767b9c30f5819cba0579172a850fa6f42.nq.gz
│   ├── 2d1d81370bbe40438262f2fe6b463d7caab3380e.nq.gz
│   ├── 2eb77232d6c08a527dc17a544c8f2a2890a80217.nq.gz
│   ├── 31cc9cee0379b1538e2110bcb5093b9cb64dc84a.nq.gz
│   ├── 47e7ad2951f3550abbb5355d477592dd8b6c5283.nq.gz
│   ├── 4af757e8915d287cee1a0f7694c1b8b4d9eaf3ec.nq.gz
│   ├── 51ed2fadc648f1a1a0d424afeede7c30810886b7.nq.gz
│   ├── 564df0df77fa481fee58321025a9b3dd8fa2b0e1.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 586c7367de1cff5d362be309c0a4014b0905edb1.nq.gz
│   ├── 59ff5c04f2f19a7eb90b658a1e6bceb7dcbb90c1.nq.gz
│   ├── 5cf8b44ff8c960a81aa0b02ee35bac67935781e8.nq.gz
│   ├── 5fb2fa258e9a952899c5705103259a9ef800e8b3.nq.gz
│   ├── 62bc14e2532cdd290a44e15ce0da98ede6f90e39.nq.gz
│   ├── 64a973ee3e7b982b33aec7f290589f89b7a6ef4b.nq.gz
│   ├── 68e639ff5d83c7cd32ee3b3f2c0e0186b00448ba.nq.gz
│   ├── 6d66a36ad5a1a0b95893af8afad4137ec04ddf41.nq.gz
│   ├── 6e974cba907c46b68b6a10ec807b9a5283471a85.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 81abe92c693af3e72279946435b3554a5f3ab807.nq.gz
│   ├── 83a43fdbd87fb9e83cd486c18168dfd391f85222.nq.gz
│   ├── 8575fa9e652951d23478879d5b669ab988d98c00.nq.gz
│   ├── 95c48ee177a8be91d8a789906f917de64a62b831.nq.gz
│   ├── a4abc50ab2dc087531e435d7ad789a95382b5a60.nq.gz
│   ├── ad842d51d97d389707466a2f855e895fa0b9f6d6.nq.gz
│   ├── cf699f9ee7c5abf56e4617052c2398e05b0ed37c.nq.gz
│   ├── d01607af0a29bbccb70ed3e82bdfdce51fd6e02e.nq.gz
│   ├── d7869ce6c2a584a61354560cb7ed422c44eae953.nq.gz
│   ├── d7f5177e6b3f1d0d320822585d75b051cd28ffde.nq.gz
│   ├── e11c7f0e7bf25a6d8a398974a6882f3ce1bb84ce.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e3bf2314dee7a95ea3f0ea0c0d3896d60f705f94.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── ef5e94b5faa1c3e14467d211da716d8f95dc65d3.nq.gz
│   ├── f5fd8a80b52041b7c037d656bf33d42b2578193d.nq.gz
│   └── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cb473d126b926621c4423ecf59387da9f0f26563.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[ionelmc/python-fields](https://github.com/ionelmc/python-fields)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
