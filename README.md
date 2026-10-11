# Repolex Knowledge Graph of pydantic/brand

RDF knowledge graph data for [pydantic/brand](https://github.com/pydantic/brand), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/brand
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 83c4f63fbf5be3c292c7e946febfdaa16e24352b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 83c4f63fbf5be3c292c7e946febfdaa16e24352b
│           └── chunk-001.nq.gz
├── blob
│   ├── 03de618dfd1edd53442fd69554ac9cef5093ac1e.nq.gz
│   ├── 049c1bf9a0dee4cc89878e030e90a4e4be0b4ee5.nq.gz
│   ├── 064ffb443721248c645b6571373835275670ab41.nq.gz
│   ├── 0a09a4fa02fa5588a69df77ab1e0854fcee5eb46.nq.gz
│   ├── 0aec86baa287fa7e97b6237cce5a17a7312c6efc.nq.gz
│   ├── 0b6665d570b469a0d198d75dc8c18de6aebbf196.nq.gz
│   ├── 13d8accdff1aee44719abbb11f37c9097a5e3046.nq.gz
│   ├── 145951472cfb9849e967ac1841a198b2541ef51c.nq.gz
│   ├── 15a7756d516d8d7e9b0926a3f02d7273cc3b2f92.nq.gz
│   ├── 1b059bebd5de8f312e3cab5b53ddac640ce948e0.nq.gz
│   ├── 1b1d30b3550ea4b8c0f092442ad1e93ff80c6fad.nq.gz
│   ├── 1ca11807994d8a68df6827f4d32d9f94cb42c9ea.nq.gz
│   ├── 1e2e86af865d4b4a16eee8fe4a8c2a5b1276af9a.nq.gz
│   ├── 2056863caefc7239c5b8cc273d9535d7deffbaf3.nq.gz
│   ├── 22665b4eee2ac75ed167858c7e7c955c38cbb5a4.nq.gz
│   ├── 22e9057b30df5972335740a7b58fad001d0b0072.nq.gz
│   ├── 24ccc434b41b008c087164eedd4c0c9f3e6bed89.nq.gz
│   ├── 258c10a96a9c949899883aa2f6b2794f8d1391ad.nq.gz
│   ├── 2d27ef460691bb10f077785d2ab6ccbb770547af.nq.gz
│   ├── 2f1b29edf48faef8f1895a8cb042566f308ce66c.nq.gz
│   ├── 311993aa028d0b250deb2dede2dbf3411efac522.nq.gz
│   ├── 338798a82ca9914a05a06054ff1c1c53544feef6.nq.gz
│   ├── 347a7d028af825b9092e3655b2e44f60f873a7fe.nq.gz
│   ├── 3843b64c463d6f73eb68200c0dbdd3ee6323528a.nq.gz
│   ├── 39c2458bf8d9a81bc9d7c693e7e70cc98bcf707a.nq.gz
│   ├── 3a2435964159904ac4da5f4702975fd7a51a7c01.nq.gz
│   ├── 41700e755db9dc27ca5c766087d8ea6721bf35bd.nq.gz
│   ├── 45dc8a20658bd09ecb8ca1c88f94fe80cc4ca286.nq.gz
│   ├── 46f52c4811d2af50de516c849f0e7898c9dc091e.nq.gz
│   ├── 47e5d652938eb8824f4632dc6989361a20018151.nq.gz
│   ├── 490c9f01ee1f43897f91fc3edb4b1af5fcbd8358.nq.gz
│   ├── 4d4518e2abf34a80469ec52c1f1becacf025aa1c.nq.gz
│   ├── 500307f7ccbdefd601fd94f9cf69f6efb0a08d04.nq.gz
│   ├── 5387ad48ccb9dd751aef3f1ee7122b5c6dd56946.nq.gz
│   ├── 5509140f2ce4ffc5aa4c77e35093e5744c301b90.nq.gz
│   ├── 56e7db7dcca8d77a6d3f5304b742cb39b6ba2d84.nq.gz
│   ├── 6200ca4c7afb0d4e7a1b5c30528f0d50428663ad.nq.gz
│   ├── 6232aaa8c3b1c81a359e12c176701fa0fb4a8f67.nq.gz
│   ├── 63fbab5c87e1c5ead339797ba4188507e06f704f.nq.gz
│   ├── 645bfdf12a8b14fea265a3625ed1d76e7d613469.nq.gz
│   ├── 64c8beed8768bda4f66cd58d9a5efd244b458844.nq.gz
│   ├── 64cb0e7525bc638fff51344d197fca3b4f7fce58.nq.gz
│   ├── 65b40631a2e7cdc354d79f71e4a7841a7115a31a.nq.gz
│   ├── 68d9040927a3597179e1fc2d59d88847fe73c8fc.nq.gz
│   ├── 6f11e691feae78ea258eae7f689931e6b876c7cb.nq.gz
│   ├── 6f7b9a992b4a7efa6e7cc6277a5145a76009989c.nq.gz
│   ├── 6fac7fa38aa24a4a83102f57282f5e6de1e349a5.nq.gz
│   ├── 7426eee6fb8ff82b5ca0a527f8de8ef0f1e18528.nq.gz
│   ├── 77832b0b8156c40d9e7d4a1bdd9819b33789d9b2.nq.gz
│   ├── 7ae38bab0445c822cf1fb8c49fb4c53f923c9db0.nq.gz
│   ├── 8177b8e07eb73bf7756e889652270384f685c9b2.nq.gz
│   ├── 827b4aac50b79c95b2f38d33508ec135986a12d9.nq.gz
│   ├── 83580e9965a65caf530b78b1933f235ef10dc061.nq.gz
│   ├── 918d4a0c44203a936f20fabe9c5edd833a25da6c.nq.gz
│   ├── 924b914f3f5e4b382542e33e599e7b0c34753573.nq.gz
│   ├── 94438bf9da23165f82023b8d047b86092f593f18.nq.gz
│   ├── 96069a4a91aadb799c2f0cdacae622fb72a24393.nq.gz
│   ├── 967dc98fda5a60c312d1b344b0150c81ba037a02.nq.gz
│   ├── 981d51425d4e4523cf42784501595da5399b2431.nq.gz
│   ├── 98454d03a35219e9fdf504d47ffa0b63c73e0341.nq.gz
│   ├── 9add8756408e967a235c3b7b605da214d5d3121f.nq.gz
│   ├── 9b9f6cef6a1638c58bc535c1ca08df40a278fae6.nq.gz
│   ├── 9fcbef2134b293b53d564d43929db5957e201791.nq.gz
│   ├── a0c42b818495d13fe6266aba00defff8794a77a3.nq.gz
│   ├── a122f21254156ad2b8875f2962629b097a432b82.nq.gz
│   ├── a42b67e918b5e408b643e21059a551dfabdf708a.nq.gz
│   ├── a4327585773b80529bc6617fd959879339987e3a.nq.gz
│   ├── a5130fcb4145a398ccf1b2dd9c081f9339ac720a.nq.gz
│   ├── a63f1c5629736481295aa89d20e38a0d4286b6eb.nq.gz
│   ├── a715d679a79b166fc26798149d9531939453f459.nq.gz
│   ├── a7c60902ba6ad242fe5af0115e6bfb945c02ac8e.nq.gz
│   ├── ab19b85de8916cb293d69a0754321c709541bf67.nq.gz
│   ├── ab46a0f1bf78613d9a2b48f98ac2c1e1e1591332.nq.gz
│   ├── ac93249a29f91232b0f4112c7280994ce19aa52e.nq.gz
│   ├── ad218c8e24d6579cf74a1c4b3d921c49fb2ac929.nq.gz
│   ├── ad9a6259bfec90b93569020247f71b32d3ff2ec4.nq.gz
│   ├── ae045fef0240eb7e94e13e74946569acae1fccac.nq.gz
│   ├── afd9f5932d5ec2ca568c28459b290c4a2e2252cb.nq.gz
│   ├── b0ae476fdcd26123c79963f140b188632e0f2d53.nq.gz
│   ├── b0cd1b2737d39cf1212a056d3f44e2a852de46cd.nq.gz
│   ├── b2ff4b1f5155e244d16ef16325747c132bd5f7c3.nq.gz
│   ├── b6dc4bf139c48d1398c43ca0edd923299910ecbb.nq.gz
│   ├── b89d402a92c86b009259dfb288009c5969232860.nq.gz
│   ├── bf4395636e534a2d0a20f77840cb51777ff03750.nq.gz
│   ├── bf466571f0c898f5b138b04f677fb590a6298962.nq.gz
│   ├── c5736926588a0aa038ff7ee8301d95242bd1e447.nq.gz
│   ├── c6cf03dc783fdb166fa71fd89b825c010337963d.nq.gz
│   ├── c8f51aad9572cce472094e5a9d080ac56acd7e14.nq.gz
│   ├── ca3de3e74f11859fce4127ef5843d7eda228f8e5.nq.gz
│   ├── cb0eb1cf234e07c03227d174d1e4dcd917af7d01.nq.gz
│   ├── cce9ff75c4818f24a8f16c298b757555dd652a3c.nq.gz
│   ├── cd729393cc99843a577a9167ba85998036bea9c5.nq.gz
│   ├── cdf06a1acdb31fc383de9ef9b217ce985b437b8a.nq.gz
│   ├── d3e9e82639adca2662a96c8d871ce7317c223e3f.nq.gz
│   ├── d9cbea1b32bdbeb88fb33af6cfaee105795ef1d3.nq.gz
│   ├── db3a599b3418ab92728d4f1327b86ec3c77ba64c.nq.gz
│   ├── dda2e8af0cc184cf71007dc9505b478014dce05c.nq.gz
│   ├── de9f0d62fbd7c403691f85dfc8b18275344b0a47.nq.gz
│   ├── e423b74780b16934a073769bd147d46479ceb8b2.nq.gz
│   ├── e6f7439786034a79dfee8b30805f468a83f7dd5b.nq.gz
│   ├── eb1ad2a23df0e202602825f8f2b057a02dfc501b.nq.gz
│   ├── ec6f0f0e32df03a679b9de4f881dad9a8521ae9b.nq.gz
│   ├── f1029b2c50e99f991d427bccb4283d8381f5d61f.nq.gz
│   ├── f2bce483b4a27c2fea573f209232a91223c50621.nq.gz
│   ├── f2be9444056fbcd2db381f036f4118b53f9a2fb9.nq.gz
│   ├── f33d87a0dea76b1b1b800af65bf2eeb11f369d17.nq.gz
│   ├── f34461bcd560bfc0e233304967e9431f1eb20c24.nq.gz
│   ├── f6b1b54a41b9f82a8691dcd444fbfb2145fe8ce6.nq.gz
│   ├── f7d1dabaecd2853eff80c2c94a4a045b3a0b794a.nq.gz
│   ├── f8f53b9d2694fed801e51e5e76a3cbe9cbe9b5e6.nq.gz
│   ├── f9e9ef613a80d960a4befc488be5e85323da6868.nq.gz
│   ├── fabdca0449a2c5ae931d272a92aff4ea92923a93.nq.gz
│   ├── fb75072d87cd07ec19d5a9e05df64ed26f430fe9.nq.gz
│   ├── fd7f8a04dab09736f9209751f83141886dcf9ae9.nq.gz
│   ├── fec8886a91ee7cfee70e81e73f6cc4b831417b38.nq.gz
│   └── ff34fed6d8e6f0829eb9400ddcfe86f5a9c9befc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 83c4f63fbf5be3c292c7e946febfdaa16e24352b.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 123 files
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

[pydantic/brand](https://github.com/pydantic/brand)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
