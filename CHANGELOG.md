# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2022-01-05

### Added

- Helm, add configurable container securityContext with secure defaults.

### Changed

- Bump `starboard`, `logr`, and `controller-runtime` dependency versions.
- Remove unneeded `releaseRevision` annotation from deployment.

### Fixed

- Helm, fix incomplete metric name in pods with high/critical CVEs panel

## [0.1.4] - 2021-12-14

### Changed

- Helm, remove unused rbac config and add if for psp and networkpolicy yaml.

## [0.1.3] - 2021-12-10

### Changed

- Make pod resource requests/limits configurable via helm values.

## [0.1.2] - 2021-11-29

### Changed

- Push images to Aliyun.
- Add `starboard-exporter` to AWS and Azure app collections.

## [0.1.1] - 2021-11-26

### Added

- Make target labels more easily configurable in `values.yaml`.

## [0.1.0] - 2021-11-26

### Added

- Add configurable target labels.
- Add Grafana dashboard.
- Support custom labels for ServiceMonitor.

## [0.0.1] - 2021-11-18

### Added

- Add `image_vulnerabilities` metric per-CVE per-image and `image_vulnerabilities_count` metric for summaries.
- Add ServiceMonitor to scrape metrics.

[Unreleased]: https://github.com/giantswarm/starboard-exporter/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/giantswarm/starboard-exporter/compare/v0.1.4...v0.2.0
[0.1.4]: https://github.com/giantswarm/starboard-exporter/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/giantswarm/starboard-exporter/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/giantswarm/starboard-exporter/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/starboard-exporter/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/starboard-exporter/compare/v0.0.1...v0.1.0
[0.0.1]: https://github.com/giantswarm/starboard-exporter/releases/tag/v0.0.1
