# Repolex Knowledge Graph of spacetelescope/drizzlepac

RDF knowledge graph data for [spacetelescope/drizzlepac](https://github.com/spacetelescope/drizzlepac), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/drizzlepac
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 07a9de88cad79da5c2acf0a683328afc0f1d5f2a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 07a9de88cad79da5c2acf0a683328afc0f1d5f2a
│           └── chunk-001.nq.gz
└── blob
    ├── 00c2fe6879902f1c4952137594a81041c11bbcfc.nq.gz
    ├── 01ad77a6d26a7c91c067630c97b7bdeb877e1fdd.nq.gz
    ├── 01c07b8a1b127842df07ba8ecf9f876d6ec6dcd0.nq.gz
    ├── 026ad0e853e2f32d05a4c1e42afe603fd9ab5009.nq.gz
    ├── 0367404df18680d13ec3db6d2f5fbc4ba3d6ae2d.nq.gz
    ├── 0378d82b161b105267987d301c5db4743bbd2707.nq.gz
    ├── 037e799cd90ec64ad9fb33fc308512a860cdf9f3.nq.gz
    ├── 0470c8f611b6aa754cd1efb915649cea22153730.nq.gz
    ├── 04e1c99569bb5257ae99da1dcb7336b9c813516f.nq.gz
    ├── 05eebee565058f4671b4522897e8bef433535ac8.nq.gz
    ├── 05fc5b5925fa4647012277ddc0d788ae150dda72.nq.gz
    ├── 060ca31d69fdcc7f1e0e0e6eabd52fe4110f808a.nq.gz
    ├── 06b7e7dd830e0f57723baabe40b206f6c3ae76af.nq.gz
    ├── 06f7402a4d75c4a99b37d4a4f391db78948377e8.nq.gz
    ├── 075c8783429bc3cbd9dc3e2c475611e1eace979f.nq.gz
    ├── 08dac3525b86acd5108c2c2db7df29ab39acf3de.nq.gz
    ├── 08f9245b07efb723d7eeeaeb47a2e494c863a33b.nq.gz
    ├── 08fe32aa9044c49e51038dc1d87f6dbbc4fcaa22.nq.gz
    ├── 09494d0f488f3ce97802d8dad4fb3e0714d1943c.nq.gz
    ├── 0968375c28daa8b8869b09fe4db6bdc6c51ce21c.nq.gz
    ├── 09f65aef893504316ee5cfef689f34fcf3b67398.nq.gz
    ├── 0ad1b06fbf3cc5513a362ae6a9c43d530864c512.nq.gz
    ├── 0ad68ba7a8e46ea317a20f50dce130bf3b0f24ce.nq.gz
    ├── 0b24ca1928f4cfa7c68dc11bf0d301efd1843928.nq.gz
    ├── 0cbfc1d7e3cbe04b8e4d66e3edeac9631b5417eb.nq.gz
    ├── 0cd2c29d7f87cb792378d03be3e32cbb44e1e7be.nq.gz
    ├── 0e6ca95b3fd4b5e91b9857150f3a46fd32d6fcc1.nq.gz
    ├── 0f05d2a8f93dc56c1b25c15ad2928bffc75b4aac.nq.gz
    ├── 0fc0fabb2b8293c660ec0eb927daed1690a7c3b9.nq.gz
    ├── 102a70639723417e9bfe1960f6c922417c17925a.nq.gz
    ├── 11079ac7d3093386cf27000eea790d88c0ae9d5f.nq.gz
    ├── 111b28c23413ed555525c15c4fceaae673de40f9.nq.gz
    ├── 112d475d0e411e9a8008ba9cb269af127e95936b.nq.gz
    ├── 12a89f38fcfcc20b37d12a06380274edc1a2ba82.nq.gz
    ├── 131d1fe22db39a35bf638b8246247f540abb6220.nq.gz
    ├── 138d4feea26613c2a0acd096aaebf71ab2d41a2b.nq.gz
    ├── 151e4a7532fb9fd7cb933d2b6d7c516afb6e96fa.nq.gz
    ├── 157f15be81d9203b43f10761e5b1b77b37484cc7.nq.gz
    ├── 159ef4ee99a063e519034e67fedace1b2ce2c7ab.nq.gz
    ├── 15b15fff3e2d37f632f008cf1f7d8d9f736c2396.nq.gz
    ├── 15dafe994e29fb315ee9dd7ee6523ee9498ea8b1.nq.gz
    ├── 15fe4aa4bf5d38f44a0f3c8af310c31291616ac2.nq.gz
    ├── 16d7710cf2cf70784a37085bfa0e0a64d2c4cbfd.nq.gz
    ├── 170c3cdb9cd36d66c9d5d774a9c428cac16b23bc.nq.gz
    ├── 17d67de09a66a7e65569e1671f9cfa1237941be3.nq.gz
    ├── 1a218f5e5bc6f6fcf957402a14d721e762095351.nq.gz
    ├── 1a691d9a804211070ef15d01667685faecc7db04.nq.gz
    ├── 1a9b00c72c4d09bf02cf716d3a85c6ca7931c674.nq.gz
    ├── 1ae8d1ceb009834eb14457d45ec1b29785af0bb0.nq.gz
    ├── 1b39895f12f80df2e4ad37905f66ef8eebda0088.nq.gz
    ├── 1b8823e44846e0c708af66ac3ea1aeb95b1ff7f2.nq.gz
    ├── 1bcbf3262711682178d6df09c649fe4bccba1939.nq.gz
    ├── 1c46c216d321646685c70a4831259c03b23e7e65.nq.gz
    ├── 1cb5a33f0a215f1154e4f888293a6d3c25514a55.nq.gz
    ├── 1d129e10f0e65a0074597f4bb8e20e4cb2912c6d.nq.gz
    ├── 1d1e0df3e296b90e545fd8ea45646b41ba25d2a0.nq.gz
    ├── 1dcf9cfdedc09d5ecabb69f5da678ae265a1ab99.nq.gz
    ├── 1ecf45870781d4e725f57323d2973d422e312e8f.nq.gz
    ├── 1ede50f39c6931725c381a629de6cca6bdcdc0ca.nq.gz
    ├── 1f9d51f48b81a0b510b7cafe61ef69bb9ec83786.nq.gz
    ├── 20059b9ba1f720fa6247258508a97b7f842eb93e.nq.gz
    ├── 2044fe65e9fdfbadeb6e2735f6712520db505c44.nq.gz
    ├── 2190eca32462e23ee705a3203073a99389b0edd9.nq.gz
    ├── 219243633d3a30d31f6903d25b106c03e041c11c.nq.gz
    ├── 22b11a6864c384a01dfd6b84b99459664d1c3fc6.nq.gz
    ├── 22d08de77631b16d9727e029b4db7dabbdd16b9f.nq.gz
    ├── 231eab87e4ed77fb1edc0922d6eb2633711a1e20.nq.gz
    ├── 2362ce4c340720749edb0860926357cb044d115f.nq.gz
    ├── 23ba7ea50c99d41c9a6c95ba074747928e88b710.nq.gz
    ├── 24daa0bb9332617694db0fbc163455d27e2235ac.nq.gz
    ├── 266c46dc683b1f8c0118ad55716e6a418e320a7d.nq.gz
    ├── 267c1d319f1e26ae134e4e1b89c867ee12a2fd50.nq.gz
    ├── 2759fa76192f72d594735734d6d0a009ee6fe634.nq.gz
    ├── 293e69d2b7da7531c1bb11ab4cab3d13010c7846.nq.gz
    ├── 2988befbb6062b2d5336716ca2ba7b4e73edc032.nq.gz
    ├── 2a862368973077072f2282e76296808ff6c2a2fc.nq.gz
    ├── 2b2170a4d6ef10d770a5ed637f1940cf9f0c48ed.nq.gz
    ├── 2dc1a97c7beacf5f4969e9fdb7d382ac8b450ff1.nq.gz
    ├── 2e253325e21046df33bdf05a69ed35b6f2d4644e.nq.gz
    ├── 2f30ef473708ee8156d31df2d250ec4095abea54.nq.gz
    ├── 2fa49f064e65325510d6b8626dbecd10cee576e3.nq.gz
    ├── 2fda47f8b00cd62993ced68456acc26c4ecf01f0.nq.gz
    ├── 2ff52fa38f819f9f287d26410e0f87faa33f2f0e.nq.gz
    ├── 3003f5087e6316cf4af31eff85ba9adea2c4e5e8.nq.gz
    ├── 31e94542c04303303eafb8bc42d7d68df8b8f80f.nq.gz
    ├── 32223661c2234b11cb9c8804802d454b10b432db.nq.gz
    ├── 3253d89028f289e2c8d097278a4fd46f454ea4c1.nq.gz
    ├── 3282a0696c1a1a0ca095489fd5936cc7a86a49a3.nq.gz
    ├── 328c6fde951af9564ed5607c7add4dbc48382842.nq.gz
    ├── 3392c1f214bbc2444bd2d051768cc58491205dac.nq.gz
    ├── 33e6cd56097912386554d7ae387c8cfe9b8d0462.nq.gz
    ├── 33fffc2cbc0ac57d840bb2c166ec1cc8747aa815.nq.gz
    ├── 344dd60ce0be667569e19b4d0742254a1e35b2d9.nq.gz
    ├── 3570ca4b9c5841aa315dcf0939cdb985bdbed6fc.nq.gz
    ├── 35f47cfca87023f408abd2c116f7014eb2a0d2cc.nq.gz
    ├── 3609592e24b3c34e56925a252bb0e3aeee8984f8.nq.gz
    ├── 368f803147afb6825c40ad50a728e1cc9d0bec41.nq.gz
    ├── 378dc5ba0fadb230fd717d51e73e2fe4195c75b7.nq.gz
    ├── 37cf8bd3ab2d79c3dbb949d3d1f44dbe53ed69f3.nq.gz
    ├── 37fd27b383e0d75759e8db7158583c42a347683e.nq.gz
    ├── 382423c2fd5dbf35a8633bc8c6049265e87e15a6.nq.gz
    ├── 3838034a76f39ea28c401d5e31b6838b07b55dbc.nq.gz
    ├── 3925634c7899b579b00bb099d3479a6c0a664350.nq.gz
    ├── 395e920b431920dab9eccb659f21ac109985c183.nq.gz
    ├── 39cfa1fbe33c7597873a1ece35f68bbbc6b9c4d9.nq.gz
    ├── 3a23669bf0ad90c553b4f1554398a084c9c9252b.nq.gz
    ├── 3a61a699dc1b1c1dfe48df219226c0a0b4f15040.nq.gz
    ├── 3b64e3715e7bc1c40a9b0a04b33d88e7feb3b6a4.nq.gz
    ├── 3b6c897c483a7da3cbce301bd730f09ea10bac8f.nq.gz
    ├── 3b9230d6a4e9a80ae3e97faeb5f35ac4f92779ba.nq.gz
    ├── 3c940ee87c07080b810a08f46a6c69ba0ce0dfba.nq.gz
    ├── 3cc003e833198689e3f311c6ca19254cb64f26c0.nq.gz
    ├── 3d10af2a879dcd56221f36922afbc1ab8d53d6d0.nq.gz
    ├── 3d4f1d8d3883b18cb04b311934ff2be0a0e5ea34.nq.gz
    ├── 3d82bb4918f7c434c2583d1114f2f183b4cf43dd.nq.gz
    ├── 3ed86141d6f7d50d48002ebf91405a0d873a2c93.nq.gz
    ├── 40422c70b85999cc48c90c14a5ffb347f1299467.nq.gz
    ├── 412f46e6268ed6b0147f76e9048b4d0c202cffa0.nq.gz
    ├── 415f6ff5b561e445e78be12609849c826fb56aa2.nq.gz
    ├── 427bd3fa2772aad455847790dcfa25ac65203cf0.nq.gz
    ├── 43c0142dbef6dd77ac8805b7f54be89a99103f47.nq.gz
    ├── 43c47b72670ea9331e00c74b3746acd83013fde4.nq.gz
    ├── 44ab8f03f4e96f3b7226d7a6f1b7283018941e72.nq.gz
    ├── 44ac1a60f707ce49147c5703395a5c59774a87e0.nq.gz
    ├── 4547ec56bb6348b55b5a9213aa75e316298209a5.nq.gz
    ├── 45b6d167f60436a46b00781bd19854e69707eef7.nq.gz
    ├── 45d099bff7b91bdf3f2580bcfa4a2666acd08e49.nq.gz
    ├── 45d15b140dcb8c701968f6aa9abc9a2447aba5b9.nq.gz
    ├── 4606b870c767bd84c5e65cda94e61bed2941e24b.nq.gz
    ├── 46447742e5db7c52503c7560d53f5b3da5cb73ca.nq.gz
    ├── 468c359b0f7d81967ccfead2b311668c9940d4eb.nq.gz
    ├── 469c5f2a33d77e6f88da53c3303ffb177766912e.nq.gz
    ├── 47b2bfab5dcf787d39f64cf2b0adb6f9e5c254fa.nq.gz
    ├── 4876c666f1c85e32e847c83b293518156503f3a8.nq.gz
    ├── 487e714b8e9db0e4b7f80e5472f523aad735e7c7.nq.gz
    ├── 48b0c785690dfffe6379f6e2698119c756a953a2.nq.gz
    ├── 4986212f2a7ee47e02744f2b53a468ea721dd4b6.nq.gz
    ├── 49fff40b5318404e42f2f8671549c114723aef53.nq.gz
    ├── 4acde05b6948f3156abc16fbd25926a53e186347.nq.gz
    ├── 4b09587f8814b815869594e84d52c21fc0f7d9ce.nq.gz
    ├── 4bca860d8905c6683ab00c92495a1f0910d67330.nq.gz
    ├── 4d42f9d0957fe01dab7af39bdd29cb78fac4da2e.nq.gz
    ├── 4d85867f0778090229c2b5c504f64c449d5da111.nq.gz
    ├── 4d9cd053f4c9d6467586dd411e31de894869770c.nq.gz
    ├── 4e397df7e3f3357987d95d3b2a42a163d4699e97.nq.gz
    ├── 4ec68d0736e0e7b1295d96bd068b224bfa0c9d99.nq.gz
    ├── 4f703e2cd8395430ebf7e616a7e744faa6d1ee37.nq.gz
    ├── 50488423190c23042a21515d1bdaad063a7a8ac6.nq.gz
    ├── 51693b269e398460029835de3a1e8a14a8e2bbd4.nq.gz
    ├── 51b4ea577f9f56c170e4b1e33895aadfe8fcf449.nq.gz
    ├── 51b530a01d1efd31c2c4d6b9d47f0967f7ac360b.nq.gz
    ├── 51cbb98d4b353fb93dcbd398709b2ab3d7ff077c.nq.gz
    ├── 51e802e6ab29e870ebc6055b092b9e67342139b8.nq.gz
    ├── 5246a57a357238afea0fc8b8870728dc73c53d39.nq.gz
    ├── 5269a8781ace1009da0e34bdabf18807c66da353.nq.gz
    ├── 528468beb19e7792c98c45fcdf5f59995d178791.nq.gz
    ├── 528f4b7eaa19043404f0c121815ec35cc35b8c90.nq.gz
    ├── 5407cc73eecada20e3827460c347ca1e62406b86.nq.gz
    ├── 547b9b5faacf110e3fae841bc2f0f6787d882c99.nq.gz
    ├── 54cdd4a8927a741a0003ed60e84eb0d4259cc371.nq.gz
    ├── 54e4357b8002e98a548a49a07815be5d6ce4d00a.nq.gz
    ├── 55039a2eb4f62316bb59cb887de88b9502a604ee.nq.gz
    ├── 555433dafbc74d904183b023d93d942015c46e29.nq.gz
    ├── 55911720cc6de9834eabbcaf2301c8b5df4a07dc.nq.gz
    ├── 55e466f2f8e6302e078aeea4a836f8337ae40c33.nq.gz
    ├── 55e70b6502ebe5c88a34f37df39975b15815b2a8.nq.gz
    ├── 56812d161588f066d4ae24c1206175e633aacec3.nq.gz
    ├── 56bf5d7c7bb78a57fd989be7fcfe5602171e0c61.nq.gz
    ├── 570549299f2cc5ea6a223a731129027b9ecb4df8.nq.gz
    ├── 572c046882e6d60d0f9cca3559bcb9884b2fa5a1.nq.gz
    ├── 5751f0719bcfa20594cfc392bfb6125052346fbc.nq.gz
    ├── 5775fc2b15c1067e5a4aac22b907a6a667c1f119.nq.gz
    ├── 57f2eeb7714e7bc4c312897a65f426dca6535498.nq.gz
    ├── 58852119487c0a0fabbc2c4719fa7515cad58487.nq.gz
    ├── 58d927cde73f72791a7d41af2ce54dd485dab080.nq.gz
    ├── 5918e7cdfa7c20f99cbd6534b8f13b4164503552.nq.gz
    ├── 59d76da484d267295413c063420ad6b6b4df06b6.nq.gz
    ├── 5a07c79f7e9a9fee02b1ae2290bc0085109d6318.nq.gz
    ├── 5a7661d35a621c22ba6a849f2140bf482221d111.nq.gz
    ├── 5aee9403fa702e406d64b32ca2f523ba0efa1fa8.nq.gz
    ├── 5b8ba2fb5bfcbc7c1c99c5aa166f5efab73db103.nq.gz
    ├── 5c82c7889a7d339b1572dd3e7663e837fe15f9bb.nq.gz
    ├── 5d10c2fcf7fbf12ae87453ef93cd6b7e6859e558.nq.gz
    ├── 5d45deeb98f54e824c5753b6618bcce1fcedbc97.nq.gz
    ├── 5e0e662a6682d4bea37c146124c349a5fce15edb.nq.gz
    ├── 5f37e3fc1c34b17916a828ef64b5df7c32fbe210.nq.gz
    ├── 600a8b0ce5743dc874944c6e05077f874ff163b8.nq.gz
    ├── 600d1a8ee35b03ce33e24c1e7de6ce2504a64cf1.nq.gz
    ├── 60137cff023af3d12bef81c1d6664de20e210b00.nq.gz
    ├── 609a3dcd860cabc5566e46900188bed9e396af1b.nq.gz
    ├── 60b46a35b48ac5ca73f071a2ebb24f35ca5c2f05.nq.gz
    ├── 60baad90d6112bb048fea0a46ca143ba75c34a42.nq.gz
    ├── 6147435b8031e822d3355f69d88623ecfd06e2e1.nq.gz
    ├── 61cceab90289c2a17278c64f641dfbe6ee7d989a.nq.gz
    ├── 61e5dee85266607fba7e2586e7a465c28cc23b34.nq.gz
    ├── 622960e375c76687775d9bbaa9fe48f92e644f81.nq.gz
    ├── 62d29d0f95ae04f84741a1a38ca2222fc872da93.nq.gz
    └── 62ef0ad8545117bccfae6a874124fee03a669f73.nq.gz

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

[spacetelescope/drizzlepac](https://github.com/spacetelescope/drizzlepac)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
