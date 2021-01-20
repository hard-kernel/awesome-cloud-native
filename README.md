# awesome-cloud-native

Some useful project and tools.

## Image

- [Distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images, minus the operating system.
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
- [Quay](https://github.com/quay/quay) - Build、Store and Distribute your Applications and Containers.
- [Sinker](https://github.com/plexsystems/sinker) - A tool to sync images from one container registry to another.
- [registry-creds operator](https://github.com/alexellis/registry-creds) - Replicate Kubernetes ImagePullSecrets to all namespaces.

## Runtime

- [runV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI.
- [footloose](https://github.com/weaveworks/footloose) - Containers that look like Virtual Machines.
- [Ignite](https://github.com/weaveworks/ignite) - Ignite is an open source Virtual Machine manager with a container UX and built-in GitOps management.

## Install & Distribution Release

- [k8s-tew](https://github.com/darxkies/k8s-tew) - The Easier Way.
- [Typhoon](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.
- [EKS](https://github.com/aws/eks-distro) - Amazon EKS Distro.
- [MetalK8s](https://github.com/scality/metalk8s) - An opinionated Kubernetes distribution with a focus on long-term on-prem deployments.
- [wksctl](https://github.com/weaveworks/wksctl) - Open Source Weaveworks Kubernetes System.
- [KOTS](https://github.com/replicatedhq/kots) - KOTS provides the framework, tools and integrations that enable the delivery and management of 3rd-party Kubernetes applications.
- [AgoraKube](https://github.com/ilkilab/agorakube) - Agorakube provides an enterprise grade solution following best practices to manage a conformant Kubernetes cluster for on-premise and public cloud providers.
- [Cybozu Kubernetes Engine](https://github.com/cybozu-go/cke) - Cybozu Kubernetes Engine.
- [Gravity](https://github.com/gravitational/gravity) - Kubernetes application deployments for restricted, regulated or remote environments.
- [K8e](https://github.com/xiaods/k8e) - Simple Enterprise Kubernetes.
- [KubeOperator](https://github.com/KubeOperator/KubeOperator) - Hop onto the sailing of Kubernetes.
- [OKD](https://github.com/openshift/okd) - The Community Distribution of Kubernetes that powers Red Hat's OpenShift.
- [oneinfra](https://github.com/oneinfra/oneinfra) - Kubernetes as a Service.

## Redefine

- [Kine](https://github.com/k3s-io/kine) - Run Kubernetes on MySQL、Postgres、sqlite、dqlite, not etcd.
- [Arktos](https://github.com/CentaurusInfra/arktos) - Arktos for large-scale cloud platform.
- [Nomad](https://github.com/hashicorp/nomad) - Nomad is a simple and flexible workload orchestrator to deploy and manage containers, non-containerized applications, and virtual machines across on-prem and clouds at scale.

## Multi Cloud

- [Triton Kubernetes](https://github.com/joyent/triton-kubernetes) - Triton Kubernetes is a multi-cloud Kubernetes solution.
- [Clusterman](https://github.com/Yelp/clusterman) - Cluster Autoscaler for Kubernetes and Mesos.

## Multi Cluster

- [Beetle](https://github.com/Clivern/Beetle) - Kubernetes multi-cluster deployment automation service.

## Multi Tenancy

- [kiosk](https://github.com/kiosk-sh/kiosk) - Secure Cluster Sharing & Self-Service Namespace Provisioning.
- [Capsule](https://github.com/clastix/capsule) - Kubernetes Operator for multi-tenancy.

## Storage

## NetWork

- [kube-keepalived-vip](https://github.com/kubernetes-retired/contrib/tree/master/keepalived-vip)
- [kube-vip](https://github.com/plunder-app/kube-vip) - Kubernetes Control Plane Virtual IP and Load-Balancer.
- [kubernetes-nmstate](https://github.com/nmstate/kubernetes-nmstate) - Declarative node network configuration driven through Kubernetes API.
- [Bond CNI plugin](https://github.com/intel/bond-cni) - Bond-cni is for fail-over and high availability of networking in cloudnative orchestration.
- [nri](https://github.com/containerd/nri) - This project is a WIP for a new, CNI like, interface for managing resources on a node for Pods and Containers.
- [Network Node Manager](https://github.com/kakao/network-node-manager) - network-node-manager is a kubernetes controller that controls the network configuration of a node to resolve network issues of kubernetes.
- [Whitelister](https://github.com/stakater/Whitelister) - A tool to white list node and developer IPs for kubernetes.
- [Kube-router](https://github.com/cloudnativelabs/kube-router) - Kube-router, a turnkey solution for Kubernetes networking.
- [Kube-OVN](https://github.com/alauda/kube-ovn) - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
- [dnsredir](https://github.com/leiless/dnsredir) - Yet another seems better forward/proxy plugin for CoreDNS.
- [Skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
- [Manba Ingress](https://github.com/domechn/manba-ingress) - Manba API Gateway for Kubernetes.
- [Tyk Kubernetes Controller](https://github.com/TykTechnologies/tyk-k8s) - Kubernetes ingress controller and sidecar injector for Tyk API Gateway.
- [Traefik](https://github.com/traefik/traefik) - The Cloud Native Application Proxy.
- [Traefik Mesh](https://github.com/traefik/mesh) - Simpler Service Mesh.

## Extension

- [podpreset-webhook](https://github.com/redhat-cop/podpreset-webhook) - Implementation of Kubernetes PodPreset as an Admission Webhook.
- [Peloton](https://github.com/uber/peloton) - Unified Resource Scheduler to co-schedule mixed types of workloads such as batch, stateless and stateful jobs in a single cluster for better resource utilization.
- [poseidon](https://github.com/kubernetes-sigs/poseidon) - A Firmament-based Kubernetes scheduler.
- [Escalator](https://github.com/atlassian/escalator) - Escalator is a batch or job optimized horizontal autoscaler for Kubernetes.
- [Armada](https://github.com/G-Research/armada) - A multi-cluster batch queuing system for high-throughput workloads on Kubernetes.
- [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
- [Brigade](https://github.com/brigadecore/brigade) - Event-based Scripting for Kubernetes.
- [Keptn](https://github.com/keptn/keptn) - Keptn is a message-driven control-plane for application delivery and automated operations.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development.
- [Couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines, such as Argo Workflows, Tekton Pipelines, and Apache Airflow.
- [Cyclone](https://github.com/caicloud/cyclone) - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.

## Operator

- [Node Feature Discovery](https://github.com/kubernetes-sigs/node-feature-discovery) - Node feature discovery for Kubernetes.
- [Node Feature Discovery Operator](https://github.com/kubernetes-sigs/node-feature-discovery-operator) - Operator for managing Node Feature Discovery deployment.

## OPS

- [Stash](https://github.com/stashed/stash) - Backup your Kubernetes Stateful Applications.
- [Gemini](https://github.com/FairwindsOps/gemini) - Automated backups of PersistentVolumeClaims in Kubernetes using VolumeSnapshots.
- [draino](https://github.com/planetlabs/draino) - Automatically cordon and drain Kubernetes nodes based on node conditions.
- [Kubemem](https://github.com/16Bitt/kubemem) - A small binary to probe memory usage in a kubernetes pod.
- [OOMHero](https://github.com/ricardomaraschini/oomhero) - Kubernetes sidecar for memory usage tracking.
- [kubernetes-oom-event-generator](https://github.com/xing/kubernetes-oom-event-generator) - Generate a Kubernetes Event when a Pod's container has been OOMKilled.
- [Replicated Troubleshoot](https://github.com/replicatedhq/troubleshoot) - Preflight Checks and Support Bundles Framework for Kubernetes Applications.
- [Reloader](https://github.com/stakater/Reloader) - A Kubernetes controller to watch changes in ConfigMap and Secrets and do rolling upgrades on Pods with their associated Deployment、StatefulSet、DaemonSet and DeploymentConfig.
- [Jamadar](https://github.com/stakater/Jamadar) - A kubernetes controller which cleans up cluster left-overs.
- [pid2pod](https://github.com/heptiolabs/pid2pod) - A small demo/experiment that shows how Linux process IDs can be mapped to Kubernetes pod metadata.

## Observability

- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time, powered by Pulumi.
- [Pixie](https://github.com/pixie-labs/pixie) - Pixie gives you instant visibility by giving access to metrics、events、traces and logs without changing code.
- [Scope](https://github.com/weaveworks/scope) - Monitoring、visualisation & management for Docker & Kubernetes.
- [Sloop](https://github.com/salesforce/sloop) - Kubernetes History Visualization.
- [kmoncon](https://github.com/Stono/kconmon) - A Kubernetes node connectivity monitoring tool.
- [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.
- [K8stream](https://github.com/last9/k8stream) - Processing kubenetes events stream.
- [pleg-watcher](https://github.com/rhdedgar/pleg-watcher)
- [DARK](https://github.com/K-Phoen/dark) - Dashboards As Resources in Kubernetes.

## Security

- [KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - KubeTEE is a collection of TEE development、deployment、maintenance middleware framework and services、especially for Kubernetes workflow.

## Test

- [bother](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester.
- [Lotus](https://github.com/lotusload/lotus) - Kubernetes controller for running load testing.

## Develop Tools

- [KT Connect](https://github.com/alibaba/kt-connect) - Manage and Integration with your Kubernetes dev environment more efficient.
- [Nocalhost](https://github.com/nocalhost/nocalhost) - Nocalhost is Cloud Native Environment.
- [Okteto](https://github.com/okteto/okteto) - Develop your applications directly in your Kubernetes Cluster.

