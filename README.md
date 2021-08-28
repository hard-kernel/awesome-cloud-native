# awesome-cloud-native

Some useful project and tools.

## Image

- [Distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images minus the operating system.
- [umoci](https://github.com/opencontainers/umoci) - Modifies Open Container images.
- [Buildah](https://github.com/containers/buildah) - A tool that facilitates building OCI images.
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
- [manifesto](https://github.com/aquasecurity/manifesto) - Store and query metadata for container images.
- [container-info](https://github.com/rhdedgar/container-info)
- [Distribution](https://github.com/distribution/distribution) - The toolkit to pack ship store and deliver container content.
- [CRFS](https://github.com/google/crfs) - Container Registry Filesystem.
- [imgpkg](https://github.com/vmware-tanzu/carvel-imgpkg) - Store application configuration files in Docker/OCI registries.
- [Sinker](https://github.com/plexsystems/sinker) - A tool to sync images from one container registry to another.
- [image-syncer](https://github.com/AliyunContainerService/image-syncer) - Docker image synchronization tool for Docker Registry V2 based services.
- [kube-fledged](https://github.com/senthilrch/kube-fledged) - A kubernetes add-on for creating and managing a cache of container images directly on the cluster worker nodes.

## Runtime

- [Sysbox](https://github.com/nestybox/sysbox)
- [footloose](https://github.com/weaveworks/footloose) - Containers that look like Virtual Machines.
- [Ignite](https://github.com/weaveworks/ignite) - Open source Virtual Machine manager with a container UX and built-in GitOps management.
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - Secure and fast microVMs for serverless computing.
- [Frakti](https://github.com/kubernetes/frakti) - The hypervisor-based container runtime for Kubernetes.
- [runV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI.
- [crun](https://github.com/containers/crun) - A fast and lightweight fully featured OCI runtime and C library for running containers.
- [iSulad](https://github.com/openeuler-mirror/iSulad) - A lightweight container runtime daemon for IOT and Cloud infrastructure.

## Distribution Release

- [bcs-k8s](https://github.com/Tencent/bk-bcs/tree/master/bcs-k8s)
- [Kubernetes](https://github.com/lyft/kubernetes) - lyft.
- [OKD](https://github.com/openshift/okd) - The Community Distribution of Kubernetes that powers RedHat's OpenShift.
- [EKS](https://github.com/aws/eks-distro) - Amazon EKS Distro.
- [Kine](https://github.com/k3s-io/kine) - Run Kubernetes on MySQL、Postgres、sqlite、dqlite, not etcd.
- [Arktos](https://github.com/CentaurusInfra/arktos) - large-scale cloud platform.

## Cluster

- [kOps](https://github.com/kubernetes/kops) - Production Grade K8s Installation Upgrades and Management.
- [kubespray](https://github.com/kubernetes-sigs/kubespray) - Deploy a Production Ready Kubernetes Cluster.
- [MetalK8s](https://github.com/scality/metalk8s) - An opinionated Kubernetes distribution with a focus on long-term on-prem deployments.
- [Gravity](https://github.com/gravitational/gravity) - Kubernetes application deployments for restricted、regulated or remote environments.
- [Typhoon](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.
- [KubeOperator](https://github.com/KubeOperator/KubeOperator) - Hop onto the sailing of Kubernetes.
- [KET](https://github.com/apprenda/kismatic) - Fully-Automated Production-Grade Kubernetes Operations.
- [kURL](https://github.com/replicatedhq/kURL) - Production-grade, airgapped Kubernetes installer combining upstream k8s with overlays and popular components.
- [AgoraKube](https://github.com/ilkilab/agorakube) - An enterprise grade solution following best practices managing a conformant Kubernetes cluster.
- [wksctl](https://github.com/weaveworks/wksctl) - Open Source Weaveworks Kubernetes System.
- [K8e](https://github.com/xiaods/k8e) - Simple Enterprise Kubernetes.
- [Gardener](https://github.com/gardener/gardener) - Kubernetes-native system managing the full lifecycle of conformant Kubernetes clusters as a service.
- [Kubicorn](https://github.com/kubicorn/kubicorn) - Simple, cloud native infrastructure for Kubernetes.
- [kubermatic](https://github.com/kubermatic/kubermatic) - The Central Kubernetes Management Platform For Any Infrastructure.
- [KubeOne](https://github.com/kubermatic/kubeone) - Kubermatic KubeOne automate cluster operations on all your cloud、on-prem、edge and IoT environments.
- [control](https://github.com/supergiant/control) - Control manages the lifecycle of clusters on your infrastructure.
- [triton-kubernetes](https://github.com/joyent/triton-kubernetes) - A multi-cloud Kubernetes solution.
- [Fleet](https://github.com/rancher/fleet) - Manage large fleets of Kubernetes clusters.
- [oneinfra](https://github.com/oneinfra/oneinfra) - Kubernetes as a Service.
- [Clusterman](https://github.com/Yelp/clusterman) - Cluster Autoscaler for Kubernetes and Mesos.
- [k8s-cronjob-prescaler](https://github.com/microsoft/k8s-cronjob-prescaler) - Kubernetes operator that prescales cluster nodes to ensure a cronjobs start exactly on time.
- [cluster-proportional-autoscaler](https://github.com/kubernetes-sigs/cluster-proportional-autoscaler) - Kubernetes Cluster Proportional Autoscaler Container.
- [Karpenter](https://github.com/awslabs/karpenter) - Kubernetes Node Autoscaling.
- [CLM](https://github.com/zalando-incubator/cluster-lifecycle-manager) - Cluster Lifecycle Manager to provision and update multiple Kubernetes clusters.
- [Federation](https://github.com/kubernetes-retired/federation) - Cluster Federation.
- [KOTS](https://github.com/replicatedhq/kots) - A framework tools and integrations that enable the delivery and management of 3rd-party Kubernetes applications.
- [arkade](https://github.com/alexellis/arkade) - Open Source Kubernetes Marketplace.
- [addon-manager](https://github.com/keikoproj/addon-manager) - Manage addons in a Kubernetes cluster.
- [Monocular](https://github.com/helm/monocular) - Search and discovery UI for Helm Chart repositories.

## Management

- [Lens](https://github.com/lensapp/lens) - The Kubernetes IDE.
- [compass](https://github.com/yametech/compass) - Kubernetes Dashboard.
- [Octant](https://github.com/vmware-tanzu/octant) - A highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
- [Verrazzano](https://github.com/verrazzano/verrazzano) - Enterprise Container Platform for deploying cloud-native and traditional applications in multi-cloud.
- [Liqo](https://github.com/liqotech/liqo) - Building your endless Kubernetes ocean.
- [Submariner](https://github.com/submariner-io/submariner) - Connect all your Kubernetes clusters, no matter where they are in the world.
- [KubeCarrier](https://github.com/kubermatic/kubecarrier) - Service Management at Scale.
- [Beetle](https://github.com/Clivern/Beetle) - Kubernetes multi-cluster deployment automation service.
- [KubePlus](https://github.com/cloud-ark/kubeplus) - CRD for CRDs to design multi-tenant platform services from Helm charts.
- [manager](https://github.com/keikoproj/manager) - Multi K8s cluster Namespace Management.

## Multi Tenancy

- [HNC](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc)
- [kiosk](https://github.com/loft-sh/kiosk) - Secure Cluster Sharing & Self-Service Namespace Provisioning.
- [Capsule](https://github.com/clastix/capsule) - Kubernetes Operator for multi-tenancy.

## NetWork

- [Seesaw](https://github.com/google/seesaw) - A Linux Virtual Server based load balancing platform.
- [gobetween](https://github.com/yyyar/gobetween) - Modern & minimalistic load balancer for the Сloud era.
- [Katran](https://github.com/facebookincubator/katran) - A high performance layer 4 load balancer.
- [KgLb](https://github.com/dropbox/kglb) - L4 Load Balancer.
- [MetalLB](https://github.com/metallb/metallb) - A network load-balancer implementation for Kubernetes using standard routing protocols.
- [Porter](https://github.com/kubesphere/porterlb) - Bare Metal Load-balancer for Kubernetes Cluster.
- [kube-keepalived-vip](https://github.com/kubernetes-retired/contrib/tree/master/keepalived-vip)
- [kube-vip](https://github.com/plunder-app/kube-vip) - Kubernetes Control Plane Virtual IP and Load-Balancer.
- [network-node-manager](https://github.com/kakao/network-node-manager) - network-node-manager controls the network configuration of a node to resolve network issues of kubernetes.
- [kubernetes-nmstate](https://github.com/nmstate/kubernetes-nmstate) - Declarative node network configuration driven through Kubernetes API.
- [kube-iptables-tailer](https://github.com/box/kube-iptables-tailer) - A service for better network visibility for your Kubernetes clusters.
- [VPN](https://github.com/gardener/vpn) - Network connector between the control plane, and a Shoot cluster.
- [whereabouts](https://github.com/k8snetworkplumbingwg/whereabouts) - A CNI IPAM plugin that assigns IP addresses cluster-wide.
- [cni-ipam-etcd](https://github.com/jeremyxu2010/cni-ipam-etcd) - IPAM CNI plugin with etcd backend.
- [bond-cni](https://github.com/intel/bond-cni) - ail-over and high availability of networking in cloudnative orchestration.
- [Knitter](https://github.com/ZTE/Knitter) - Kubernetes network solution.
- [cni-migration](https://github.com/jetstack/cni-migration) - A CLI to migrate the CNI on a Kubernetes cluster from Canal to Cilium, live with no downtime.
- [multus-config-injector](https://github.com/withlin/multus-config-injector)
- [Kube-router](https://github.com/cloudnativelabs/kube-router) - A turnkey solution for Kubernetes networking.
- [Bifrost](https://github.com/harmonycloud/Bifrost) - An open source solution enabling L2 network for kubernetes.
- [Kube-OVN](https://github.com/alauda/kube-ovn) - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
- [Weave](https://github.com/weaveworks/weave) - Simple, resilient multi-host containers networking and more.
- [terway](https://github.com/AliyunContainerService/terway) - CNI plugin for Alibaba Cloud VPC/ENI.
- [gardener-extension-networking-calico](https://github.com/gardener/gardener-extension-networking-calico) - Gardener extension controller for the Calico CNI network plugin.
- [sriov-cni](https://github.com/k8snetworkplumbingwg/sriov-cni) - DPDK & SR-IOV CNI plugin.
- [sriov-network-operator](https://github.com/openshift/sriov-network-operator) - SR-IOV Network Operator.
- [k8s-rdma-sriov-dev-plugin](https://github.com/Mellanox/k8s-rdma-sriov-dev-plugin) - Kubernetes Rdma SRIOV device plugin.
- [Kilo](https://github.com/squat/kilo) - A multi-cloud network overlay built on WireGuard and designed for Kubernetes.
- [Galaxy](https://github.com/tkestack/galaxy) - Providing high-performance network for Kubernetes.
- [illuminatio](https://github.com/inovex/illuminatio) - The kubernetes network policy validator.
- [Whitelister](https://github.com/stakater/Whitelister) - A tool to white list node and developer IPs for kubernetes.
- [dnsredir](https://github.com/leiless/dnsredir) - Yet another seems better forward/proxy plugin for CoreDNS.
- [SmartNat](https://github.com/DevFactory/smartnat) - Kubernetes controller to expose Services with TCP/UDP.
- [inlets-operator](https://github.com/inlets/inlets-operator) - Add public LoadBalancers to your local Kubernetes clusters.
- [Gimbal](https://github.com/projectcontour/gimbal) - An ingress load balancing platform capable of routing traffic to multiple Kubernetes and OpenStack clusters.
- [k8s-externalipcontroller](https://github.com/Mirantis/k8s-externalipcontroller) - External IP controller configures External IPs on k8s worker nodes to provide IP connectivity.
- [kubeIP](https://github.com/doitintl/kubeip) - Assign static external IPs from predefined pool of external IP addresses to Google GKE nodes.
- [federated-ingress-controller](https://github.com/oracle/federated-ingress-controller) - Alternative implementation of Federated Ingress using external DNS.
- [Skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
- [Xposer](https://github.com/stakater/Xposer) - A Kubernetes controller to manage Kubernetes Ingresses based on the Service.
- [Kubernetes Gateway API](https://github.com/kubernetes-sigs/gateway-api) - Repository for the next iteration of composite service and load balancing APIs.
- [Easegress](https://github.com/megaease/easegress) - A Cloud Native traffic orchestration system.

## Service Mesh

- [Linkerd](https://github.com/linkerd/linkerd2) - Ultralight, security-first service mesh for Kubernetes.
- [linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) - A purpose-built proxy for the Linkerd service mesh.
- [Pipy](https://github.com/flomesh-io/pipy) - A tiny, high performance, highly stable, programmable proxy.
- [MOSN](https://github.com/mosn/mosn) - A cloud native proxy for edge or service mesh.
- [meshach](https://github.com/symcn/meshach) - It is in charge of all things about implements of Service Mesh.
- [NSM](https://github.com/networkservicemesh/networkservicemesh) - The Hybrid/Multi-cloud IP Service Mesh.
- [wesher](https://github.com/costela/wesher) - Wireguard overlay mesh network manager.
- [Meshery](https://github.com/layer5io/meshery) - The service mesh management plane.
- [Slime](https://github.com/slime-io/slime) - Smart ServiceMesh Manager.
- [OSM](https://github.com/openservicemesh/osm) - A lightweight, extensible, cloud native service mesh that allows users to uniformly manage, secure, and get out-of-the-box observability features for highly dynamic microservice environments.
- [Gloo](https://github.com/solo-io/gloo) - The Feature-rich, Kubernetes-native, Next-Generation API Gateway Built on Envoy.
- [gloo-mesh](https://github.com/solo-io/gloo-mesh) - The Service Mesh Orchestration Platform.
- [Emissary-Ingress](https://github.com/emissary-ingress/emissary) - Open source Kubernetes-native API gateway for microservices built on the Envoy Proxy.
- [Contour](https://github.com/projectcontour/contour) - A Kubernetes ingress controller using Envoy proxy.
- [Aeraki](https://github.com/aeraki-framework/aeraki) - Manage any layer 7 traffic in Istio Service Mesh.
- [Kiali](https://github.com/kiali/kiali) - Observability for the Istio service mesh.

## Storage

- [external-resizer](https://github.com/kubernetes-csi/external-resizer) - Watche Kubernetes PersistentVolumeClaims objects and triggers controller side expansion operation.
- [COSI](https://github.com/kubernetes-sigs/container-object-storage-interface-provisioner-sidecar) - Container Object Storage Interface provisioner responsible to interface.
- [TopoLVM](https://github.com/topolvm/topolvm) - Capacity-aware CSI plugin for Kubernetes.
- [Piraeus](https://github.com/piraeusdatastore/piraeus) - High Available Datastore for Kubernetes.
- [Longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes.
- [Stork](https://github.com/libopenstorage/stork) - Storage Orchestration Runtime for Kubernetes.
- [Kanister](https://github.com/kanisterio/kanister) - An extensible framework for application-level data management on Kubernetes.

## Scheduler

- [Nomad](https://github.com/hashicorp/nomad) - A simple and flexible workload orchestrator to deploy and manage containers non-containerized applications at scale.
- [Apache YuniKorn](https://github.com/apache/incubator-yunikorn-core) - Apache YuniKorn Core.
- [Eru](https://github.com/projecteru2/core) - A simple stateless flexible production-ready orchestrator designed to easily integrate into existing workflows.
- [poseidon](https://github.com/kubernetes-sigs/poseidon) - A Firmament-based Kubernetes scheduler.
- [Peloton](https://github.com/uber/peloton) - Unified Resource Scheduler to co-schedule mixed types of workloads such as batch、stateless and stateful jobs for better resource utilization.
- [Armada](https://github.com/G-Research/armada) - A multi-cluster batch queuing system for high-throughput workloads on Kubernetes.
- [Bistro](https://github.com/facebook/bistro) - A flexible distributed scheduler, a high-performance framework supporting multiple paradigms.
- [crl-scheduler](https://github.com/cockroachlabs/crl-scheduler)
- [Admiralty](https://github.com/admiraltyio/admiralty) - A system of Kubernetes controllers that intelligently schedules workloads across clusters.
- [Super scheduling](https://github.com/cwdsuzhou/super-scheduling) - A topology-scheduler and a descheduler extened from descheduler.

## Workflows

- [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
- [PipeCD](https://github.com/pipe-cd/pipe) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
- [Space Cloud](https://github.com/spacecloud-io/space-cloud) - Open source Firebase + Heroku to develop, scale and secure serverless apps on Kubernetes.
- [Keptn](https://github.com/keptn/keptn) - A message-driven control-plane for application delivery and automated operations.
- [Brigade](https://github.com/brigadecore/brigade) - Event-based Scripting for Kubernetes.

- [Couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines.
- [Cyclone](https://github.com/caicloud/cyclone) - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.

## Autoscaler

- [autoscaler](https://github.com/kubernetes/autoscaler) - Autoscaling components for Kubernetes.
- [Pangolin](https://github.com/dpeckett/pangolin) - An enhanced Horizontal Pod Autoscaler for Kubernetes.
- [custom-pod-autoscaler](https://github.com/jthomperoo/custom-pod-autoscaler) - Custom Pod Autoscaler base allows creation of Custom Pod Autoscalers.
- [custom-pod-autoscaler-operator](https://github.com/jthomperoo/custom-pod-autoscaler-operator) - Operator for managing Kubernetes Custom Pod Autoscalers.
- [horizontal-pod-autoscaler](https://github.com/jthomperoo/horizontal-pod-autoscaler) - Horizontal Pod Autoscaler, modified to work as a Custom Pod Autoscaler.
- [Escalator](https://github.com/atlassian/escalator) - A batch or job optimized horizontal autoscaler for Kubernetes.
- [kubernetes-cronhpa-controller](https://github.com/AliyunContainerService/kubernetes-cronhpa-controller) - HPA controller that allows to scale your workload based on time schedule.
- [CronHPA](https://github.com/tkestack/cron-hpa) - Cron Horizontal Pod Autoscaler.

## kubelet

- [nri](https://github.com/containerd/nri) - Node Resource Interface.
- [Krustlet](https://github.com/deislabs/krustlet) - Kubernetes Rust Kubelet.

## Operator

- [hardware-classification-controller](https://github.com/metal3-io/hardware-classification-controller) - Controller for matching host hardware characteristics to expected values.
- [node-feature-discovery](https://github.com/openshift/node-feature-discovery) - Node feature discovery, detects the available hardware features and configuration in a cluster.
- [Node Feature Discovery Operator](https://github.com/kubernetes-sigs/node-feature-discovery-operator) - Operator for managing Node Feature Discovery deployment.
- [nodepool-labels-operator](https://github.com/banzaicloud/nodepool-labels-operator) - Nodepool Labels operator for Kubernetes.
- [etcd-cloud-operator](https://github.com/Quentin-M/etcd-cloud-operator) - Deploying and managing production-grade etcd clusters on cloud providers.
- [Etcd-Backup-Restore](https://github.com/gardener/etcd-backup-restore) - Collection of components to back up and restore the Etcd of a Kubernetes cluster.
- [etcd-druid](https://github.com/gardener/etcd-druid) - A druid for etcd management in Gardener.
- [etcd-backup](https://github.com/gravitational/etcd-backup) - For handling backup/restore of etcd database from userspace.

## Elastic Training

- [elastic-jupyter-operator](https://github.com/tkestack/elastic-jupyter-operator) - Cloud-native way to provide elastic Jupyter Notebook services on Kubernetes.

## Framework

- [admission-control](https://github.com/elithrar/admission-control) - A helpful micro-framework for writing Kubernetes Admission Controllers.
- [generic-admission-server](https://github.com/openshift/generic-admission-server) - A library for writing admission webhooks based on k8s.io/apiserver.
- [Multicluster-Controller](https://github.com/admiraltyio/multicluster-controller) - A Library for Building Hybrid and Multicloud Kubernetes Operators.
- [whitebox-controller](https://github.com/summerwind/whitebox-controller) - Extensible generic controller for Kubernetes.
- [KUDO](https://github.com/kudobuilder/kudo) - Kubernetes Universal Declarative Operator.
- [operator-kit](https://github.com/rook/operator-kit) - A library for creating a Kubernetes Operator.
- [CRAFT](https://github.com/salesforce/craft) - Removes the language barrier to create Kubernetes Operators.
- [Metacontroller](https://github.com/metacontroller/metacontroller) - Writing kubernetes controllers can be simple.
- [Gontroller](https://github.com/spotahome/gontroller) - Go library to create resilient feedback loop/control controllers.

## OPS

- [Tini](https://github.com/krallin/tini) - A tiny but valid init for containers.

- [dumb-init](https://github.com/Yelp/dumb-init) - A minimal init system for Linux containers.
- [OOMHero](https://github.com/ricardomaraschini/oomhero) - Kubernetes sidecar for memory usage tracking.
- [kubernetes-oom-event-generator](https://github.com/xing/kubernetes-oom-event-generator) - Generate a Kubernetes Event when a Pod's container has been OOMKilled.
- [kubefs](https://github.com/configurator/kubefs) - Mount kubernetes metadata storage as a filesystem.
- [kubent](https://github.com/doitintl/kube-no-trouble) - Easily check your cluster for use of deprecated APIs.
- [Sonobuoy](https://github.com/vmware-tanzu/sonobuoy) - A diagnostic tool that makes it easier to understand the state of a Kubernetes cluster.
- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts.
- [k8s-platform-lcm](https://github.com/arminc/k8s-platform-lcm) - A faster and easier way to manage the lifecycle of applications and tools.
- [troubleshoot](https://github.com/replicatedhq/troubleshoot) - Preflight Checks and Support Bundles Framework for Kubernetes Applications.
- [Crashd](https://github.com/vmware-tanzu/crash-diagnostics) - A tool to help investigate analyze and troubleshoot unresponsive or crashed Kubernetes clusters.
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Get your resource requests Just Right.
- [governor](https://github.com/keikoproj/governor) - A collection of cluster reliability tools for Kubernetes.
- [pod-reaper](https://github.com/ptagr/pod-reaper) - A kubernetes operator that reaps pods that have reached their lifetime.

- [Jamadar](https://github.com/stakater/Jamadar) - A kubernetes controller which cleans up cluster left-overs.
- [draino](https://github.com/planetlabs/draino) - Automatically cordon and drain Kubernetes nodes based on node conditions.
- [astrolabe](https://github.com/vmware-tanzu/astrolabe) - Data protection framework for complex applications.
- [Gemini](https://github.com/FairwindsOps/gemini) - Automated backups of PersistentVolumeClaims in Kubernetes using VolumeSnapshots.
- [Stash](https://github.com/stashed/stash) - Backup your Kubernetes Stateful Applications.
- [ksync](https://github.com/ksync/ksync) - Sync files between your local system and kubernetes cluster.
- [Kubecost](https://github.com/kubecost/cost-model) - Cross-cloud cost allocation models for workloads running on Kubernetes.

- [podpreset-webhook](https://github.com/redhat-cop/podpreset-webhook) - A helpful micro-framework for writing Kubernetes Admission Controllers.
- [mutating-trace-admission-controller](https://github.com/kubernetes-retired/mutating-trace-admission-controller) - Enables experimental tracing of kubernetes object lifecycle.
- [cert-injection-webhook](https://github.com/vmware-tanzu/cert-injection-webhook) - Provides a Kubernetes webhook to inject CA certificates and proxy environment variables into pods.

## Observability

- [Sloop](https://github.com/salesforce/sloop) - Kubernetes History Visualization.
- [Scope](https://github.com/weaveworks/scope) - Monitoring、visualisation & management for Docker & Kubernetes.
- [metering-operator](https://github.com/kube-reporting/metering-operator) - The Metering Operator is responsible for collecting metrics and other information.
- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time.
- [Pixie](https://github.com/pixie-labs/pixie) - Instant visibility by giving access to metrics、events、traces and logs without changing code.
- [dead-mans-switch](https://github.com/pingcap/dead-mans-switch) - A bypass monitoring prober.
- [pleg-watcher](https://github.com/rhdedgar/pleg-watcher)
- [Kubemem](https://github.com/16Bitt/kubemem) - A small binary to probe memory usage in a kubernetes pod.
- [kmoncon](https://github.com/Stono/kconmon) - A Kubernetes node connectivity monitoring tool.
- [Kubenurse](https://github.com/postfinance/kubenurse) - Kubernetes network monitoring.
- [Eventrouter](https://github.com/heptiolabs/eventrouter) - A simple introspective kubernetes service that forwards events to a specified sink.pid2pod.
- [K8stream](https://github.com/last9/k8stream) - Processing kubenetes events stream.
- [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.
- [Kvass](https://github.com/tkestack/kvass) - A Prometheus horizontal auto-scaling solution.

- [prometheus-adapter](https://github.com/kubernetes-sigs/prometheus-adapter) - An implementation of the custom.metrics.k8s.io API using Prometheus.
- [Promxy](https://github.com/jacksontj/promxy) - An aggregating proxy to enable HA prometheus.
- [Promscale](https://github.com/timescale/promscale) - An open-source analytical platform for Prometheus metrics.
- [Promgen](https://github.com/line/promgen) - Promgen is a configuration file generator for Prometheus.
- [promdump](https://github.com/ihcsim/promdump) - A tool to dump and restore Prometheus data blocks.
- [InfluxDB IOx](https://github.com/influxdata/influxdb_iox) - New core of InfluxDB written in Rust on top of Apache Arrow.
- [chronus](https://github.com/angopher/chronus) - Distributed InfluxDB.
- [InfluxDB Proxy](https://github.com/chengshiwen/influx-proxy) - InfluxDB Proxy with High Availability and Consistent Hash.
- [Cortex](https://github.com/cortexproject/cortex) - A horizontally scalable, highly available, multi-tenant, long term Prometheus.
- [Grafana Tempo](https://github.com/grafana/tempo) - Grafana Tempo is a high volume, minimal dependency distributed tracing backend.
- [Sloth](https://github.com/slok/sloth) - Easy and simple Prometheus SLO generator.
- [kubernetes-mixin](https://github.com/kubernetes-monitoring/kubernetes-mixin) - A set of Grafana dashboards and Prometheus alerts for Kubernetes.
- [awesome-prometheus-alerts](https://github.com/samber/awesome-prometheus-alerts) - Collection of Prometheus alerting rules.
- [Alerta](https://github.com/alerta/alerta) - Alerta monitoring system.
- [DARK](https://github.com/K-Phoen/dark) - Dashboards As Resources in Kubernetes.
- [Trickster](https://github.com/trickstercache/trickster) - Open Source HTTP Reverse Proxy Cache and Time Series Dashboard Accelerator.

## Security

- [permission-manager](https://github.com/sighupio/permission-manager) - Permission Manager is a project that brings sanity to Kubernetes RBAC and Users management, Web UI FTW.
- [rback](https://github.com/team-soteria/rback) - RBAC in Kubernetes visualizer.
- [kubeaudit](https://github.com/Shopify/kubeaudit) - kubeaudit helps you audit your Kubernetes clusters against common security controls.
- [audit2rbac](https://github.com/liggitt/audit2rbac) - Autogenerate RBAC policies based on Kubernetes audit logs.
- [kube-rbac-proxy](https://github.com/brancz/kube-rbac-proxy) - Kubernetes RBAC authorizing HTTP proxy for a single upstream.
- [Guard](https://github.com/kubeguard/guard) - Kubernetes Authentication & Authorization WebHook Server.
- [rakkess](https://github.com/corneliusweig/rakkess) - kubectl plugin to show an access matrix for k8s server resources.
- [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can) - Show who has RBAC permissions to perform actions on different resources in Kubernetes.
- [dex](https://github.com/dexidp/dex) - OpenID Connect Identity and OAuth 2.0 Provider with Pluggable Connectors.
- [gangway](https://github.com/heptiolabs/gangway) - An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster.
- [Pinniped](https://github.com/vmware-tanzu/pinniped) - Pinniped provides identity services for Kubernetes clusters.
- [BOtB](https://github.com/brompwnie/botb) - A container analysis and exploitation tool for pentesters and engineers.
- [Terrier](https://github.com/heroku/terrier) - Terrier can be used to scan Images and Containers to identify and verify the presence of specific files according to their hashes.
- [fanal](https://github.com/aquasecurity/fanal) - Static Analysis Library for Containers.
- [Secrets](https://github.com/deepfence/SecretScanner) - Find secrets and passwords in container images and file systems.
- [Dockle](https://github.com/goodwithtech/dockle) - Container Image Linter for Security Helping build the Best-Practice Docker Image Easy to start.
- [ThreatMapper](https://github.com/deepfence/ThreatMapper) - Identify vulnerabilities in running containers images hosts and repositories.
- [Kubei](https://github.com/Portshift/kubei) - A flexible Kubernetes runtime scanner scanning images of worker and Kubernetes nodes providing accurate vulnerabilities assessment.

- [Portieris](https://github.com/IBM/portieris) - A Kubernetes Admission Controller for verifying image trust with Notary.
- [Karydia](https://github.com/karydia/karydia) - Kubernetes Security Walnut.
- [Kube-Scan](https://github.com/octarinesec/kube-scan) - Octarine k8s cluster risk assessment tool.
- [Kubesec](https://github.com/controlplaneio/kubesec) - Security risk analysis for Kubernetes resources.
- [MKIT](https://github.com/darkbitio/mkit) - Validates several common security-related configuration settings of managed Kubernetes cluster objects and the workloads/resources.
- [kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security.
- [k8s-security-dashboard](https://github.com/k8scop/k8s-security-dashboard) - A security monitoring solution for Kubernetes.
- [kubectl-kubesec](https://github.com/controlplaneio/kubectl-kubesec) - Security risk analysis for Kubernetes resources.
- [Falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security.
- [KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - A collection of TEE development、deployment、maintenance middleware framework for Kubernetes.

## Test

- [bother](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester.
- [Lotus](https://github.com/lotusload/lotus) - Kubernetes controller for running load testing.
- [K-Bench](https://github.com/vmware-tanzu/k-bench) - Workload Benchmark for Kubernetes.
- [k8s-sched-perf-stat](https://github.com/Huang-Wei/k8s-sched-perf-stat) - A tool to analyze the result of Kubernetes Scheduler Integration Performance test.

## Develop Tools

- [Tilt](https://github.com/tilt-dev/tilt) - A multi-service dev environment for teams on Kubernetes.
- [Nocalhost](https://github.com/nocalhost/nocalhost) - Cloud Native Environment.
- [KT Connect](https://github.com/alibaba/kt-connect) - Manage and Integration with your Kubernetes dev environment more efficient.
- [Okteto](https://github.com/okteto/okteto) - Develop your applications directly in your Kubernetes Cluster.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development.
- [CDS](https://github.com/ovh/cds) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform.

