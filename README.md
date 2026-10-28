# Repolex Knowledge Graph of sdispater/eloquent

RDF knowledge graph data for [sdispater/eloquent](https://github.com/sdispater/eloquent), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/eloquent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0638b688d5fd0c1a46b7471dd465eeb4c2f84666
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0638b688d5fd0c1a46b7471dd465eeb4c2f84666
│           └── chunk-001.nq.gz
├── blob
│   ├── 076c85ab7e30afb757e46c845247d56987a9dcc5.nq.gz
│   ├── 08812dd8b4dea6e322144cff0fcd7bbc5ae5373e.nq.gz
│   ├── 089e35d7a5368998b0adc572d1c80d5f2f3f0b7f.nq.gz
│   ├── 095ed9a262f1021cc4e6c0d20fb6349c928345ff.nq.gz
│   ├── 09c7da9fc3325e9da492b1114ec957ba864c3be4.nq.gz
│   ├── 0bab9332eeb0aedb1b8791e494ac89f7bae85a1c.nq.gz
│   ├── 0c738421d6a41dc32ab049a68f3d3f781a67b3d2.nq.gz
│   ├── 0c7bedde4c2360c5173d890a131b721a4f49fcbb.nq.gz
│   ├── 0c84aa8d22c0eb757dfdbcf6617ce5524a829ecd.nq.gz
│   ├── 0effc00986183074114f4836b88be533e24f3c30.nq.gz
│   ├── 10e19a0ba64c4e5a96aa87d6992f2378fd7b6bde.nq.gz
│   ├── 122fe0ece43eb995a9de5e52d1181d78c6210f96.nq.gz
│   ├── 1360b541dfa79c0eafcaf8452601466870513153.nq.gz
│   ├── 136a7743ab1fc058767ea49679d49e1d335c6b79.nq.gz
│   ├── 15e68fe035e32aa12bd94cf4c98921dfbd036d82.nq.gz
│   ├── 182f8fdd560845e3af04944593d97a5667286060.nq.gz
│   ├── 1943c03b7fe2d346072b7bf1c8fa1bb2f0184889.nq.gz
│   ├── 19b135cbd2097f1a5ce3b57ea1396f4eeb7f6b91.nq.gz
│   ├── 1ae8663fe9873e265deebb9879274b6504ad1f78.nq.gz
│   ├── 1afdfe0b212100c5a0a105a923bff3c627da3e83.nq.gz
│   ├── 1b3be71e0abcec4db1cc5c1daec8953af886d7d6.nq.gz
│   ├── 1b3f822d1503b05648688789fbcea83040a05228.nq.gz
│   ├── 1db9f1308c571dbf631755b003f16e637ede954a.nq.gz
│   ├── 1dcae62a062b53d9b4de464b02b0060bfbb97ff7.nq.gz
│   ├── 1f86ddaea7b1edb925c2502ea61825d99cd62cab.nq.gz
│   ├── 20bfd858f164446d523f43e5f0aaad5db901fdeb.nq.gz
│   ├── 227bfc4e096a8b3a00190ef42a6407df7acfa722.nq.gz
│   ├── 2791cd00290094e358f495c0aaba53357c34d579.nq.gz
│   ├── 27e2e3e801b0612599d8650fb931d3e4a5e289c2.nq.gz
│   ├── 2938df1a18fbad1bac3f2f7f55709bf815b729fa.nq.gz
│   ├── 2b30043965a95226f6ae8466b213f82bda4b9a94.nq.gz
│   ├── 2bb49ad11f5fccbc01fa428f7a8ae7391ede4388.nq.gz
│   ├── 2da8240717276c8b9b3ed4eaf524bd82d988f319.nq.gz
│   ├── 30dd68e82699c8714e655ba9d1fc314ecb8802c7.nq.gz
│   ├── 30e16ec1d06dde76dfb07a8fbd1cd34c774f2dfb.nq.gz
│   ├── 3133ca9b0124dc1b5ba27ab8a3fffe2bb763d9bd.nq.gz
│   ├── 32b2245590db9df4891c6db988eff19891bd25ac.nq.gz
│   ├── 335414713b36e054f3278ea3897cc3799917415d.nq.gz
│   ├── 35febbec9b624649ec8eceda2574b138b60ebea6.nq.gz
│   ├── 381b97f6acf69ce1fd1e8da7ce9245635caf9e85.nq.gz
│   ├── 3a2b5b5d3ddf630dcb692554c0e017ef68f90473.nq.gz
│   ├── 403707315263cbd91a2acf6af93e4d3351bf7ae1.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 40b8f049b016c90b4f223d8ab35481359d98898c.nq.gz
│   ├── 44cb1052d30992e5b91a9705958e1307322bdff3.nq.gz
│   ├── 4f09ea4476720c8a4dceb2d9763c3a1d4ce0d8b2.nq.gz
│   ├── 4ff5f43176417c4125e13ae5c39bab0060717f28.nq.gz
│   ├── 50239fad01ebbfa8fa939f036c7f39a2a12c3b9e.nq.gz
│   ├── 52c9d90ab2e0e8e9632fd87e25cb0e53f23aa1d5.nq.gz
│   ├── 5340203fffdc770768285bc5bf857257ae6277d7.nq.gz
│   ├── 55049f84285ae96f028415ad6e6c6c30e4c0e26c.nq.gz
│   ├── 55600ad368cc068ba11fc95abd431587192450e6.nq.gz
│   ├── 595918e71de147c77c7c32cbf253b39291515abc.nq.gz
│   ├── 598ef98b505471445ee51dcf659277d7646ea224.nq.gz
│   ├── 59e07c402d6a1185c2f3b7f79b3bfe90f20ba862.nq.gz
│   ├── 5bc0e600e21fa4301786afe770823e70bb1f4821.nq.gz
│   ├── 5ccf84b1c7c2275c97f46884eb88d0ac40b0dea8.nq.gz
│   ├── 5cd3e39ea84667e1635228a0becbdf4b2c95a79c.nq.gz
│   ├── 5dbeea00b73a991c0a2dfe387fd57fffe34f67e6.nq.gz
│   ├── 6013cd9121d65da2109c99b5e4429bb873bb974a.nq.gz
│   ├── 6195ac684071418e9a4d637a2f747257b64d6a99.nq.gz
│   ├── 633f866158ac742cf754a2c43edcb07e3a094f3c.nq.gz
│   ├── 6346f49ea5439efa102ccff7bd991ec5c3a87cb4.nq.gz
│   ├── 6460c8d0c10c4358cc0801d408243e560010b66f.nq.gz
│   ├── 64d471751abb156b2daa7c0254442d1cd02e01be.nq.gz
│   ├── 65b8433794b47fc6a5c2add83b7c1df1ec5142f4.nq.gz
│   ├── 6bf8b32e654f27d365aad09207f8edf73961d6d2.nq.gz
│   ├── 701df228d97e9bf3f2b10c5634107daff2f7bd3d.nq.gz
│   ├── 71dd7096aa8aee9a8773addabd487aafec5a416e.nq.gz
│   ├── 73572c4e401c659577b87a4c406f22f11f2ce3d8.nq.gz
│   ├── 739291ea1ad21dc3fd315ca669314cf8457cacf5.nq.gz
│   ├── 786f24b88ecc338043f62f0dfee92a36e53d4dca.nq.gz
│   ├── 7897e09f91ab210d06a53841f48743430e8bb7c9.nq.gz
│   ├── 7b6297b13f9bd9f3129117e0ae13337f4ae6d99a.nq.gz
│   ├── 7c02a193e71df1db120dcf7707913e0e2d002fea.nq.gz
│   ├── 7c616e1b1d85bb002e97cfa5a2808d6c87f6dc05.nq.gz
│   ├── 7c76360e48831508541d4b0bf2c1e379b8887449.nq.gz
│   ├── 7dd4561e1ce18b3b5551723ec0d0f456cc42a358.nq.gz
│   ├── 7efc0515be6feda2843f517409dc3f99cff0c853.nq.gz
│   ├── 812d44d1dbf8efc05b95053662808d2b3963afa5.nq.gz
│   ├── 81410d22ad8f4099e0dd5d8e7853afe5b29ff355.nq.gz
│   ├── 85726e34150b96a53f23de3ce50090a7d81c9582.nq.gz
│   ├── 862e1fb0d02e2277940beaa255c3c54641167629.nq.gz
│   ├── 8892c60368aee5b89f85961818b7582142d36af4.nq.gz
│   ├── 892e890d36799151ebcd9450ae8c8b6c7172db78.nq.gz
│   ├── 91046dd36736fe547aad10924aba4a25eb7270c4.nq.gz
│   ├── 911ba33f5f7199a5d440cced45f1d267004e5393.nq.gz
│   ├── 955760a8dc08d2ca320f2f72ba81960c115fc217.nq.gz
│   ├── 97a71366786b4f3e923f087cf7be1a534ee03587.nq.gz
│   ├── 98d3669f34a5c49e22a9b360ec04d4be2d8987c8.nq.gz
│   ├── 99d16e91bd744152ea7ca15179c4fcba41193e49.nq.gz
│   ├── 9c3311439187094996488aea21ad2258034857c5.nq.gz
│   ├── 9e278f094d12fbd80c1dbe533e1583b8e1852ff5.nq.gz
│   ├── 9e837dd4caefc1a0ce3737f3216361a86920de0a.nq.gz
│   ├── 9f0f8a84d6610ac7259ac0c0937e638d46a2b498.nq.gz
│   ├── 9ff7a889c1c6765b34ed7c785e67f1fc4ef1f91c.nq.gz
│   ├── a0556a9d694dc395aa7b2a6f06de20a7adfee9bc.nq.gz
│   ├── a08ba811fe45d22cdb256a1faae689fc0bf1764e.nq.gz
│   ├── a306beee0b6f972868a580339588b20d261a3b07.nq.gz
│   ├── a5856db18f63e028b79ff25267371aa85a883488.nq.gz
│   ├── a61ca0fbcde7e8768103cf6528cb1471d5f29a20.nq.gz
│   ├── a923fa84b85a76871be7d11aeacbd74453b09508.nq.gz
│   ├── a9a7a639e6a81b8658c7d9c286c2170a297e1862.nq.gz
│   ├── ab37bfce9a203a99c5f601f6d13c6c6d64adb07c.nq.gz
│   ├── ab7d32f040c74c7049e7ee3db850c093111f3378.nq.gz
│   ├── adccc305354bb15b8fc2ef9d66659e7885b1dad7.nq.gz
│   ├── ae958d67384909ec32ff2376c54c38caa679b29c.nq.gz
│   ├── aece5f6d2aa689ab152a6e6f8b3b694e300232cd.nq.gz
│   ├── aee3493f4f522ba090346e921ef87c4a5236edd9.nq.gz
│   ├── b0f0e4f081b6e48aaaae603e00bdb350a14567ee.nq.gz
│   ├── b1d2782dd987e7602b8ca0d2c91680b3149a70f6.nq.gz
│   ├── b64b6f2876065fc7b11218df2d0062b25fd5c46f.nq.gz
│   ├── b6c9229fba9bd621be68635acb887cdae6c2be3c.nq.gz
│   ├── b916d5532ee7d9cae97291cd8ac73f9fb7ff1868.nq.gz
│   ├── bb4d43d09be556a8d6403c32a3ca90eaa4cc1d7a.nq.gz
│   ├── bcd5aac4554843fba3d454995477568a9551d84d.nq.gz
│   ├── be16b66d9db46be51b41128db18104c22cb0809b.nq.gz
│   ├── bf43d16f7c3ba365dc8b747d2311af26c4c52d5d.nq.gz
│   ├── c0c648492458a2cba6c380a937134f2a7a87c1e8.nq.gz
│   ├── c16ab609ef003fff9497cac9524efd8d8cf2af38.nq.gz
│   ├── c39554dcec1697b15f55de90a5418a5cbaffe35f.nq.gz
│   ├── c3a26ff6f9f2be1e105dba632d2d6a6cd237c0d9.nq.gz
│   ├── c8581c5d1f423e8aa61835b8ec1def7c600b6dd4.nq.gz
│   ├── c869c611330ebe3571566f869ef91f4edd64c0d7.nq.gz
│   ├── c8dbf1196fe1e9aeccc348d4c21384aaf5b3e9d8.nq.gz
│   ├── caa8801073bd947e3d34a05d3353eaaa45b07bc8.nq.gz
│   ├── cc0749b9990d8865980269ef5b331d00740448bd.nq.gz
│   ├── ce22205d0e1bbdcf0d92f007b8f85c583e016eed.nq.gz
│   ├── ce347a0cc4fa42965a81eef50f75318a5e2fa60a.nq.gz
│   ├── ce8e967b556302121b4a1b2f80155f6d176c2282.nq.gz
│   ├── d01d60498272fec7fd9e49149f63a4f9b61b1794.nq.gz
│   ├── d0ad4f7a01493740e33c85607bf796882d20353a.nq.gz
│   ├── d2532e7239981d5d41f256eeb19d0a188c55b16e.nq.gz
│   ├── d58494010d8a05c6b81497911f5a7099cd1eda16.nq.gz
│   ├── d64fecebdb23901bfeb6e3bf9a6abc1dbb360f3f.nq.gz
│   ├── d6eda742afe39b40443b7089eca190f2534d5abb.nq.gz
│   ├── d7b5107a639c29cc6879ee18cc900d89a3d0475c.nq.gz
│   ├── d896940fd9910d562500d71b3df8831ac81e16bb.nq.gz
│   ├── d89b36b3db56a5ffe284654246ba84827fb564c8.nq.gz
│   ├── d9329b90e1fbac6360e55d1002b8fb8560da082b.nq.gz
│   ├── d98370da7ce15d4df699b9623cb3a8f944eb314a.nq.gz
│   ├── dc04fb10cbe2cac44c31bdbfcc2a73ae5182042f.nq.gz
│   ├── e024a411845bbcce0ec359ea75376ca37297e493.nq.gz
│   ├── e056bb569595aa2a38dadb3479752b155c170b0b.nq.gz
│   ├── e18e09de260557cb2f29b8b3c9eb0aeb49740501.nq.gz
│   ├── e36ce16eccaa07c03254211f3bc014a4cf717e24.nq.gz
│   ├── e439ff2ee18066ae3d6baaa2493b6f21e20d4219.nq.gz
│   ├── e52dbf4b1b39c728b3b6b3ea0ad07b26264cefbd.nq.gz
│   ├── e8cbd40afd97173dfbf1fcfe8a8d806774499b2e.nq.gz
│   ├── e94f21267f3edf3801439fdfca75225ec0db8664.nq.gz
│   ├── ec05da93c6edc6c0fcea78387d5983314013203e.nq.gz
│   ├── ed9f69ea0f59e7bbaf9b011499d694ef1ac4d2f3.nq.gz
│   ├── ef15d0faaf61e602b5394094892469523c4e1408.nq.gz
│   ├── f0249ba414ef75bad066383f8c136a9329eae720.nq.gz
│   ├── f1332dbbfba91a76f75f63a961d34d9b22c91849.nq.gz
│   ├── f13ae01d185b93bf939af0e98c8bed656e40ab25.nq.gz
│   ├── f2dd7e7a7aff8ffc219e7d3fc085e649130363b9.nq.gz
│   ├── f31322f5b6313e3887d2d24acbfcfc7a9c0849ae.nq.gz
│   ├── f432b8c4504108471bae34574fac7c136d36cdc6.nq.gz
│   ├── f50b51a8595bc0b0f2774cdb3e9ad530d9b51df9.nq.gz
│   ├── f62d2392f3087097db2fcbba982ef0819b51a6f6.nq.gz
│   ├── f6499c6a73efb5402b9dea32c8871e57016ed534.nq.gz
│   ├── f70fcec201aadc2ae8017ed9ede79957d301a8d7.nq.gz
│   ├── fae4907e2f242dac3a634a217c34a4fe1492e2ed.nq.gz
│   └── fb2f8e05d6470c78323685e13847b4279334c659.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0638b688d5fd0c1a46b7471dd465eeb4c2f84666.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 172 files
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

[sdispater/eloquent](https://github.com/sdispater/eloquent)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
