# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0] - 2022-03-31

### Changed

- Cleaned up values.yaml file

## [0.3.0] - 2022-03-28

### Added 

- Enable snapshotter by default.

## [0.2.2] - 2022-02-14

## [0.2.1] - 2022-02-14

### Changed

- Update helm charts with latest upstream versions

## [0.2.0] - 2022-01-26

### Changed

- Set the default reclaim policy to delete.
- Set default to create Loadbalancer health monitors 

## [0.1.1] - 2022-01-04

### Added

- Add toleration for `node-role.kubernetes.io/master="":NoSchedule` taint (default CAPI CP taint).

## [0.1.0] - 2021-12-03

[Unreleased]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.4.0...HEAD
[0.4.0]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.2.2...v0.3.0
[0.2.2]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.1.1...v0.2.0
[0.1.1]: https://github.com/giantswarm/cloud-provider-openstack-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/cloud-provider-openstack-app/releases/tag/v0.1.0
