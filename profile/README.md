# NostrMash

A Go-based, Docker-native Nostr ingestion and indexing platform. Raw events stay durable in
Postgres. Read models can be rebuilt. The API speaks the Primal Cache boundary so existing clients
can use it.

The public explorer is [nostrmash.com](https://nostrmash.com). The license is the
[Unlicense](https://unlicense.org).

## Repositories

| Repository | What it does |
| --- | --- |
| [nostrmash](https://github.com/nostrmash/nostrmash) | Go-based, Docker-native Nostr ingestion and indexing platform. Durable raw events in Postgres, rebuildable read models, and a Primal-compatible API for existing clients. |
| [nostrmash-web](https://github.com/nostrmash/nostrmash-web) | Public explorer for NostrMash. Search notes and profiles, and browse trends, relays, and network stats. |

The explorer reads the NostrMash API and does not talk to relays itself. SmartFlowSocial's
[cache worker](https://github.com/smartflowsocial/smartflowsocial-cache-worker) calls that API
before it falls back to Primal.

## Start

- [Open the explorer](https://nostrmash.com)
- [Run the index](https://github.com/nostrmash/nostrmash#quick-start)
- [Report a security issue](https://github.com/nostrmash/nostrmash/blob/main/SECURITY.md)
- [Read the contributor guide](https://github.com/nostrmash/nostrmash/blob/main/CONTRIBUTING.md)
