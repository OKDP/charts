[![ci](https://github.com/okdp/charts/actions/workflows/ci.yml/badge.svg)](https://github.com/okdp/charts/actions/workflows/ci.yml)
[![release-please](https://github.com/okdp/charts/actions/workflows/release-please.yml/badge.svg)](https://github.com/okdp/charts/actions/workflows/release-please.yml)
[![License Apache2](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center">
    <img width="400px" height=auto src="docs/logo/inverted/okdp-inverted.png" />
</p>


Provides a collection of [helm](https://helm.sh/) charts used by the [okdp](https://okdp.io) Platform.

## TL;DR

```console
$ helm repo add odkp https://okdp.github.io/charts/
$ helm install my-release odkp/[chart]
```

## Requirements

- Kubernetes cluster
- [Helm](https://helm.sh/) installed

> [!NOTE]
> An OKDP sandbox, with all these helm charts installed, is under development and you can use it once released.
> 