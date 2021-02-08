# awesome-cloud-native

Some useful project and tools.

## Image

- [CRFS](https://github.com/google/crfs) - Container Registry Filesystem.
- [Distribution](https://github.com/distribution/distribution) - The toolkit to pack ship store and deliver container content.
- [Distroless](https://github.com/GoogleContainerTools/distroless) - Language focused docker images, minus the operating system.
- [Quay](https://github.com/quay/quay) - Build Store and Distribute your Applications and Containers.
- [Sinker](https://github.com/plexsystems/sinker) - A tool to sync images from one container registry to another.
- [kube-fledged](https://github.com/senthilrch/kube-fledged) - A kubernetes add-on for creating and managing a cache of container images directly on the cluster worker nodes.

## Image Explore

- [skopeo](https://github.com/containers/skopeo) - Work with remote images registries retrieving information images signing content.
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a docker image.
- [image-spec](https://github.com/opencontainers/image-spec) - OCI Image Format.
- [BOtB](https://github.com/brompwnie/botb) - A container analysis and exploitation tool for pentesters and engineers.
- [manifesto](https://github.com/aquasecurity/manifesto) - Use Manifesto to store and query metadata for container images.
- [container-info](https://github.com/rhdedgar/container-info)

## Runtime

- [Frakti](https://github.com/kubernetes/frakti) - The hypervisor-based container runtime for Kubernetes.
- [Krustlet](https://github.com/deislabs/krustlet) - Kubernetes Rust Kubelet.
- [runV](https://github.com/hyperhq/runv) - Hypervisor-based Runtime for OCI.
- [footloose](https://github.com/weaveworks/footloose) - Containers that look like Virtual Machines.
- [Ignite](https://github.com/weaveworks/ignite) - Ignite is an open source Virtual Machine manager with a container UX and built-in GitOps management.

## Install

- [kubespray](https://github.com/kubernetes-sigs/kubespray) - Deploy a Production Ready Kubernetes Cluster.
- [kubeasz](https://github.com/easzlab/kubeasz)
- [Breeze](https://github.com/wise2c-devops/breeze) - Deploy a Production Ready Kubernetes Cluster with a graphical interface.
- [Typhoon](https://github.com/poseidon/typhoon) - Minimal and free Kubernetes distribution with Terraform.
- [kOps](https://github.com/kubernetes/kops) - Production Grade K8s Installation Upgrades and Management.
- [Gravity](https://github.com/gravitational/gravity) - Kubernetes application deployments for restricted、regulated or remote environments.
- [CKE](https://github.com/cybozu-go/cke) - Cybozu Kubernetes Engine.
- [MetalK8s](https://github.com/scality/metalk8s) - An opinionated Kubernetes distribution with a focus on long-term on-prem deployments.
- [Sugarkube](https://github.com/sugarkube/sugarkube) - Ephemeral Kubernetes clusters.

## Distribution Release

- [K8e](https://github.com/xiaods/k8e) - Simple Enterprise Kubernetes.
- [AgoraKube](https://github.com/ilkilab/agorakube) - Agorakube provides an enterprise grade solution following best practices managing a conformant Kubernetes cluster.
- [OKD](https://github.com/openshift/okd) - The Community Distribution of Kubernetes that powers RedHat's OpenShift.
- [EKS](https://github.com/aws/eks-distro) - Amazon EKS Distro.
- [KubeOperator](https://github.com/KubeOperator/KubeOperator) - Hop onto the sailing of Kubernetes.
- [k8s-tew](https://github.com/darxkies/k8s-tew) - The Easier Way.

## Redefine

- [Kine](https://github.com/k3s-io/kine) - Run Kubernetes on MySQL、Postgres、sqlite、dqlite, not etcd.
- [Arktos](https://github.com/CentaurusInfra/arktos) - Arktos for large-scale cloud platform.

## Cluster

- [Clusterman](https://github.com/Yelp/clusterman) - Cluster Autoscaler for Kubernetes and Mesos.
- [cluster-autoscaler](https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler)
- [control](https://github.com/supergiant/control) - Control manages the lifecycle of clusters on your infrastructure.
- [Gardener](https://github.com/gardener/gardener) - Kubernetes-native system managing the full lifecycle of conformant Kubernetes clusters as a service.
- [KubeOne](https://github.com/kubermatic/kubeone) - Kubermatic KubeOne automate cluster operations on all your cloud、on-prem、edge and IoT environments.
- [wksctl](https://github.com/weaveworks/wksctl) - Open Source Weaveworks Kubernetes System.
- [oneinfra](https://github.com/oneinfra/oneinfra) - Kubernetes as a Service.
- [instance-manager](https://github.com/keikoproj/instance-manager) - Create and manage instance groups with Kubernetes.
- [machine-controller](https://github.com/kubermatic/machine-controller)
- [baremetal-operator](https://github.com/metal3-io/baremetal-operator) - Bare metal host provisioning integration for Kubernetes.
- [Fleet](https://github.com/rancher/fleet) - Manage large fleets of Kubernetes clusters.
- [arkade](https://github.com/alexellis/arkade) - Open Source Kubernetes Marketplace.
- [KOTS](https://github.com/replicatedhq/kots) - KOTS provides the framework tools and integrations that enable the delivery and management of 3rd-party Kubernetes applications.
- [addon-manager](https://github.com/keikoproj/addon-manager) - Manage addons in a Kubernetes cluster.

## Multi Cloud

- [Kubicorn](https://github.com/kubicorn/kubicorn) - Simple, cloud native infrastructure for Kubernetes.
- [triton-kubernetes](https://github.com/joyent/triton-kubernetes) - Triton Kubernetes is a multi-cloud Kubernetes solution.
- [kubermatic](https://github.com/kubermatic/kubermatic) - the Central Kubernetes Management Platform For Any Infrastructure.

## Multi Cluster

- [Octant](https://github.com/vmware-tanzu/octant) - A highly extensible platform for developers to better understand the complexity of Kubernetes clusters.
- [KubeCarrier](https://github.com/kubermatic/kubecarrier) - Service Management at Scale.
- [Beetle](https://github.com/Clivern/Beetle) - Kubernetes multi-cluster deployment automation service.
- [Liqo](https://github.com/liqotech/liqo) - Building your endless Kubernetes ocean.
- [Lens](https://github.com/lensapp/lens) - The Kubernetes IDE.
- [compass](https://github.com/yametech/compass) - Kubernetes Dashboard.

## Multi Tenancy

- [manager](https://github.com/keikoproj/manager) - Multi K8s cluster Namespace Management.
- [kiosk](https://github.com/kiosk-sh/kiosk) - Secure Cluster Sharing & Self-Service Namespace Provisioning.
- [HNC](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc)
- [Capsule](https://github.com/clastix/capsule) - Kubernetes Operator for multi-tenancy.
- [Guard](https://github.com/appscode/guard) - Kubernetes Authentication & Authorization WebHook Server.
- [gangway](https://github.com/heptiolabs/gangway) - An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster.
- [Pinniped](https://github.com/vmware-tanzu/pinniped) - Pinniped provides identity services for Kubernetes clusters.
- [dex](https://github.com/dexidp/dex) - OpenID Connect Identity and OAuth 2.0 Provider with Pluggable Connectors.
- [k-rail](https://github.com/cruise-automation/k-rail) - Kubernetes security tool for policy enforcement.

## NetWork

- [kube-keepalived-vip](https://github.com/kubernetes-retired/contrib/tree/master/keepalived-vip)
- [kube-vip](https://github.com/plunder-app/kube-vip) - Kubernetes Control Plane Virtual IP and Load-Balancer.
- [Seesaw](https://github.com/google/seesaw) - Seesaw v2 is a Linux Virtual Server based load balancing platform.
- [MetalLB](https://github.com/metallb/metallb) - A network load-balancer implementation for Kubernetes using standard routing protocols.
- [Porter](https://github.com/kubesphere/porter) - Bare Metal Load-balancer for Kubernetes Cluster.
- [kubernetes-nmstate](https://github.com/nmstate/kubernetes-nmstate) - Declarative node network configuration driven through Kubernetes API.
- [nri](https://github.com/containerd/nri) - This project is a WIP for a new, CNI like, interface for managing resources on a node for Pods and Containers.
- [network-node-manager](https://github.com/kakao/network-node-manager) - network-node-manager controls the network configuration of a node to resolve network issues of kubernetes.
- [bond-cni](https://github.com/intel/bond-cni) - Bond-cni is for fail-over and high availability of networking in cloudnative orchestration.
- [Kube-router](https://github.com/cloudnativelabs/kube-router) - Kube-router, a turnkey solution for Kubernetes networking.
- [felix](https://github.com/projectcalico/felix) - Project Calico's per-host agent Felix responsible for programming routes and security policy.
- [Kube-OVN](https://github.com/alauda/kube-ovn) - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
- [Galaxy](https://github.com/tkestack/galaxy) - Providing high-performance network for Kubernetes.
- [dnsredir](https://github.com/leiless/dnsredir) - Yet another seems better forward/proxy plugin for CoreDNS.
- [Whitelister](https://github.com/stakater/Whitelister) - A tool to white list node and developer IPs for kubernetes.
- [SmartNat](https://github.com/DevFactory/smartnat) - Kubernetes controller to expose Services with TCP/UDP.
- [k8s-externalipcontroller](https://github.com/Mirantis/k8s-externalipcontroller) - External IP controller configures External IPs on k8s worker nodes to provide IP connectivity.
- [Skipper](https://github.com/zalando/skipper) - An HTTP router and reverse proxy for service composition, including use cases like Kubernetes Ingress.
- [Xposer](https://github.com/stakater/Xposer) - A Kubernetes controller to manage Kubernetes Ingresses based on the Service.
- [federated-ingress-controller](https://github.com/oracle/federated-ingress-controller) - Alternative implementation of Federated Ingress using external DNS.
- [manba-ingress](https://github.com/domechn/manba-ingress) - Manba API Gateway for Kubernetes.
- [tyk-k8s](https://github.com/TykTechnologies/tyk-k8s) - Kubernetes ingress controller and sidecar injector for Tyk API Gateway.
- [Traefik](https://github.com/traefik/traefik) - The Cloud Native Application Proxy.
- [mesh](https://github.com/traefik/mesh) - Simpler Service Mesh.
- [mesh](https://github.com/weaveworks/mesh) - A tool for building distributed applications.

## Storage

- [Longhorn](https://github.com/longhorn/longhorn) - Cloud-Native distributed block storage built on and for Kubernetes.
- [dynamic-pv-scaler](https://github.com/opstree/dynamic-pv-scaler) - A golang based Kubernetes application which can scale volume dynamically.

## Scheduler

- [Nomad](https://github.com/hashicorp/nomad) - Nomad is a simple and flexible workload orchestrator to deploy and manage containers、non-containerized applications and virtual machines at scale.
- [Eru](https://github.com/projecteru2/core) - A simple stateless flexible production-ready orchestrator designed to easily integrate into existing workflows.
- [poseidon](https://github.com/kubernetes-sigs/poseidon) - A Firmament-based Kubernetes scheduler.
- [Peloton](https://github.com/uber/peloton) - Unified Resource Scheduler to co-schedule mixed types of workloads such as batch、stateless and stateful jobs for better resource utilization.
- [Armada](https://github.com/G-Research/armada) - A multi-cluster batch queuing system for high-throughput workloads on Kubernetes.
- [Escalator](https://github.com/atlassian/escalator) - Escalator is a batch or job optimized horizontal autoscaler for Kubernetes.

## Orchestration

- [Nuclio](https://github.com/nuclio/nuclio) - High-Performance Serverless event and data processing platform.
- [Brigade](https://github.com/brigadecore/brigade) - Event-based Scripting for Kubernetes.
- [Couler](https://github.com/couler-proj/couler) - Unified Interface for Constructing and Managing Workflows on different workflow engines.
- [Cyclone](https://github.com/caicloud/cyclone) - Powerful workflow engine and end-to-end pipeline solutions implemented with native Kubernetes resources.
- [Keptn](https://github.com/keptn/keptn) - Keptn is a message-driven control-plane for application delivery and automated operations.
- [Skaffold](https://github.com/GoogleContainerTools/skaffold) - Easy and Repeatable Kubernetes Development.
- [PipeCD](https://github.com/pipe-cd/pipe) - Continuous Delivery for Declarative Kubernetes, Serverless and Infrastructure Applications.
- [CDS](https://github.com/ovh/cds) - Enterprise-Grade Continuous Delivery & DevOps Automation Open Source Platform.

## Application Delivery

- [TAPP](https://github.com/tkestack/tapp) - Another great app kind for Kubernetes.
- [Kedge](https://github.com/kedgeproject/kedge) - Simple Concise & Declarative Kubernetes Applications.
- [kubegen](https://github.com/errordeveloper/kubegen) - simple way to describe Kubernetes resources in a structured way but without new syntax or magic.
- [Nuwa](https://github.com/yametech/nuwa) - kubernetes CRD resource.
- [flagger](https://github.com/fluxcd/flagger) - Progressive delivery Kubernetes operator.
- [Rio](https://github.com/rancher/rio) - Application Deployment Engine for Kubernetes.
- [Keel](https://github.com/keel-hq/keel) - Kubernetes Operator to automate Helm、DaemonSet、StatefulSet & Deployment updates.
- [k8s-deployment-strategies](https://github.com/ContainerSolutions/k8s-deployment-strategies) - Kubernetes deployment strategies explained.
- [KET](https://github.com/apprenda/kismatic) - Fully-Automated Production-Grade Kubernetes Operations.
- [kd](https://github.com/UKHomeOffice/kd) - Minimalistic kubernetes resources deployment tool with templating.
- [Kanarini](https://github.com/nilebox/kanarini) - Canary Deployment Controller for Kubernetes.
- [stackset-controller](https://github.com/zalando-incubator/stackset-controller) - Opinionated StackSet resource for managing application life cycle and traffic switching in Kubernetes.
- [pdb-controller](https://github.com/mikkeloscar/pdb-controller) - Controller for adding default Pod Disruption Budgets to Kubernetes Deployments and StatefulSets.
- [KubeDirector](https://github.com/bluek8s/kubedirector) - Kubernetes Director for deploying and managing stateful applications on Kubernetes.
- [ExtendedDaemonSet](https://github.com/DataDog/extendeddaemonset) - Kubernetes Extended Daemonset controller.
- [k8s-cronjob-prescaler](https://github.com/microsoft/k8s-cronjob-prescaler) - Kubernetes operator that prescales cluster nodes to ensure a cronjobs start exactly on time.
- [Cronjobber](https://github.com/hiddeco/cronjobber) - Cronjobber is a cronjob controller for Kubernetes with support for time zones.

## Autoscaler

- [KEDA](https://github.com/kedacore/keda) - KEDA is a Kubernetes-based Event Driven Autoscaling component.
- [Pangolin](https://github.com/dpeckett/pangolin) - An enhanced Horizontal Pod Autoscaler for Kubernetes.
- [custom-pod-autoscaler](https://github.com/jthomperoo/custom-pod-autoscaler) - Custom Pod Autoscaler base allows creation of Custom Pod Autoscalers.
- [custom-pod-autoscaler-operator](https://github.com/jthomperoo/custom-pod-autoscaler-operator) - Operator for managing Kubernetes Custom Pod Autoscalers.
- [horizontal-pod-autoscaler](https://github.com/jthomperoo/horizontal-pod-autoscaler) - Horizontal Pod Autoscaler, modified to work as a Custom Pod Autoscaler.
- [custom-pod-autoscaler-experiments](https://github.com/jthomperoo/custom-pod-autoscaler-experiments)
- [kubernetes-cronhpa-controller](https://github.com/AliyunContainerService/kubernetes-cronhpa-controller) - HPA controller that allows to scale your workload based on time schedule.
- [CronHPA](https://github.com/tkestack/cron-hpa) - Cron Horizontal Pod Autoscaler.
- [vertical-pod-autoscaler](https://github.com/kubernetes/autoscaler/tree/master/vertical-pod-autoscaler)
- [Goldilocks](https://github.com/FairwindsOps/goldilocks) - Get your resource requests Just Right.

## Operator

- [hardware-classification-controller](https://github.com/metal3-io/hardware-classification-controller) - Controller for matching host hardware characteristics to expected values.
- [node-feature-discovery](https://github.com/openshift/node-feature-discovery) - Node feature discovery, detects the available hardware features and configuration in a cluster.
- [nodepool-labels-operator](https://github.com/banzaicloud/nodepool-labels-operator) - Nodepool Labels operator for Kubernetes.
- [kubernetes-operator](https://github.com/jenkinsci/kubernetes-operator) - Kubernetes native Jenkins Operator.
- [nats-streaming-operator](https://github.com/nats-io/nats-streaming-operator) - NATS Streaming Operator.
- [memcached-operator](https://github.com/ianlewis/memcached-operator) - A Kubernetes operator for memcached.
- [fdb-kubernetes-operator](https://github.com/FoundationDB/fdb-kubernetes-operator) - A kubernetes operator for FoundationDB.
- [postgres-operator](https://github.com/CrunchyData/postgres-operator) - Production PostgreSQL for Kubernetes from high availability Postgres clusters to full-scale database-as-a-service.
- [postgres-operator](https://github.com/zalando/postgres-operator) - Postgres operator creates and manages PostgreSQL clusters running in Kubernetes.
- [mongodb-kubernetes-operator](https://github.com/mongodb/mongodb-kubernetes-operator) - MongoDB Community Kubernetes Operator.
- [druid-operator](https://github.com/druid-io/druid-operator) - Druid Kubernetes Operator.

## OPS

- [governor](https://github.com/keikoproj/governor) - A collection of cluster reliability tools for Kubernetes.
- [Sonobuoy](https://github.com/vmware-tanzu/sonobuoy) - Sonobuoy is a diagnostic tool that makes it easier to understand the state of a Kubernetes cluster.
- [Jamadar](https://github.com/stakater/Jamadar) - A kubernetes controller which cleans up cluster left-overs.
- [draino](https://github.com/planetlabs/draino) - Automatically cordon and drain Kubernetes nodes based on node conditions.
- [astrolabe](https://github.com/vmware-tanzu/astrolabe) - Data protection framework for complex applications.
- [Gemini](https://github.com/FairwindsOps/gemini) - Automated backups of PersistentVolumeClaims in Kubernetes using VolumeSnapshots.
- [Kubemem](https://github.com/16Bitt/kubemem) - A small binary to probe memory usage in a kubernetes pod.
- [OOMHero](https://github.com/ricardomaraschini/oomhero) - Kubernetes sidecar for memory usage tracking.
- [kubernetes-oom-event-generator](https://github.com/xing/kubernetes-oom-event-generator) - Generate a Kubernetes Event when a Pod's container has been OOMKilled.
- [troubleshoot](https://github.com/replicatedhq/troubleshoot) - Preflight Checks and Support Bundles Framework for Kubernetes Applications.
- [Crashd](https://github.com/vmware-tanzu/crash-diagnostics) - Crash-Diagnostics is a tool to help investigate analyze and troubleshoot unresponsive or crashed Kubernetes clusters.
- [Chowkidar](https://github.com/stakater/Chowkidar) - A kubernetes controller that watches/observes events & then takes configured actions.
- [cert-injection-webhook](https://github.com/vmware-tanzu/cert-injection-webhook) - Provides a Kubernetes webhook to inject CA certificates and proxy environment variables into pods.
- [Kubecost](https://github.com/kubecost/cost-model) - Cross-cloud cost allocation models for workloads running on Kubernetes.

## Observability

- [Sloop](https://github.com/salesforce/sloop) - Kubernetes History Visualization.
- [Scope](https://github.com/weaveworks/scope) - Monitoring、visualisation & management for Docker & Kubernetes.
- [kubespy](https://github.com/pulumi/kubespy) - Tools for observing Kubernetes resources in real time.
- [kmoncon](https://github.com/Stono/kconmon) - A Kubernetes node connectivity monitoring tool.
- [Eventrouter](https://github.com/heptiolabs/eventrouter) - A simple introspective kubernetes service that forwards events to a specified sink.pid2pod.
- [K8stream](https://github.com/last9/k8stream) - Processing kubenetes events stream.
- [pleg-watcher](https://github.com/rhdedgar/pleg-watcher)
- [stern](https://github.com/wercker/stern) - Multi pod and container log tailing for Kubernetes.
- [Pixie](https://github.com/pixie-labs/pixie) - Pixie gives you instant visibility by giving access to metrics、events、traces and logs without changing code.
- [prometheus-adapter](https://github.com/kubernetes-sigs/prometheus-adapter) - An implementation of the custom.metrics.k8s.io API using Prometheus.
- [node-cert-exporter](https://github.com/amimof/node-cert-exporter) - An SSL certificate Prometheus exporter.
- [DARK](https://github.com/K-Phoen/dark) - Dashboards As Resources in Kubernetes.
- [Searchlight](https://github.com/searchlight/searchlight) - Alerts for Kubernetes.
- [Alerta](https://github.com/alerta/alerta) - Alerta monitoring system.
- [karma](https://github.com/prymitive/karma) - Alert dashboard for Prometheus Alertmanager.

## RBAC

- [rback](https://github.com/team-soteria/rback) - RBAC in Kubernetes visualizer.
- [audit2rbac](https://github.com/liggitt/audit2rbac) - Autogenerate RBAC policies based on Kubernetes audit logs.
- [kubeaudit](https://github.com/Shopify/kubeaudit) - kubeaudit helps you audit your Kubernetes clusters against common security controls.
- [rakkess](https://github.com/corneliusweig/rakkess) - kubectl plugin to show an access matrix for k8s server resources.
- [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can) - Show who has RBAC permissions to perform actions on different resources in Kubernetes.

## Security

- [fanal](https://github.com/aquasecurity/fanal) - Static Analysis Library for Containers.
- [Terrier](https://github.com/heroku/terrier) - Terrier can be used to scan Images and Containers to identify and verify the presence of specific files according to their hashes.
- [Dockle](https://github.com/goodwithtech/dockle) - Container Image Linter for Security Helping build the Best-Practice Docker Image Easy to start.
- [ThreatMapper](https://github.com/deepfence/ThreatMapper) - Identify vulnerabilities in running containers images hosts and repositories.
- [Kubei](https://github.com/Portshift/kubei) - Kubei is a flexible Kubernetes runtime scanner scanning images of worker and Kubernetes nodes providing accurate vulnerabilities assessment.
- [Portieris](https://github.com/IBM/portieris) - A Kubernetes Admission Controller for verifying image trust with Notary.
- [kube-bench](https://github.com/aquasecurity/kube-bench) - Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark.
- [kube-hunter](https://github.com/aquasecurity/kube-hunter) - Hunt for security weaknesses in Kubernetes clusters.
- [Popeye](https://github.com/derailed/popeye) - A Kubernetes cluster resource sanitizer.
- [Kube-Scan](https://github.com/octarinesec/kube-scan) - Octarine k8s cluster risk assessment tool.
- [MKIT](https://github.com/darkbitio/mkit) - MKIT validates several common security-related configuration settings of managed Kubernetes cluster objects and the workloads/resources.
- [Kubesec](https://github.com/controlplaneio/kubesec) - Security risk analysis for Kubernetes resources.
- [kubectl-kubesec](https://github.com/controlplaneio/kubectl-kubesec) - Security risk analysis for Kubernetes resources.
- [kube-score](https://github.com/zegl/kube-score) - Kubernetes object analysis with recommendations for improved reliability and security.
- [Karydia](https://github.com/karydia/karydia) - Kubernetes Security Walnut.
- [Falco](https://github.com/falcosecurity/falco) - Cloud Native Runtime Security.
- [KubeTEE](https://github.com/SOFAEnclave/KubeTEE) - KubeTEE is a collection of TEE development、deployment、maintenance middleware framework and services、especially for Kubernetes workflow.
- [k8s-security-dashboard](https://github.com/k8scop/k8s-security-dashboard) - A security monitoring solution for Kubernetes.

## Test

- [bother](https://github.com/mhausenblas/kboom) - The Kubernetes scale & soak load tester.
- [Lotus](https://github.com/lotusload/lotus) - Kubernetes controller for running load testing.
- [K-Bench](https://github.com/vmware-tanzu/k-bench) - Workload Benchmark for Kubernetes.

## Develop Tools

- [KubeLinter](https://github.com/stackrox/kube-linter) - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts.
- [kubefs](https://github.com/configurator/kubefs) - Mount kubernetes metadata storage as a filesystem.
- [Tilt](https://github.com/tilt-dev/tilt) - A multi-service dev environment for teams on Kubernetes.
- [KT Connect](https://github.com/alibaba/kt-connect) - Manage and Integration with your Kubernetes dev environment more efficient.
- [Nocalhost](https://github.com/nocalhost/nocalhost) - Nocalhost is Cloud Native Environment.
- [Okteto](https://github.com/okteto/okteto) - Develop your applications directly in your Kubernetes Cluster.
- [kapp](https://github.com/vmware-tanzu/carvel-kapp) - kapp is a simple deployment tool focused on the concept of Kubernetes application.

