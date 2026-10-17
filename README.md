# Repolex Knowledge Graph of Nixtla/hierarchicalforecast

RDF knowledge graph data for [Nixtla/hierarchicalforecast](https://github.com/Nixtla/hierarchicalforecast), parsed by [repolex](https://repolex.ai).

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
rlex download Nixtla/hierarchicalforecast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56cc4fac0c5c7b4ff33884d4a8a929f3cd8f03ec
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 56cc4fac0c5c7b4ff33884d4a8a929f3cd8f03ec
│           └── chunk-001.nq.gz
├── blob
│   ├── 0739d51c1fba44a849d03e1d0be624b448280f52.nq.gz
│   ├── 075b2542afb820ca0c990f02a196dfbb35c41a3a.nq.gz
│   ├── 09f75dda7a96237ad1ad9d8c918c71a19fe90e44.nq.gz
│   ├── 0b60b65fa4b218c8df067e0fdfa52dc45d703e3c.nq.gz
│   ├── 0ceadef05c4c4cb34d75da2143ce5a882e314bda.nq.gz
│   ├── 0d0ea32157e64fb73390884bbb418a26092d6b3e.nq.gz
│   ├── 0e9c5ee2c885ad6326ce3d62a6e1ba22be181a7d.nq.gz
│   ├── 1015b687b0515fcdefc78951ea779eb0392d6b9a.nq.gz
│   ├── 1292a51804271cdca0498328f580b3e37f3ebc68.nq.gz
│   ├── 1504f7660274a5370cd7bf13866af44cf2089899.nq.gz
│   ├── 15f437d0043f609a840f77fe6fae3a8f07e9824e.nq.gz
│   ├── 18e0f2e8b7909e2635090066cb9bd430efa4cbdf.nq.gz
│   ├── 1be4525dd987e8ca49a106660f2d4919db17e043.nq.gz
│   ├── 234bfea5521cec8513ca88c4eff7564ba44518bc.nq.gz
│   ├── 28c016fd86ba16170ef8c5f1c0f624dbf7e55c38.nq.gz
│   ├── 29ec5a7707d4e90a7f0008bebd8d9a98037c6c37.nq.gz
│   ├── 2b8eeafe1a313530a37c4917f3539085c52a70a1.nq.gz
│   ├── 2de8562a22abecaa77720c0e41b561e3eba55fdf.nq.gz
│   ├── 331cfa2cdd5321b1d48438d0e99c7371213e42ea.nq.gz
│   ├── 35e6dff5b282fb03927d7022197380fce5554fbd.nq.gz
│   ├── 36539083511be65a1b4d11ea75b77ad4101a7e19.nq.gz
│   ├── 36887b83ad93dd8c3bd0b36f5a7ce83d18cd744f.nq.gz
│   ├── 37f1c567ae0d40d00ab2c67fdf1e13325283aca8.nq.gz
│   ├── 39a05b2eb39036a632724030ef7914704610f81c.nq.gz
│   ├── 3a61fca37e20a55dcb2b6a4b7d83b85bedbb905c.nq.gz
│   ├── 3b9ae0d3055dbba9b04bfae60269bd56284647a3.nq.gz
│   ├── 3c1fb35a9498d7f3b1b253a2658bb625940b0854.nq.gz
│   ├── 3ebb5923e467ab3fa0c16cdbf00dd57220a541cb.nq.gz
│   ├── 4142a0bbde38d8801c80e73a8fa18df0baffb465.nq.gz
│   ├── 4646982abaec9ab4d89ab4b3a2623c65a0dd68d7.nq.gz
│   ├── 4a9684db576e0e8f920ea02b6dcd45e6603a9776.nq.gz
│   ├── 4af814966c4f6e0989eaf6cca498ee1682686310.nq.gz
│   ├── 4b22576c4543b12fd6cb68c1b4a437e013e29817.nq.gz
│   ├── 4ceadfa9f95d85a30b4be133ec433632c7569399.nq.gz
│   ├── 50c43df3a56398240ad2d45aa5c39d83bcf5fc4c.nq.gz
│   ├── 511ebf73e30f36f738f8df09a9b1327371906e1f.nq.gz
│   ├── 5198456823476da10cf98fb69cda3a242593a237.nq.gz
│   ├── 522c0731f2cfa22c498a3a6ed383bef650d3deb9.nq.gz
│   ├── 54536ab911d66206fe9d045277a81e013481edea.nq.gz
│   ├── 549fad86f2b079871910fb34962154171ad6220e.nq.gz
│   ├── 583c398f70f90be6844a82d5cff4c877a3e629d4.nq.gz
│   ├── 584c20870bff28d4a9fad326ebf3c72f63065199.nq.gz
│   ├── 586b58d6583eddb2c8d59559c46ed0a3435e688b.nq.gz
│   ├── 5a1b00456f9b0349bc9a046d7d517aa858da1770.nq.gz
│   ├── 5ad5919935255398beff165d70912b38156cd3ea.nq.gz
│   ├── 63bb11af09efe51736224a7301ea560adbc837c4.nq.gz
│   ├── 650befcc5c611c81288370205315c73ddf197e6f.nq.gz
│   ├── 66d6aeab6b00a2ac1b36996544a7c79272de4251.nq.gz
│   ├── 6dc8486cc22a1c93c8e320632030fb0ae01a3771.nq.gz
│   ├── 7004b70f16d0ff51abe8c6306bbfa4834a4cfb23.nq.gz
│   ├── 70b019a849a516f3c77939f8fad6e2234812081c.nq.gz
│   ├── 71415a60d079eaedc27e13019a4b4ba87a6a0bef.nq.gz
│   ├── 72f903e68b0ad30b6b1f7a494f8dddd9d6a915a1.nq.gz
│   ├── 731432fd7af39fdcb1e56268d20e01a71fec4a76.nq.gz
│   ├── 7879d1258d78f2f4da5258d5d82bff54176fe064.nq.gz
│   ├── 7924815719113995e51d8b4f0042a39e78e420d0.nq.gz
│   ├── 7e3f6da3a6bf2413b70359e9b903625af399f234.nq.gz
│   ├── 7f4a2c3e20b262ab58f98616d003e38721bb72ab.nq.gz
│   ├── 7f81f0fdc5c307da7c74ed133e049510c988e434.nq.gz
│   ├── 808bfe2f0b4f032ac51b606bb353d0abb9e9ff6f.nq.gz
│   ├── 81341ce6d8baedc317c2b45a73603d31844391f8.nq.gz
│   ├── 821814eebdb9a516f210edf71365b348d9d8f77a.nq.gz
│   ├── 84006aee3aedb5f4a901aee65b19f6c71e80692f.nq.gz
│   ├── 85a1a9fce254bf7897543d5a3895c6ff17b8cd9b.nq.gz
│   ├── 85efcb6af9317b64faac51da846d20146a7231a5.nq.gz
│   ├── 8fca33742ba00dbe5cca0b3b67e7749ec99f339b.nq.gz
│   ├── 903b155ac59dc06516cd18862322075f6436dd2c.nq.gz
│   ├── 90db8c906c6f6321f2822bc5e7336361e4b83b42.nq.gz
│   ├── 917c639d8b0915d6328f0e5e3995298e580f828b.nq.gz
│   ├── 93f8a003e03dac28de98a68728fcae42160d3a0b.nq.gz
│   ├── 942dbc30f89bf9aa7e32496c37a9643a3aa59f46.nq.gz
│   ├── 9b92adbe7d1d48309e15c6911d5d72ab7dd59c4f.nq.gz
│   ├── 9f73cd11434b26c4beacda8cf516accb3386ee92.nq.gz
│   ├── a5c44e911dc82cf195ce55bc47ba4831cae3adf8.nq.gz
│   ├── a740a6c84583ef18d667baf660b1429658f8211f.nq.gz
│   ├── a77b1340dbe1ad7da0242423d220210fb4f01ddf.nq.gz
│   ├── a9e9f6f03d5d3ad3e0ed8f583feec9136a650a17.nq.gz
│   ├── aa4fe8f857b221afbba11839315399fd00bd56a2.nq.gz
│   ├── af6222386e3e36178191f2da008e01a90fbf4dec.nq.gz
│   ├── b386cc110b4561a6ee1824cddfd34844c03669ab.nq.gz
│   ├── b4e4b8f141fcb7c63422b1629c016d0d5b8ca953.nq.gz
│   ├── bbb99b5497a62503432e3c770f9fd6290b304ed6.nq.gz
│   ├── bd5dc86df858d051923f9d2356b3222c7fc9dd0c.nq.gz
│   ├── c0accc33a9669ccc5bd13e8cf917214be51d1680.nq.gz
│   ├── c3a737fb3f0276d8d88e6da17b5ffeb6c230b8a9.nq.gz
│   ├── c62dc5ccc2c999af76f522d7a55550d25f37782e.nq.gz
│   ├── c677c3c6efcfc17957c8b9c973fc0cf69f2abe65.nq.gz
│   ├── c77baac5feee065cc9055ae67635f077deff5ce6.nq.gz
│   ├── c9ab762f4eeb5b3161f467d31e9854911ec3bc4a.nq.gz
│   ├── c9d3b7fa231eab450b827033cd2d60f074d30d0d.nq.gz
│   ├── c9f8431b78c3396c35ab735a2b2aa83218b1a8e4.nq.gz
│   ├── cb69d36654e15387271ac101f80d9a48e2704320.nq.gz
│   ├── cc0a82dab1a213ab21259c029e5bd7931d9c9854.nq.gz
│   ├── cce28b9a3b255b3536bc0f4893df09cffc10612e.nq.gz
│   ├── cf017ab538d62d4d0bee9b8773b82bb44904fec4.nq.gz
│   ├── cf29e7c6ca2f9a73d54ef1d12689985180457a4e.nq.gz
│   ├── d0f9a66ae0790b49f149dc6b55f3bd2fd6556a37.nq.gz
│   ├── d175d5e09aa1f882a976dfa88507d79fb16a50e4.nq.gz
│   ├── d3b13fc0b758e78c4f6c9240ae2eca70a3dd4536.nq.gz
│   ├── d81e836a5fa135194af4c21bd6d3cafc147eb7b0.nq.gz
│   ├── d8471848fff4167187580bfe9e0bd0191cce1d1c.nq.gz
│   ├── e0d79c64ea87e6ba63106c00486662908ba9848b.nq.gz
│   ├── e5f33342874295f851fa548fd3811f054487bfd8.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ebdd9d3e047c10b120006a14f2ee6e6a528893a6.nq.gz
│   ├── f0b828627ce8e292cdd09df9067f267f114d14cd.nq.gz
│   ├── f16a4422eb0801b44d0881763bbfd6507987ff8a.nq.gz
│   ├── f54ec71dd5c5fc49e11abc4b086e799357271506.nq.gz
│   ├── f7408bef7afc5b7d72469f4a76c690e5e6afdb87.nq.gz
│   ├── fbcac4336f799a702c49d3c8308394dd1965ef15.nq.gz
│   ├── fc4f988c9ddfa0d16eb286461f887e98e5f5014b.nq.gz
│   ├── fd4a2262e3454c4c11386e041884f5aba5de01f8.nq.gz
│   ├── ff6a14885948af01f139b4dcb7c9158b1aa9510e.nq.gz
│   └── fffe69a8c052e9f11c7a4fcf57d4b347ef22f183.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 56cc4fac0c5c7b4ff33884d4a8a929f3cd8f03ec.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[Nixtla/hierarchicalforecast](https://github.com/Nixtla/hierarchicalforecast)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
