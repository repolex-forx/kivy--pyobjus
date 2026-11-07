# Repolex Knowledge Graph of kivy/pyobjus

RDF knowledge graph data for [kivy/pyobjus](https://github.com/kivy/pyobjus), parsed by [repolex](https://repolex.ai).

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
rlex download kivy/pyobjus
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0c204ada4a5aa4f065ac65fc678c6cb35e4dcb81
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0c204ada4a5aa4f065ac65fc678c6cb35e4dcb81
│           └── chunk-001.nq.gz
├── blob
│   ├── 0466d43bec8d21a9f31173a3f6910cffeb80b7a1.nq.gz
│   ├── 08f653469dcf54c7d21783b7944a9df1f42fe8e6.nq.gz
│   ├── 0c2cf81228811197db1bdf032e3afe2e00c4ff9d.nq.gz
│   ├── 0cb960468bea374d84a758bc0826a74d49c3088f.nq.gz
│   ├── 0e4e5389d175aa199e181f75d6a3ef42a014fad0.nq.gz
│   ├── 10122291a9dcc0a3f38f4a36655104e2368507e1.nq.gz
│   ├── 10cc5f0a27aa9bb54e64e805f076143ebf0280d1.nq.gz
│   ├── 133b243c54e38a4290004d8b0b737b69df7ceac1.nq.gz
│   ├── 1f16e120ae6a9fc5391398c947b3e735681ef9f2.nq.gz
│   ├── 21f535caeab6fbb9acd711837144fe7d7bb0953e.nq.gz
│   ├── 231ffef604494018f19326160c6db01af24eacbc.nq.gz
│   ├── 250af9489b88f6a76d38f2cd2b405f1d57e2cdd6.nq.gz
│   ├── 2b323b547c855638d07773d7512454768d717616.nq.gz
│   ├── 2eab776bc4d1dac6cf9456553e67ac554b7e8aca.nq.gz
│   ├── 2ed62a1de7411ceb685de0be5c3342139e145114.nq.gz
│   ├── 2f48d1be75f7c3baf0e4b51adacde084a6af6c4b.nq.gz
│   ├── 3599d68b8d3e775b471fa98a8c6185ac03eb6b2d.nq.gz
│   ├── 37294baf85b40643f085547865b95108ccf88b0b.nq.gz
│   ├── 38f42d87accde863d0fd057d5bc7b082cf853830.nq.gz
│   ├── 398c9993c52e9d61bb37bc5638327ae3fc244221.nq.gz
│   ├── 3bc1ce8864a88465e18f459eb5a2ff7119100839.nq.gz
│   ├── 40a0f991533929b52f83eadd871d14369be5a94a.nq.gz
│   ├── 413fd75ebb2122eacc7dfb8b444898c458e61312.nq.gz
│   ├── 42891129ff14ba67c61cdae5e6269d8c3003e2cf.nq.gz
│   ├── 4474332af11a41e73f26bb0375e647e2d3c9ce00.nq.gz
│   ├── 480c9197811bdb7834c725f790bcaff42c69a9f8.nq.gz
│   ├── 4f4242445b97f07ec04833cfc9d90e3c46891ba6.nq.gz
│   ├── 50ee5059b777af61ad59d689ac7cd3826ba7d9fa.nq.gz
│   ├── 51834296b4450089434a193d700e903d15941bbf.nq.gz
│   ├── 52f603b22791c684181087437f82e2ea2fc4bfcb.nq.gz
│   ├── 5732604c53fb5b5c59502b1f18ec522e5b7569ee.nq.gz
│   ├── 57dcb425ffc4edb58aff18501bf974354f8c1d7b.nq.gz
│   ├── 5b4e490ef5dd930f4f6b054b25ecb6da4c3aef7d.nq.gz
│   ├── 618533b0b4cad62c41b1478326f8c97144762520.nq.gz
│   ├── 73f8c7cf59feac43b347f89a84980d1162f3f398.nq.gz
│   ├── 7520148ec253b32a2049fbfddbc57af653907e45.nq.gz
│   ├── 76240fe1adf0c1bfb71ecefb6b87392cd6a90d51.nq.gz
│   ├── 76c14cd2602d2214ef494c453ec5d192ab6af91f.nq.gz
│   ├── 7764ca62c5edaf44afd1fe754db520f2efe1786e.nq.gz
│   ├── 7ac9e91d5087f55c71731cf42904fb55a9e43b28.nq.gz
│   ├── 7c95099e47b87d0464188f9cd8a7b2d8add8b9b8.nq.gz
│   ├── 7cbc96ef692a84dec9dd990983627bc406ed655a.nq.gz
│   ├── 7fcbb18cb4616649ec4170efbe0253d247f07629.nq.gz
│   ├── 84bf1503c65411cc564d9b9e676ba3eb1471f08d.nq.gz
│   ├── 8639f3acbaaf0273a3ce8613ad0e172836aa87e5.nq.gz
│   ├── 865524b4bdc5d934cf234e0ff0e66c08168add62.nq.gz
│   ├── 8a3f6aea1e514f0ff7c4fe272a25fd981ad767ed.nq.gz
│   ├── 8b33d0f266bf95eb8dfd1df137f99ccefa567243.nq.gz
│   ├── 8e654c53a22cfffe384ce48174ec43ca485ca063.nq.gz
│   ├── 8ef4dfd12d21a7d7644fab16f4ccc5ff00694564.nq.gz
│   ├── 93a6ae83fb69528634119516d7616a03ac37f66f.nq.gz
│   ├── 94db8d4c1977cd06a49975cf7156ad6c0eca5e92.nq.gz
│   ├── 96941a0d09e2ab7c0c16ed8731f38371fc19b140.nq.gz
│   ├── 9b1e1eaa41463d6939a99df21db8478a728f8cad.nq.gz
│   ├── 9ef7d7aaceff42995dfa0224558e00728bb91c10.nq.gz
│   ├── a790e03ddfb629b2520b52644dffde7bc4479eb9.nq.gz
│   ├── aa1a48d8b3c64e3d146bef5615707c2c8e475eb3.nq.gz
│   ├── acb051eeba23a6dff681fc55ea9e8f5c79c14382.nq.gz
│   ├── b4e675b48e81d1e6926a824242cf42a3ce2d65c6.nq.gz
│   ├── b5f396b1acbc43076b48a8b65f82f930be3373cb.nq.gz
│   ├── b6257ee4434ccfd1c6e14300ccc9445449694d44.nq.gz
│   ├── b87a80a4d04ea214e5a5c7cbd956365da129f3cf.nq.gz
│   ├── b8ee9cccc2e76f70b294378b739720f82c2ffc2f.nq.gz
│   ├── ba9be641f3a12e0919063984c3d66beae7f302b9.nq.gz
│   ├── bb2d541a64abda85009a9cf75f095d0ce4ed81d4.nq.gz
│   ├── bca9a95273e533205099a407d6659f92510a19a4.nq.gz
│   ├── c620b73d267d2899da4d86a49abe5173e0891a45.nq.gz
│   ├── c891d0ee73e74844951b24857e4a8713cd24ac7e.nq.gz
│   ├── cf8ffbcdd3f9bcd33aed26de9cfe3888fc006009.nq.gz
│   ├── d2edb1e24d89b7dc5ed65afc2f368f571af59743.nq.gz
│   ├── d5d6b13c8523290257544a9fc3b75abf911b367d.nq.gz
│   ├── d6396ab1112b2ae72a36ebbf6e10292ea902ec97.nq.gz
│   ├── d7fbead82c22d249f6486c452a9e2ae7fac48bf7.nq.gz
│   ├── d8c5e48dc3e7f1a7e4f239894b7b68cb9f8487f2.nq.gz
│   ├── d8ff468bc07131e74a69776011d5ac59798e0055.nq.gz
│   ├── dda6e9110ce2de9586f4867f385859d68265dcd0.nq.gz
│   ├── e022d308e0a08ebbca728d3eb1af5bbd067106ed.nq.gz
│   ├── e1209f5689e7f138b6f7612b036741ec81622433.nq.gz
│   ├── e296432be44ff73c13d2e7d922c508a97ebc2ef4.nq.gz
│   ├── e2d8cb560a0cfd2da988102df76567dee8bbcabf.nq.gz
│   ├── e3087f22c87ac73ba626bc1baf88377cded6dd0f.nq.gz
│   ├── e619a0d4966e2333b1b1b8eb1afc7f6c37e5caff.nq.gz
│   ├── e94ce792604b2d894269857b977dff76761f2cc8.nq.gz
│   ├── ea4bd644945d5a91bed5d772392c6bbbd2db9898.nq.gz
│   ├── ecd9a48aec52d00e9953d8cbc5de410871c731e7.nq.gz
│   ├── ee7255b96189c7012b5ace6fd4be719ffe706a7f.nq.gz
│   ├── ee9c4bdbf30374498dc70af205c585fccc8b4e47.nq.gz
│   ├── f0ea119dc92df5ca6426bb6361f092ff29332df6.nq.gz
│   ├── f1aa8a64e404d880bb3e66749d72a7647b5491cf.nq.gz
│   ├── f2596d701693afb497a54f1895919bf0be6c9aa6.nq.gz
│   ├── f2ab1e90a980ee76eb42739310ef788f3c14c12a.nq.gz
│   ├── f32c868a2241f0c6e4b102f363614dac1f09aad0.nq.gz
│   ├── f34d0641315cc1a4875099294d2ed6cfbedc770c.nq.gz
│   ├── f7d42a5c3ecc5a1fb8442673ad037628ca239376.nq.gz
│   ├── f9428517841db02623b3a5b668066828cba1f1d6.nq.gz
│   ├── fa8c82fc58ec978fbd491707633815fbe4d954a6.nq.gz
│   ├── fb29c5de814833a2edbad2df0df2616db125e34c.nq.gz
│   ├── fba418fb1b762bb978d2a46c76b82eeab3757119.nq.gz
│   ├── fcf968cf26d8a2e570c8e111f3845ab90fa194c1.nq.gz
│   ├── fd460fbf9284d7540e1369b648b809d29efa1c88.nq.gz
│   ├── fd6b86c16ed5e05e67d15e5add449d4308d64bad.nq.gz
│   ├── fd6e01ef60e4499ba86e85998d8017637d74b6ee.nq.gz
│   └── fe1a7af4bbbd4ba66de894988d73ab0e53e03cbe.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0c204ada4a5aa4f065ac65fc678c6cb35e4dcb81.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 111 files
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

[kivy/pyobjus](https://github.com/kivy/pyobjus)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
