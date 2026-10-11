# Repolex Knowledge Graph of pallets-eco/flask-docs-translations

RDF knowledge graph data for [pallets-eco/flask-docs-translations](https://github.com/pallets-eco/flask-docs-translations), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-docs-translations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 71e4a78866f66fab9737b9c4c9d1108a71a74ee3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 71e4a78866f66fab9737b9c4c9d1108a71a74ee3
│           └── chunk-001.nq.gz
└── blob
    ├── 002476ce4eb520203348309abc3c5caf9da19e17.nq.gz
    ├── 0049c8f96d8329d80a9276230cc061585191ee64.nq.gz
    ├── 008b94db85791729cc25bd407b74f80353720474.nq.gz
    ├── 012d596e5e39c120fd89d418d59bc9c40b8572f5.nq.gz
    ├── 017869a37455ca709b06de729cd0bc521703b8e8.nq.gz
    ├── 01f6b62abe6f820e82d1edad71a87f4dd6e4611e.nq.gz
    ├── 04b56c2673a00b03caaf23beb10496c9c0f588f6.nq.gz
    ├── 0588eaed70a0c9f774c1ff1fcba1537b9ed6d316.nq.gz
    ├── 05fb265756ca578ffe4589a7ccbe4027e16095ba.nq.gz
    ├── 062a3dcc7896cdda5f847f4942dad73b7e97a74d.nq.gz
    ├── 068556ea90d7ecdeb6c210f54a89c54e09625486.nq.gz
    ├── 0810254dcfb36a6f945c06f60b03e3f210f4c4a3.nq.gz
    ├── 08245ddd780196d7991277c6449aa4ba3e288d08.nq.gz
    ├── 08dac7fb4c62c9f79acea37518851cb1d635d135.nq.gz
    ├── 09d3072ad8625f5c5505925f9c131180231159d9.nq.gz
    ├── 0a239fe44b1da65a1fd5a82bae1926b092d20808.nq.gz
    ├── 0a4aed14a4fe712568a0eb440d3e5f07d281f6e2.nq.gz
    ├── 0a9e786f9fbb0fbef5564ab8f5db103d6ac1eebd.nq.gz
    ├── 0b427d5c4f4f7552370313c11ef5600f52b404f7.nq.gz
    ├── 0b484364e8083ae525f542d19b1dfbf63348e49c.nq.gz
    ├── 0bc6c8db8c1f7a22340a7152716f32b182567c47.nq.gz
    ├── 0c093205b3a0804584b37d6e609ecff110e20d15.nq.gz
    ├── 0c5410db1e432f9431d7fff26d4c4e8eabc64bc5.nq.gz
    ├── 0cd7b8e42e3dbc09c478d1865e4288c3d6b39a1b.nq.gz
    ├── 0d1fd6f08912e63fcffe28677f09579cd5b1ef6a.nq.gz
    ├── 0e0b9b092f5d469ff38c40db920924b5dbded6d6.nq.gz
    ├── 0e3345a82802bbd3b91db5eb9e6edf3893aa3015.nq.gz
    ├── 0e40266e1c5ee4c1340b83f09ae04eca9b4b08f2.nq.gz
    ├── 0f2925c4955bf75d3db4d00e95fff802bcc82abb.nq.gz
    ├── 104827c4f67f63c6a3d01a2ebc837c6fdd4db9e6.nq.gz
    ├── 10617eadd00a3ac6872f74abe33aef10297929e8.nq.gz
    ├── 108aa43b6f42b7439a653157406970c04383ed5e.nq.gz
    ├── 10c37fc903d4e7268da3f595ab9ca70e191b7977.nq.gz
    ├── 10d1fb8862baf061416355bf2a5aef99114e7fce.nq.gz
    ├── 11dbb687c4477a6afb1709273756644aa34f2742.nq.gz
    ├── 11fcb5587c3c8a383c3c7b1d9b21a40e228d41ed.nq.gz
    ├── 123be9448b38aa6cb959b71e2a0cd3487c94fbdc.nq.gz
    ├── 12571edf2616fcb8ac32388f9499e1efcb2e3bf7.nq.gz
    ├── 13d358938dea890e6b65de0856db56152514cc90.nq.gz
    ├── 13ebb4232075c127cfe6f4167e51d274533158bf.nq.gz
    ├── 148ca4e5ab2011d122368af18559854e7ae4d36a.nq.gz
    ├── 15e695c7bff25e8fb21f39c786e682d2abc528ac.nq.gz
    ├── 1609b602572e175de18a99e679d84e887cb1da21.nq.gz
    ├── 168fec0e3b9609f327ab89136ac6a44189c74835.nq.gz
    ├── 169e45a84efc27c1667237bd8d0234de68379027.nq.gz
    ├── 16f56488d6957056139a95979988b39f615aa4a0.nq.gz
    ├── 170f597bb9e8b8455a8e61ee4d70948494d30e83.nq.gz
    ├── 1724de34b1236849c5eaf0f86f186c821a3f7055.nq.gz
    ├── 179cd37bbb8dcdec48e863ed7c6e724c782a77b2.nq.gz
    ├── 17d7b55cbc1f3ce5315f97324c91839c0a867dd1.nq.gz
    ├── 18ac6f385b073f08a2ece85238f288a4dbec8689.nq.gz
    ├── 1984b6047f376f3348e8503e37e37753b7e2dde1.nq.gz
    ├── 19bbeaf41a467f88f71e626d103df6ead71143b6.nq.gz
    ├── 19ebccac2987ed96ff7b569812c276e663f4bfb9.nq.gz
    ├── 1a08a4079fc69f26dca3f0f244306deeda50edd0.nq.gz
    ├── 1a75bb5d8db8ef995f06cad4a441c3533e28db13.nq.gz
    ├── 1b0971339d4bdd3d75359f906d0142533a8a7e21.nq.gz
    ├── 1ba5bf3732c39135e31a0b16dde328144906f5a5.nq.gz
    ├── 1ed7a63d060ae03195ea78603f8baad269ed5d0a.nq.gz
    ├── 1f147666ebadc9d361e7cea15c5a89f7a0f3cee7.nq.gz
    ├── 1f7f80c03067b4f90a26b56bcaa8fbc8c6e7ca40.nq.gz
    ├── 204fb3f1224811beb28e85a5a9e71ecdba76d24c.nq.gz
    ├── 207759ccf46506438720b2c29f04eb790ea0c02e.nq.gz
    ├── 20a47a0b1e9052ca4bf5c4542b4b573511f1a59f.nq.gz
    ├── 22959bf1635d13a637ff4f3ddbb7989d2b72b595.nq.gz
    ├── 2306bcb6184eb28bcbe7454cfb629e8c6a8bb1ea.nq.gz
    ├── 249600b1c2f0d66342c000cdda3302ff264177fc.nq.gz
    ├── 255e3f818a99b78ed0fbf4ad2e2187409ff1351f.nq.gz
    ├── 257669fd0d431a95061979d12dbf50d1f303c37a.nq.gz
    ├── 27844c4be5e992421f7a3ad621da942fa4e6cdc8.nq.gz
    ├── 27b11a0909f9f5c7e5233958cd2901b24699ee89.nq.gz
    ├── 281f1d30c4f55e4adf50ae5b358ab7266d9b9f59.nq.gz
    ├── 2863aee67cd9003a5bbec85750fcb488bf22bc03.nq.gz
    ├── 297ab1ba2ebf363e6a7b64af5fd0175c4491c233.nq.gz
    ├── 29be0b9011092005ca69f311f2233b86cde7a077.nq.gz
    ├── 29f560fcf3efce09ca1ace35cfd0dff577ef0c8e.nq.gz
    ├── 2a638abb0efabd14d4cec1ce83240def507dcfbc.nq.gz
    ├── 2b7d406e9f1a7ec37124c2db415779a7d7931140.nq.gz
    ├── 2ba1ea5cac8258ddbd07b5c263c4ae4f1c7cd712.nq.gz
    ├── 2bb66e617350360a4ac941a60af02f60c62fb98a.nq.gz
    ├── 2befd939dde768111e2b4bc68c6eb5a9c100377a.nq.gz
    ├── 2c3a80e29fa71ce41225dcd4ebb68b1da6358a00.nq.gz
    ├── 2e443f37ec1dd9f37acd0ad3bfb3e27f584f8044.nq.gz
    ├── 2f185f97d1d6be5561866b3c5423b597c8af8a2f.nq.gz
    ├── 2fc0f0c3b106d321a8cde12ad694db7362ec6834.nq.gz
    ├── 305153d1edeb95ff21e3101eab795371305f3f36.nq.gz
    ├── 310653408f8a38866cb69ea7dad0cc92828a8d66.nq.gz
    ├── 31bbdc230d7d76e6b9624bf67192016d7d1e9908.nq.gz
    ├── 31c9e774f783d6a52a4f6e64bcd50f59b21c54c3.nq.gz
    ├── 31ed8cd205bca0d444247e5620f727ac701e6dd2.nq.gz
    ├── 320653921842f2752f1b5970eaac3e42b4008049.nq.gz
    ├── 323d76583d6a7c47301c65a0065653fdc0e0ad00.nq.gz
    ├── 327116784fc146f337117adc5a38f2b5aaef7edb.nq.gz
    ├── 34075982d38ce894964d363319e51dbcb6805de5.nq.gz
    ├── 35a1773eb5fe21a54ba62853c67e9e79b50dcb5b.nq.gz
    ├── 35b293402dc7374715ace1a93371fa462bf6f11d.nq.gz
    ├── 372b4a62e96bf57264c4af17539809fa263c52dd.nq.gz
    ├── 37810c5f5aad24d672ac3b8d9d015b55e4bddc21.nq.gz
    ├── 37c039ffeb97258e47763439d4b2c0286d7a54d0.nq.gz
    ├── 37f082c57c1e9e2a6ea879a6f857487d560a265a.nq.gz
    ├── 37f20a6deb1a4aa197cf2826fbe9f03cde36a8fa.nq.gz
    ├── 380729a75a31175332b049d57525eee0efd64d8b.nq.gz
    ├── 38a01d49a8c2b498bd2b6692d6fda05a3ea2e57b.nq.gz
    ├── 38d3b3a7ff025b552aa509a9e2caa62d8b169a65.nq.gz
    ├── 396e61d99bfc361ddd97dbe127e4ba15799b0248.nq.gz
    ├── 3976475a2ae38c7d1e92d0b7aef3c79da956cd11.nq.gz
    ├── 39897aebcb6ecaeef347b24f61c7d960e1682022.nq.gz
    ├── 399e369b423a4a563ffe182302faaa078a7ee907.nq.gz
    ├── 39f297bd7a04e29eb6556e2a65eb76a589ba4aec.nq.gz
    ├── 3a3067a7d6cbde53022c7e95b5b1ea991e50888d.nq.gz
    ├── 3a4c9f3a1dab6a6e7b9b2234e097bb8391bdb24e.nq.gz
    ├── 3a6a4089f9f9405ecfdc82bc0da2b5f1668c689c.nq.gz
    ├── 3bb40370079a1d161571d32957ad5e8f7888a93e.nq.gz
    ├── 3bd6480680f1ff830ee9567c12d3c84523c6d6fb.nq.gz
    ├── 3c823fd684ddfa92c358cf7a80a083ac5e147ca9.nq.gz
    ├── 3d09d367fe31fd53f85a46d0be65928133e571a7.nq.gz
    ├── 3e14f2ead5e333425484c94fd06c8ca05e064f54.nq.gz
    ├── 3f80143bdeaff99a5ca0d28bcc129bc1acc99649.nq.gz
    ├── 4001b5ba665962eb93448104b038f2bae061a898.nq.gz
    ├── 4015686a83d25428596b43f26c12653f8e8dfe7a.nq.gz
    ├── 40290ebab8059d3d53e338945b423dba43358f87.nq.gz
    ├── 4035ca26c34d736eb5dfdeef8981fad8647d2c01.nq.gz
    ├── 4097d04bbdc269076469814249efc34f8c330bc6.nq.gz
    ├── 418818980d75ba381199f51ba0f7e27d5c71c192.nq.gz
    ├── 444ce0df98cdb0d2d9ff709fd52e1abaa6d8a93a.nq.gz
    ├── 44681619968c156fe8ae9e08dc122d33f9372ae9.nq.gz
    ├── 44d70525489d78d3f9f3c72d943253178895f8aa.nq.gz
    ├── 44de62f70fc8475941f840120c6cc4a1336c5110.nq.gz
    ├── 4529f1a1de418cfabc47a06131616a8bd6917289.nq.gz
    ├── 454864af6bd71f037108d0c44ea4f44c1041276f.nq.gz
    ├── 456815ca7dea4102364fd5a4936e8c5ce811006e.nq.gz
    ├── 4658731128b3cc53a23c447e82f321df21c7a0ad.nq.gz
    ├── 46ef3acceec012f23704e49c43ab964ef1617eb3.nq.gz
    ├── 46f02082cde4bea3cb138853707887a351b82d41.nq.gz
    ├── 46f221407723485252b6eff9000f67d141b1f7c3.nq.gz
    ├── 48e82f80716ae54a25c6f99585c1ab97deb5259c.nq.gz
    ├── 4b3095f3a8746647a18a87389c3b0465e2556685.nq.gz
    ├── 4bf1a1890a0a7f5603ede272f6d4eef3240954fd.nq.gz
    ├── 4c1979501865f828839c72990a7c638b639ace68.nq.gz
    ├── 4d648aa42f68c5d046c53f5c562c80ec8faaf5e1.nq.gz
    ├── 4d73840db5db7d9998454c50a08555c8e8fca76a.nq.gz
    ├── 4da9f31d2d425f0fc6547617bfb2cc08f6172b4d.nq.gz
    ├── 4db3ba73984c288327fbbf306bbadc4104e483a9.nq.gz
    ├── 4f8142f54fea3ea2b6a9e687028c18ea6ee54df0.nq.gz
    ├── 501eb25e5494d7e7f4678d68c15cf7d818d0f800.nq.gz
    ├── 5044578d9baba9ba25a1d13d537c0e4e53d20f3e.nq.gz
    ├── 504cd2f1aead81c9b148aff9b13871ce2ccb7ba2.nq.gz
    ├── 506f11f52363a37e74643db6249752dfc93c51dd.nq.gz
    ├── 5100875bdbdca40ff471be19987400a5ee6ffe93.nq.gz
    ├── 512953ff0aedb67e0bc5858acf5e411badf34746.nq.gz
    ├── 51e5a1c8754f35d538162a8be898294bb1d4b3df.nq.gz
    ├── 52f4f94a1bbba3159093e2337fee5d1baaf3fa3d.nq.gz
    ├── 53176223947bda27dda910662e44b9f306e645b6.nq.gz
    ├── 53b7457ea830c828396e4ded3eae811b5b012259.nq.gz
    ├── 53e5158e06b15b67b5c769647635e03fbabfebaf.nq.gz
    ├── 541aae9aae56e8826c764a9174aa4a15d50c706b.nq.gz
    ├── 541dcca145ad56cc8bbae8a9166bad008a648240.nq.gz
    ├── 542ac51eea7cb787fcca64a6474523757698fe9c.nq.gz
    ├── 547961445b272a3b1323afd7048879fdbcc3dff1.nq.gz
    ├── 551c23f0d22274b61e8b9c9c27450cf7998da950.nq.gz
    ├── 556ab29eb532e68ec1534ca886f5d8b51f7e96b4.nq.gz
    ├── 55c89866278db835c4d1427e2758f92baa211222.nq.gz
    ├── 564278d98e976e4b7797f4d8d962ecd39bad720b.nq.gz
    ├── 56707648a6356e47f7a2ffeac6895651034acdf3.nq.gz
    ├── 570272e45605a596850da210b7fc5d99865e6dc5.nq.gz
    ├── 57facb9452c3c640322a3a1aaa0d2574f298f324.nq.gz
    ├── 585c0fa81c6f51cceccde163764fdf3c8346790a.nq.gz
    ├── 586b430e0ebbc73d3eb04064977311637a533123.nq.gz
    ├── 596babf74cce83949786779897e407699c539f25.nq.gz
    ├── 5a4e1e4f2d18bf38e70f48fdb9a229e7ff39f6af.nq.gz
    ├── 5a73a43aea05921206bfeb685e45d5694f3892b5.nq.gz
    ├── 5b0be073fe38672f5b51d4691bfb2c4389b4e06f.nq.gz
    ├── 5b2bd3ce2ab0254b884adb535e05dd3107853fb3.nq.gz
    ├── 5bae44b71ee067c525b437ac43f25b63eb694d45.nq.gz
    ├── 5c011bdd0320f9aa6d987c1931d672d061492818.nq.gz
    ├── 5c7949ab6e9c43566358c86d6c642d4656af431b.nq.gz
    ├── 5d1a308b889e8dfb9f033db61f2f01d9d8d9c8f6.nq.gz
    ├── 5d5e4bed50e41f0e594b3a59097d1cf92d965ddc.nq.gz
    ├── 5d7f7c649761f50c8fdd399cd65689d64357c45b.nq.gz
    ├── 5d9d261aa88aa627e47ac6893a20ee0eab4d10db.nq.gz
    ├── 5f068983f93ec7631572f33424194000ddfac831.nq.gz
    ├── 5fbfeedf8764351753b3bb60b8a86c28e3af6b6f.nq.gz
    ├── 602c66b23c61160dcc012de801761ea28a45c4c5.nq.gz
    ├── 612bac2d836eedfe23466e60bbb24e73c47731d8.nq.gz
    ├── 618945e47799ccfaa50802fa16ffef43b98a3ff9.nq.gz
    ├── 620c610d93d62c900272806ceb7ef1471bda621a.nq.gz
    ├── 62b6d2cc7d6ee46054307d7ca168f80eb04173a8.nq.gz
    ├── 63064feaf2c9503df45ec8caa11ec17020f3c74a.nq.gz
    ├── 638b2de22e62786b9743a1f7f83f7f7885845b31.nq.gz
    ├── 63f0d6e4f5dc051de54dd4076d468fb55c47f50c.nq.gz
    ├── 6406f46ad9244cdfd1b5876ff7caa4401c5d507f.nq.gz
    ├── 64ddf1057c8bffa4895f92f8b3c7588f0bb11d35.nq.gz
    ├── 65e9a0995f7287d5915f533294e2b3da440cb989.nq.gz
    ├── 65f77f30d131c53fbd1e8db39fbce7969563d4da.nq.gz
    ├── 662fa484b03c32fb0267667f69285eb1252d10eb.nq.gz
    ├── 66b8f4f1b3364a7d33b6b6a20db84829095aa4d5.nq.gz
    ├── 671595bb91a9615eb73d11ea26994ef5c42a3c54.nq.gz
    └── 6761c39c9358bf1e32d7f002505e8b652568f96c.nq.gz

7 directories, 200 files
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

[pallets-eco/flask-docs-translations](https://github.com/pallets-eco/flask-docs-translations)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
