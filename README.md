# awesome-cloud-native

Some useful project and tools.

## Image

- [Distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images, minus the operating system.
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
- [Quay](https://github.com/quay/quay) - Build、Store and Distribute your Applications and Containers.
- [Sinker](https://github.com/plexsystems/sinker) - A tool to sync images from one container registry to another.
- [kube-fledged](https://github.com/senthilrch/kube-fledged) - A kubernetes add-on for creating and managing a cache of container images directly on the cluster worker nodes.
- [registry-creds operator](https://github.com/alexellis/registry-creds) - Replicate Kubernetes ImagePullSecrets to all namespaces.

## Container Runtime

- [runV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI.
- [footloose](https://github.com/weaveworks/footloose) - Containers that look like Virtual Machines.
- [Ignite](https://github.com/weaveworks/ignite) - Ignite is an open source Virtual Machine manager with a container UX and built-in GitOps management.

## Install & Distribution Release & Cluster

- [Typhoon](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.
- [k8s-tew](https://github.com/darxkies/k8s-tew) - The Easier Way.
- [KOTS](https://github.com/replicatedhq/kots) - KOTS provides the framework, tools and integrations that enable the delivery and management of 3rd-party Kubernetes applications.
- [AgoraKube](https://github.com/ilkilab/agorakube) - Agorakube provides an enterprise grade solution following best practices managing a conformant Kubernetes cluster.
- [MetalK8s](https://github.com/scality/metalk8s) - An opinionated Kubernetes distribution with a focus on long-term on-prem deployments.
- [Cybozu Kubernetes Engine](https://github.com/cybozu-go/cke) - Cybozu Kubernetes Engine.
- [K8e](https://github.com/xiaods/k8e) - Simple Enterprise Kubernetes.
- [OKD](https://github.com/openshift/okd) - The Community Distribution of Kubernetes that powers Red Hat's OpenShift.
- [EKS](https://github.com/aws/eks-distro) - Amazon EKS Distro.
- [wksctl](https://github.com/weaveworks/wksctl) - Open Source Weaveworks Kubernetes System.
- [Gravity](https://github.com/gravitational/gravity) - Kubernetes application deployments for restricted, regulated or remote environments.
- [KubeOperator](https://github.com/KubeOperator/KubeOperator) - Hop onto the sailing of Kubernetes.
- [Kubicorn](https://github.com/kubicorn/kubicorn) - Simple, cloud native infrastructure for Kubernetes.
- [oneinfra](https://github.com/oneinfra/oneinfra) - Kubernetes as a Service.
- [Gardener](https://github.com/gardener/gardener) - Kubernetes-native system managing the full lifecycle of conformant Kubernetes clusters as a service.
- [Kubermatic KubeOne](https://github.com/kubermatic/kubeone) - Kubermatic KubeOne automate cluster operations on all your cloud、on-prem、edge and IoT environments.
- [instance-manager](https://github.com/keikoproj/instance-manager) - Create and manage instance groups with Kubernetes.
- [Kubermatic machine-controller](https://github.com/kubermatic/machine-controller)
- [Bare Metal Operator](https://github.com/metal3-io/baremetal-operator) - Bare metal host provisioning integration for Kubernetes.
- [Cluster Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler)
- [Supergiant Control](https://github.com/supergiant/control) - Control manages the lifecycle of clusters on your infrastructure.
- [arkade](https://github.com/alexellis/arkade) - Open Source Kubernetes Marketplace.

## Redefine

- [Kine](https://github.com/k3s-io/kine) - Run Kubernetes on MySQL、Postgres、sqlite、dqlite, not etcd.
- [Arktos](https://github.com/CentaurusInfra/arktos) - Arktos for large-scale cloud platform.
- [Nomad](https://github.com/hashicorp/nomad) - Nomad is a simple and flexible workload orchestrator to deploy and manage containers、non-containerized applications and virtual machines at scale.
- [Clusterman](https://github.com/Yelp/clusterman) - Cluster Autoscaler for Kubernetes and Mesos.

## Multi Cloud & Cluster

- [Triton Kubernetes](https://github.com/joyent/triton-kubernetes) - Triton Kubernetes is a multi-cloud Kubernetes solution.
- [Octant](https://github.com/vmware-tanzu/octant) - A highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
- [Kubermatic Kubernetes Platform](https://github.com/kubermatic/kubermatic) - the Central Kubernetes Management Platform For Any Infrastructure.
- [KubeCarrier](https://github.com/kubermatic/kubecarrier) - Service Management at Scale.
- [Beetle](https://github.com/Clivern/Beetle) - Kubernetes multi-cluster deployment automation service.
- [Liqo](https://github.com/liqotech/liqo) - Building your endless Kubernetes ocean.
- [Addon Manager](https://github.com/keikoproj/addon-manager) - Manage addons in a Kubernetes cluster.

## Multi Tenancy

- [The Hierarchical Namespace Controller](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc)
- [kiosk](https://github.com/kiosk-sh/kiosk) - Secure Cluster Sharing & Self-Service Namespace Provisioning.
- [manager](https://github.com/keikoproj/manager) - Multi K8s cluster Namespace Management.
- [Capsule](https://github.com/clastix/capsule) - Kubernetes Operator for multi-tenancy.
- [Guard](https://github.com/appscode/guard) - Kubernetes Authentication & Authorization WebHook Server.
- [gangway](https://github.com/heptiolabs/gangway) - An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster.
- [Pinniped](https://github.com/vmware-tanzu/pinniped) - Pinniped provides identity services for Kubernetes clusters.

## Storage

- [Longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes.
- [Volume Booster](https://github.com/opstree/dynamic-pv-scaler) - A golang based Kubernetes application which can scale volume dynamically.
- [ksync](https://github.com/ksync/ksync) - Sync files between your local system, and a kubernetes cluster.
- [kubefs](https://github.com/configurator/kubefs) - Mount kubernetes metadata storage as a filesystem.

## NetWork

- [kube-keepalived-vip](https://github.com/kubernetes-retired/contrib/tree/master/keepalived-vip)
- [kube-vip](https://github.com/plunder-app/kube-vip) - Kubernetes Control Plane Virtual IP and Load-Balancer.
- [Seesaw v2](https://github.com/google/seesaw) - Seesaw v2 is a Linux Virtual Server based load balancing platform.
- [gobetween](https://github.com/yyyar/gobetween) - Modern & minimalistic load balancer for the Сloud era.
- [MetalLB](https://github.com/metallb/metallb) - A network load-balancer implementation for Kubernetes using standard routing protocols.
- [Porter](https://github.com/kubesphere/porter) - Bare Metal Load-balancer for Kubernetes Cluster.
- [kubernetes-nmstate](https://github.com/nmstate/kubernetes-nmstate) - Declarative node network configuration driven through Kubernetes API.
- [nri](https://github.com/containerd/nri) - This project is a WIP for a new, CNI like, interface for managing resources on a node for Pods and Containers.
- [Network Node Manager](https://github.com/kakao/network-node-manager) - network-node-manager controls the network configuration of a node to resolve network issues of kubernetes.
- [Bond CNI plugin](https://github.com/intel/bond-cni) - Bond-cni is for fail-over and high availability of networking in cloudnative orchestration.
- [Kube-router](https://github.com/cloudnativelabs/kube-router) - Kube-router, a turnkey solution for Kubernetes networking.
- [Kube-OVN](https://github.com/alauda/kube-ovn) - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
- [Galaxy](https://github.com/tkestack/galaxy) - Providing high-performance network for Kubernetes.
- [dnsredir](https://github.com/leiless/dnsredir) - Yet another seems better forward/proxy plugin for CoreDNS.
- [Whitelister](https://github.com/stakater/Whitelister) - A tool to white list node and developer IPs for kubernetes.
- [SmartNat](https://github.com/DevFactory/smartnat) - Kubernetes controller to expose Services with TCP/UDP.
- [External IP Controller](https://github.com/Mirantis/k8s-externalipcontroller) - External IP controller configures External IPs on k8s worker nodes to provide IP connectivity.
- [Skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
- [Xposer](https://github.com/stakater/Xposer) - A Kubernetes controller to manage Kubernetes Ingresses based on the Service.
- [Federated Ingress Round Robin DNS Controller](https://github.com/oracle/federated-ingress-controller) - Alternative implementation of Federated Ingress using external DNS.
- [Manba Ingress](https://github.com/domechn/manba-ingress) - Manba API Gateway for Kubernetes.
- [Tyk Kubernetes Controller](https://github.com/TykTechnologies/tyk-k8s) - Kubernetes ingress controller and sidecar injector for Tyk API Gateway.
- [Traefik](https://github.com/traefik/traefik) - The Cloud Native Application Proxy.
- [Traefik Mesh](https://github.com/traefik/mesh) - Simpler Service Mesh.
- [mesh](https://github.com/weaveworks/mesh) - A tool for building distributed applications.

## Orchestration & Scheduler

- [Eru](https://github.com/projecteru2/core) - A simple stateless flexible production-ready orchestrator designed to easily integrate into existing workflows.
- [Peloton](https://github.com/uber/peloton) - Unified Resource Scheduler to co-schedule mixed types of workloads such as batch、stateless and stateful jobs for better resource utilization.
- [poseidon](https://github.com/kubernetes-sigs/poseidon) - A Firmament-based Kubernetes scheduler.
- [Escalator](https://github.com/atlassian/escalator) - Escalator is a batch or job optimized horizontal autoscaler for Kubernetes.
- [Armada](https://github.com/G-Research/armada) - A multi-cluster batch queuing system for high-throughput workloads on Kubernetes.
- [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
- [Brigade](https://github.com/brigadecore/brigade) - Event-based Scripting for Kubernetes.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development.
- [Keptn](https://github.com/keptn/keptn) - Keptn is a message-driven control-plane for application delivery and automated operations.
- [Cyclone](https://github.com/caicloud/cyclone) - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.
- [Couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines.
- [PipeCD](https://github.com/pipe-cd/pipe) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
- [CDS](https://github.com/ovh/cds) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform.

## Application Delivery

- [podpreset-webhook](https://github.com/redhat-cop/podpreset-webhook) - Implementation of Kubernetes PodPreset as an Admission Webhook.
- [TAPP](https://github.com/tkestack/tapp) - Another great app kind for Kubernetes.
- [kapp](https://github.com/vmware-tanzu/carvel-kapp) - kapp is a simple deployment tool focused on the concept of Kubernetes application.
- [Kubernetes deployment strategies](https://github.com/ContainerSolutions/k8s-deployment-strategies) - Kubernetes deployment strategies explained.
- [kd](https://github.com/UKHomeOffice/kd) - Minimalistic kubernetes resources deployment tool with templating.
- [Kdo](https://github.com/stepro/kdo) - Deployless Development on Kubernetes.
- [Rio](https://github.com/rancher/rio) - Application Deployment Engine for Kubernetes.
- [Kanarini](https://github.com/nilebox/kanarini) - Canary Deployment Controller for Kubernetes.
- [flagger](https://github.com/fluxcd/flagger) - Progressive delivery Kubernetes operator.
- [Logan App Operator](https://github.com/Gallardot/logan-app-operator) - Simple App Operator for Running Production Ready Statefulless Application in Kubernetes.
- [KET](https://github.com/apprenda/kismatic) - Fully-Automated Production-Grade Kubernetes Operations.
- [Kedge](https://github.com/kedgeproject/kedge) - Simple Concise & Declarative Kubernetes Applications.
- [kubegen](https://github.com/errordeveloper/kubegen) - simple way to describe Kubernetes resources in a structured way, but without new syntax or magic.
- [Nuwa](https://github.com/yametech/nuwa) - kubernetes CRD resource.
- [Keel](https://github.com/keel-hq/keel) - Kubernetes Operator to automate Helm、DaemonSet、StatefulSet & Deployment updates.
- [KubeDirector](https://github.com/bluek8s/kubedirector) - Kubernetes Director for deploying and managing stateful applications on Kubernetes。
- [Pod Disruption Budget Controller](https://github.com/mikkeloscar/pdb-controller) - Controller for adding default Pod Disruption Budgets to Kubernetes Deployments and StatefulSets.
- [ExtendedDaemonSet](https://github.com/DataDog/extendeddaemonset) - Kubernetes Extended Daemonset controller.
- [kured](https://github.com/weaveworks/kured) - Kubernetes Reboot Daemon.
- [Kubernetes StackSet Controller](https://github.com/zalando-incubator/stackset-controller) - Opinionated StackSet resource for managing application life cycle and traffic switching in Kubernetes.
- [KEDA](https://github.com/kedacore/keda) - KEDA is a Kubernetes-based Event Driven Autoscaling component.
- [Pangolin](https://github.com/dpeckett/pangolin) - An enhanced Horizontal Pod Autoscaler for Kubernetes.
- [Custom Pod Autoscaler](https://github.com/jthomperoo/custom-pod-autoscaler) - Custom Pod Autoscaler base, allows creation of Custom Pod Autoscalers.
- [Custom Pod Autoscaler Operator](https://github.com/jthomperoo/custom-pod-autoscaler-operator) - Operator for managing Kubernetes Custom Pod Autoscalers.
- [Custom Pod Autoscaler - Horizontal Pod Autoscaler](https://github.com/jthomperoo/horizontal-pod-autoscaler) - Horizontal Pod Autoscaler, modified to work as a Custom Pod Autoscaler.
- [Custom Pod Autoscaler Experiments](https://github.com/jthomperoo/custom-pod-autoscaler-experiments)
- [kubernetes-cronhpa-controller](https://github.com/AliyunContainerService/kubernetes-cronhpa-controller) - HPA controller that allows to scale your workload based on time schedule.
- [CronHPA](https://github.com/tkestack/cron-hpa) - Cron Horizontal Pod Autoscaler.
- [Kubernetes CronJob Prescaler](https://github.com/microsoft/k8s-cronjob-prescaler) - Kubernetes operator that prescales cluster nodes to ensure a cronjobs start exactly on time.
- [Cronjobber](https://github.com/hiddeco/cronjobber) - Cronjobber is a cronjob controller for Kubernetes with support for time zones.
- [Vertical Pod Autoscaler](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler)
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Get your resource requests Just Right.

## Operator

- [Node Feature Discovery](https://github.com/kubernetes-sigs/node-feature-discovery) - Node feature discovery for Kubernetes.
- [Node Feature Discovery Operator](https://github.com/kubernetes-sigs/node-feature-discovery-operator) - Operator for managing Node Feature Discovery deployment.
- [Hardware classification controller](https://github.com/metal3-io/hardware-classification-controller) - Controller for matching host hardware characteristics to expected values.
- [Node Feature Discovery](https://github.com/openshift/node-feature-discovery) - Node feature discovery, detects the available hardware features and configuration in a cluster.
- [Nodepool Labels Operator](https://github.com/banzaicloud/nodepool-labels-operator) - Nodepool Labels operator for Kubernetes.
- [Jenkins Operator](https://github.com/jenkinsci/kubernetes-operator) - Kubernetes native Jenkins Operator.
- [NATS Streaming Operator](https://github.com/nats-io/nats-streaming-operator) - NATS Streaming Operator.
- [Memcached Operator](https://github.com/ianlewis/memcached-operator) - A Kubernetes operator for memcached.
- [fdb-kubernetes-operator](https://github.com/FoundationDB/fdb-kubernetes-operator) - A kubernetes operator for FoundationDB.
- [Crunchy Data PostgreSQL Operator](https://github.com/CrunchyData/postgres-operator) - Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service.
- [Postgres Operator](https://github.com/zalando/postgres-operator) - Postgres operator creates and manages PostgreSQL clusters running in Kubernetes.
- [MongoDB Community Kubernetes Operator](https://github.com/mongodb/mongodb-kubernetes-operator) - MongoDB Community Kubernetes Operator.
- [Druid Operator](https://github.com/druid-io/druid-operator) - Druid Kubernetes Operator.

## OPS

- [Stash](https://github.com/stashed/stash) - Backup your Kubernetes Stateful Applications.
- [Gemini](https://github.com/FairwindsOps/gemini) - Automated backups of PersistentVolumeClaims in Kubernetes using VolumeSnapshots.
- [astrolabe](https://github.com/vmware-tanzu/astrolabe) - Data protection framework for complex applications.
- [draino](https://github.com/planetlabs/draino) - Automatically cordon and drain Kubernetes nodes based on node conditions.
- [Kubemem](https://github.com/16Bitt/kubemem) - A small binary to probe memory usage in a kubernetes pod.
- [OOMHero](https://github.com/ricardomaraschini/oomhero) - Kubernetes sidecar for memory usage tracking.
- [kubernetes-oom-event-generator](https://github.com/xing/kubernetes-oom-event-generator) - Generate a Kubernetes Event when a Pod's container has been OOMKilled.
- [Replicated Troubleshoot](https://github.com/replicatedhq/troubleshoot) - Preflight Checks and Support Bundles Framework for Kubernetes Applications.
- [Sonobuoy](https://github.com/vmware-tanzu/sonobuoy) - Sonobuoy is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster.
- [Crashd](https://github.com/vmware-tanzu/crash-diagnostics) - Crash-Diagnostics is a tool to help investigate、analyze and troubleshoot unresponsive or crashed Kubernetes clusters.
- [pid2pod](https://github.com/heptiolabs/pid2pod) - Shows how Linux process IDs can be mapped to Kubernetes pod metadata.
- [Cert Injection Webhook for Kubernetes](https://github.com/vmware-tanzu/cert-injection-webhook) - Provides a Kubernetes webhook to inject CA certificates and proxy environment variables into pods.
- [Jamadar](https://github.com/stakater/Jamadar) - A kubernetes controller which cleans up cluster left-overs.
- [governor](https://github.com/keikoproj/governor) - A collection of cluster reliability tools for Kubernetes.

## Observability

- [Scope](https://github.com/weaveworks/scope) - Monitoring、visualisation & management for Docker & Kubernetes.
- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time.
- [Searchlight](https://github.com/searchlight/searchlight) - Alerts for Kubernetes.
- [Sloop](https://github.com/salesforce/sloop) - Kubernetes History Visualization.
- [kmoncon](https://github.com/Stono/kconmon) - A Kubernetes node connectivity monitoring tool.
- [node-cert-exporter](https://github.com/amimof/node-cert-exporter) - An SSL certificate Prometheus exporter.
- [Eventrouter](https://github.com/heptiolabs/eventrouter) - A simple introspective kubernetes service that forwards events to a specified sink.pid2pod.
- [K8stream](https://github.com/last9/k8stream) - Processing kubenetes events stream.
- [pleg-watcher](https://github.com/rhdedgar/pleg-watcher)
- [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.
- [Pixie](https://github.com/pixie-labs/pixie) - Pixie gives you instant visibility by giving access to metrics、events、traces and logs without changing code.
- [DARK](https://github.com/K-Phoen/dark) - Dashboards As Resources in Kubernetes.

## Security

- [KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - KubeTEE is a collection of TEE development、deployment、maintenance middleware framework and services、especially for Kubernetes workflow.

## Test

- [bother](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester.
- [Lotus](https://github.com/lotusload/lotus) - Kubernetes controller for running load testing.
- [K-Bench](https://github.com/vmware-tanzu/k-bench) - Workload Benchmark for Kubernetes.

## Develop Tools

- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts.
- [Tilt](https://github.com/tilt-dev/tilt) - A multi-service dev environment for teams on Kubernetes.
- [KT Connect](https://github.com/alibaba/kt-connect) - Manage and Integration with your Kubernetes dev environment more efficient.
- [Nocalhost](https://github.com/nocalhost/nocalhost) - Nocalhost is Cloud Native Environment.
- [Okteto](https://github.com/okteto/okteto) - Develop your applications directly in your Kubernetes Cluster.

