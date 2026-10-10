# Repolex Knowledge Graph of samuelcolvin/openartifact

RDF knowledge graph data for [samuelcolvin/openartifact](https://github.com/samuelcolvin/openartifact), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/openartifact
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 29b03bc46ce85c8681afe8b1489a9344af123637
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 29b03bc46ce85c8681afe8b1489a9344af123637
│           └── chunk-001.nq.gz
├── blob
│   ├── 073995d10b008d470136f5c771d0f8ab8625d38d.nq.gz
│   ├── 07e4f46bddc274faf0fdda224519a14126cf2593.nq.gz
│   ├── 08c3c7449b230eee4c993e137fe97e772739a56e.nq.gz
│   ├── 0978a4f5209af0b3dd9d37d9972dd4ff3af6d15a.nq.gz
│   ├── 0b9d637e75e799bc779e300dabaf2e02cbdc054e.nq.gz
│   ├── 0f6ae554953d9b66e8c8aa477dfa87556de7c217.nq.gz
│   ├── 10c984aad2d2364c95bdb5c63c5eb2864ba2556a.nq.gz
│   ├── 16b9a18505a6248056103b8f2cf40be9a0093e8a.nq.gz
│   ├── 16c70c9759a71c1c9109ac35891c65a73e1a658e.nq.gz
│   ├── 1735e7bfd220c5483e2e8d1ea02e2e37cdba77f7.nq.gz
│   ├── 19ec4265812db302864b4ba8758db46fdc3b726e.nq.gz
│   ├── 1a322b009554fa3f0b2aa6e18ffb5a446c4ae255.nq.gz
│   ├── 1c71db30055fdbef8fc2bdba09861163ee72c4dd.nq.gz
│   ├── 1dcdc087e29a843fffc2edb55e4a845b92d09f47.nq.gz
│   ├── 249d1e0eda81f227fa032de6fecd8846e929608a.nq.gz
│   ├── 25a54e7397c92a41c136241357ab3a7907e2aca0.nq.gz
│   ├── 27261de68b292840b8190043d8b50924b78b9469.nq.gz
│   ├── 2d3a0a6815ff9b787a186a0a996a604da1efba70.nq.gz
│   ├── 2f196b0c1cb03947d3dee79d442d8ea95e88bdb9.nq.gz
│   ├── 3016e1f92543218bf9ea2288b5c911fcf47b3943.nq.gz
│   ├── 315d2a7f538490eb8819999e7ee09924a800ea88.nq.gz
│   ├── 355acbc29f8e840c403499ae6d51e0d1421d34be.nq.gz
│   ├── 35767d5a7d11fc3658e6b8a748b96f3208e18231.nq.gz
│   ├── 36e0c12efa30e639f85e827931ecbb43011c2a2f.nq.gz
│   ├── 3c6e1dfea130acca2a69f7c73619f76d109c818a.nq.gz
│   ├── 3d7a33791b4a90174c9132534f02deaf6a2bc06d.nq.gz
│   ├── 3db5f2e97c991078bec735f4fd161565f2bacfe0.nq.gz
│   ├── 3efe8ecd394097460fa44032541e3352dceb94ac.nq.gz
│   ├── 485180a6a1e6c1a7691b29dab6ef61c192c822de.nq.gz
│   ├── 539830693a057b4fbd11985e9469fe417527da03.nq.gz
│   ├── 55e2bed4c280cb6ac8a989173b95cb19a02a73d3.nq.gz
│   ├── 5610a2f9868b20fbf0545b1b406fb18f497278da.nq.gz
│   ├── 5799b61b0b9063e0c33a1ba9c5a9b352be10c0a6.nq.gz
│   ├── 5adccdc8d27cdcfb9c1186eda0cb434a54db9be8.nq.gz
│   ├── 5b3b535c4c890adc59539d4b15ae790b2612d12d.nq.gz
│   ├── 5dc68cdc6bea9309a13a304e8572e40c35378a54.nq.gz
│   ├── 5f14eee575795557798357fccc9fbf10564aa04b.nq.gz
│   ├── 5f9dde4fb1121f3e29cb52c2d91ef63c076246eb.nq.gz
│   ├── 60daba7491a3cd52b6265f96e0a0949529f23959.nq.gz
│   ├── 61cf06d5ee0c53d9b582eed064b783aee2e62eaf.nq.gz
│   ├── 676a55b8014e10db64ed7cd55b1467c57b213b65.nq.gz
│   ├── 681311eb9cf453d0faddf3aacaec7357e97ba8e9.nq.gz
│   ├── 68f444141704f83d09e203bc4ffc689e27b8f671.nq.gz
│   ├── 6c719c6f890b0072cffa534b224a7057486b7598.nq.gz
│   ├── 6d3f76d79b2aae6ab3e77ae87b535d01e5b6e1a8.nq.gz
│   ├── 6db1c6e3d0918003047ef349aedeeb5c937c03db.nq.gz
│   ├── 6df2b93142986a38d44fada11db161a6131398ac.nq.gz
│   ├── 7187378f63199e3dd6408ec79c87af1d7ecf4c8a.nq.gz
│   ├── 72a3613eef34b577677d80b701e0030371d49f42.nq.gz
│   ├── 73ea76b556ba07c4b633e11e61f5c2f30fcda908.nq.gz
│   ├── 7859de321ce1bdcd5d908fba7cde463c9d93172e.nq.gz
│   ├── 7f972506b8f92bef960e852f6f06005c472d3c85.nq.gz
│   ├── 80394a74a8a53d04dd0f5c69c90107e1d2e64632.nq.gz
│   ├── 8101a9ccc4f954b046a498b85b8aa2150c0501ec.nq.gz
│   ├── 843e18aabc99d83a87b4564fd97041d4c14a7e11.nq.gz
│   ├── 885411d77247cb12b59c107625a4972d98263290.nq.gz
│   ├── 88d4571c0fc58e3af1141789f1285a02fb1bece6.nq.gz
│   ├── 895b0f22fe7881b2dbec8d657c3e748d358f521f.nq.gz
│   ├── 89c62453b508c307fd1db38ca89e545ddf8460b7.nq.gz
│   ├── 8e0b6a408f33683ae591484f4607e23ff08133d8.nq.gz
│   ├── 8ed170cf3dc8c2b55cc2c98a4aa27cc3ff66d659.nq.gz
│   ├── 91419e14371716f91ec7a4366ce59fe1d76c1270.nq.gz
│   ├── 92e98deb70faa08438826142e804b8d402633173.nq.gz
│   ├── 95052e7e018d962c019e197a17ab8638e1071188.nq.gz
│   ├── 96196fc415d650bd23516945ecf987d4d9df26bd.nq.gz
│   ├── 9778f26d565df3187e709b8af38d3338d7635d61.nq.gz
│   ├── 9a1c7f24efdd0639304bec355e6b7c151bd5d3e8.nq.gz
│   ├── 9b932049d82987497c593cf4b83008dee17a3ca8.nq.gz
│   ├── a119642ae8bf252fcf0895b4d4af9b73f2ab9aae.nq.gz
│   ├── a4de25985589b6f8928fb22183c56de81985eb03.nq.gz
│   ├── a62713e2e9a0cd155590d1d92867106df9b036db.nq.gz
│   ├── a7f9926635a07d50eb3777ab5cc18b1a851b40df.nq.gz
│   ├── aa4bfba696e4772328fea47c8a1d7c93015b3891.nq.gz
│   ├── ac0729d4e457260ccc425ed67ec6a88b803ab511.nq.gz
│   ├── ae89025e364d243d194140e1330a88148d327e20.nq.gz
│   ├── b61cf8100cf82b7c6095bae1f84b7f7528735049.nq.gz
│   ├── b876a46bcfc847636ac7aae18122d65ceef82b32.nq.gz
│   ├── b9458b7ed09c714fcad93636322221ca597c51e5.nq.gz
│   ├── bcbb62513f8dd31fd1e276d923c6ef368d297963.nq.gz
│   ├── be849ca3bb8c31933a7444b44bc013f59036e591.nq.gz
│   ├── bfd55af9755f50a84b051fdfb6ca60f811912b9c.nq.gz
│   ├── c341be944e33fae0a3dc9fa5dc617a3ac9fe2c65.nq.gz
│   ├── c4cd1ce18aa7471cdafef31cff5c1ece8255694f.nq.gz
│   ├── c50e00a35996d00e8f86050003c550b22c88a3c8.nq.gz
│   ├── c51bdca28ecc66699e0cb80a44acdb807aa343ff.nq.gz
│   ├── c94d745311ab03d273a11bbd7ea0148822f46173.nq.gz
│   ├── ca81ef858e0346d6c636922f30591ab5d3c6c740.nq.gz
│   ├── cbc88f3bc7cc1b8379e6ed577b6a072152f6b852.nq.gz
│   ├── cd16e43e6bd4c874803e015cfe4ff555f405c7fe.nq.gz
│   ├── cd6cc141ef4506fb9681f4d0ef8990be091fd5d4.nq.gz
│   ├── ce833bd4eea5be2a7ed6b4ad0057dceda84aafad.nq.gz
│   ├── cf9e2d80214a83afb53159526b217e7b367b2b5d.nq.gz
│   ├── d2c41716b94be5d1a919bbed94043f3929a30633.nq.gz
│   ├── d4bbf41f76b8b0f8b8fd152953753ae29c60c6b5.nq.gz
│   ├── d5b3ae725135e29a9e0e09f409ab2d3ee33dd815.nq.gz
│   ├── d7ca263bcb75bdbb5d2642381496b67ba6b03952.nq.gz
│   ├── d90f024cd687523bbee18307e95cbc53e63ecd62.nq.gz
│   ├── d9cbe9415a9b968bebed1974b44e04746ad81a34.nq.gz
│   ├── da58f36ca1afe6aea2af888d459b5c76821905f2.nq.gz
│   ├── dbc499cef06a9b51d3b66babd761a658f3f2a32e.nq.gz
│   ├── dd060681b5b7b084e55e446ce9457a1fd152843c.nq.gz
│   ├── de4063a2c012a51d7dc10e8b41b05921345a3912.nq.gz
│   ├── de6db2a3b4c16f0e4bcaf9189958f578989c9de4.nq.gz
│   ├── de9730c5e9747be215921cae70ef7d5c7b0cc147.nq.gz
│   ├── e5f5d8baa19dc667020ae74aa91d28edac879796.nq.gz
│   ├── e72e72decfef4e1cc6e8f65bffac8175fe5a57b6.nq.gz
│   ├── e7e4b350f3c2286dd919284aadc5a2f66491b6f3.nq.gz
│   ├── e91b368e60669488898b3ca61b528ce46f2e36bf.nq.gz
│   ├── e9be38af86bcac7d77fcdc2e2e480d3a4ee4ce64.nq.gz
│   ├── eb02b239a6e939a84074e2eb9e1e319f04ab4096.nq.gz
│   ├── eb37b028c4e906f537e51dbf154e5848ebe41a57.nq.gz
│   ├── eb84ea48d943f7b2ae80ca7384099245a2a7515b.nq.gz
│   ├── ee917965674a2f293acbaee094c9e425f98a9b4e.nq.gz
│   ├── f1b64f04cd79391959113d07bc788b81b0cdd5b8.nq.gz
│   ├── f42dd785dbbc3b5da2ee1e110c92d5f1b81e7c3e.nq.gz
│   ├── f48b4544b0d069dfa020ccad09d0f885c740ebd6.nq.gz
│   ├── f560436bf1bbf6fd90b4571e7be5840ea83d75ea.nq.gz
│   ├── f93bfd80a3113f36ff674da90fc1669b762b09b1.nq.gz
│   ├── fd00f7c29ef6bb29a74658ea6107adc38c680e6f.nq.gz
│   ├── fef752ab0834de26fd07073e894163b5c2879784.nq.gz
│   └── ff7b7e09665f8b4305ef91f8bd46e4e841fb17ce.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 29b03bc46ce85c8681afe8b1489a9344af123637.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 128 files
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

[samuelcolvin/openartifact](https://github.com/samuelcolvin/openartifact)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
