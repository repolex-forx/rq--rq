# Repolex Knowledge Graph of rq/rq

RDF knowledge graph data for [rq/rq](https://github.com/rq/rq), parsed by [repolex](https://repolex.ai).

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
rlex download rq/rq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a0048377aceaadef3bea0e71c70b3e326fb78687
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── a0048377aceaadef3bea0e71c70b3e326fb78687
│           └── chunk-001.nq.gz
├── blob
│   ├── 01a2c28334ab5f4afcfc39b95fad95704d796707.nq.gz
│   ├── 08919540f4d01f4e6913fcc8c4d62c4132ed36a8.nq.gz
│   ├── 09173b7e6290dfcfc4bee08961aa8af745be33b7.nq.gz
│   ├── 0abd3166cbd8cfe98c8cbe9a83f0d95525e44957.nq.gz
│   ├── 0be4a10b502e79ea4d978bcab8b7c7a3a680dd93.nq.gz
│   ├── 0c835afe558a95ab14857468e9d7b973e9b3c894.nq.gz
│   ├── 0e2adda2ab627924277a8a8d1790f11794ac5044.nq.gz
│   ├── 0e424b54e0f28a41504c4236c6873a749ee5c8a3.nq.gz
│   ├── 12a73471dd9be8a21436007bd9e68ec3a2c727de.nq.gz
│   ├── 13859610f07483fb68104a22c46b6fdd63e24e79.nq.gz
│   ├── 15b42cfb2718518155d9c3bb94665d8699e40da8.nq.gz
│   ├── 1890145802d4fc45a6f5989c9011e8184e2f0fb6.nq.gz
│   ├── 18a338638a01afc2e0c0bf9194bd5a5837e3716a.nq.gz
│   ├── 1ccfb3bbd21bf1fbd1abbfff323162aee8f6fafc.nq.gz
│   ├── 1ff2af3ca8653248f05aa68c31e5bad1c605f874.nq.gz
│   ├── 2084a95e22414983f30e2d8623b26ec234fb3fc6.nq.gz
│   ├── 24cfb28050ec482bc7cde230c9a32e1c95f874f6.nq.gz
│   ├── 2622af9bbae1f67a63b971b63c2fecd06645db62.nq.gz
│   ├── 27af777eb5182910a4f1e0a24d262aaccb6cdf42.nq.gz
│   ├── 2838512602b503768a1db0334cc5fdff2e5b4301.nq.gz
│   ├── 283eff638c48387fb5c4ed74c00c78e2423ec536.nq.gz
│   ├── 29d3d90c891d46600b2e2ff268ea2f141f177ad3.nq.gz
│   ├── 2eba96e083221f4426ef1f0fc4659461bed9a134.nq.gz
│   ├── 2f94379a772f7e22b005528f081010b437a7d519.nq.gz
│   ├── 317639852dc3ed0b6f2a234df47190e7efba80a8.nq.gz
│   ├── 32ceb3fdabf2d061671e07cb2c33a0d95253d432.nq.gz
│   ├── 33331b56d93c59b73b62cf30bff5844f0fc83b00.nq.gz
│   ├── 336e399c6c10bf2b457b7b2763cb4bb7be65abf5.nq.gz
│   ├── 342065080d214ae365470341e0282da5e8752183.nq.gz
│   ├── 347c5052cfc7d43af04f238848bd636cc517eebd.nq.gz
│   ├── 34fb765e3524c4150198f57ba7032dba65097360.nq.gz
│   ├── 357c66126eb7f072068c4f5d543b4c75eee617d0.nq.gz
│   ├── 35e71e688779d9da82806624deef572070b193f3.nq.gz
│   ├── 36be3cca3d941bc448551c5ec9ea4e7dfe377cda.nq.gz
│   ├── 36e07f7ddb7faded60458c3930c45f898d87f33b.nq.gz
│   ├── 378a752c00b1f3c96b88e34375fd5325b38f08ce.nq.gz
│   ├── 388757a663883d0556b3f511ca9c3d2d6a90bdba.nq.gz
│   ├── 3b364222ab99bf98f5172d0370192a72f6c8a489.nq.gz
│   ├── 3cd453d37670f7ed04b4f5de37d9a74c00bf8a34.nq.gz
│   ├── 43dc8553a632b2e8aac03990ec1b94675981d2b5.nq.gz
│   ├── 452c025a5f68fb1193c8b4dd3111d9b43af8df60.nq.gz
│   ├── 4531e4a021fab001c8cb1b9f3ee7720ec0885f0f.nq.gz
│   ├── 4704e3d2b556a5198116c589b9ea503016cef619.nq.gz
│   ├── 477dbe7c08e189385fb7c5d02b5b470b412656f0.nq.gz
│   ├── 47b28dd8fcd82eb760d6b9ae5f432b403bd53f82.nq.gz
│   ├── 4aa34dc48676434550b52c2535612090a2193fe9.nq.gz
│   ├── 4b3f1852e8f375e3344b158c13b730b8ff90b4bd.nq.gz
│   ├── 4ca44937adc9bd7ee45cd6976a2fde763e1bcac4.nq.gz
│   ├── 52534711b7c2b7b15e1fecff87983648d219fd63.nq.gz
│   ├── 52a60c78e60f7e2ca63687d37578dd6a29961cbe.nq.gz
│   ├── 53784a0d9120055be8deaac907e90be2f12d2a35.nq.gz
│   ├── 5512961777a2ca75aadecaf625a8c28a9c85cb60.nq.gz
│   ├── 56e4d23c103cdeb5e377501e6518ab21508ebce8.nq.gz
│   ├── 5705650a3577e546ad5e00dd873c12babff1110a.nq.gz
│   ├── 5755180450b0582ac3faef8f51c3468c8baa0cce.nq.gz
│   ├── 5b10b851bf97d4d6fe8d420876c0e0bf22643810.nq.gz
│   ├── 5c5d9ce140ca4b2ffacf414853ad9458ea353919.nq.gz
│   ├── 5f31b59fb2919249dcdb17fac743fb7977b87bfe.nq.gz
│   ├── 6021c6b671a16467136ab7a84294f6068238f3f4.nq.gz
│   ├── 603b8f5af172c88887a2f9ea0ac706a0272780bd.nq.gz
│   ├── 62dabc893de2e88cf0103cea229ab616bc3ce438.nq.gz
│   ├── 647d71be1c12ca0b83c9d389a522344467241e3d.nq.gz
│   ├── 6496fd27a393feef72cb764384f4c7c5c7456f52.nq.gz
│   ├── 64c50c7d241fd3815856ed67292e2e1631f4e9c8.nq.gz
│   ├── 681caa039f7f59c5df8f9e7b7bdaccced5b68013.nq.gz
│   ├── 688dfbfdc9a5c5efd1d7e1fcafd31333246466d6.nq.gz
│   ├── 699ae6488e3de08640e050bd3d7c3c12236be41b.nq.gz
│   ├── 6e566ad0e82ffc099dfc6836a32bd90411a28107.nq.gz
│   ├── 70839799111e264b1c8362ba17019d70c6b2abeb.nq.gz
│   ├── 70fcafa6d0258a98770cf70a1e541b922be27ae5.nq.gz
│   ├── 7445fc0ab442e399fd9e71fe03226ef227fb67b1.nq.gz
│   ├── 7799e9990b8edcfa330a8c59401e0c757f40fc10.nq.gz
│   ├── 77e618562f67ea466a656c4f0b0267559e6909f6.nq.gz
│   ├── 7c389bd56204cc1eb29e279086d3f0cec4efb81d.nq.gz
│   ├── 7f7f49fe950a0dd19f622a113be4b70bd6b41e1d.nq.gz
│   ├── 7f907acbddf79c8638aa91dd0175131326f6df0f.nq.gz
│   ├── 82aa2052e6285eb0986e07a14b96410f736e7f3b.nq.gz
│   ├── 82efc12c246d19764995cc6e2d28201080400a9d.nq.gz
│   ├── 84c77703b74fa36a167b632b2a5a7d1064fd810d.nq.gz
│   ├── 8b0a7690b35205025fb49f95f37c6e3f621493bf.nq.gz
│   ├── 8b10f07c5223bab186bd5a7499d207e9ba4b173b.nq.gz
│   ├── 8b5eb9727958a4450d4ac1b737e5668e3587944b.nq.gz
│   ├── 8ca5f7f08b2b85afd8ef61d04903342c632f1264.nq.gz
│   ├── 90a5ab9f533e6adeb937ffe511b30440a7b1182d.nq.gz
│   ├── 90e10c49dacc0453b80eaa489b38d296b9ee6c10.nq.gz
│   ├── 90fe24a412e05ab34a2419ec7e957b73ec2f9bae.nq.gz
│   ├── 93d07887c7b9303ce05d95cf54c150fb5b2c8fb1.nq.gz
│   ├── 9674bb852566d333728ad209f3de1637524e7282.nq.gz
│   ├── 9a6cfeba3df0c3d48b8b110826da2b6657bfc430.nq.gz
│   ├── 9d10455235860c2ad15924982bd738317eda04f2.nq.gz
│   ├── 9fc2bcb39c493acfe3a5815d289c15446c21e829.nq.gz
│   ├── 9fe3b6742bd75be61d3d157e62d4d26805101f9a.nq.gz
│   ├── a10587c8398be85a0e1b330f89a85c5e1f0aaed6.nq.gz
│   ├── a328672612238ef0193974ae37f564ab14fca111.nq.gz
│   ├── a3729a35d782ad12e659732bd8bf1c5437ef9e25.nq.gz
│   ├── a421a7838f6459fd27f4d43e05fa5d2ded5e04c3.nq.gz
│   ├── a4375afd82ba353c38dd5643fdaabba9794c5c68.nq.gz
│   ├── a51f37cf1dcaf2d31c4795aca937d5aac99550fd.nq.gz
│   ├── a662d0f157c635b88f3618fe27f8e7b5783765f8.nq.gz
│   ├── a84605ba92111b32e7338ce2097ee6ca1736dad3.nq.gz
│   ├── aca6d3cc4f9d3aebe4dcebad4e137a4ad7bc1ee0.nq.gz
│   ├── adc8aabcaf6475d167bee6b434b662e982a9ec2c.nq.gz
│   ├── aff3c225d2f52b3d7ed9348e8ca50b99b19f0b08.nq.gz
│   ├── b0780dc607c293472f2b28346d3ebd97a215a9fa.nq.gz
│   ├── b24796c2788f8c8229659b583843af883c475248.nq.gz
│   ├── b313b6d33d7378bdd4976221e6da536035d85c33.nq.gz
│   ├── b45ae91da01f14b3fa353f44bdbc9a4a8edf85f7.nq.gz
│   ├── ba42a8565024e1f9a97ab974807155de09bc9277.nq.gz
│   ├── bb83559b58cfae474f5f69957b41ed45934fd85c.nq.gz
│   ├── bc14587312662eb374c73810bfb2aacc411dee42.nq.gz
│   ├── bd35a3b75208c183f140a6de554e6652897c35f3.nq.gz
│   ├── c114c7ca57352592dac403527cb16d0da249550e.nq.gz
│   ├── c136389144abd7d2119d8a73394a610e05af6ca2.nq.gz
│   ├── c1f9e63925e1b42a06427edaec5ba1c140c40c11.nq.gz
│   ├── c351b77ca4b15fa80a7a78e1cf4b651e6c836c2f.nq.gz
│   ├── c37e53f2435ef1e85c13d340c37448f1fe7e5874.nq.gz
│   ├── c51d74095f19b31348fbb98b83cc13e3f3d02baf.nq.gz
│   ├── c82ff1fbde6f2412d51d83c6b59994330623134d.nq.gz
│   ├── ca97aa4ac44462d84a9b48686a74cfe123d3c2d1.nq.gz
│   ├── cb2d407a26176fd8ad94636ac80739d4d5dd509e.nq.gz
│   ├── ccaede11588ce89e56fca216cc825b74751f70f0.nq.gz
│   ├── ce43969dda27cc1c90679b31b6e346d80c574ebc.nq.gz
│   ├── cf9c67e021deccb93a27d0af6ccc59a76e6a24d4.nq.gz
│   ├── cfe00ef5d64ffd5b80cfc6e00e1ca00b1c6b63e4.nq.gz
│   ├── d0a57183a59a7efaa89254b165ba39a7233d1301.nq.gz
│   ├── d340868fb2af501c56863a67bf6f6f696f9f18c8.nq.gz
│   ├── d41d189569fc508894a32d92c7906f05d2551fa2.nq.gz
│   ├── d53c769cc2e7e1dd75e0db03fc25e16aa89ec06d.nq.gz
│   ├── d8efdd793a14643ff4b6c6a7fec6a3892404b473.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dceb52419e3a6172e330e91175d1ce069d3f0491.nq.gz
│   ├── df37f94f87c0855ce44bc752abcb15509aaed518.nq.gz
│   ├── e0e2af57ebb6b512dfae39e7fb53b49b8f1d5018.nq.gz
│   ├── e0ec819d4d1cf123c3baaf4af7b906368216dda3.nq.gz
│   ├── e2e2dd72d58a05929540c9e78960b7991a085860.nq.gz
│   ├── e44e1a4eca0d6d7923d519837bbab4f010334ae3.nq.gz
│   ├── e482645b546acaee70f4444dd3204e708e513f5b.nq.gz
│   ├── e4dc838832bb28a915b25c4784060613a1bf6176.nq.gz
│   ├── e5288b605f4d2e938e3968c13d38984ce04c1b29.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e84af64c5afc1d62573c4d385d23583f5cd6506a.nq.gz
│   ├── e8a36976a5589402a53fa663230d7d93b44444b4.nq.gz
│   ├── e91985257a5b9c406eaf37e79c6912c0e7a5931e.nq.gz
│   ├── e93a8ed164da60bad7d7f0f6c59c4e0bb0a19b68.nq.gz
│   ├── eaa02b174e31517b946e63dee95744e096d51d9b.nq.gz
│   ├── eaa70a988f273352a806d1a48610e6d1a1e5e7a1.nq.gz
│   ├── eb66e7908a8260a91eb452cc51fd050675ded555.nq.gz
│   ├── ed11813c4e691793cebd51002408e510d8e2a691.nq.gz
│   ├── ee139e808762121855b3383412270d1f835224f4.nq.gz
│   ├── f5bb5c2b909729472c497cb1734e2b18d6290990.nq.gz
│   ├── f7d3f5af553c9a18fb52e80f108a7c4399d0f3c0.nq.gz
│   ├── f7deafbae9616535673e55d9f1868824d74bb611.nq.gz
│   ├── f92b6b3b32cb8a1e88eebbdb2e3a0b6c3ee3e898.nq.gz
│   ├── fc3e6e207b3a4f488741a331308a090e2a0ce4a8.nq.gz
│   └── ff517772167b33f5c14503565ee4670371db224c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── a0048377aceaadef3bea0e71c70b3e326fb78687.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 163 files
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

[rq/rq](https://github.com/rq/rq)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
