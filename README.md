# Repolex Knowledge Graph of twisted/twistedchecker

RDF knowledge graph data for [twisted/twistedchecker](https://github.com/twisted/twistedchecker), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/twistedchecker
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a69f3f7d80f2f42d915bc128d4257a2e15804e4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a69f3f7d80f2f42d915bc128d4257a2e15804e4
│           └── chunk-001.nq.gz
├── blob
│   ├── 07030af8db5793242e2e0fb810b4bc51f3d32d2a.nq.gz
│   ├── 07ad65b02834e530b1aa6669d14b52de4d273fc1.nq.gz
│   ├── 09af19cdc1fa548555b0712a63c4631c7547785f.nq.gz
│   ├── 0c5d3925fb406a01a0fdf9651b15219a85aca57c.nq.gz
│   ├── 100d27204ff1183ebdfd3c14d3898a69490c55fa.nq.gz
│   ├── 12f5b7bd08a49bff5d28cda87fa7638aaebb4bdf.nq.gz
│   ├── 16bed20a24f49869ea8f70b9dfa5224057220638.nq.gz
│   ├── 177beabf261321f747029f6c283a9182d5dbcb85.nq.gz
│   ├── 196bf2b1ce151e7bbe8e2e7662adb990ec1ceb3f.nq.gz
│   ├── 1b38cee26501272f388daa97ecd450f74273cee8.nq.gz
│   ├── 1b684243acefe732aee143662859557db3a49d93.nq.gz
│   ├── 1b92926009ef06c85928fd8aa16d3c3cc5a1c781.nq.gz
│   ├── 1bfffc70a70fba82f9ee6d63fb53b38613df28bf.nq.gz
│   ├── 1c13c1c6e590548e40d30eea7be12f50045b14d3.nq.gz
│   ├── 1c32ab8dde7a37d392ee659a6ea689faa12727e2.nq.gz
│   ├── 1d40add3954300911b21158d4fb274846b0b522f.nq.gz
│   ├── 216e73a3e98873228d5139c74e8d9ee035216ad2.nq.gz
│   ├── 281c13adf06e72133ebd8c9e2dfadb0f9b2be13b.nq.gz
│   ├── 2f457819d682d6465ea953f714134dc92342dd62.nq.gz
│   ├── 305e74afeb7e69329548470cd4fe866c4160946b.nq.gz
│   ├── 3c53937e4e9f14704aaae7227ee70ba43b856a8d.nq.gz
│   ├── 3c6e79cf31da1c0433d2fa666bf50b53f6359f26.nq.gz
│   ├── 3eaa875ef27d37c38704fa518ada6d3562b0df64.nq.gz
│   ├── 3fa8c2ac729e2328ee637967b917ca6808379d84.nq.gz
│   ├── 4160ea52121b4563474333c9e9df8ee8125f63d2.nq.gz
│   ├── 4400294a76bed224d15bad711cd02c7831dc7209.nq.gz
│   ├── 45b5b1f7c03f5d8f9387e4067066d101335602df.nq.gz
│   ├── 48bbf90aa4d6c33c85f154ef677434913468babc.nq.gz
│   ├── 4bd5bc550a544f28bb0c37f4dd8c1c7d5d72433e.nq.gz
│   ├── 587e03729af37899002d464d91411ce71d72e956.nq.gz
│   ├── 618e61a12de9ca328972b8a883821691635df83a.nq.gz
│   ├── 620461e2eabc6ca330c770bdee7dbe101d5927c0.nq.gz
│   ├── 631d56c47673b84a2e9fd0e555c222cc5b678ef0.nq.gz
│   ├── 6421f4e33aef9b494efb20118d0b1bbec3f94521.nq.gz
│   ├── 6600c0de125b0f90a59256754a04696094df7b15.nq.gz
│   ├── 6d91968cb1bbcc39bd1c186959b18668f5364548.nq.gz
│   ├── 6db5353338deab47bb207641f13471ab15398948.nq.gz
│   ├── 706287157a522d77d1ecaa90ad4a16efc1805f32.nq.gz
│   ├── 7183e1ab8e8a196822b01389fbd3ef6b524efee0.nq.gz
│   ├── 84f417f7e655ef54ec00276f67407d65b2f7c426.nq.gz
│   ├── 88f64f314c34da2ff10fb362473b47f2b639742d.nq.gz
│   ├── 8b276429115c89a8969799fa495a99590dcd008b.nq.gz
│   ├── 8ec1e3be7ff6baddf47176831a992f5dce889ba9.nq.gz
│   ├── 8f4adfea2d05f0eceabf49643e9fdbafcaf950c1.nq.gz
│   ├── 93d8d708b017d37d30ffa4e4cec61b5c8491b87a.nq.gz
│   ├── 97567b73850937c5eb39ac0461827062b5c15e32.nq.gz
│   ├── 981e2857068d5b96cf0d1d77e050eb389334c46c.nq.gz
│   ├── 9ab51da9898a58457b98821756b4ea632cf6e6c8.nq.gz
│   ├── 9bdb220b589b6db220d3944931fdd7be1840b9dd.nq.gz
│   ├── 9dbbc3176ec6c4a10d40a6b66a61921fa21afd62.nq.gz
│   ├── 9e35dbd55dc5323b3934c32e636a8ef99f987e1c.nq.gz
│   ├── b0ab58f0fcedff86a080c7d5d7d29e4e6a2340e3.nq.gz
│   ├── b138217e46599bcc2b777fb9cc1e187fb77aae9e.nq.gz
│   ├── b1ecee7c0dd4ee05afedba1701b66abe416b15b9.nq.gz
│   ├── b46534be218257f16d6c3796d8ca048e6b6117d4.nq.gz
│   ├── b9b0a49101b2c983100cfe65a0fecb20c4bbff87.nq.gz
│   ├── ba4656ce11e3b2b7851e06ff7c4800a81ec0f3b8.nq.gz
│   ├── baf87695ee1bd86c29dbd3c411fa87394b4cd43e.nq.gz
│   ├── bbf65fcfd953d203ddee63b6cdad7ed1bbd8f352.nq.gz
│   ├── bcd86af729d602aee168de7183364492d08e7ea6.nq.gz
│   ├── bcdb8ae8bd8762a79aac0b8e0e43ad1cb09bbf78.nq.gz
│   ├── be405ad5b7117668ab848d466503bda5eef548ab.nq.gz
│   ├── be44c5405db22d1a494925ef913f5127b9f55213.nq.gz
│   ├── c04849379518191a5b6d54a231fcdeef293a5e9b.nq.gz
│   ├── c195247715ac5b97c3c5a15fb9fdae7e47f71a77.nq.gz
│   ├── c253d6cc724398cb2b006d17dad105afd9205fdf.nq.gz
│   ├── ca1c4125adc1f0fcea771c212549ac4c879e5f10.nq.gz
│   ├── cca223873468834be9fba00b73d18da032cb918b.nq.gz
│   ├── cda3af63468cff81db87662eb01928efd5526441.nq.gz
│   ├── cdc15581702e93336757a6644b14f2f5db392696.nq.gz
│   ├── dbd41e7953e71467725302bf44918c8bf045aa73.nq.gz
│   ├── ddc0fba8506281941357c6c66925bab3c8b01875.nq.gz
│   ├── e25050b4402f48e30dd5578fed9f5b958dcc1fe0.nq.gz
│   ├── e26794e6a3ae38e155ea78055c149860c6e3bb9a.nq.gz
│   ├── e3d13dff5719ac4daf563d08a978d0621176e0f3.nq.gz
│   ├── e459b00523355c4c31144ec331236fd5ed3c462e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9cd818d0e6530708354c77c9c58f99f4f964845.nq.gz
│   ├── eac0625b5889233185d81bcd762e87613a36bdf4.nq.gz
│   ├── eb8ca2e009b9360b6b0c0c1bf75f366e00310223.nq.gz
│   ├── ecc13b139d008b53b1956bff91f47eee6dcb0283.nq.gz
│   ├── ed5f2d73acb5948455b0ce9dbf3ffa4331742dc2.nq.gz
│   ├── edd4be0537a1ae4a92167a96ddfae147be6de3c4.nq.gz
│   ├── f0d024556836ce0ae36fb2a76cf51bb685c78d80.nq.gz
│   ├── f4ecf6d7b2f8499c215e871557636ac328c77306.nq.gz
│   ├── f76ee953915c56c1eb7c985a6f2d0b94bbe053ce.nq.gz
│   ├── fda2f5cfbb5e99ce4891868964ddadfaa34ceba7.nq.gz
│   └── ff76a9210ebe269a77a889378944c1fbcbed0e6a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4a69f3f7d80f2f42d915bc128d4257a2e15804e4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[twisted/twistedchecker](https://github.com/twisted/twistedchecker)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
