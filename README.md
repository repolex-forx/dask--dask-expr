# Repolex Knowledge Graph of dask/dask-expr

RDF knowledge graph data for [dask/dask-expr](https://github.com/dask/dask-expr), parsed by [repolex](https://repolex.ai).

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
rlex download dask/dask-expr
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 42e7a8958ba286a4c7b2f199d143a70b0b479489
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 42e7a8958ba286a4c7b2f199d143a70b0b479489
│           └── chunk-001.nq.gz
├── blob
│   ├── 01376224272d62ba05edc616db69c831bf6435ef.nq.gz
│   ├── 0313448a01d51218a8c918b453be912acc1d626f.nq.gz
│   ├── 037eb3b3b4b532b996b7cdb8c248a1bb0f5420c3.nq.gz
│   ├── 06a998e672c47629e5308d61f7a2ff1a061b8a7d.nq.gz
│   ├── 07aa45f83d0bd72ffed9ca0f512b669b45657e8f.nq.gz
│   ├── 081f0b5f3c167ad20ff25e505fb08c7baf60d016.nq.gz
│   ├── 0b5c25a0a26eeab68165c72c0cebfe79f49ce970.nq.gz
│   ├── 0ca19022de45257354c75683c20fd4f43e906e74.nq.gz
│   ├── 0db979577ed8dc2adabfe2c10b3439f0d979d0b1.nq.gz
│   ├── 0ef48d0e6ecf16db29d41303b15d2f62041f3722.nq.gz
│   ├── 10002eaa19eed2d7fe39ec4b033815757f55c938.nq.gz
│   ├── 11f73d0b1415aab8ccd52396a575ce3973920699.nq.gz
│   ├── 120757377d3b1ed7366cc5ecdfb0e5385577851b.nq.gz
│   ├── 12e933d2b8e476056fdd5dd2148359acf6c082a4.nq.gz
│   ├── 1921ae42bf84df95a0b868cb7a7fb14d6b99f2af.nq.gz
│   ├── 1a82bb14b27b123bc22ad5e63853769c4bcf957b.nq.gz
│   ├── 1d17bc928a406bee9bd5db037b0ed469e97bc9f8.nq.gz
│   ├── 1f24bfda1b9d1d66a710b6fad71b379bd765d093.nq.gz
│   ├── 1fc807aaa4eb71ee48724a2464850049ecadb3cd.nq.gz
│   ├── 257b791a52f070ab3673cc99d8b7dfcc236f7301.nq.gz
│   ├── 276d90b8f0d6d9bb56e09003ee2ef45e81732ad7.nq.gz
│   ├── 2a0a107b44a43cd7dadd8ccb32b3f9daf31679ed.nq.gz
│   ├── 2bbaa197b64e4beb7b33ff1983f7ed4ed120961e.nq.gz
│   ├── 321dd6e0c03eab3be994c9369d9f3ba36af9345a.nq.gz
│   ├── 32d83b2049caf02fa926a7e317cf40da7461f6d4.nq.gz
│   ├── 336cf2ea1e7b9a436615a93c8cacf2772febb1fd.nq.gz
│   ├── 38741c39edb50e3e268d59097f93dc85833da0e5.nq.gz
│   ├── 3ab5186fdce06ffd6126d498b57b8ee218b6e000.nq.gz
│   ├── 3d111d5da6040017c4e0dc8bb76c18f8eeb135d5.nq.gz
│   ├── 3db7c9d72b073a7e4a50e6311f8763d3811f8f2d.nq.gz
│   ├── 3dc5af6b7b58e38d88404533bd5b50b693f0ce43.nq.gz
│   ├── 4553f05c7126a2cbd647ca202b62ab693ae8b9a9.nq.gz
│   ├── 465325c122227b151708db5f541dc7f31daf3ef0.nq.gz
│   ├── 48acd5dbec5bee14ebec3d2d0024ae0e9bb8d296.nq.gz
│   ├── 4dca52c2cfd260991f539f6fe7b82b9fbcb39f13.nq.gz
│   ├── 4f09b98767b14056bf082a82c024943d9b55273d.nq.gz
│   ├── 50bbc041d4ef277fd9d9e0d72b7a2c19114e0c36.nq.gz
│   ├── 53947f4f66e9bd40058a347f621a29522f705816.nq.gz
│   ├── 5491ae99406a5e04098bfd50bce6ac12f219450a.nq.gz
│   ├── 570246f15f3c0411496441daa31db7d0d843b284.nq.gz
│   ├── 5a3187bc0a6882b293c3f8108fbc7efb1fafe7fd.nq.gz
│   ├── 601d780345b6c074da648fd9f641100b21bb59f2.nq.gz
│   ├── 638c0c202a248eee552659cb8c31657e39b4c146.nq.gz
│   ├── 68c17823c1aa012a6dd84c38d46aaffb3a03bf13.nq.gz
│   ├── 696b2d6d9fde72bc147f55b5dec994d1a7b7ed8b.nq.gz
│   ├── 699e3329ecdd23bcc523f1ab915ebbddbb5bc3b7.nq.gz
│   ├── 69cf923d9f615f85ca0ecf3ac2b3e829383be69f.nq.gz
│   ├── 6aede42ed475edf4c5d34510b49e60af5b6ae9fb.nq.gz
│   ├── 6c03f465d4fa2b9438a0c61be80b3158d6cc38e9.nq.gz
│   ├── 6ca9e4ce4b340b357aa704ab1ef67f66f4726486.nq.gz
│   ├── 6d2bcf224e98c54875dc1f2adca9c186d03b157d.nq.gz
│   ├── 6e0f3230017218f9365e859528065b136c442fcc.nq.gz
│   ├── 7ce47068a827cbd388de80d72a577019ec406252.nq.gz
│   ├── 7e56a00e289a7aa4d30ceec3e63477df7b523129.nq.gz
│   ├── 7ed28e327f150ed7070502533a08b612aaf0a78f.nq.gz
│   ├── 80f4568f0fabe3c2cb27f3334254cf0bc56c92b8.nq.gz
│   ├── 85e635f23ca9bd9b7362d07c0e8ccf6a8ea83bc9.nq.gz
│   ├── 86d2efd21d276f5b800b32dbeb3280e4d74fbc20.nq.gz
│   ├── 874ed2c67b3655e6b04c541dfb2f54f16f50ed7a.nq.gz
│   ├── 8a4d42c6bc251f9f1584949f68102a7dc821dcf8.nq.gz
│   ├── 8ba86f2f5db535b91fb69471860533527527c4f5.nq.gz
│   ├── 8e697e51ec68b0cfd95733d91bbfc174675c6f13.nq.gz
│   ├── 9093c96ff58a4dba0f96aec740121780491c54f2.nq.gz
│   ├── 91f586bc0ec892581887b16079d6ec04810f3e77.nq.gz
│   ├── 93775272205ca08b2d006d9daf74bc5d3481f020.nq.gz
│   ├── 9457f09440d391bfa4745adc6d1511cb2a915cfa.nq.gz
│   ├── 94ed15996eddaaf75e9e34a4f358772d771531a6.nq.gz
│   ├── 976f344b1d81e06cd13487e3f33253ed3a2e6da1.nq.gz
│   ├── 989b01b7b8c1b4c4e070ad81cf1b03a2446c20e3.nq.gz
│   ├── 9d025f373cb00df0f068a57ca1c3ebb600418877.nq.gz
│   ├── 9e6dacffba9a4cd9f80f71437a9d7ab15ced4cd9.nq.gz
│   ├── a506f22d9747257a17c35a28980b7401692798de.nq.gz
│   ├── a5e0a6daf4310274dd87a409a795bb56108df2d9.nq.gz
│   ├── a9935b9a7e7fb822a4b697d3f416b93f58bfafd9.nq.gz
│   ├── aa78de625b69f52eab83677ab5a290ea91ee1ab8.nq.gz
│   ├── af813789892cb7dd869658ff4758ea2847ff0fb0.nq.gz
│   ├── b152fea8176a8e55ad9fbcf2eb30ec9aa9337c95.nq.gz
│   ├── b26ddcba4300730948d6fc9797af93c394f711ec.nq.gz
│   ├── b70f14b63227e280d7c9ea06818e0bc682876f0d.nq.gz
│   ├── b80919095c74c61d96b7d87289d9e3374a6dbd4f.nq.gz
│   ├── b8cca6b613529124e6e406e5110a93ba5078fab4.nq.gz
│   ├── b8de0fbc1397b97d9b89cf2a012e5eb26105a47a.nq.gz
│   ├── bbaa97210fe76504640a4e85cd28572f76573590.nq.gz
│   ├── be15d553a488239457886eca074bc5a6806a41e6.nq.gz
│   ├── bf378945d6278fd0c70c1a73042ab6073696d58e.nq.gz
│   ├── c35094f4b64d100d8107b0f27bd3113292ce08cc.nq.gz
│   ├── c3c9c2172cb46a84d500d762b879e7092899609a.nq.gz
│   ├── c4b37e0ad4b294522ab9ce22ea6534764ced36cd.nq.gz
│   ├── c8d99ebf8b3f529881e6baa35ce7409b9d709413.nq.gz
│   ├── c9845f6f6d03bf894bb93fbd55323b815ae9a2b5.nq.gz
│   ├── c999c12bb06c977a450bf93a0e870897e6c5dcac.nq.gz
│   ├── d0b0ef2d31a51be9f4eabc9111fed9b07e6f5d34.nq.gz
│   ├── d28a9f227a55fb2a6f552f71985b2a177e5a1d7e.nq.gz
│   ├── d5b089252be2d9fa900b1a696c75369b934b8226.nq.gz
│   ├── d937da8b4548c5f07f3091f0d55abdecdb4e1796.nq.gz
│   ├── dd0b571dce9fb841dc783a2c707f078edb5b38de.nq.gz
│   ├── dee5178e1eed09648570ed0bb692bea0547e29b5.nq.gz
│   ├── e18777961ab46dc928b052eaeb83231e7ae7ec30.nq.gz
│   ├── e21f8dc9db237ece270f65d3067f47ae1598bd10.nq.gz
│   ├── e2877f432627299d720d153e55a8e27472d36009.nq.gz
│   ├── e5bb956bd661faf0c8513791a898fdf3c7aa1060.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea4ac2b28854a3232af4c5349b5d475dc852614c.nq.gz
│   ├── eb063411c5c448deb31850cccf0b9acca4761d48.nq.gz
│   ├── ec74da2fd82140516ea3630fca9b401088b0a386.nq.gz
│   ├── ed9b8c41fa3a3e07d3247b7737b529e41df47582.nq.gz
│   ├── eebafada56cd9a030d8f35540829d9a5a33decf5.nq.gz
│   ├── eecb91c0ecb409d016e6e406d9abb748854374ec.nq.gz
│   ├── eee542b28d670c61adc00d5047228a0e1d75d428.nq.gz
│   ├── f2c0ba0e752d72f9445ffa490bc5cc1c21db11a7.nq.gz
│   ├── f55ae2142cd6c3056340060180acea9cda9d16f8.nq.gz
│   └── f5feb038c1204bd19cb7aeb92e221b239af7017f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 42e7a8958ba286a4c7b2f199d143a70b0b479489.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 120 files
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

[dask/dask-expr](https://github.com/dask/dask-expr)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
