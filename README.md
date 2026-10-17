# Repolex Knowledge Graph of neo4j/neo4j-python-driver

RDF knowledge graph data for [neo4j/neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver), parsed by [repolex](https://repolex.ai).

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
rlex download neo4j/neo4j-python-driver
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9755761235bb61be44bc871b0067495b763281fd
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9755761235bb61be44bc871b0067495b763281fd
│           └── chunk-001.nq.gz
└── blob
    ├── 0030dda826188daa43f5ef3d8e180b2546075dba.nq.gz
    ├── 006df1cb5e74a9f2c91f24ac2077a6e98b206ab2.nq.gz
    ├── 0101fd2a023f24227acf92c1d23e1f64d9701686.nq.gz
    ├── 01b027d49323eae804ff9cd8efdc327272e60c14.nq.gz
    ├── 01fc27072369b6101a0069145075e5112cf0321a.nq.gz
    ├── 0207532a563ba288176877f5f0143f3e6151cb4c.nq.gz
    ├── 0230ead2044642a8edbb707dc3d73c08d62aa3e2.nq.gz
    ├── 02c5a3bc012698003b751aee9c98fbdcbfd9fdf1.nq.gz
    ├── 02d9b373b796ef4bffc64931e7a71dd0e20e0724.nq.gz
    ├── 031c477ae8ddcea2ed294539c9f4ec21ee0e55b9.nq.gz
    ├── 033742adc277915d05906db5bb90a025990bb356.nq.gz
    ├── 0377ea9139929fbcf535ad0b994a9245c4d4a651.nq.gz
    ├── 056b212bb6e78e53116390275d8462f2401fd245.nq.gz
    ├── 062fb99adfcc8f42be3fa69a7db9ca044a837aca.nq.gz
    ├── 077760321f68b927b28fa1b0efafd384f1bde10d.nq.gz
    ├── 07fbe85c365a650a9a3c89240e14784d8da79614.nq.gz
    ├── 0800771968a6efe423a0ea8a7c17d64b1b235c83.nq.gz
    ├── 081c5d79e57159c1fc9847a36f8ee5080efb115b.nq.gz
    ├── 08658a3508afa481d93bcbab0023e9e171ac1648.nq.gz
    ├── 091a6736a78adb81ac2e3213760f59681c725eae.nq.gz
    ├── 0a32800ba1eaf6dfa0ab32e1385b1af57e23b051.nq.gz
    ├── 0a395ec48ffcbdc480f4784b7e555e3c5de646a3.nq.gz
    ├── 0a4ede9550484abacbd094f2fb55e61847fa8f3b.nq.gz
    ├── 0b6f1e68c3f73689b006ae63c473587e9e77a714.nq.gz
    ├── 0b994410854d1645a209e4b8d981206dc12cdd74.nq.gz
    ├── 0c6ccf4798b026f8ccd7393969656cc057bd4b63.nq.gz
    ├── 0c7d6836e2b31965f3d4ca5f51c029d5fd53b29e.nq.gz
    ├── 0c966d074fdc2903d19880e8f74f4f1fe47d4b5e.nq.gz
    ├── 0d08a73237585ab7c653941efae8297fd3330761.nq.gz
    ├── 0d7d7f3375a256e2ae38875d9bcd1b82252154b6.nq.gz
    ├── 0f954f75a831f5f9b63dfe6417eb5f6f97c5d2de.nq.gz
    ├── 0fbd8fb89b2d4a7db89e954fdc1cfc1ef1264b62.nq.gz
    ├── 0fc196e7544f5c0cddb4f6f5a8d594e129d21580.nq.gz
    ├── 1066986a559362124b5407e395afeac3d00016a6.nq.gz
    ├── 108106e14e3e6b892aa688e523629a2f44293741.nq.gz
    ├── 1177c93109277ecec23717cc62613d7d6896a386.nq.gz
    ├── 1235466cdb600e9d768ed0b3d679b020da422132.nq.gz
    ├── 141238e74b8c5849a05d8fac04e49d0e540b28cc.nq.gz
    ├── 1414e1f9ab8c757664192c255cf7e52e7d2973ab.nq.gz
    ├── 150922a8d6c46f5f0bf0b96779ee87c7a769567d.nq.gz
    ├── 1509e519dac7864cc4a2031241a212ea5c76d56c.nq.gz
    ├── 156ba057e9b5fb06e851bb2f756cd4f0e1892898.nq.gz
    ├── 158bf263a2880a3e5151b878c499c8bd8ac048a6.nq.gz
    ├── 15e1f18d7f47cc7308b28e743997b47299395f07.nq.gz
    ├── 15f3711357923773d07495b0e522b7cc7aec97bc.nq.gz
    ├── 1627389445f9eb5b7b4a50f6aefe83072d83e6c3.nq.gz
    ├── 16e5eda4f9b61f0495cc752e6a78627010b23a9b.nq.gz
    ├── 177a063529f8fe0366d1eeda28772d90a1d0ff3c.nq.gz
    ├── 17bb3495e6ea5334a74fa6cd94f84adbd7eb8fcc.nq.gz
    ├── 1870e6c3fb9fef2252486c939c294b9f623e4a40.nq.gz
    ├── 19550951deed9361d4adb5bf3ff70093b39d7b60.nq.gz
    ├── 197840daeac189221b613777a30d3b9acea8c4ba.nq.gz
    ├── 1a14187c1016231c07fdf3123be546c78ae25676.nq.gz
    ├── 1a7cb644f50ef9f34e7665219248e78441636f00.nq.gz
    ├── 1bb4d030cee96f80938b371a27e609921a130a3d.nq.gz
    ├── 1bc069807c70d9d3568835eec0c111d263d1140c.nq.gz
    ├── 1c52d726c9d9ad5728fdee882aa77ba571116de7.nq.gz
    ├── 1dee1edd99f0e067ffe65b5d766c85b7d165ee76.nq.gz
    ├── 1e4aa012f821343ba9ac22db0fcc35710a85b56a.nq.gz
    ├── 1e637e292d962b6cd59edc6d87895f98fcbd8ba9.nq.gz
    ├── 1f464be72381561a055be012fc1d304022922ba1.nq.gz
    ├── 20ee027f344b4baedca3ea5931c3af2cce887306.nq.gz
    ├── 21d0b898ff61470da684cc5e8f7d6efa648de8cf.nq.gz
    ├── 222a450ca34bf65acee9ef48c8886b5aa2327a76.nq.gz
    ├── 22bac7bf3bab21c29e0f22d0f65d020629b6df20.nq.gz
    ├── 2307f93ca103d2359d8d17398e21c43c206876da.nq.gz
    ├── 233e24cc621bfec292b7409fcd51c94ca185401a.nq.gz
    ├── 238cf2d94ee8bc7478cc0659e5ae25f02a5f7730.nq.gz
    ├── 23a9b3d0d182584f303b04aa00bfa06f60be86b1.nq.gz
    ├── 23b20e336866737fa55decb3bf39feec66fb8343.nq.gz
    ├── 247b45aab33f8786a77c242a7fc9ed50a4574f08.nq.gz
    ├── 2482690f8f7a3c2dda9b272d225b98c9851724bc.nq.gz
    ├── 27a20bf4b0b28bef105f67c2ed0052301c788092.nq.gz
    ├── 27cf2845037eb26203fe73a064f44387a58bdf7a.nq.gz
    ├── 27d26d2801a998ceb1d9d59466db286760463780.nq.gz
    ├── 2805fb8838a59e8e4b263c1667fc59db50e84311.nq.gz
    ├── 282b5fb1c3ecf594ac2fd339621c018e1336e004.nq.gz
    ├── 285a8ae1652e9d08ca9923b87d536392cc1cd236.nq.gz
    ├── 28d8081335d19b000f3522b5ba5387a4aeac000b.nq.gz
    ├── 28ebf2eb50c8724c67ff81652fb97ea198a7df9e.nq.gz
    ├── 29a1a51e83e99da2de61ffe5cf73edcf83d2f6f6.nq.gz
    ├── 2a0bfaf7a43080efdbb8cece4850e7cd38af1766.nq.gz
    ├── 2b71e89f855ad14a989646f754ea6a59ca42e738.nq.gz
    ├── 2bf2a361e3f35a00922d7a80964a3c627ed845fa.nq.gz
    ├── 2c43cc52b87189f11dcd0002522f7f285700fca6.nq.gz
    ├── 2c4e42b9c25abd0b86d327f095e32c0d3f08e133.nq.gz
    ├── 2c701fb9e7680b329c18151f429b6c9cfcf8f3eb.nq.gz
    ├── 2d13a85fd699abbfbec8490912f41f14fa18f85d.nq.gz
    ├── 2d300e3a9ebe0ca28770af3a9941d56ee5dd4de9.nq.gz
    ├── 2dde426b90e4257b6d873edb459ce154d8471146.nq.gz
    ├── 2e07cf30b1a640de82c66b59368bbcbc8e217319.nq.gz
    ├── 2e5b347b6ea2db70b72b2270ff266ef4abd2f3b6.nq.gz
    ├── 2ec90061656f3a1463d2ec6585487799f54e547d.nq.gz
    ├── 2f0cb8fc8a490f5984da887ac98cf6ea3f86f859.nq.gz
    ├── 304942635229010133d849b366bdbb4223531630.nq.gz
    ├── 30890bda2d14c9e90c4e6ddf6409b31a34bf22d6.nq.gz
    ├── 31dc3153f201ed868d27f070d10e7e57b0ba630d.nq.gz
    ├── 328071122b8ef3f9ad79c3bc373a95f65e9f4117.nq.gz
    ├── 33036e9997e43aa682bd8f442a1ee10507c72702.nq.gz
    ├── 3371ec338b2af6114e605d0e98a60d456feb5331.nq.gz
    ├── 33ceacbffaec0ae1142a7a5672e5d1340560ea09.nq.gz
    ├── 3424886edfe0ec7c460ca9a59c86ccb114282df0.nq.gz
    ├── 348a8fbbff0c9f26b6b54b8f3288a1f16503f3b4.nq.gz
    ├── 352d2278d83e83ff7e73d43a034f2d28413ba8b6.nq.gz
    ├── 35b80d698ee382226b6dec335bbb54ac72ee0ca6.nq.gz
    ├── 35ca233f0c6ddf0f8d8ce546f81bf61cadfc86e9.nq.gz
    ├── 35dc3fdcc5137bbd70a5087a5bee11b3f2b9e930.nq.gz
    ├── 35f246da71b8dde0d9e13116f3f1be631c632269.nq.gz
    ├── 364e5dfc78427071a5af8e33cf57366ec4320b14.nq.gz
    ├── 3727fb64456708f93131ecf345ffd95b33e6fbf7.nq.gz
    ├── 373599e3689eefc64d079f1cf72bac0bc508300b.nq.gz
    ├── 3740b431638acdab437eddc876e838fd7f20fbd6.nq.gz
    ├── 37b90ad56d201420fb6d5b502a9b8bdfe5997bc2.nq.gz
    ├── 37f18a7eb338144cf01c9282ad2c5180dd9f2a8c.nq.gz
    ├── 381927604b2643e4ba2769b568cfc857ea786ca9.nq.gz
    ├── 381d41fb6b7dd8cf9c5042c955f4438b2b20c031.nq.gz
    ├── 39bf61482acda9444d3f26a59f57878c64df1825.nq.gz
    ├── 3ade7dc9d254e7ac3a82b0b6305d87657e5bd6d6.nq.gz
    ├── 3ae059665888c5c81572c685ebf25dc9495aba97.nq.gz
    ├── 3bb968d39b6018a1db8d8ba445d4a388a8fc5bff.nq.gz
    ├── 3bc4251aa9ffde0e7faaef79d2873af853750c70.nq.gz
    ├── 3df1adcd9d2be9464d8ad4abdbce5f01bf2ea763.nq.gz
    ├── 3dfc7c2117abeadc4188f4d1cf8aa3733353f48b.nq.gz
    ├── 3e8a60ef036e69df239d1f15824e46824b1fcccf.nq.gz
    ├── 3e9c8d304ba67402f1b8760c52499e2699f6c2ed.nq.gz
    ├── 3f266d99f78fa52a914e5f200aa00026df837709.nq.gz
    ├── 3f6b62f2747cfeaea36ed8bb7fe98ad2fc1b60d5.nq.gz
    ├── 3f96809948e216f62583fa32a636917bcedf8439.nq.gz
    ├── 40d4e5a4728c465f9c9213ad8b41d1bd15e8d09f.nq.gz
    ├── 40fb246795c9541297343d4a5c6264295c9086c9.nq.gz
    ├── 415e2d23faaf9e1691a768eda5321ff2447d8de1.nq.gz
    ├── 4239dabedd22007633f37dfdcb57168f5e341016.nq.gz
    ├── 426a75e41fedf60871e0f16bb29fb8266a7c6d6d.nq.gz
    ├── 428b4c5d3b47b4200f503ad64f28ed33fdaf6118.nq.gz
    ├── 430e9b5508bf2f987d593532f235b69a8287bc4c.nq.gz
    ├── 4313f05bea8870cd2f2b1932fe6c4dd4216ffb8a.nq.gz
    ├── 43d10e4580585b0781c1a51c6029c3e8865b73e3.nq.gz
    ├── 44bc1c8f77403b5cae6c2910ce3bdcac3c98a6b8.nq.gz
    ├── 456458771c37af30e21cfaabcc7eb27f7a36e8d7.nq.gz
    ├── 45bb261c49122ec4a29aba77e26eacb42d9723c6.nq.gz
    ├── 464cf8c6ebe4d3caba002f37c5ff1fae95de1ac5.nq.gz
    ├── 466f1481e16e1e84ad7316ce6b4b747953598dbb.nq.gz
    ├── 4696a2b01ed85567a6fb8643b2cc9aff095e2cf7.nq.gz
    ├── 4736ebd7a20df05e9144f86e344d0829f3f3c063.nq.gz
    ├── 474c47f920744e4ebffc2bd5b1e7ecf6c3a4c30d.nq.gz
    ├── 487d80ded8e30f4d91d5cc4c2b8bee474eeaef90.nq.gz
    ├── 489da7b594c4f3036efe6dd089c938cae294ebd1.nq.gz
    ├── 48b20d49b6d08a3f3a3af27d084144abab96220a.nq.gz
    ├── 48c8527660fe0b383ae3e6bd9f37536e86f229b0.nq.gz
    ├── 4922f1344149639a1b1824f83a03b9bc8be683c3.nq.gz
    ├── 492e489d8e17e74008ed9ecbae35561c0a5e49a4.nq.gz
    ├── 498b81373ed9ec13fb38ef564ec28c3a0f64b1dd.nq.gz
    ├── 49cdc985954903f3d340764b96b2d7a7a60fc4fa.nq.gz
    ├── 4a660bfb26e1c396c0d70b3e2e275654d8146135.nq.gz
    ├── 4b46a6ccfca3093707e35cfb188e2d4ea1209847.nq.gz
    ├── 4b5c6909c922d1dcba04feaa11e5ee8e4220f851.nq.gz
    ├── 4ba66fb04d305741da5ebaafba1f1691e0242ffe.nq.gz
    ├── 4bada29ebcd8b58bed0b8ecd045640d253708313.nq.gz
    ├── 4bcda7838497fb95296d6dfcbe0f472e79226f41.nq.gz
    ├── 4cce80b9f27cd5494b931f43881a8086eb2de73b.nq.gz
    ├── 4d2e3a30ffa69c2c3e3a04800751e067895a1127.nq.gz
    ├── 4d926b8152abc176509c16449f3cfa78bcb25895.nq.gz
    ├── 4db4c4aa5ee1f477bbc780d2a4b55d93a9434a85.nq.gz
    ├── 4de455667e2780da5c7fa5334b857d06cd849a5f.nq.gz
    ├── 4df313605aa2b53b46bd477505ccf3e31d87814f.nq.gz
    ├── 4e52277c447376fbb388fb878c70882be2ba3eeb.nq.gz
    ├── 4f6c71ebb32bc13f12a5768c8b081cfcb75196cf.nq.gz
    ├── 501a25b5a2b5cac392e3bf92bae5fee91ccadfa3.nq.gz
    ├── 50a63ffff7d4851de045fcdf707833d02893423b.nq.gz
    ├── 50f382b5461c2b9da637f9003db49793d14b8cc1.nq.gz
    ├── 5156f828c73799a736aa5588d5533bafaa1416b9.nq.gz
    ├── 515b906c21c29cfbd22b3932d4da53371ed17fa6.nq.gz
    ├── 52344805c7758dbac2b0d2b9b470c44e7f15ff13.nq.gz
    ├── 529da4aac36a737e0cfe40c5420c9fe6a22e0de2.nq.gz
    ├── 52d8c9233821cf55130d8b1a9f2c76fc8329b1c2.nq.gz
    ├── 52f73744ebb328cdd355fdf6e0673424efb585b7.nq.gz
    ├── 53b20c31c19b247974fe070d1235c7fd63593ded.nq.gz
    ├── 54e96b788385a3283b46df97e6352096be486e25.nq.gz
    ├── 56a0045030417e5cc72b0d242ed7cbf85fd8b6fe.nq.gz
    ├── 56f0d8a1072ab946fa2a72396fbc5bc82fbfb7f5.nq.gz
    ├── 5745010f1db33521e1b0e4629ec2f1971444a6fb.nq.gz
    ├── 57981b02b8cbef83665006ca40a378793b286e7b.nq.gz
    ├── 57f1ce1458a402faf6df8e397b50f215b10b233c.nq.gz
    ├── 5823e16f03739f764c281065932519032054b833.nq.gz
    ├── 5989ef4e6eb8dbb4807307f1e9651a6d6084e5a8.nq.gz
    ├── 5ad80eae3a4a7e05ee0b881f025ae7859354ada8.nq.gz
    ├── 5b29bba3beaeaeafc6be4e83184ad440fa274e7f.nq.gz
    ├── 5d0b25b75b42b1b86c6a3d023ef436eea4e06045.nq.gz
    ├── 5d159324b2dcbe4a2773cca72ebbb3b2e94d380a.nq.gz
    ├── 5dfc4f89d3d694ccf30117de4d873913151410c9.nq.gz
    ├── 5ed335b21ab2a2d088ebe3d679ed7026255effd7.nq.gz
    ├── 5f0da4df6f85873e9188c6791c2cb9aacac2e53f.nq.gz
    ├── 5f7ad4825f738362fd0c6f2be1e7f876cd07e85b.nq.gz
    ├── 5fcd51893bc42aec19902f042b2fd4543bd1d42b.nq.gz
    ├── 604a9a4fe8a878aa963f24e913bef54f39e2a1c0.nq.gz
    ├── 61cb1807b92b59bf208896e814b9d8f91525e1f1.nq.gz
    ├── 61d646b53433153c608a4a361e876300b9697560.nq.gz
    └── 62589edd12a37dd28b6b6fed1e2d728ac9f05c8d.nq.gz

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

[neo4j/neo4j-python-driver](https://github.com/neo4j/neo4j-python-driver)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
