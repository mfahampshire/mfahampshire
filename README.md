I run one part of DevRel (everything aside from node operation) and do integrations for the mixnet project Nym. 

Current work centers around: 
- Maintaining the [Nym docs](https://nym.com/docs)
- Working on the [Nym SDKs](https://nym.com/docs/developers) 

Recent work: 
- Implementing the [Diataxis framework](https://diataxis.fr/) for the Nym docs
- Debugging WASM runtime errors and multiple (Go + Rust) runtime interaction for [`mixFetch`](https://nym.com/docs/developers/typescript/playground/mixfetch) + modifying its concurrency restrictions
- Rust SDK [`stream`](https://nym.com/docs/developers/rust/stream) module
- [`smolmix`](https://github.com/nymtech/nym/commit/7ceaf9a40ec9ee41758100c9785dcf836b9ff3e7) Rust crate (crate publication + docs forthcoming)
- [crates.io](https://crates.io/search?q=nym) preparation and publication flows for majority of the Nym monorepo crates 

Main focuses: 
- System programming with Rust (especially focussed on networking abstractions)
- Using WASM for privacy-preserving code within the confines of browsers (e.g. userspace TCP/IP, certs, and security restrictions) 

Note on Git commit heatmap: since we use squash-and-merge for PRs, the majority of the commits in the heatmap below are merged PRs into the Nym monorepo. 
