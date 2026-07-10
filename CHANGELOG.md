# Changelog

All notable changes to `sqlmerge`, derived mechanically from the [monorepo commits](https://github.com/indexable-inc/index/commits/main/packages/sqlmerge) that touched [`packages/sqlmerge`](https://github.com/indexable-inc/index/tree/main/packages/sqlmerge). Section names follow [Keep a Changelog](https://keepachangelog.com/en/1.1.0/); the mirror tracks the monorepo continuously, so entries are grouped by month instead of by release.

## 2026-07

### Changed

- clone: consolidate duplicate implementations ([#2618](https://github.com/indexable-inc/index/issues/2618)) ([`6b1a52b`](https://github.com/indexable-inc/index/commit/6b1a52b7a706fba73132a8950421817e9016275c), 2026-07-09)
- readme sweep: core tools (sqlmerge, dag-runner, astlog, scipql, mirror, unibind, indexbench) ([#2097](https://github.com/indexable-inc/index/issues/2097)) ([`d3aeadd`](https://github.com/indexable-inc/index/commit/d3aeadd2a5da98209e3247e5c31dcb9643d7c411), 2026-07-06)
- repo metadata: declarative description/homepage/topics, synced and required by CI ([#2069](https://github.com/indexable-inc/index/issues/2069)) ([`feda2d4`](https://github.com/indexable-inc/index/commit/feda2d4bf7893a83121eea864cf5a3505564ec95), 2026-07-06)
- mirror: opt-in auto-generated standalone repos per package ([#2022](https://github.com/indexable-inc/index/issues/2022)) ([`f0ec27f`](https://github.com/indexable-inc/index/commit/f0ec27fb31325c3e54582e463ac9076db8c9bf47), 2026-07-06)
- sqlmerge: declarative per-table conflict policy (sqlmerge.toml) ([#1889](https://github.com/indexable-inc/index/issues/1889)) ([`04d3f04`](https://github.com/indexable-inc/index/commit/04d3f04cb42ad650fbdb3f340c9cbf8cba323858), 2026-07-06)
- sqlmerge: ignore SQL comments in schema normalization ([#1887](https://github.com/indexable-inc/index/issues/1887)) ([`ef1c064`](https://github.com/indexable-inc/index/commit/ef1c0649d4387ad68b99e9e0f3e2a67d1566e16d), 2026-07-06)
- sqlmerge: git merge driver for SQLite databases + base-profile git wiring ([#1876](https://github.com/indexable-inc/index/issues/1876)) ([`0b5881b`](https://github.com/indexable-inc/index/commit/0b5881bc2f2d6a68e38dc40039ae5952750b4240), 2026-07-06)
