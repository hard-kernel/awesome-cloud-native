# awesome-cloud-native

Some useful project and tools.

## Image

- [Distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images minus the operating system.
- [Buildah](https://github.com/containers/buildah) - A tool that facilitates building OCI images.
- [umoci](https://github.com/opencontainers/umoci) - umoci modifies Open Container images.
- [manifesto](https://github.com/aquasecurity/manifesto) - Use Manifesto to store and query metadata for container images.
- [container-info](https://github.com/rhdedgar/container-info)
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
- [Distribution](https://github.com/distribution/distribution) - The toolkit to pack ship store and deliver container content.
- [imgpkg](https://github.com/vmware-tanzu/carvel-imgpkg) - Store application configuration files in Docker/OCI registries.
- [CRFS](https://github.com/google/crfs) - Container Registry Filesystem.
- [Quay](https://github.com/quay/quay) - Build Store and Distribute your Applications and Containers.
- [Sinker](https://github.com/plexsystems/sinker) - A tool to sync images from one container registry to another.
- [image-syncer](https://github.com/AliyunContainerService/image-syncer) - Docker image synchronization tool for Docker Registry V2 based services.
- [kube-fledged](https://github.com/senthilrch/kube-fledged) - A kubernetes add-on for creating and managing a cache of container images directly on the cluster worker nodes.

## Runtime

- [footloose](https://github.com/weaveworks/footloose) - Containers that look like Virtual Machines.
- [Ignite](https://github.com/weaveworks/ignite) - Ignite is an open source Virtual Machine manager with a container UX and built-in GitOps management.
- [Sysbox](https://github.com/nestybox/sysbox) - Sysbox repository.
- [Firecracker](https://github.com/firecracker-microvm/firecracker) - Secure and fast microVMs for serverless computing.
- [Frakti](https://github.com/kubernetes/frakti) - The hypervisor-based container runtime for Kubernetes.
- [iSulad](https://github.com/openeuler-mirror/iSulad) - A lightweight container runtime daemon for IOT and Cloud infrastructure.
- [runV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI.
- [crun](https://github.com/containers/crun) - A fast and lightweight fully featured OCI runtime and C library for running containers.

## Distribution Release

- [kOps](https://github.com/kubernetes/kops) - Production Grade K8s Installation Upgrades and Management.
- [kubespray](https://github.com/kubernetes-sigs/kubespray) - Deploy a Production Ready Kubernetes Cluster.
- [MetalK8s](https://github.com/scality/metalk8s) - An opinionated Kubernetes distribution with a focus on long-term on-prem deployments.
- [KubeOperator](https://github.com/KubeOperator/KubeOperator) - Hop onto the sailing of Kubernetes.
- [Typhoon](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.
- [Kubernetes](https://github.com/lyft/kubernetes)
- [EKS](https://github.com/aws/eks-distro) - Amazon EKS Distro.
- [OKD](https://github.com/openshift/okd) - The Community Distribution of Kubernetes that powers RedHat's OpenShift.
- [wksctl](https://github.com/weaveworks/wksctl) - Open Source Weaveworks Kubernetes System.
- [Gravity](https://github.com/gravitational/gravity) - Kubernetes application deployments for restricted、regulated or remote environments.
- [KET](https://github.com/apprenda/kismatic) - Fully-Automated Production-Grade Kubernetes Operations.
- [kURL](https://github.com/replicatedhq/kURL) - Production-grade, airgapped Kubernetes installer combining upstream k8s with overlays and popular components.
- [AgoraKube](https://github.com/ilkilab/agorakube) - Agorakube provides an enterprise grade solution following best practices managing a conformant Kubernetes cluster.
- [K8e](https://github.com/xiaods/k8e) - Simple Enterprise Kubernetes.
- [bcs-k8s](https://github.com/Tencent/bk-bcs/tree/master/bcs-k8s)

## Redefine

- [Kine](https://github.com/k3s-io/kine) - Run Kubernetes on MySQL、Postgres、sqlite、dqlite, not etcd.
- [Arktos](https://github.com/CentaurusInfra/arktos) - Arktos for large-scale cloud platform.

## Cluster

- [Gardener](https://github.com/gardener/gardener) - Kubernetes-native system managing the full lifecycle of conformant Kubernetes clusters as a service.
- [Kubicorn](https://github.com/kubicorn/kubicorn) - Simple, cloud native infrastructure for Kubernetes.
- [kubermatic](https://github.com/kubermatic/kubermatic) - the Central Kubernetes Management Platform For Any Infrastructure.
- [KubeOne](https://github.com/kubermatic/kubeone) - Kubermatic KubeOne automate cluster operations on all your cloud、on-prem、edge and IoT environments.
- [control](https://github.com/supergiant/control) - Control manages the lifecycle of clusters on your infrastructure.
- [triton-kubernetes](https://github.com/joyent/triton-kubernetes) - Triton Kubernetes is a multi-cloud Kubernetes solution.
- [Fleet](https://github.com/rancher/fleet) - Manage large fleets of Kubernetes clusters.
- [oneinfra](https://github.com/oneinfra/oneinfra) - Kubernetes as a Service.
- [machine-controller-manager-provider-metal](https://github.com/metal-stack/machine-controller-manager-provider-metal) - gardener machine controller manager for metal-stack.
- [gardener-extension-provider-metal](https://github.com/metal-stack/gardener-extension-provider-metal) - Implementation of the gardener-extension-controller for metal-stack.
- [machine-controller](https://github.com/kubermatic/machine-controller)
- [baremetal-operator](https://github.com/metal3-io/baremetal-operator) - Bare metal host provisioning integration for Kubernetes.
- [cluster-api-provider-metal3](https://github.com/metal3-io/cluster-api-provider-metal3)
- [Clusterman](https://github.com/Yelp/clusterman) - Cluster Autoscaler for Kubernetes and Mesos.
- [k8s-cronjob-prescaler](https://github.com/microsoft/k8s-cronjob-prescaler) - Kubernetes operator that prescales cluster nodes to ensure a cronjobs start exactly on time.
- [cluster-proportional-autoscaler](https://github.com/kubernetes-sigs/cluster-proportional-autoscaler) - Kubernetes Cluster Proportional Autoscaler Container.
- [Karpenter](https://github.com/awslabs/karpenter) - Kubernetes Node Autoscaling.
- [CLM](https://github.com/zalando-incubator/cluster-lifecycle-manager) - Cluster Lifecycle Manager to provision and update multiple Kubernetes clusters.
- [Federation](https://github.com/kubernetes-retired/federation) - Cluster Federation.
- [KOTS](https://github.com/replicatedhq/kots) - KOTS provides the framework tools and integrations that enable the delivery and management of 3rd-party Kubernetes applications.
- [arkade](https://github.com/alexellis/arkade) - Open Source Kubernetes Marketplace.
- [addon-manager](https://github.com/keikoproj/addon-manager) - Manage addons in a Kubernetes cluster.
- [Monocular](https://github.com/helm/monocular) - Search and discovery UI for Helm Chart repositories.

## Cluster Manager

- [Lens](https://github.com/lensapp/lens) - The Kubernetes IDE.
- [compass](https://github.com/yametech/compass) - Kubernetes Dashboard.
- [Octant](https://github.com/vmware-tanzu/octant) - A highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
- [Submariner](https://github.com/submariner-io/submariner) - Connect all your Kubernetes clusters, no matter where they are in the world.
- [Verrazzano](https://github.com/verrazzano/verrazzano) - Enterprise Container Platform for deploying cloud-native and traditional applications in multi-cloud.
- [KubeCarrier](https://github.com/kubermatic/kubecarrier) - Service Management at Scale.
- [Beetle](https://github.com/Clivern/Beetle) - Kubernetes multi-cluster deployment automation service.
- [Liqo](https://github.com/liqotech/liqo) - Building your endless Kubernetes ocean.
- [KubePlus](https://github.com/cloud-ark/kubeplus) - CRD for CRDs to design multi-tenant platform services from Helm charts.

## Multi Tenancy

- [kiosk](https://github.com/loft-sh/kiosk) - Secure Cluster Sharing & Self-Service Namespace Provisioning.
- [HNC](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc)
- [Capsule](https://github.com/clastix/capsule) - Kubernetes Operator for multi-tenancy.
- [manager](https://github.com/keikoproj/manager) - Multi K8s cluster Namespace Management.

## NetWork

- [Seesaw](https://github.com/google/seesaw) - Seesaw v2 is a Linux Virtual Server based load balancing platform.
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
- [bond-cni](https://github.com/intel/bond-cni) - Bond-cni is for fail-over and high availability of networking in cloudnative orchestration.
- [Knitter](https://github.com/ZTE/Knitter) - Kubernetes network solution.
- [cni-migration](https://github.com/jetstack/cni-migration) - A CLI to migrate the CNI on a Kubernetes cluster from Canal to Cilium, live with no downtime.
- [multus-config-injector](https://github.com/withlin/multus-config-injector) - Pod 多网卡配置注入.
- [Kube-router](https://github.com/cloudnativelabs/kube-router) - Kube-router, a turnkey solution for Kubernetes networking.
- [Bifrost](https://github.com/harmonycloud/Bifrost) - Bifrost is an open source solution enabling L2 network for kubernetes.
- [Kube-OVN](https://github.com/alauda/kube-ovn) - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
- [Weave](https://github.com/weaveworks/weave) - Simple, resilient multi-host containers networking and more.
- [terway](https://github.com/AliyunContainerService/terway) - CNI plugin for Alibaba Cloud VPC/ENI.
- [gardener-extension-networking-calico](https://github.com/gardener/gardener-extension-networking-calico) - Gardener extension controller for the Calico CNI network plugin.
- [sriov-cni](https://github.com/k8snetworkplumbingwg/sriov-cni) - DPDK & SR-IOV CNI plugin.
- [sriov-network-operator](https://github.com/openshift/sriov-network-operator) - SR-IOV Network Operator.
- [k8s-rdma-sriov-dev-plugin](https://github.com/Mellanox/k8s-rdma-sriov-dev-plugin) - Kubernetes Rdma SRIOV device plugin.
- [Kilo](https://github.com/squat/kilo) - Kilo is a multi-cloud network overlay built on WireGuard and designed for Kubernetes.
- [Galaxy](https://github.com/tkestack/galaxy) - Providing high-performance network for Kubernetes.
- [dnsredir](https://github.com/leiless/dnsredir) - Yet another seems better forward/proxy plugin for CoreDNS.
- [SmartNat](https://github.com/DevFactory/smartnat) - Kubernetes controller to expose Services with TCP/UDP.
- [k8s-externalipcontroller](https://github.com/Mirantis/k8s-externalipcontroller) - External IP controller configures External IPs on k8s worker nodes to provide IP connectivity.
- [kubeIP](https://github.com/doitintl/kubeip) - Assign static external IPs from predefined pool of external IP addresses to Google GKE nodes.
- [Skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
- [federated-ingress-controller](https://github.com/oracle/federated-ingress-controller) - Alternative implementation of Federated Ingress using external DNS.
- [Xposer](https://github.com/stakater/Xposer) - A Kubernetes controller to manage Kubernetes Ingresses based on the Service.
- [Gimbal](https://github.com/projectcontour/gimbal) - Gimbal is an ingress load balancing platform capable of routing traffic to multiple Kubernetes and OpenStack clusters.
- [inlets-operator](https://github.com/inlets/inlets-operator) - Add public LoadBalancers to your local Kubernetes clusters.
- [Whitelister](https://github.com/stakater/Whitelister) - A tool to white list node and developer IPs for kubernetes.
- [illuminatio](https://github.com/inovex/illuminatio) - The kubernetes network policy validator.

## Service Mesh

- [Meshery](https://github.com/layer5io/meshery) - Meshery, the service mesh management plane.
- [Gloo](https://github.com/solo-io/gloo) - The Feature-rich, Kubernetes-native, Next-Generation API Gateway Built on Envoy.
- [gloo-mesh](https://github.com/solo-io/gloo-mesh) - The Service Mesh Orchestration Platform.
- [Contour](https://github.com/projectcontour/contour) - Contour is a Kubernetes ingress controller using Envoy proxy.
- [Linkerd](https://github.com/linkerd/linkerd2) - Ultralight, security-first service mesh for Kubernetes.
- [linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) - A purpose-built proxy for the Linkerd service mesh.
- [wesher](https://github.com/costela/wesher) - wireguard overlay mesh network manager.
- [NSM](https://github.com/networkservicemesh/networkservicemesh) - The Hybrid/Multi-cloud IP Service Mesh.
- [mesh](https://github.com/weaveworks/mesh) - A tool for building distributed applications.
- [Pipy](https://github.com/flomesh-io/pipy) - Pipy is a tiny, high performance, highly stable, programmable proxy.

## Storage

- [csi-driver-host-path](https://github.com/kubernetes-csi/csi-driver-host-path) - A sample CSI Driver that creates a local directory as a volume on a single node.
- [csi-driver-lvm](https://github.com/metal-stack/csi-driver-lvm)
- [TopoLVM](https://github.com/topolvm/topolvm) - Capacity-aware CSI plugin for Kubernetes.
- [local-path-provisioner](https://github.com/rancher/local-path-provisioner) - Dynamically provisioning persistent local storage with Kubernetes.
- [dynamic-pv-scaler](https://github.com/opstree/dynamic-pv-scaler) - A golang based Kubernetes application which can scale volume dynamically.
- [external-resizer](https://github.com/kubernetes-csi/external-resizer) - watche Kubernetes PersistentVolumeClaims objects and triggers controller side expansion operation.
- [COSI](https://github.com/kubernetes-sigs/container-object-storage-interface-provisioner-sidecar) - Container Object Storage Interface provisioner responsible to interface.
- [csi-s3](https://github.com/ctrox/csi-s3) - A Container Storage Interface for S3.
- [Longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes.
- [Stork](https://github.com/libopenstorage/stork) - Storage Orchestration Runtime for Kubernetes.
- [Piraeus](https://github.com/piraeusdatastore/piraeus) - High Available Datastore for Kubernetes.
- [Kanister](https://github.com/kanisterio/kanister) - An extensible framework for application-level data management on Kubernetes.

## Scheduler

- [Nomad](https://github.com/hashicorp/nomad) - Nomad is a simple and flexible workload orchestrator to deploy and manage containers non-containerized applications at scale.
- [Eru](https://github.com/projecteru2/core) - A simple stateless flexible production-ready orchestrator designed to easily integrate into existing workflows.
- [poseidon](https://github.com/kubernetes-sigs/poseidon) - A Firmament-based Kubernetes scheduler.
- [Peloton](https://github.com/uber/peloton) - Unified Resource Scheduler to co-schedule mixed types of workloads such as batch、stateless and stateful jobs for better resource utilization.
- [Escalator](https://github.com/atlassian/escalator) - Escalator is a batch or job optimized horizontal autoscaler for Kubernetes.
- [Armada](https://github.com/G-Research/armada) - A multi-cluster batch queuing system for high-throughput workloads on Kubernetes.
- [Bistro](https://github.com/facebook/bistro) - Bistro is a flexible distributed scheduler, a high-performance framework supporting multiple paradigms.
- [Admiralty](https://github.com/admiraltyio/admiralty) - A system of Kubernetes controllers that intelligently schedules workloads across clusters.
- [crl-scheduler](https://github.com/cockroachlabs/crl-scheduler)

## kubelet

- [nri](https://github.com/containerd/nri) - This project is a WIP for a new, CNI like, interface for managing resources on a node for Pods and Containers.
- [Krustlet](https://github.com/deislabs/krustlet) - Kubernetes Rust Kubelet.
- [tensile-kube](https://github.com/virtual-kubelet/tensile-kube) - A Kubernetes Provider.

## Application Delivery

- [TAPP](https://github.com/tkestack/tapp) - Another great app kind for Kubernetes.
- [application](https://github.com/kubernetes-sigs/application) - Application metadata descriptor CRD.
- [Kedge](https://github.com/kedgeproject/kedge) - Simple Concise & Declarative Kubernetes Applications.
- [kubegen](https://github.com/errordeveloper/kubegen) - simple way to describe Kubernetes resources in a structured way but without new syntax or magic.
- [Nuwa](https://github.com/yametech/nuwa) - kubernetes CRD resource.
- [pdb-controller](https://github.com/mikkeloscar/pdb-controller) - Controller for adding default Pod Disruption Budgets to Kubernetes Deployments and StatefulSets.
- [kured](https://github.com/weaveworks/kured) - Kubernetes Reboot Daemon.
- [ExtendedDaemonSet](https://github.com/DataDog/extendeddaemonset) - Kubernetes Extended Daemonset controller.
- [Cronjobber](https://github.com/hiddeco/cronjobber) - Cronjobber is a cronjob controller for Kubernetes with support for time zones.
- [Agones](https://github.com/googleforgames/agones) - Dedicated Game Server Hosting and Scaling for Multiplayer Games on Kubernetes.

## Deployment Engine

- [flagger](https://github.com/fluxcd/flagger) - Progressive delivery Kubernetes operator.
- [Rio](https://github.com/rancher/rio) - Application Deployment Engine for Kubernetes.
- [k8s-deployment-strategies](https://github.com/ContainerSolutions/k8s-deployment-strategies) - Kubernetes deployment strategies explained.
- [Keel](https://github.com/keel-hq/keel) - Kubernetes Operator to automate Helm、DaemonSet、StatefulSet & Deployment updates.
- [stackset-controller](https://github.com/zalando-incubator/stackset-controller) - Opinionated StackSet resource for managing application life cycle and traffic switching in Kubernetes.
- [Kanarini](https://github.com/nilebox/kanarini) - Canary Deployment Controller for Kubernetes.
- [kapp](https://github.com/vmware-tanzu/carvel-kapp) - kapp is a simple deployment tool focused on the concept of Kubernetes application.
- [Ketch](https://github.com/shipa-corp/ketch) - Ketch is an application delivery framework.

## Autoscaler

- [Pangolin](https://github.com/dpeckett/pangolin) - An enhanced Horizontal Pod Autoscaler for Kubernetes.
- [custom-pod-autoscaler-operator](https://github.com/jthomperoo/custom-pod-autoscaler-operator) - Operator for managing Kubernetes Custom Pod Autoscalers.
- [custom-pod-autoscaler](https://github.com/jthomperoo/custom-pod-autoscaler) - Custom Pod Autoscaler base allows creation of Custom Pod Autoscalers.
- [horizontal-pod-autoscaler](https://github.com/jthomperoo/horizontal-pod-autoscaler) - Horizontal Pod Autoscaler, modified to work as a Custom Pod Autoscaler.
- [kubernetes-cronhpa-controller](https://github.com/AliyunContainerService/kubernetes-cronhpa-controller) - HPA controller that allows to scale your workload based on time schedule.
- [CronHPA](https://github.com/tkestack/cron-hpa) - Cron Horizontal Pod Autoscaler.
- [autoscaler](https://github.com/kubernetes/autoscaler) - Autoscaling components for Kubernetes.
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Get your resource requests Just Right.

## Serverless

- [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
- [PipeCD](https://github.com/pipe-cd/pipe) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
- [Keptn](https://github.com/keptn/keptn) - Keptn is a message-driven control-plane for application delivery and automated operations.
- [Brigade](https://github.com/brigadecore/brigade) - Event-based Scripting for Kubernetes.

## Workflows

- [Couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines.
- [Cyclone](https://github.com/caicloud/cyclone) - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development.
- [CDS](https://github.com/ovh/cds) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform.

## Operator

- [hardware-classification-controller](https://github.com/metal3-io/hardware-classification-controller) - Controller for matching host hardware characteristics to expected values.
- [node-feature-discovery](https://github.com/openshift/node-feature-discovery) - Node feature discovery, detects the available hardware features and configuration in a cluster.
- [nodepool-labels-operator](https://github.com/banzaicloud/nodepool-labels-operator) - Nodepool Labels operator for Kubernetes.
- [etcd-cluster-operator](https://github.com/improbable-eng/etcd-cluster-operator) - A controller to deploy and manage etcd clusters inside of Kubernetes.
- [cluster-etcd-operator](https://github.com/openshift/cluster-etcd-operator) - Operator to manage the lifecycle of the etcd members of an OpenShift cluster.
- [etcd-backup](https://github.com/gravitational/etcd-backup) - For handling backup/restore of etcd database from userspace.
- [Etcd-Backup-Restore](https://github.com/gardener/etcd-backup-restore) - Collection of components to back up and restore the Etcd of a Kubernetes cluster.
- [etcd-druid](https://github.com/gardener/etcd-druid) - A druid for etcd management in Gardener.
- [etcd-cloud-operator](https://github.com/Quentin-M/etcd-cloud-operator) - Deploying and managing production-grade etcd clusters on cloud providers.
- [kubernetes-operator](https://github.com/jenkinsci/kubernetes-operator) - Kubernetes native Jenkins Operator.
- [nats-streaming-operator](https://github.com/nats-io/nats-streaming-operator) - NATS Streaming Operator.
- [memcached-operator](https://github.com/ianlewis/memcached-operator) - A Kubernetes operator for memcached.
- [cass-operator](https://github.com/datastax/cass-operator) - The DataStax Kubernetes Operator for Apache Cassandra.
- [scylla-operator](https://github.com/scylladb/scylla-operator) - The Kubernetes Operator for ScyllaDB.
- [postgres-operator](https://github.com/zalando/postgres-operator) - Postgres operator creates and manages PostgreSQL clusters running in Kubernetes.
- [postgres-operator](https://github.com/CrunchyData/postgres-operator) - Production PostgreSQL for Kubernetes from high availability Postgres clusters to full-scale database-as-a-service.
- [mongodb-kubernetes-operator](https://github.com/mongodb/mongodb-kubernetes-operator) - MongoDB Community Kubernetes Operator.
- [solr-operator](https://github.com/apache/solr-operator) - Kubernetes Operator for Apache Solr.
- [druid-operator](https://github.com/druid-io/druid-operator) - Druid Kubernetes Operator.
- [elastic-jupyter-operator](https://github.com/tkestack/elastic-jupyter-operator) - Cloud-native way to provide elastic Jupyter Notebook services on Kubernetes.
- [fuxi](https://github.com/yametech/fuxi) - Kubernetes Control Plane.

## Framework

- [generic-admission-server](https://github.com/openshift/generic-admission-server) - A library for writing admission webhooks based on k8s.io/apiserver.
- [admission-control](https://github.com/elithrar/admission-control) - A helpful micro-framework for writing Kubernetes Admission Controllers.
- [Multicluster-Controller](https://github.com/admiraltyio/multicluster-controller) - A Library for Building Hybrid and Multicloud Kubernetes Operators.
- [whitebox-controller](https://github.com/summerwind/whitebox-controller) - Extensible generic controller for Kubernetes.
- [Metacontroller](https://github.com/metacontroller/metacontroller) - Writing kubernetes controllers can be simple.
- [CRAFT](https://github.com/salesforce/craft) - CRAFT removes the language barrier to create Kubernetes Operators.
- [Operatify](https://github.com/operatify/operatify) - Operators made simple for resources with CRUD APIs.
- [KUDO](https://github.com/kudobuilder/kudo) - Kubernetes Universal Declarative Operator.
- [Gontroller](https://github.com/spotahome/gontroller) - Go library to create resilient feedback loop/control controllers.
- [operator-kit](https://github.com/rook/operator-kit) - A library for creating a Kubernetes Operator.
- [reconciler-runtime](https://github.com/vmware-labs/reconciler-runtime) - Kubernetes reconciler framework building on controller-runtime.

## OPS

- [kubent](https://github.com/doitintl/kube-no-trouble) - Easily check your cluster for use of deprecated APIs.
- [podpreset-webhook](https://github.com/redhat-cop/podpreset-webhook) - A helpful micro-framework for writing Kubernetes Admission Controllers.
- [lxcfs-initializer](https://github.com/denverdino/lxcfs-initializer) - Kubernetes Initializer example to support LXCFS.
- [lxcfs-admission-webhook](https://github.com/denverdino/lxcfs-admission-webhook)
- [mutating-trace-admission-controller](https://github.com/kubernetes-retired/mutating-trace-admission-controller) - enables experimental tracing of kubernetes object lifecycle.
- [Tini](https://github.com/krallin/tini) - A tiny but valid init for containers.
- [dumb-init](https://github.com/Yelp/dumb-init) - A minimal init system for Linux containers.
- [OOMHero](https://github.com/ricardomaraschini/oomhero) - Kubernetes sidecar for memory usage tracking.
- [kubernetes-oom-event-generator](https://github.com/xing/kubernetes-oom-event-generator) - Generate a Kubernetes Event when a Pod's container has been OOMKilled.
- [Sonobuoy](https://github.com/vmware-tanzu/sonobuoy) - Sonobuoy is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster.
- [k8s-platform-lcm](https://github.com/arminc/k8s-platform-lcm) - A faster and easier way to manage the lifecycle of applications and tools.
- [troubleshoot](https://github.com/replicatedhq/troubleshoot) - Preflight Checks and Support Bundles Framework for Kubernetes Applications.
- [Crashd](https://github.com/vmware-tanzu/crash-diagnostics) - Crash-Diagnostics is a tool to help investigate analyze and troubleshoot unresponsive or crashed Kubernetes clusters.
- [governor](https://github.com/keikoproj/governor) - A collection of cluster reliability tools for Kubernetes.
- [pod-reaper](https://github.com/ptagr/pod-reaper) - A kubernetes operator that reaps pods that have reached their lifetime.
- [Jamadar](https://github.com/stakater/Jamadar) - A kubernetes controller which cleans up cluster left-overs.
- [draino](https://github.com/planetlabs/draino) - Automatically cordon and drain Kubernetes nodes based on node conditions.
- [astrolabe](https://github.com/vmware-tanzu/astrolabe) - Data protection framework for complex applications.
- [Gemini](https://github.com/FairwindsOps/gemini) - Automated backups of PersistentVolumeClaims in Kubernetes using VolumeSnapshots.
- [Stash](https://github.com/stashed/stash) - Backup your Kubernetes Stateful Applications.
- [cert-injection-webhook](https://github.com/vmware-tanzu/cert-injection-webhook) - Provides a Kubernetes webhook to inject CA certificates and proxy environment variables into pods.
- [Kubecost](https://github.com/kubecost/cost-model) - Cross-cloud cost allocation models for workloads running on Kubernetes.
- [ksync](https://github.com/ksync/ksync) - Sync files between your local system and kubernetes cluster.

## Observability

- [Sloop](https://github.com/salesforce/sloop) - Kubernetes History Visualization.
- [Scope](https://github.com/weaveworks/scope) - Monitoring、visualisation & management for Docker & Kubernetes.
- [Pixie](https://github.com/pixie-labs/pixie) - Pixie gives you instant visibility by giving access to metrics、events、traces and logs without changing code.
- [metering-operator](https://github.com/kube-reporting/metering-operator) - The Metering Operator is responsible for collecting metrics and other information.
- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time.
- [kmoncon](https://github.com/Stono/kconmon) - A Kubernetes node connectivity monitoring tool.
- [Kubenurse](https://github.com/postfinance/kubenurse) - Kubernetes network monitoring.
- [Eventrouter](https://github.com/heptiolabs/eventrouter) - A simple introspective kubernetes service that forwards events to a specified sink.pid2pod.
- [K8stream](https://github.com/last9/k8stream) - Processing kubenetes events stream.
- [pleg-watcher](https://github.com/rhdedgar/pleg-watcher)
- [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.
- [Kubemem](https://github.com/16Bitt/kubemem) - A small binary to probe memory usage in a kubernetes pod.
- [dead-mans-switch](https://github.com/pingcap/dead-mans-switch) - A bypass monitoring prober.
- [prometheus-adapter](https://github.com/kubernetes-sigs/prometheus-adapter) - An implementation of the custom.metrics.k8s.io API using Prometheus.
- [Promxy](https://github.com/jacksontj/promxy) - An aggregating proxy to enable HA prometheus.
- [Kvass](https://github.com/tkestack/kvass) - Kvass is a Prometheus horizontal auto-scaling solution.
- [Promscale](https://github.com/timescale/promscale) - An open-source analytical platform for Prometheus metrics.
- [Promgen](https://github.com/line/promgen) - Promgen is a configuration file generator for Prometheus.
- [kubernetes-mixin](https://github.com/kubernetes-monitoring/kubernetes-mixin) - A set of Grafana dashboards and Prometheus alerts for Kubernetes.
- [awesome-prometheus-alerts](https://github.com/samber/awesome-prometheus-alerts) - Collection of Prometheus alerting rules.
- [Alerta](https://github.com/alerta/alerta) - Alerta monitoring system.
- [DARK](https://github.com/K-Phoen/dark) - Dashboards As Resources in Kubernetes.

## RBAC

- [permission-manager](https://github.com/sighupio/permission-manager) - Permission Manager is a project that brings sanity to Kubernetes RBAC and Users management, Web UI FTW.
- [kubeaudit](https://github.com/Shopify/kubeaudit) - kubeaudit helps you audit your Kubernetes clusters against common security controls.
- [audit2rbac](https://github.com/liggitt/audit2rbac) - Autogenerate RBAC policies based on Kubernetes audit logs.
- [rback](https://github.com/team-soteria/rback) - RBAC in Kubernetes visualizer.
- [rakkess](https://github.com/corneliusweig/rakkess) - kubectl plugin to show an access matrix for k8s server resources.
- [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can) - Show who has RBAC permissions to perform actions on different resources in Kubernetes.
- [kube-rbac-proxy](https://github.com/brancz/kube-rbac-proxy) - Kubernetes RBAC authorizing HTTP proxy for a single upstream.
- [Guard](https://github.com/kubeguard/guard) - Kubernetes Authentication & Authorization WebHook Server.
- [dex](https://github.com/dexidp/dex) - OpenID Connect Identity and OAuth 2.0 Provider with Pluggable Connectors.
- [gangway](https://github.com/heptiolabs/gangway) - An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster.
- [Pinniped](https://github.com/vmware-tanzu/pinniped) - Pinniped provides identity services for Kubernetes clusters.

## Security

- [BOtB](https://github.com/brompwnie/botb) - A container analysis and exploitation tool for pentesters and engineers.
- [Terrier](https://github.com/heroku/terrier) - Terrier can be used to scan Images and Containers to identify and verify the presence of specific files according to their hashes.
- [fanal](https://github.com/aquasecurity/fanal) - Static Analysis Library for Containers.
- [Secrets](https://github.com/deepfence/SecretScanner) - Find secrets and passwords in container images and file systems.
- [Dockle](https://github.com/goodwithtech/dockle) - Container Image Linter for Security Helping build the Best-Practice Docker Image Easy to start.
- [ThreatMapper](https://github.com/deepfence/ThreatMapper) - Identify vulnerabilities in running containers images hosts and repositories.
- [Kubei](https://github.com/Portshift/kubei) - Kubei is a flexible Kubernetes runtime scanner scanning images of worker and Kubernetes nodes providing accurate vulnerabilities assessment.
- [Portieris](https://github.com/IBM/portieris) - A Kubernetes Admission Controller for verifying image trust with Notary.
- [Kube-Scan](https://github.com/octarinesec/kube-scan) - Octarine k8s cluster risk assessment tool.
- [Kubesec](https://github.com/controlplaneio/kubesec) - Security risk analysis for Kubernetes resources.
- [MKIT](https://github.com/darkbitio/mkit) - MKIT validates several common security-related configuration settings of managed Kubernetes cluster objects and the workloads/resources.
- [kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security.
- [k8s-security-dashboard](https://github.com/k8scop/k8s-security-dashboard) - A security monitoring solution for Kubernetes.
- [kubectl-kubesec](https://github.com/controlplaneio/kubectl-kubesec) - Security risk analysis for Kubernetes resources.
- [Falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security.
- [Karydia](https://github.com/karydia/karydia) - Kubernetes Security Walnut.
- [KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - KubeTEE is a collection of TEE development、deployment、maintenance middleware framework for Kubernetes.

## Test

- [bother](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester.
- [Lotus](https://github.com/lotusload/lotus) - Kubernetes controller for running load testing.
- [K-Bench](https://github.com/vmware-tanzu/k-bench) - Workload Benchmark for Kubernetes.

## Develop Tools

- [kubefs](https://github.com/configurator/kubefs) - Mount kubernetes metadata storage as a filesystem.
- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts.
- [Tilt](https://github.com/tilt-dev/tilt) - A multi-service dev environment for teams on Kubernetes.
- [Nocalhost](https://github.com/nocalhost/nocalhost) - Nocalhost is Cloud Native Environment.
- [KT Connect](https://github.com/alibaba/kt-connect) - Manage and Integration with your Kubernetes dev environment more efficient.
- [Okteto](https://github.com/okteto/okteto) - Develop your applications directly in your Kubernetes Cluster.

