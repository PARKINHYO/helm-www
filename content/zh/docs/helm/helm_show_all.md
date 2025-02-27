---
title: "Helm 展示所有"
---

## helm show all

显示chart的所有信息

### 简介

该命令检查chart(目录、文件或URL)并显示所有的内容（values.yaml, Chart.yaml, README）

```shell
helm show all [CHART] [flags]
```

### 可选项

```shell
      --ca-file string             verify certificates of HTTPS-enabled servers using this CA bundle
      --cert-file string           identify HTTPS client using this SSL certificate file
      --devel                      use development versions, too. Equivalent to version '>0.0.0-0'. If --version is set, this is ignored
  -h, --help                       help for all
      --insecure-skip-tls-verify   skip tls certificate checks for the chart download
      --key-file string            identify HTTPS client using this SSL key file
      --keyring string             location of public keys used for verification (default "~/.gnupg/pubring.gpg")
      --pass-credentials           pass credentials to all domains
      --password string            chart repository password where to locate the requested chart
      --repo string                chart repository url where to locate the requested chart
      --username string            chart repository username where to locate the requested chart
      --verify                     verify the package before using it
      --version string             specify a version constraint for the chart version to use. This constraint can be a specific tag (e.g. 1.1.1) or it may reference a valid range (e.g. ^2.0.0). If this is not specified, the latest version is used
```

### 从父命令继承的命令

```shell
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         username to impersonate for the operation
      --kube-ca-file string         the certificate authority file for the Kubernetes API server connection
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry/config.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### 请参阅

* [helm show](helm_show.md) - 显示chart信息
