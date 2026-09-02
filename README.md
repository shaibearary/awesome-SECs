# Awesome SECs

> A community-maintained directory of public GitHub projects demonstrated during Sovereign Engineering Cohorts (SEC).

[Sovereign Engineering](https://sovereignengineering.io/) brings builders together for six weeks of shipping and demos. This list organizes projects by cohort and records only demos that have a public GitHub repository.

## Contents

- [SEC 8](#sec-8)
- [Contributing](#contributing)

## SEC 8


### André

- Week 2: [FIPS Exit Node](https://github.com/fr34aky/fips-exit-gate)![stars](https://img.shields.io/github/stars/fr34aky/fips-exit-gate.svg?style=social) - An FIPS exit-node project for routing mesh traffic to external networks.
- Week 3: [FIPS Layer 7 Protection](https://github.com/fr34aky/fips-shield)![stars](https://img.shields.io/github/stars/fr34aky/fips-shield.svg?style=social) - Layer 7 protection for services and traffic running through FIPS.
- Week 4: [FIPS GW Android](https://github.com/fr34aky/fips-android)![stars](https://img.shields.io/github/stars/fr34aky/fips-android.svg?style=social) - An Android VPN app embedding the FIPS mesh daemon with per-app split tunneling and `.fips` DNS.
- Week 5: [myco-desktop](https://github.com/fr34aky/myco-desktop)![stars](https://img.shields.io/github/stars/fr34aky/myco-desktop.svg?style=social) - A desktop application for working with Myco.



### JeffG

- Week 1: [Automated testing with generated scenarios](https://github.com/marmot-protocol/mdk)![stars](https://img.shields.io/github/stars/marmot-protocol/mdk.svg?style=social) - Generated scenarios, conformance tests, and simulation work for the Marmot Development Kit.
- Week 2: [fips-mac](https://github.com/erskingardner/fips-mac)![stars](https://img.shields.io/github/stars/erskingardner/fips-mac.svg?style=social) - A macOS project for running and integrating FIPS on Mac; and [wok](https://github.com/erskingardner/wok)![stars](https://img.shields.io/github/stars/erskingardner/wok.svg?style=social) - A Wok codebase used for the FIPS integration demo.
- Week 3: [wok with fips](https://github.com/erskingardner/wok/commit/bec28dd94b3b2c44791ede52fec6ce11c4e5d59d)![stars](https://img.shields.io/github/stars/erskingardner/wok.svg?style=social) - A commit documenting the Wok and FIPS integration state; and [marmot over fips](https://github.com/marmot-protocol/mdk/tree/codex/fips-relay-transport-spike)![stars](https://img.shields.io/github/stars/marmot-protocol/mdk.svg?style=social) - A branch exploring relay transport over FIPS.



### hzrd149

- Week 1: [stlstr](https://github.com/hzrd149/stlstr) - A Thingiverse-style app for publishing, browsing, and discussing 3D printables on Nostr, with a deliberately small host shell and the product UI split into sandboxed NIP-5D napplets.
- Week 2: [Napplet Portal](https://github.com/hzrd149/napplet-portal) - A Deno Fresh runtime for one trusted operator, where a mobile browser hosts a sandboxed napplet while the server owns account credentials, Nostr relay connections, and state.
- Week 3: [Hashtree explainer](https://gitworkshop.dev/hzrd149.com/git.shakespeare.diy/hashtree-explainer) - A slide-based walkthrough of the four draft Blossom BUDs that let a client store a whole directory tree using nothing but ordinary blobs.
- Week 3: [deno2nix](https://github.com/hzrd149/deno2nix) - Small Nix builders for installing locked Deno dependencies and packaging Deno applications that run without network dependency resolution.
- Week 3: [nostr-ownership](https://github.com/hzrd149/nostr-ownership) - A specialized Nostr relay that validates ownership definitions (`kind:3900`) and transfers (`kind:3901`) and derives a deterministic per-relay owner; and [Collectstr](https://github.com/hzrd149/nostr-collectables) - A browser client for creating, transferring, inspecting, and showcasing ownership claims over Nostr events.
- Week 4: [nix-golsim](https://gitworkshop.dev/hzrd149.com/git.shakespeare.diy/nix-golsim) - A deterministic Conway's Game of Life frame renderer that runs a named starting pattern on a toroidal grid and serves the preview over HTTP.
- Week 4: [nixstr-cache](https://github.com/hzrd149/nixstr-cache) - Publishes and retrieves Nix binary caches through Nostr and Blossom while presenting a normal HTTP binary cache to Nix.
- Week 6: [nostr-relay-tray with fips](https://github.com/hzrd149/nostr-relay-tray/tree/fips-integration) - A desktop Nostr relay tray app with its proxy replaced by a fips mesh integration, plus platform-appropriate data storage locations.



### CruxCoach

- Week 4: [Offline app and board-data sharing](https://github.com/CruxCoach/CruxCoach)![stars](https://img.shields.io/github/stars/CruxCoach/CruxCoach.svg?style=social) - A phone-to-phone local hotspot flow for sharing the APK and public board catalogues without internet access.
- Week 5: [Shared climbing playlists over a local BLE/FIPS mesh](https://github.com/CruxCoach/CruxCoach)![stars](https://img.shields.io/github/stars/CruxCoach/CruxCoach.svg?style=social) - An encrypted, serverless mesh that keeps a group's climbing playlist and connected-board state in sync over BLE.
- Week 6: [MoonBoard logbook import via Android Accessibility](https://github.com/CruxCoach/CruxCoach)![stars](https://img.shields.io/github/stars/CruxCoach/CruxCoach.svg?style=social) - An on-device importer that transfers ascents and attempts from the official MoonBoard app into CruxCoach.



### brenorb

- Week 1: [Granola](https://github.com/brenorb/granola)![stars](https://img.shields.io/github/stars/brenorb/granola.svg?style=social) - Cashu atomic swaps coordinated over Nostr.
- Week 2: [Hosted Nowhere CLI](https://github.com/brenorb/nowhere-cli)![stars](https://img.shields.io/github/stars/brenorb/nowhere-cli.svg?style=social) - A CLI port of Nowhere, the sites that are hosted nowhere.
- Week 4: [Cashu Sync for Silent Link](https://github.com/brenorb/cashu-sync)![stars](https://img.shields.io/github/stars/brenorb/cashu-sync.svg?style=social) - Synchronizing Cashu wallets across devices for Silent Link.
- Week 5: [NutFT](https://github.com/brenorb/NutFT)![stars](https://img.shields.io/github/stars/brenorb/NutFT.svg?style=social) - Nut Fungible Tokens, an application-level Cashu extension (draft NUT-31) for proofs that represent individually identifiable bearer assets; and [600 Billion Timelock TCG](https://github.com/BIMbeamFLX/600BillionTimelockTCG)![stars](https://img.shields.io/github/stars/BIMbeamFLX/600BillionTimelockTCG.svg?style=social) - The trading card game built on that draft, where Bitcoin proves the time and Nostr owns the object.
- Week 6: [Envelope](https://github.com/brenorb/envelope)![stars](https://img.shields.io/github/stars/brenorb/envelope.svg?style=social) - An nsite-hosted opener shell for content-addressed Nostr napplets, for unstoppable napplets.



### julien

- Week 1: [nostrpkgs](https://github.com/jurraca/nostrpkgs)![stars](https://img.shields.io/github/stars/jurraca/nostrpkgs.svg?style=social) - Nix packages for Nostr software.
- Week 2: [ngit-deploy](https://github.com/jurraca/ngit-deploy)![stars](https://img.shields.io/github/stars/jurraca/ngit-deploy.svg?style=social) - An example ngit-grasp NixOS deploy configuration.
- Week 3: [pyramid-nix](https://github.com/jurraca/pyramid-nix)![stars](https://img.shields.io/github/stars/jurraca/pyramid-nix.svg?style=social) - A Nix flake for fiatjaf's Pyramid relay; [fips (nix-module)](https://github.com/jurraca/fips/tree/nix-module)![stars](https://img.shields.io/github/stars/jurraca/fips.svg?style=social) - A NixOS module for the Free Internetworking Peering System; and [demo-nixos](https://github.com/jurraca/demo-nixos)![stars](https://img.shields.io/github/stars/jurraca/demo-nixos.svg?style=social) - A bare-basics NixOS configuration to deploy them from.
- Week 4: [narwal](https://github.com/jurraca/narwal)![stars](https://img.shields.io/github/stars/jurraca/narwal.svg?style=social) - Nix packages over Nostr; and [narwal-publisher](https://github.com/jurraca/narwal-publisher)![stars](https://img.shields.io/github/stars/jurraca/narwal-publisher.svg?style=social) - Publishes Nix packages to Blossom and resolves them via Nostr.
- Week 6: [Mist](https://github.com/jurraca/mist)![stars](https://img.shields.io/github/stars/jurraca/mist.svg?style=social) - A Phoenix web interface to Nostr, with a single GenServer owning every relay subscription.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for the entry format and submission rules.
