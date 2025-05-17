# OpenFGA Operator

[![Release](v1Alpha1)](https://github.com/ZEISS/openfga-operator/actions/workflows/release.yml)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

OpenFGA Operator automates the management of [OpenFGA](https://openfga.dev/) instances in Kubernetes.

## Installation

```shell
docker login <registry>
make docker-build IMG=<registry>/openfga-operator:latest
docker push <registry>g/openfga-operator:latest
make deploy IMG=<registry>/openfga-operator:latest
kubectl apply -f config/samples/authz_v1alpha1_openfga.yaml
```

## License

[Apache 2.0](/LICENSE)
