# Repolex Knowledge Graph of juanbindez/pytubefix

RDF knowledge graph data for [juanbindez/pytubefix](https://github.com/juanbindez/pytubefix), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download juanbindez/pytubefix
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6a54cef9f6c9d184b84890c3106203057ea708fc
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 6a54cef9f6c9d184b84890c3106203057ea708fc.nq.gz
│   └── repolex
│       └── 6a54cef9f6c9d184b84890c3106203057ea708fc
│           └── chunk-001.nq.gz
├── blob
│   ├── 04698ee85c3b061ee96c5f787927de83f6a45aa5.nq.gz
│   ├── 056a4137a8111c66992527d5b5e0d5b1eef13181.nq.gz
│   ├── 064190a7a4b5971fde2daa6b9412a9bbaf26bfbb.nq.gz
│   ├── 0877920321315a79ed7ceb54e42c7ad3ac98e8ba.nq.gz
│   ├── 0bb169b41daac13c8e865c442fa4b6d241d6c99d.nq.gz
│   ├── 0e40102f4b4064969512f47320d162717052aa16.nq.gz
│   ├── 0f571a039039dcbbcba1bbbb3933b4580eee0a75.nq.gz
│   ├── 10fed6d3f4d595926e02e77b5be69aac7abfadc2.nq.gz
│   ├── 1121b3a93d23a25ca3ce23a0cc1c42d8ef8c7478.nq.gz
│   ├── 146aca90e96277567b066989bff69985d47a542b.nq.gz
│   ├── 16cd65e815d9637c847e171a2a1a5c706516d4f3.nq.gz
│   ├── 170f250d6915942b7b4a82357ad47ec007400799.nq.gz
│   ├── 194ebaa0672b588f2673e1e984c4e0145a8e8f74.nq.gz
│   ├── 1af95335e6b62c5f88c4820c8fd78555e9bf73ca.nq.gz
│   ├── 1f6d503e52ca6ee2d379823a805e7c58bd9ec2be.nq.gz
│   ├── 244918c2eea47b1fb1c22646c776dab47b0be8d5.nq.gz
│   ├── 281a9f6661654186e2882886b59b9032e31c56a0.nq.gz
│   ├── 28465bf2fef52851aefae7d40263a6500a3b0259.nq.gz
│   ├── 2a7a48051018b28b44324285f74b5e4b5cbdb965.nq.gz
│   ├── 2b54335343262a5f03b9c7286feddee124923003.nq.gz
│   ├── 2b87ee9e59b533f3a1a2f90a6574908ba2946222.nq.gz
│   ├── 34f91c5acab1fd7c74c8c0fe8f338a5a3e3e8c4d.nq.gz
│   ├── 3a81750ac33ca547d5ef477f16bd9bb0e34dd8f2.nq.gz
│   ├── 3fde1e4f2b5a49cc0ea625e6e5bf51b737e31137.nq.gz
│   ├── 459f65a6ec8fbf5228d968ac65195a009895da58.nq.gz
│   ├── 4871efb3f7dd86fb6cec596af8274a4580a83b78.nq.gz
│   ├── 48a45d5d06bccd58c8ee4426dc3e80a4a36e67eb.nq.gz
│   ├── 48b1f89696d9987ec165f4638c3281ac34f6671f.nq.gz
│   ├── 49713b5a73fa1502efd7688071e8cc6590449791.nq.gz
│   ├── 50610534f0515bd3d2ae348236be89fa59e006fb.nq.gz
│   ├── 52f666454bd612491d0fe33cc9c77d58cddc9af3.nq.gz
│   ├── 52fa93bce6349bccd7a539f080831b0aa6ea66e6.nq.gz
│   ├── 53738e829a6bccf0b78e933c2b97ed6eb002a59f.nq.gz
│   ├── 54abb048898518c0d4e4fa731c0ed080ed59995e.nq.gz
│   ├── 556f3d35e03e46c0c94e2f85ae93fa7108d15132.nq.gz
│   ├── 59205c2582d7073515c02c3d0fd230b99b137ffb.nq.gz
│   ├── 5f11e97b51b918870864c12b711cfef9b0704bf1.nq.gz
│   ├── 604615a703185179d12c0f6aca0cc0647f189bf8.nq.gz
│   ├── 64f0c26411fb65cc6c70d35c9b50880a2dd5ce40.nq.gz
│   ├── 6d680c2ea53b94ed3c84120bd9e99f28702d225e.nq.gz
│   ├── 6d6fa110ede3b610c7f6aa93380134b70d7f10ed.nq.gz
│   ├── 6dc3bc217b909b1fd60c55e262421068a862f831.nq.gz
│   ├── 71eede478ed09de90c1c5d44f736f05b077cccfa.nq.gz
│   ├── 746b3d50a0b71f906c4df084f2592b0b703e0457.nq.gz
│   ├── 7601b8582741766efef9038957b25e1c70cda405.nq.gz
│   ├── 7c66c6aa0680475e24aaa7ce67ef601383e23183.nq.gz
│   ├── 885f0c1b03740673eb7c3eb6a70072042701d49f.nq.gz
│   ├── 897fdea6471a283bfb154d1063552425e3a3aad3.nq.gz
│   ├── 8e09554be42aa2f755b29f5d070fd6a437c1e7f4.nq.gz
│   ├── 8f98d9aa71d1a786be12f19ef80647c79fa86bf0.nq.gz
│   ├── 936c5c6e6fe09367b93a217ebb132329319acd18.nq.gz
│   ├── 93b4ca24114b375ae8b8c84536c77451b0393319.nq.gz
│   ├── 9819031e9fed8bda1269781cf370d8497141244b.nq.gz
│   ├── 9efb9346df3939f4f659c98857b79f075e03758b.nq.gz
│   ├── 9f4698a1c92a0bb996904b94d34db479f0886075.nq.gz
│   ├── a544eb3617335e9365f9521cf3851a9cf282d136.nq.gz
│   ├── a63140643915db0dc8b4e55d8943f89da9cefc2c.nq.gz
│   ├── a8093d01e52980168543eb2cee2eef9144dac954.nq.gz
│   ├── a90961ad8da34c2a18131504f29174d2130d8373.nq.gz
│   ├── aa41f0c58ea33fa82ceeee2aefedd69b79f8b15e.nq.gz
│   ├── ab3faf940da15aa035bb7c7d4d9b4a5b69fb587c.nq.gz
│   ├── adb057bcde07741cb8b226a4359026120bbcf583.nq.gz
│   ├── af73c04e0771e42f004f851766ea12a2f2158b81.nq.gz
│   ├── b197dc81e63672d957fe30f4bdf2465e5a0b90fe.nq.gz
│   ├── b2fa1b8cef1b37d5040dcd9d7b5ca84087834cb2.nq.gz
│   ├── b6f2f8695de3d7b49db6ae260e4ee37d93f66785.nq.gz
│   ├── badab8496b5732f798648035f9d9098665fa6c21.nq.gz
│   ├── bb3ec5f0d4c70ef732aa4d399282a5ddb2a008fd.nq.gz
│   ├── bf11e44916b46d23da15104f49f442a0bc12351f.nq.gz
│   ├── c1b18ad315a74b9e9d13b97287a45a02cc2f985b.nq.gz
│   ├── c31f6107426e74cc43e8507e512118e99894b12a.nq.gz
│   ├── c49659baf2b0f83303e7dd7dcaa79392ff164141.nq.gz
│   ├── c5d24c061d1bbdd5d00ea4b888e31df99ed22d51.nq.gz
│   ├── c758f943d73036c4f479815c3835ddb23864de05.nq.gz
│   ├── c8c52c602dc2803a790dc54dd1743c7e91d55053.nq.gz
│   ├── ca71a60bc7276e20d14632a2ca35a414a46f9f05.nq.gz
│   ├── cb15687f754cc3d38e97fcf0ac2e26bcfefb06f0.nq.gz
│   ├── cb3c345f5cc22e250c6960cc310374eeb3ed113d.nq.gz
│   ├── cbe42b7cc8c8eddbf4970dbbaa4fd547a8e0208a.nq.gz
│   ├── cebcbade40aa49d1dac129cb9b666b3b6b7f3cae.nq.gz
│   ├── ceec598d3e60272e21c7efc76869160636758020.nq.gz
│   ├── d397782fb61e22db5646166ae267e0592982191f.nq.gz
│   ├── d5d28ac533ebb324972515653ddfef7e1cbc193d.nq.gz
│   ├── dc5b41b18869e01e0d2a861290a15c042cfb842b.nq.gz
│   ├── dcc80fd234ee309b60f836d9f16102d8fad55103.nq.gz
│   ├── e19a060873dc1cdaff1384f7804d13e7d059c969.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8152b2daf1a5e1d65e0ea83813db7834843d22b.nq.gz
│   ├── f0aae7663fc1fb448404ddcf79fa01d5c55e5d4f.nq.gz
│   ├── f234fa82f6eb3e542a45e8df5b5c5d125be7ed92.nq.gz
│   ├── f53b33fdcf983bfc18478aca7f1523e75e5e043e.nq.gz
│   ├── f621a93d2282c5875ee88e61ce74330730733280.nq.gz
│   ├── f6368d2171f15ef7b5d34bff57fc5b03db357157.nq.gz
│   ├── f897247200c6ca3b1aaecc8f93dd986aacd13c03.nq.gz
│   ├── faa770c792bcdba0c348bbf301fb8f9b0d318dc6.nq.gz
│   └── fb1a5f9de7323acbcad564ac5d90faaea8f3b41c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6a54cef9f6c9d184b84890c3106203057ea708fc.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

14 directories, 105 files
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

## Source repository

[juanbindez/pytubefix](https://github.com/juanbindez/pytubefix)

---
*Parsed on 2026-04-20 by [repolex](https://repolex.ai)*
