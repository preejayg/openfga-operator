# OpenFGA Operator

![Release](https://img.shields.io/badge/version-v1alpha1-greem)
![Dependabot status](https://img.shields.io/badge/dependabot-enabled-brightgreen)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

OpenFGA Operator automates the management of [OpenFGA](https://openfga.dev/) instances in Kubernetes. This is created using [Operator SDK](https://sdk.operatorframework.io/).

## Prerequisites

- [Operator SDK](https://sdk.operatorframework.io/docs/installation/)
- [Kubernetes cluster](https://kubernetes.io/docs/setup/)
- [Helm](https://helm.sh/docs/intro/install/)
- [OpenFGA](https://openfga.dev/docs/getting-started/installation)

## Usage

```shell
kubectl apply -f config/samples/authz_v1alpha1_openfga.yaml
```

## License

[Apache 2.0](/LICENSE)
