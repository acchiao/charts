# charts

## Prerequisites

  * [Helm] ^3.7.0

[Helm]: https://helm.sh/

## Charts

* [galactus](charts/galactus/): A Helm chart for [papaya]

[papaya]: https://github.com/acchiao/papaya/

## Usage

Add the chart repository.

```sh
helm repo add acchiao https://acchiao.github.io/charts
helm repo update
```

To search the repository:

```sh
helm repo search acchiao
````

To install the charts:

```sh
helm install [RELEASE_NAME] acchiao/galactus
```

To upgrade the charts:

```sh
helm upgrade --install [RELEASE_NAME] acchiao/galactus
```

To uninstall the charts:

```sh
helm uninstall [RELEASE_NAME]
````
