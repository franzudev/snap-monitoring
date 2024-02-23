
[![Made for](https://img.shields.io/badge/made_for-k8s-green)](https://img.shields.io/badge/made_for-k8s-green)
[![With](https://img.shields.io/badge/with-helmfile-white)](https://img.shields.io/badge/with-helmfile-white)
[![For](https://img.shields.io/badge/for-monitoring-red)](https://img.shields.io/badge/with-helmfile-red)

# K8S monitoring

A simple monitoring setup with Thanos, Prometheus, Grafana, on-top of minIO. There's a kafka cluster if you want to process prometheus metrics.

##  Requirements
- a kubernetes cluster
- [helmfile](https://github.com/helmfile/helmfile)


## Usage/Examples

Simple as:

```shell
git clone https://github.com/franzudev/snap-monitoring.git
cd snap-monitoring
helmfile apply
```


## Authors

- [@franzudev](https://www.github.com/franzudev)
