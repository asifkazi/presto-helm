
Presto Helm Charts
===========

Fast distributed SQL query engine for big data analytics that helps you explore your data universe


## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add presto-helm https://asifkazi.github.io/presto-helm/charts/
```

You can then run `helm search repo presto-helm` to see the charts.

Then you can install chart using:

```console
helm install my-presto asifkazi/prestodb --version 0.268
```
