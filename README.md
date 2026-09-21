# Disco release artifacts

Public distribution files for Disco: reviewed source snapshots, container-install files, benchmark sources and evidence, and launch materials. The development repository and its history remain private.

## Benchmark sources and evidence

[September 2026 benchmark release](https://github.com/Dyluhn/disco-releases/releases/tag/benchmarks-2026-09-21) includes the compact source/score-audit bundle, the full DeepResearch evidence publication copy, and all 24 App-Bench generated source archives with final grading evidence. These are local comparisons, not official leaderboard submissions. Read the included methodology, fairness disclosures, redaction ledgers, and checksum manifests.

## Application release

The [Disco v0.2.0 source and launch artifacts](https://github.com/Dyluhn/disco-releases/releases/tag/v0.2.0) are published from source commit `e06ad0eb3e65576d80b406c7ac191562051f0c93`. The prerelease includes a source archive, Compose files, frontend build, validation results, and launch video. Native amd64 images are built and locally tested; registry uploads and anonymous image-pull verification are still pending. Build locally from the source archive using its Compose build override.

The public repository commit identifies distribution documentation. The source archive and image metadata identify the actual Disco source commit.

## License and provenance

Disco source is Apache-2.0. Benchmark tasks, copied vendor/reference documents, and third-party evidence retain upstream authorship and terms. The Apache license in this repository does not relicense those materials.

## Reference documentation

The [self-host reference](docs/self-host.md), [capability overview](docs/overview.md), and [source README](SOURCE-README.md) are based on the reviewed source snapshot, with archive-based installation links for public distribution. Historical source documentation may describe planned multi-architecture registry publishing; consult the release notes for the actual published architectures and availability. Some governance checks require the development Git history, which is not part of the source archive.
