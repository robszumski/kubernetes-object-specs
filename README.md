# Kubernetes object and CRD specs

Turns out it is hard to get the object spec for built-in Kubernetes resources. Here's a whole pile of em.

These were pulled with [kcp's object puller](https://github.com/kcp-dev/kcp). Note that this just dumps them out in the current directory, which will be your kcp git directory.

```
$ go run ./cmd/crd-puller/pull-crds.go --kubeconfig path/to/your/cluster/kubeconfig
```
