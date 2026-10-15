# Repolex Knowledge Graph of holoviz/colorcet

RDF knowledge graph data for [holoviz/colorcet](https://github.com/holoviz/colorcet), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/colorcet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 076eb84bf86c222cdac830073990f1a08c99778b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 076eb84bf86c222cdac830073990f1a08c99778b
│           └── chunk-001.nq.gz
├── blob
│   ├── 007227f765a71ca070bd63b599b1d6427de0ea8f.nq.gz
│   ├── 0ec3ab41b40637be959195f452a0e8d45a9d6b6d.nq.gz
│   ├── 0f754f821f48bb7413fc1b9cf4983466ae57d59f.nq.gz
│   ├── 1342f390b07939987afa6a01b022a412c5d362e9.nq.gz
│   ├── 1420c27e0371953ed75669a2263507abbdde6dbb.nq.gz
│   ├── 18a4ebe01cd7c78628c30de5b66d3d180a11e970.nq.gz
│   ├── 19a23ab68525451267beebf0139f51922b0334d5.nq.gz
│   ├── 1e32099be382d2274b738861fcb55198d45b76d9.nq.gz
│   ├── 1f0aeabb95648ef1348ae8222d67cac43ab657a9.nq.gz
│   ├── 1fe89ef3e6ec310a9b88e94ee02a746ce78ade43.nq.gz
│   ├── 2a174526b1bb6858619672b18db152d9993863ad.nq.gz
│   ├── 2cec4ccd22bf0ee1415db5b3543e3019be7b96ac.nq.gz
│   ├── 2f5cc1211c41ad5af99c3a0edcc0411f64fd13cd.nq.gz
│   ├── 336701a1e0dd6ef2ac1f307c0cad45fafc09ec0c.nq.gz
│   ├── 345f731f6e14aa02c1f05d1606b5a52f340059f9.nq.gz
│   ├── 36790535ceb416da90d11bbdd65e5258d3b1951f.nq.gz
│   ├── 3c4e8b15c665694cb6bfd79bbeb721d750ed14a6.nq.gz
│   ├── 42f632aef1128239e9c15f13e3817f01a442b4fa.nq.gz
│   ├── 42fe921b4dfdbc202a77e0dafe6d719eb5cc3748.nq.gz
│   ├── 4744d3b9e05c53a4ba4da16c04b4715e2990112d.nq.gz
│   ├── 478e0be2fc0b8a1633b3290205b73653cd44900b.nq.gz
│   ├── 4920305065608ec33f6147e368af1428ac4fa15c.nq.gz
│   ├── 4cddf716edb38bc0f0fa50e63fa04408231986fd.nq.gz
│   ├── 4f9ccb6ac95860f88ab2b2154185c22e0dcad22f.nq.gz
│   ├── 53d6df7b38351baddef43daf0c7bfe088f043149.nq.gz
│   ├── 64d1b9cb935af8e6f7a36da44f832b602bbbc9c6.nq.gz
│   ├── 748a42f28fbb885600050e28009f5989235c4803.nq.gz
│   ├── 799a4eedde4041d2f5e62c03249295d84f559b4d.nq.gz
│   ├── 79d997495e09f6dc2b4f135ac09e17137ebdf93f.nq.gz
│   ├── 7aeb4b81fd0061796682974a357b3544491b5f17.nq.gz
│   ├── 7cfbf9f40d691f00d95c679eff4cc1bc865b4e92.nq.gz
│   ├── 7f63b51366199bef0193152e585a8635048caad6.nq.gz
│   ├── 812e130a1733d48ce0f6e8af596f26be0527bdef.nq.gz
│   ├── 8a8cb07932849b9ca38ed14218a3d21efccf7254.nq.gz
│   ├── 8dd1d7a5dbf615a1b9665203cbd7b7d4a5e23e9a.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 9740380df436ee5c6e1e3373d6bb4ed255e646bc.nq.gz
│   ├── 9b04d61c3929b1ba02b053b9123b31bcef059d5b.nq.gz
│   ├── a216e1eb2593dd77a11840dd11454ce9a2098361.nq.gz
│   ├── b0c38365b771e0e906c9e73a9b9451137b176727.nq.gz
│   ├── b2f0d295fef277a081f2ddebb7171b173d33a74a.nq.gz
│   ├── b321a76e2af67bb6002ff7410c01aaf5fa69093e.nq.gz
│   ├── b37d62a14ea7ea1588cb5b4ae513e339c8d30723.nq.gz
│   ├── b63533f691d0209154dd702547a684abb3f2c55c.nq.gz
│   ├── bec773c996df7013b3108e14c0fbcef6ba91fcf9.nq.gz
│   ├── c111ae5a9118baa913616e68d3fbfacf86a1555c.nq.gz
│   ├── c67f55f7afea8508d973215c9d80aeb19bd96c31.nq.gz
│   ├── c8738f7955a5883a5c61120a3c38125415220091.nq.gz
│   ├── cae0371ba789aea56759639ec1163159a7f9c96a.nq.gz
│   ├── cae4c144acdc9fde9bebe38279bcb6082588ad28.nq.gz
│   ├── d4244f93a2a0966ae4e8342420cc2c0ef0755ebd.nq.gz
│   ├── db031512910cc57b26cbd74168bcbc450b34d47a.nq.gz
│   ├── db21f9cf4524bc0878f577de689188a3080a074c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78d23f8d4c96ff0ed9abeba1f09b18a859def3e.nq.gz
│   ├── e8f60443888a81c068cedd2a5d6da3d0108e3895.nq.gz
│   ├── e9a1ee1df18008babb3e74c8a7a56f53e392dcd9.nq.gz
│   ├── ec6d16e91a0378be6a1eef8ad9dc00c60344f7e7.nq.gz
│   ├── f2a34149394d971e0092d1275233424607954f7d.nq.gz
│   ├── f57af477d70c0f91ae290b780e753592c1316ee1.nq.gz
│   ├── fb16dd196225a2e3c7f3de9ecaca6053dfd08ade.nq.gz
│   ├── fdf59df094b8927980454c80de473d1c82542e58.nq.gz
│   ├── fe38ffcb04e23b8421272aa7a48071cbcfe97968.nq.gz
│   └── ff234092a51794b92eb936b0cf2d4f5d0672c95c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 076eb84bf86c222cdac830073990f1a08c99778b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[holoviz/colorcet](https://github.com/holoviz/colorcet)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
