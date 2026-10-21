# Repolex Knowledge Graph of executablebooks/sphinx-tomyst

RDF knowledge graph data for [executablebooks/sphinx-tomyst](https://github.com/executablebooks/sphinx-tomyst), parsed by [repolex](https://repolex.ai).

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
rlex download executablebooks/sphinx-tomyst
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b0eeecc787d74681ab3cfeff41d22aa9e56c11c5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b0eeecc787d74681ab3cfeff41d22aa9e56c11c5
│           └── chunk-001.nq.gz
├── blob
│   ├── 08e18aa52c5021e7e7dab33310076921ef3ff967.nq.gz
│   ├── 095fda6630bbd74238a645844fde246508079fbc.nq.gz
│   ├── 0b2854268e9a648d48a761b0f2e8270b4a887b04.nq.gz
│   ├── 0edced97f20b34f7a491cfa5943a0b2942ecda74.nq.gz
│   ├── 11f62d89a07b7f1aa638a95441a8bf03e1304a9f.nq.gz
│   ├── 1847ea4062101197761c23f526a35a74e1bb49da.nq.gz
│   ├── 1a668cbb9b8925a167a8b858033e1fc0102cca6b.nq.gz
│   ├── 1ab6b738c074f41ada652f791afb09e881fd58da.nq.gz
│   ├── 1ed3a2f95aed8adf96bf599f54162a90d518efd2.nq.gz
│   ├── 1edef32774873f0370193df870f8ec747d26f339.nq.gz
│   ├── 20d41297ab6d1e53a6d8db2d6d9ad5fc2dcbe6c4.nq.gz
│   ├── 28aa98f17411ee720022fa6153f330271455618e.nq.gz
│   ├── 2cffad1307a13691664dcc9d3230431522e12db9.nq.gz
│   ├── 2e0ea8c6fb605cc487ea771db7838805a758c9d7.nq.gz
│   ├── 2f445922c29223798e8320798183e545b23bc002.nq.gz
│   ├── 306b86dd45bf9e8169c95bb4942e39df4618ec32.nq.gz
│   ├── 329e3a4b17923cfd9cab6beb8e8fc9f2c5a42297.nq.gz
│   ├── 3907583c971da4964c606d7b14db013a9de3e0d4.nq.gz
│   ├── 3aaece6f4d9b5a8c0b447bb43abac4dbfc12a7af.nq.gz
│   ├── 3f1fffd8313061c94fff2eb36c24d2577e5625c6.nq.gz
│   ├── 4686eb2459ae337ac2738487f52af422efeb95d3.nq.gz
│   ├── 4c4dc0cd28f1d75b4e1c3c1ef3a555866190f17e.nq.gz
│   ├── 55a158f9a0adfe6f65a11e8e69bb64284788ce06.nq.gz
│   ├── 582ddf59e08277fe6e78cee924d2c84805fe36fe.nq.gz
│   ├── 58b715bed84924e872272e5ce407ffd409b487c6.nq.gz
│   ├── 5b06661a1cdf32aff1a2d8116d7cf53509f41af7.nq.gz
│   ├── 6001789df0be94db499b2062cf7579cd1c992990.nq.gz
│   ├── 6247f7e231716482115f34084ac61030743e0715.nq.gz
│   ├── 6875376e1fd497c3c0dc447bb7c7a81083c2f6a2.nq.gz
│   ├── 6b7775c3963b792ad9c980feb6dc51931418cd77.nq.gz
│   ├── 6b8d05e83777879534aaf6456e878ef76663d7ba.nq.gz
│   ├── 71171d243fb2f76ef310f2c5ab8d97588e5cbc96.nq.gz
│   ├── 741298aec89bea6c5eb85cd5e948da06077213ff.nq.gz
│   ├── 797b31950617ee045f1be3cb5ffb1967dc517c01.nq.gz
│   ├── 7b3c8aae6c1ddcf83864e5ffc8a974fe7c3d6e57.nq.gz
│   ├── 7c546706ce2dfe67fbaccd222c5bea614bc829a4.nq.gz
│   ├── 82dbe988be925deb5d40b30bce988268f0173fdc.nq.gz
│   ├── 8308519c9ca7627a286e383e73eb8a226c5bffd2.nq.gz
│   ├── 86d09d47889eacd191a662cf7202933273fa3d4a.nq.gz
│   ├── 944de87f47825cc60a72e6591f736ac58ba2ed38.nq.gz
│   ├── 970578a0eabbd358d9a6fe8b9da82daa94c43070.nq.gz
│   ├── 98c095aefb18ebee33e2db1a8f0822e44442860e.nq.gz
│   ├── 9b9fcea3b1abdb27e6389375724d92f24decf55d.nq.gz
│   ├── 9c52f09ac6d5f7f6394ef90504782aeed21f1b41.nq.gz
│   ├── 9c79f8d4fcf259e95e6dc9f6c47ed768330477c3.nq.gz
│   ├── a02ccab3d91e3d10de1dbd7cb68a9090de0127f3.nq.gz
│   ├── a195122d1d780234bb3997320d192c560c84bba6.nq.gz
│   ├── a5052db2dabf044450c21810585cb667fae7a022.nq.gz
│   ├── a5beb3af507bc8d434b42e5e6f9fec5c131bd41a.nq.gz
│   ├── aedc4a88ddb4f0800356b3d1f2dbb03c0613d0b1.nq.gz
│   ├── aede757782506022128f11b93461a6cb6a8ac219.nq.gz
│   ├── af9ab9318fd616db3315039890e2d9c4abecd9c9.nq.gz
│   ├── b152e592456684d12eb6ba5738488ab829f4e944.nq.gz
│   ├── b5e87095e939de5ed407538f9e496e3e5b5049bb.nq.gz
│   ├── b7177428c3364815ab7ccb81b0cfae7a5c0d10c4.nq.gz
│   ├── c2ea87b4ca4bea600881118a28123ac9f44c2b81.nq.gz
│   ├── c317a1bfd66a5e120ae657c7ffe166c33c41ef95.nq.gz
│   ├── c54f9107d060fa5ce617eacca1d92b00ca9a5aea.nq.gz
│   ├── c68a78310fede7583b2b4f5c4bcdd067b7d016a6.nq.gz
│   ├── c77fa5819115ce8555aeb14a1ccc90e1c63ca8c4.nq.gz
│   ├── c78686530902d4a13110a6ff445e29c1e038839d.nq.gz
│   ├── c901f7dabb75a651fc2f96352a0a3233ebd2efe8.nq.gz
│   ├── c970f1b1235b08c080d8894ea4155552e0f681e1.nq.gz
│   ├── c9ffa4a6e9bd52135e2273e77676abe7f59b6c03.nq.gz
│   ├── cc4970564c3bbecc11d96afa35ee166f0aa910d4.nq.gz
│   ├── cd528451b344c3deb62bf17d33cfab3e2e948605.nq.gz
│   ├── cffaff018b331ac708d4e8a51ce2e3bb13447c85.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d15a49c3b462b71f1ae4fd74113cfb880b8b7748.nq.gz
│   ├── d4971f7088e018c5f2a0a2f69437b91697c6237a.nq.gz
│   ├── d677cc0530e55627510b3b0ef58ca232f9b0c672.nq.gz
│   ├── d93c5ebd0b8bc83f5d17fde252265583f743e184.nq.gz
│   ├── d95dc9c261b3a0f1ce14ed1bdaa8c0dffe1fc420.nq.gz
│   ├── d97687a5659566c7c74e8b58c5c44e34a8e04a8d.nq.gz
│   ├── dda9865ad01e8f6ecebfc69f0889c81050a594f0.nq.gz
│   ├── e115262346f503833f3e8b1c66b1671c69b5f743.nq.gz
│   ├── e27251a3e142bf7efbf994b7b71de48c857c2dac.nq.gz
│   ├── e2d149408cf56c6895bca3a25df02f2d022d0201.nq.gz
│   ├── e52d828b2f49b4e2dc9d1f559455a9f1b8662961.nq.gz
│   ├── e5e2b4f144cf28f0d12c3d8b5777d53a962eacfa.nq.gz
│   ├── f23f50e3b5a3f04e0db36dbfa0f10ba7d859e75d.nq.gz
│   ├── f6bca2606345940f440b98ad21e07fa85d690528.nq.gz
│   ├── fa996bbba2bffaa647ccc5428d758107c924125a.nq.gz
│   ├── fe03608098d4c67d722658f5a82cf1f23cb1a27f.nq.gz
│   ├── fe6774db7c61f8e15959dc6f829c856a38a3c743.nq.gz
│   └── ffa461eed75b957aaba3c73850b8339278f2020d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b0eeecc787d74681ab3cfeff41d22aa9e56c11c5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[executablebooks/sphinx-tomyst](https://github.com/executablebooks/sphinx-tomyst)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
