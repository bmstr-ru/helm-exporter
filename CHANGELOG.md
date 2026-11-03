# Changelog

## [1.5.0](https://github.com/bmstr-ru/helm-exporter/compare/1.4.0...1.5.0) (2026-11-03)


### Features

* add healthz handler ([a91257a](https://github.com/bmstr-ru/helm-exporter/commit/a91257a0071dbfb509246ebd05acc340de1d9c79))
* add release-please workflow and configuration ([59b8b12](https://github.com/bmstr-ru/helm-exporter/commit/59b8b12438429f539ac5af313ec21a8809239760))
* Adding Basic Auth to access Helm repo ([#77](https://github.com/bmstr-ru/helm-exporter/issues/77)) ([32bf24c](https://github.com/bmstr-ru/helm-exporter/commit/32bf24c78f610d067ce90661f9d19537b2d22360))
* **app:** 192 Add common labels to chart ([930cff8](https://github.com/bmstr-ru/helm-exporter/commit/930cff8ebc3c49f8b5f032d55cb57085a9cf373e))
* **chart:** add `metricRelabelings` and `relabelings` on serviceMonitor ([#85](https://github.com/bmstr-ru/helm-exporter/issues/85)) ([925390c](https://github.com/bmstr-ru/helm-exporter/commit/925390c371fe32ac4263c3bd5dc3ff9691a061a8))
* Include grafana dashboard into the chart ([#79](https://github.com/bmstr-ru/helm-exporter/issues/79)) ([b876878](https://github.com/bmstr-ru/helm-exporter/commit/b87687837bdcc668e6d72d8e46011ef28504a369))
* use scratch base ([c7cb7ee](https://github.com/bmstr-ru/helm-exporter/commit/c7cb7ee44baaa3c881a1a5efe829fb3267070e20))


### Bug Fixes

* **ci:** remove token from public helm-charts checkout ([d60bef4](https://github.com/bmstr-ru/helm-exporter/commit/d60bef46df5d61d29fc5d06a2ac7411a68137250))
* Dockerfile to reduce vulnerabilities ([e3c49dc](https://github.com/bmstr-ru/helm-exporter/commit/e3c49dc7b76f2bf3370647796f02af0371397920))
* Dockerfile to reduce vulnerabilities ([f0d8de0](https://github.com/bmstr-ru/helm-exporter/commit/f0d8de04d0c2622ea8d8c5859551bf7048519822))
* wait for the clients before starting to collect metrics when using the interval-duration option ([bbf045b](https://github.com/bmstr-ru/helm-exporter/commit/bbf045b3a160e9896fbe2065e420ac65cfbfa14f))


### Miscellaneous Chores

* update go mods ([2bd970b](https://github.com/bmstr-ru/helm-exporter/commit/2bd970bf914e389d3d375809b356d526543c23a5))
* update go mods to fix known vulnerabilities ([e2eee28](https://github.com/bmstr-ru/helm-exporter/commit/e2eee287e72124cd0d54f8996e4bdc4c5caf557b))
* update go to 1.26 ([91e3dd3](https://github.com/bmstr-ru/helm-exporter/commit/91e3dd3331a858f4ee755032820dcb9285f99769))
