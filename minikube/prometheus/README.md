# Promethues monitoring settings

Install using go commmand or brew

Kind have dependencies with the Cluster image, so make sure the version we have.

```bash
go install sigs.k8s.io/kind@v0.11.1 (or) brew install kind
```

```bash
brew install helm
```

### Create KIND cluster and install monitoring

```bash
make cluster
make monitoring
```
