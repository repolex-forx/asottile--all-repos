# Repolex Knowledge Graph of asottile/all-repos

RDF knowledge graph data for [asottile/all-repos](https://github.com/asottile/all-repos), parsed by [repolex](https://repolex.ai).

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
rlex download asottile/all-repos
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── cef3a75a19590e8c23fc088a0bfc81ac0350cacf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── cef3a75a19590e8c23fc088a0bfc81ac0350cacf
│           └── chunk-001.nq.gz
├── blob
│   ├── 0833183b4b36f1da722cb77cf1fca83b5cd4dcd5.nq.gz
│   ├── 093637ce6379890f623e6055bb75104b5ab379b4.nq.gz
│   ├── 10ff4322682d880c09c89f57187ede1018d6cdca.nq.gz
│   ├── 11acd1d9f8c751cd473d1b951203fc2a80777413.nq.gz
│   ├── 123ffe5cb378efa5fa4695868df46db36edb1e2a.nq.gz
│   ├── 12d57e288f94ba59dcf096108effaa7032281f34.nq.gz
│   ├── 160fd5fb990409907709718a330d90ab25109ab4.nq.gz
│   ├── 1764925739bf5730ea2a220a9d2cc353136085ad.nq.gz
│   ├── 177e87a7adf682ee8c9a910211a06ec0a3e3f705.nq.gz
│   ├── 180364930a3ef87cf10037986ca4fbe990a07a2b.nq.gz
│   ├── 183840175ab4b9cdb1114bdcc1ae4b2c53dac156.nq.gz
│   ├── 1a7f82376239387f0839dc2812bf00d6ef454abd.nq.gz
│   ├── 1b66bab85f7e468d73b8a184304ee2cb1b963c36.nq.gz
│   ├── 1ddd67f46ad0bf0e876dacbf2bbdb0618c0235a6.nq.gz
│   ├── 1de860f28004584360f97914c1728498363e1fcc.nq.gz
│   ├── 1df56f6a62d27f80a5b13f49d7b7821ca4af5494.nq.gz
│   ├── 2306c8c6000b8d1966df8b848f71b8e4aae0f97b.nq.gz
│   ├── 255e3bc555f869d78eacb98e0cbd27ac654973d3.nq.gz
│   ├── 264a54230f74f01a253599ef5cd7c5dc4a14d919.nq.gz
│   ├── 27ed588da37fb035148b54719d388f2775cde244.nq.gz
│   ├── 2c54d261f41baa2f82dbaa03d4e79a4cfca0ab71.nq.gz
│   ├── 3065a855acac2270543814ca8bb18544ce23c71a.nq.gz
│   ├── 308f01b21e3c8ae3eb8406f687dd1355a8e03bc3.nq.gz
│   ├── 30f5cc953210a30a289182bde4386b01d4cb7849.nq.gz
│   ├── 326bcd1ae5d0e777ff8a99bc4ad4160761909ded.nq.gz
│   ├── 3326e0bfb6c1df177490494d64621f3a5bbb001f.nq.gz
│   ├── 33a25cd38cf8191dc22672d360aead36f7f79113.nq.gz
│   ├── 34671c189f2f13c48b0e1f4b5b8437df40354825.nq.gz
│   ├── 34d540c4ca42537730d8775cbf08b66f1febf995.nq.gz
│   ├── 39d92d585e83660cf0715efb723f4033d2e41124.nq.gz
│   ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
│   ├── 3d99140c10711892e18979576e361ad2e1ea9bb2.nq.gz
│   ├── 4025a4694b62fc5341ac3b0c41c98b442696aa0a.nq.gz
│   ├── 413b66c45ea931eac07173916676a0c3c587598f.nq.gz
│   ├── 41620667980a2ee605faaa1dbb1d0188c3148f54.nq.gz
│   ├── 422a99c08f8c2a6fa912ab6569686cffdb719b09.nq.gz
│   ├── 48ff641c469022de195e8f1e2fbcfa0b08dbb391.nq.gz
│   ├── 4e1836b181ed6c58e8f6b80dbda350a626cba9a6.nq.gz
│   ├── 4fefdc399b3bc3edd820f6404bf407565d70f917.nq.gz
│   ├── 522fbe20b89911bb8d68b4a684a51225dd571764.nq.gz
│   ├── 532f1b6383793826c92ac043b367a7134c9c2258.nq.gz
│   ├── 55735d4764646baad25634ae14b2e6c8feeeab53.nq.gz
│   ├── 58036c045f702388981d85095ed72ecdc241d810.nq.gz
│   ├── 583b7451f467674154f66f134adea7e53936ec58.nq.gz
│   ├── 58d71e8fb025d175fc8d82880aa7fca4ed6c4825.nq.gz
│   ├── 58f8d0774268f8abe01d44770a784bf6e20e5a5a.nq.gz
│   ├── 5a99619f4fa6e380c51b30ef14a7d9179fa9ba7a.nq.gz
│   ├── 5ac10d4cfe91fd63e83764597d0aa5e2033453b0.nq.gz
│   ├── 5de7961348cd4737968e078b988fa7a916c08f0d.nq.gz
│   ├── 69d0b4c33c81f96893717d109c35130c2943226b.nq.gz
│   ├── 6a4d613cfb09f688b832f3e0aade77ea1e52469d.nq.gz
│   ├── 71a0b4b5ca342c9cabf2fa8d739f6a5a3ff868de.nq.gz
│   ├── 7470eef349e1b6606cb39a1e2e7b40dd71ffa2a1.nq.gz
│   ├── 78ac1e9b7d641c51a4d7c7982f54bd90d3046fef.nq.gz
│   ├── 791a4f3d245c8378c0722fdafcae5258e238c3c2.nq.gz
│   ├── 79b7dcb58357140e88acce64502c40f81b780f0a.nq.gz
│   ├── 80c274d85708a972091cbcf59cf06839a9d71d83.nq.gz
│   ├── 833e85273cd8313bdd03f7f636417c9c0108a1e1.nq.gz
│   ├── 8591c6cb6444ae653d2184261e83dece42f43072.nq.gz
│   ├── 8690c513d638b8d153cc2440c919079b94e0cdaa.nq.gz
│   ├── 8ef678beca0b5b88684338afb0ccbc7834b46e15.nq.gz
│   ├── 90cfc78704c64c2103a5400d571d76dc7da67a8a.nq.gz
│   ├── 92be04f5da80ba3b622cd30c21e129d95c0935d0.nq.gz
│   ├── 991cdfa5d914027bdd178657512b7f7abac4f917.nq.gz
│   ├── 9de714c67ed521f1b9c17e5aabbd6740b7da0715.nq.gz
│   ├── 9fa2d37eb4c3236b7fdab6e10b2e8e6479bb4779.nq.gz
│   ├── a0e69f191398ccc7d87848a58ca4b38bfa11f998.nq.gz
│   ├── a155a477198ee9621a87691bcefe15ab62deebc9.nq.gz
│   ├── a3ca502577395c236adf4ccbe09d8f746d4ae85e.nq.gz
│   ├── a3db1b190862e300f6492a654231376e7c199edc.nq.gz
│   ├── aa53db4e1bf28e6310f6507b08120fb7b89d8a25.nq.gz
│   ├── b064b2cf473ef430d824f6570d74f6e192c6a986.nq.gz
│   ├── b287ef89b92c870221100779714c06b57103f35a.nq.gz
│   ├── b67fbb426cf2517b0eef7f9d487f6b865dede1a3.nq.gz
│   ├── b859b9698e0b6baa15066ae0151f6cf6c0d9cb95.nq.gz
│   ├── b9740fa00ce4fb1ecd06d0706579a7869fcc05c2.nq.gz
│   ├── b993a97b3d32c8422a5c0af1377fa52f347f6d50.nq.gz
│   ├── bc5e211729c67fb0800b15e47e02d2fb95687036.nq.gz
│   ├── bf6bac9ba1fa56b92b756415a2c5afc5595b49c5.nq.gz
│   ├── c1d8cbc925fbadeaf30efeefdc8e4e0c1d3cd529.nq.gz
│   ├── c2098185ad42ae78221eb56fec24c12f9d9813fd.nq.gz
│   ├── c365eb8f017d436b81b17d87850cb571cf0e028b.nq.gz
│   ├── c74e1a7e076d7dc59bf7b8db7172dea864ca188d.nq.gz
│   ├── cea29bdf46f4ac9e26b3b5b5a42e87581bdc0284.nq.gz
│   ├── cf3ee1f50962c148d29eed02113dcbb627448af9.nq.gz
│   ├── d01425e63720005f38ccc24ddbee150fa8b54d98.nq.gz
│   ├── d1898d740482ed6fa70fa1ecde625f1d79dec0a3.nq.gz
│   ├── d4c631d8e97a6cceb890a13f3ee5d0c2e60bad72.nq.gz
│   ├── d5aec8169c7e6c783a3830bf5cc8b484eb002ee8.nq.gz
│   ├── d5be74ebff8e7285a438225675750abb0596d25e.nq.gz
│   ├── d781bbc3164a3a5984ff76151647fa6c05fbedad.nq.gz
│   ├── da441e79ebd5fb8788a4751ae64602313acf6a04.nq.gz
│   ├── da8aee0eb1f35b6fc8f01f7b639f65d9f4e779a0.nq.gz
│   ├── dbcfb75e2688e89e8fd8e148277ca38289f9dfef.nq.gz
│   ├── dde30a1a87877a7d5cc1237c8b1a5b2d17f412ed.nq.gz
│   ├── e02dd2be5f90b5fb3f6ce83983af3f77276e8ccd.nq.gz
│   ├── e03f50b230c8e661176d3957a3709bc3ee9b5ef8.nq.gz
│   ├── e27f0d99404c5dde5955ef6d394b2db9a1de1409.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e73e348df63b8706add7f942f19a3a67d8bbc7a2.nq.gz
│   ├── e984716eb0a38382327520d7a2dac017cb9fdd60.nq.gz
│   ├── ea4c2d3d6dc1d8f7223ed9bae6bb49b8784e720c.nq.gz
│   ├── ede485b790f1e70c46b5db27419457137c49dd10.nq.gz
│   ├── ef1494950f43eec122a63dc5f8287569d0f46ad7.nq.gz
│   ├── f0a1a883a48b39559b888bd4cb22805c2e3975ef.nq.gz
│   ├── f2f9daf4edcd91e9f05c18ad982cb554d4eaab65.nq.gz
│   ├── f6f77521892855db12c05970718f0d7d76a62484.nq.gz
│   ├── f7b2d291f66ed564376f05d8dd2f0ad29085e805.nq.gz
│   └── fe5d0d50a9dd182b325be9f1b7e14dd9f23b9cdc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── cef3a75a19590e8c23fc088a0bfc81ac0350cacf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 117 files
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

[asottile/all-repos](https://github.com/asottile/all-repos)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
