# charts

[![CI](https://github.com/acchiao/charts/actions/workflows/ci.yml/badge.svg)](https://github.com/acchiao/charts/actions/workflows/ci.yml)
[![Release](https://github.com/acchiao/charts/actions/workflows/release.yml/badge.svg)](https://github.com/acchiao/charts/actions/workflows/release.yml)
[![pages-build-deployment](https://github.com/acchiao/charts/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/acchiao/charts/actions/workflows/pages/pages-build-deployment)

## Prerequisites

  * [Helm] ^3.8.0

[Helm]: https://helm.sh/

## Charts

* [galactus](charts/galactus/): A Helm chart for [galactus]

[galactus]: https://github.com/acchiao/galactus/

## Usage

Add the chart repository.

```sh
helm repo add raccoon https://charts.raccoon.team
helm repo update
```

To search the repository:

```sh
helm repo search raccoon
````

To install the charts:

```sh
helm install [RELEASE_NAME] raccoon/galactus
```

To upgrade the charts:

```sh
helm upgrade --install [RELEASE_NAME] raccoon/galactus
```

To uninstall the charts:

```sh
helm uninstall [RELEASE_NAME]
````
