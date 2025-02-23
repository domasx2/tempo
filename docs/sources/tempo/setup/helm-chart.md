---
title: Deploy Tempo with Helm
menuTitle: Deploy with Helm
weight: 350
---

# Deploy Tempo with Helm

The Helm charts for Grafana Tempo and Grafana Enterprise Traces allows you to configure, install, and upgrade Grafana Tempo or Grafana Enterprise Traces within a Kubernetes cluster.

The Tempo repository has an [example Helm chart](https://github.com/grafana/tempo/tree/main/example/helm) that shows a complete microservice-based deployment.

Tempo has two primary charts used for deployment:

* [`tempo-distributed` Helm chart](https://github.com/grafana/helm-charts/tree/main/charts/tempo-distributed) deploys Tempo in microservices mode
* [`tempo` Helm chart](https://github.com/grafana/helm-charts/tree/main/charts/tempo) deploys Tempo in monolithic (single binary) mode

To deploy Tempo using the `tempo-distributed` Helm chart, read the [Get started with Grafana Tempo using Helm]({{< relref "/docs/helm-charts/tempo-distributed/next/get-started-helm-charts/" >}}).