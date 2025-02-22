<!-- BEGIN MUNGE: GENERATED_TOC -->

- [v1.25.0-alpha.1](#v1250-alpha1)
  - [Downloads for v1.25.0-alpha.1](#downloads-for-v1250-alpha1)
    - [Source Code](#source-code)
    - [Client Binaries](#client-binaries)
    - [Server Binaries](#server-binaries)
    - [Node Binaries](#node-binaries)
    - [Container Images](#container-images)
  - [Changelog since v1.24.0](#changelog-since-v1240)
  - [Urgent Upgrade Notes](#urgent-upgrade-notes)
    - [(No, really, you MUST read this before you upgrade)](#no-really-you-must-read-this-before-you-upgrade)
  - [Changes by Kind](#changes-by-kind)
    - [Deprecation](#deprecation)
    - [API Change](#api-change)
    - [Feature](#feature)
    - [Failing Test](#failing-test)
    - [Bug or Regression](#bug-or-regression)
    - [Other (Cleanup or Flake)](#other-cleanup-or-flake)
  - [Dependencies](#dependencies)
    - [Added](#added)
    - [Changed](#changed)
    - [Removed](#removed)

<!-- END MUNGE: GENERATED_TOC -->

# v1.25.0-alpha.1


## Downloads for v1.25.0-alpha.1



### Source Code

filename | sha512 hash
-------- | -----------
[kubernetes.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes.tar.gz) | 01aa5755e4d58e2f5e449af62342155e784973f504f831b52aed13fa941075ea06e8fbcadca2445ac570318e7dd9f1042e0447bb74d6042e447dc87dd472b3fc
[kubernetes-src.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-src.tar.gz) | e62170247fb7c50f52274a6e86fde244766cf1cf86bab2913905e9063d03ce5a3882042c755291c766f66b4f4ab630e126d1a9446e31392f77c90a398af57570

### Client Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-client-darwin-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-darwin-amd64.tar.gz) | bb9408704de0f2adac81031d347cfa229a6aef413102a116193f50bf690eac8443bb97cfe59044a1857f7859b462f98fef5c9b7db52f9895d70d399e0d381f19
[kubernetes-client-darwin-arm64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-darwin-arm64.tar.gz) | 0d8aafe99969241019685348bd40c9a5e252110121a9c19c6008874c54c4e6c62eb9470cc55e2eab300bebbaa78696539989a8a23d1e958a222aeabadad9e740
[kubernetes-client-linux-386.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-386.tar.gz) | 67db15a269e252c8945b40e049137a8e7575128f9890ffb121f8dd72b1a79f55aa92aa9e66d5299ef05dcd30bdf1856878f0373ba8c33c46a161cad696dd1c0a
[kubernetes-client-linux-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-amd64.tar.gz) | 58079330c0ebb41806782a7675bf37e8e6466d37ec50d75466b6a2633918d36326863c55a258f0cec8134f3a3abaaf66ab51be70cdb981499ed6f411d58d04fd
[kubernetes-client-linux-arm.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-arm.tar.gz) | afc3b8b30ee5a4baef2b8bf69603884dc488ecd16ab790cdb94859abcbfee0103aff858f7e5778856a7265c54d1eef9df392b0f10ecd26c929a2fe89dcb292e5
[kubernetes-client-linux-arm64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-arm64.tar.gz) | ef1417a70c0a3a428d966e7711f244a2553d85a330898c461a826082533358e0f4a220fd3ccf9295554a6e284fd89d2ebfc37b30cc69d323bf16ce4b9f5e02a4
[kubernetes-client-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-ppc64le.tar.gz) | 5aec975459b3141f7dbb38c86c86fb89ee75470b77095280d2c4e6f5e9f8a4c3b5ef323cd6e4a4403c90d725276621c2d85e749090ce93648f238f289de83ceb
[kubernetes-client-linux-s390x.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-linux-s390x.tar.gz) | 91dbe24885b0fad1bef4c0d60ac4c36ba78669e912ec51f7cfb9d4cc33e6f1ece4ee832a96eedb4d117d7defeaffa539e50b42433caf5145543463deb26146fb
[kubernetes-client-windows-386.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-windows-386.tar.gz) | b9afed1db794c6df8a325c2831643965a7f4c0633b1a8e73432a08bc21a63f57d98a67115c5d8ede46e8b3ea002c1c2ef7d16d62e53530eb9cff92471f06e840
[kubernetes-client-windows-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-windows-amd64.tar.gz) | 95f80902ecae4fac9aa2ef863c63bef752b2554a2e0b07cebd49db37d0ce06b5aafcad779793852634f92e1f0d6a3da4dec48387a361a4ede3f9bd77ee2b70ff
[kubernetes-client-windows-arm64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-client-windows-arm64.tar.gz) | dee0a8658117f90c138e4bcc5dcba7bc201dcac3a993806eaeacc4ed1ba4a4b2aed0eed395169f372010bcde1966b5ba60734729247f7dc7610421ebf70746ba

### Server Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-server-linux-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-server-linux-amd64.tar.gz) | 144c23ff1718b3635cb227c5bda29e7f57a63dc80b9aa5120046deb8cff44946a7ca1844303f6fcaebe3d9b9c91f41f57ec96cb407862322fb783068819ab917
[kubernetes-server-linux-arm.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-server-linux-arm.tar.gz) | b989cacd95bce88d70a2f17200f5d50e06c66e184bb1ab72ee94e65174a1cb8acbbbfb29dc22e85a0893cae31b903ef93ecc62aa7425d8fcbb35c365b588e72c
[kubernetes-server-linux-arm64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-server-linux-arm64.tar.gz) | 0a2ce7c6f016e52149cbe5df5f35db47fcd0c4de5dd04e8054305e3f6ad4554719d658af7cf6ddb40e8e3420bfbc32bbfc87d9f209a9e59813a17f51c4b0581d
[kubernetes-server-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-server-linux-ppc64le.tar.gz) | 63bb9ec0e88a6560cb9a415ee8d5656e5bfd9f63a8388f7abd960b72b6d58e0ba664f7aef7aaa6d436aafcc595a19766b85b1af9d076cf3985786888bdd8a258
[kubernetes-server-linux-s390x.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-server-linux-s390x.tar.gz) | 8f99b8c0133771d0326b7c11ba65009c245f40fe71b1d7737343860e022d4be3c032df8dedf728184d017014c17df93df971622ced800788045fd234b50f36b4

### Node Binaries

filename | sha512 hash
-------- | -----------
[kubernetes-node-linux-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-linux-amd64.tar.gz) | 02f764c2f83992f0820d0186898da449616c4f6ce8a771990ac1f17e277ae369bfeadd24aa0ce2405c6386ff308556437e4f968401b2ef4fb6f344a0a6e60ebd
[kubernetes-node-linux-arm.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-linux-arm.tar.gz) | 6d87f6554d8051be21c268c9d847c1b66cf7785a9cb781b44494f013b9f1afb1018ad2ce54cedb62b33e93517cd630f3168ab63a6b03e7badde70e300bab9a9a
[kubernetes-node-linux-arm64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-linux-arm64.tar.gz) | 9d8d34cb09a73db6c3dabd04975fddbf7387db0f0a241c285fb7995c7256fc5ca37285b680f0f978438e5ca92451f163e1e4c90642c82101d415aa40b06afa2f
[kubernetes-node-linux-ppc64le.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-linux-ppc64le.tar.gz) | 6c5d27306f65ab4eab19f0b39cadd5adb33a3dc3ef602cf4c1e7afd51ac250dea8fef58f748bdbd651d0d77806442b214d098b8a40910627b8a359e482a2706a
[kubernetes-node-linux-s390x.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-linux-s390x.tar.gz) | c8d45846d19e8179969f339bfb4cd13c6d952990b30d301bbb345ac17c4ddaab38c22f798986af6ded6aad96e8415c92c86f2f8fb7fe1bda8b0aba6216758112
[kubernetes-node-windows-amd64.tar.gz](https://dl.k8s.io/v1.25.0-alpha.1/kubernetes-node-windows-amd64.tar.gz) | dd1607634a718d790662420cbaa30af6d7c89b6f9ae64cef5ee224e42c32fe318bf6e1b2180894723fc890c315c4943004dd16c59f94e6daaa09e4435aed1e07

### Container Images

All container images are available as manifest lists and support the described
architectures. It is also possible to pull a specific architecture directly by
adding the "-$ARCH" suffix  to the container image name.

name | architectures
---- | -------------
[k8s.gcr.io/conformance:v1.25.0-alpha.1](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance) | [amd64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance-amd64), [arm](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance-arm), [arm64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance-arm64), [ppc64le](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance-ppc64le), [s390x](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/conformance-s390x)
[k8s.gcr.io/kube-apiserver:v1.25.0-alpha.1](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver) | [amd64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver-amd64), [arm](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver-arm), [arm64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver-arm64), [ppc64le](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver-ppc64le), [s390x](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-apiserver-s390x)
[k8s.gcr.io/kube-controller-manager:v1.25.0-alpha.1](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager) | [amd64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager-amd64), [arm](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager-arm), [arm64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager-arm64), [ppc64le](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager-ppc64le), [s390x](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-controller-manager-s390x)
[k8s.gcr.io/kube-proxy:v1.25.0-alpha.1](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy) | [amd64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy-amd64), [arm](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy-arm), [arm64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy-arm64), [ppc64le](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy-ppc64le), [s390x](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-proxy-s390x)
[k8s.gcr.io/kube-scheduler:v1.25.0-alpha.1](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler) | [amd64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler-amd64), [arm](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler-arm), [arm64](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler-arm64), [ppc64le](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler-ppc64le), [s390x](https://console.cloud.google.com/gcr/images/k8s-artifacts-prod/us/kube-scheduler-s390x)

## Changelog since v1.24.0

## Urgent Upgrade Notes

### (No, really, you MUST read this before you upgrade)

 - Deprecated beta APIs scheduled for removal in 1.25 are no longer served. See https://kubernetes.io/docs/reference/using-api/deprecation-guide/#v1-25 for more information. ([#108797](https://github.com/kubernetes/kubernetes/pull/108797), [@deads2k](https://github.com/deads2k)) [SIG API Machinery, Instrumentation and Testing]
  - No action required; No API/CLI changed; Add new Windows Image Support ([#110333](https://github.com/kubernetes/kubernetes/pull/110333), [@liurupeng](https://github.com/liurupeng)) [SIG Cloud Provider and Windows]
  - There is a new OCI image registry (registry.k8s.io) that can be used to pull kubernetes images. The old registry (k8s.gcr.io) will continue to be supported for the foreseeable future, but the new name should perform better because it frontends equivalent mirrors in other clouds.  Please point your clusters to the new registry going forward. 
  
  Admission/Policy integrations that have an allowlist of registries need to include "registry.k8s.io" alongside "k8s.gcr.io".
  Air-gapped environments and image garbage-collection configurations will need to update to pre-pull and preserve required images under "registry.k8s.io" as well as "k8s.gcr.io". ([#109938](https://github.com/kubernetes/kubernetes/pull/109938), [@dims](https://github.com/dims)) [SIG API Machinery, Architecture, Auth, CLI, Cloud Provider, Cluster Lifecycle, Instrumentation, K8s Infra, Node, Release, Scalability, Storage and Testing]
 
## Changes by Kind

### Deprecation

- Kube-controller-manager:  'deleting-pods-qps'  'deleting-pods-burst'  'register-retry-count' flags are removed. ([#109612](https://github.com/kubernetes/kubernetes/pull/109612), [@pandaamanda](https://github.com/pandaamanda)) [SIG API Machinery]
- Kubeadm: during "upgrade apply/diff/node", in case the "ClusterConfiguration.imageRepository" stored in the "kubeadm-config" ConfigMap contains the legacy "k8s.gcr.io" repository, modify it to the new default "registry.k8s.io". Reflect the change in the in-cluster ConfigMap only during "upgrade apply". ([#110343](https://github.com/kubernetes/kubernetes/pull/110343), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Kubeadm: graduate the kubeadm specific feature gate UnversionedKubeletConfigMap to GA and lock it to "true" by default. The kubelet related ConfigMap and RBAC rules are now locked to have a simplified naming "*kubelet-config" instead of the legacy naming "*kubelet-config-x.yy", where "x.yy" was the version of the control plane. If you have previously used the old naming format with UnversionedKubeletConfigMap=false, you must manually copy the config map from kube-system/kubelet-config-x.yy to kube-system/kubelet-config before upgrading to 1.25. ([#110327](https://github.com/kubernetes/kubernetes/pull/110327), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle and Testing]
- Kubeadm: stop applying the "node-role.kubernetes.io/master:NoSchedule" taint to control plane nodes for new clusters. Remove the taint from existing control plane nodes during "kubeadm upgrade apply" ([#110095](https://github.com/kubernetes/kubernetes/pull/110095), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle and Testing]
- The `gcp` and `azure` auth plugins have been removed from client-go and kubectl. See https://github.com/Azure/kubelogin and https://cloud.google.com/blog/products/containers-kubernetes/kubectl-auth-changes-in-gke for details about the cloud-specific replacements. ([#110013](https://github.com/kubernetes/kubernetes/pull/110013), [@enj](https://github.com/enj)) [SIG API Machinery and Auth]
- The beta `PodSecurityPolicy` admission plugin, deprecated since 1.21, is removed. Follow the instructions at https://kubernetes.io/docs/tasks/configure-pod-container/migrate-from-psp/ to migrate to the built-in PodSecurity admission plugin (or to another third-party policy webhook) prior to upgrading to v1.25. ([#109798](https://github.com/kubernetes/kubernetes/pull/109798), [@liggitt](https://github.com/liggitt)) [SIG API Machinery, Apps, Auth, Cloud Provider, Instrumentation, Node, Security, Storage and Testing]

### API Change

- Introduce NodeInclusionPolicies to specify nodeAffinity/nodeTaint strategy when calculating pod topology spread skew. ([#108492](https://github.com/kubernetes/kubernetes/pull/108492), [@kerthcet](https://github.com/kerthcet)) [SIG API Machinery, Apps, Scheduling and Testing]
- The `metadata.clusterName` field is completely removed. This should not have any user-visible impact. ([#109602](https://github.com/kubernetes/kubernetes/pull/109602), [@lavalamp](https://github.com/lavalamp)) [SIG API Machinery, Apps, Auth and Testing]
- This release add support for NodeExpandSecret for CSI driver client which enables the CSI drivers to make use of this secret while performing node expansion operation based on the user request. Previously there was no secret  provided as part of the nodeexpansion call, thus CSI drivers were not make use of the same while expanding the volume at node side. ([#105963](https://github.com/kubernetes/kubernetes/pull/105963), [@zhucan](https://github.com/zhucan)) [SIG API Machinery, Apps and Storage]

### Feature

- Added sum feature to `kubectl top pod` ([#105100](https://github.com/kubernetes/kubernetes/pull/105100), [@lauchokyip](https://github.com/lauchokyip)) [SIG CLI]
- Adds the `Apply` and `ApplyStatus` methods to the dynamic `ResourceInterface` ([#109443](https://github.com/kubernetes/kubernetes/pull/109443), [@kevindelgado](https://github.com/kevindelgado)) [SIG API Machinery and Testing]
- Graduate ServiceIPStaticSubrange feature to beta (disabled by default) ([#110419](https://github.com/kubernetes/kubernetes/pull/110419), [@aojea](https://github.com/aojea)) [SIG Network]
- Kube-up now includes CoreDNS version v1.9.3 ([#110488](https://github.com/kubernetes/kubernetes/pull/110488), [@mzaian](https://github.com/mzaian)) [SIG Cloud Provider]
- Kubeadm: Added support for additional authentication strategies in `kubeadm join` with discovery/kubeconfig file: client-go authentication plugins (`exec`), `tokenFile`, and `authProvider` ([#110553](https://github.com/kubernetes/kubernetes/pull/110553), [@tallaxes](https://github.com/tallaxes)) [SIG Cluster Lifecycle]
- Kubeadm: add support for the flag "--print-manifest" to the addon phases "kube-proxy" and "coredns" of "kubeadm init phase addon". If this flag is used kubeadm will not apply a given addon and instead print to the terminal the API objects that will be applied. ([#109995](https://github.com/kubernetes/kubernetes/pull/109995), [@wangyysde](https://github.com/wangyysde)) [SIG Cluster Lifecycle]
- Kubeadm: enhance the "patches" functionality to be able to patch kubelet config files containing v1beta1.KubeletConfiguration. The new patch target is called "kubeletconfiguration" (e.g. patch file "kubeletconfiguration+json.json"). This makes it possible to apply node specific KubeletConfiguration options during "init", "join" and "upgrade", while the main KubeletConfiguration that is passed to "init" as part of the "--config" file can still act as the global / stored in the cluster KubeletConfiguration. ([#110405](https://github.com/kubernetes/kubernetes/pull/110405), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle and Testing]
- Kubeadm: modify the etcd static Pod liveness and readyness probes to use a new etcd 3.5.3+ HTTP(s) health check endpoint "/health?serializable=true" that allows to track the health of individual etcd members and not fail all members if a single member is not healthy in the etcd cluster. ([#110072](https://github.com/kubernetes/kubernetes/pull/110072), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Kubeadm: support experimental JSON/YAML output for "kubeadm upgrade plan" with the "--output" flag ([#108447](https://github.com/kubernetes/kubernetes/pull/108447), [@pacoxu](https://github.com/pacoxu)) [SIG Cluster Lifecycle]
- Kubeadm: update CoreDNS to v1.9.3. ([#110489](https://github.com/kubernetes/kubernetes/pull/110489), [@pacoxu](https://github.com/pacoxu)) [SIG Cluster Lifecycle]
- Kubectl: support multiple resources for kubectl rollout status ([#108777](https://github.com/kubernetes/kubernetes/pull/108777), [@pjo256](https://github.com/pjo256)) [SIG CLI and Testing]
- Kubernetes is now built with Golang 1.18.2 ([#110043](https://github.com/kubernetes/kubernetes/pull/110043), [@cpanato](https://github.com/cpanato)) [SIG Release and Testing]
- Kubernetes is now built with Golang 1.18.3 ([#110421](https://github.com/kubernetes/kubernetes/pull/110421), [@cpanato](https://github.com/cpanato)) [SIG Release and Testing]
- Lock CSIMigrationAzureDisk feature gate to default ([#110491](https://github.com/kubernetes/kubernetes/pull/110491), [@andyzhangx](https://github.com/andyzhangx)) [SIG Cloud Provider]
- MaxUnavailable for StatefulSets, allows faster RollingUpdate by taking down more than 1 pod at a time. The number of pods you want to take down during a RollingUpdate is configurable using maxUnavailable parameter. ([#109251](https://github.com/kubernetes/kubernetes/pull/109251), [@krmayankk](https://github.com/krmayankk)) [SIG Apps and CLI]
- Return a warning when applying a pod-security.kubernetes.io label to a PodSecurity-exempted namespace.
  Stop including the pod-security.kubernetes.io/exempt=namespace audit annotation on namespace requests. ([#109680](https://github.com/kubernetes/kubernetes/pull/109680), [@tallclair](https://github.com/tallclair)) [SIG Auth]
- TopologySpreadConstraints will be shown in describe command for pods, deployments, daemonsets, etc. ([#109563](https://github.com/kubernetes/kubernetes/pull/109563), [@ardaguclu](https://github.com/ardaguclu)) [SIG CLI]
- Updat debian-base, debian-iptables, and setcap images:
  - debian-base:bullseye-v1.3.0
  - debian-iptables:bullseye-v1.4.0
  - setcap:bullseye-v1.3.0 ([#110558](https://github.com/kubernetes/kubernetes/pull/110558), [@wespanther](https://github.com/wespanther)) [SIG Architecture, Release and Testing]
- When using the OpenStack legacy cloud provider, kubelet and KCM will ignore unknown configuration directives rather than failing to start. ([#109709](https://github.com/kubernetes/kubernetes/pull/109709), [@mdbooth](https://github.com/mdbooth)) [SIG Cloud Provider]

### Failing Test

- E2e tests: the e2e image, agnhost:2.38, has a bug and it hangs instead of exiting if a SIGTERM signal is received and the shutdown-delay option is 0` ([#110214](https://github.com/kubernetes/kubernetes/pull/110214), [@aojea](https://github.com/aojea)) [SIG Testing]

### Bug or Regression

- Allow expansion of ephemeral volumes ([#109987](https://github.com/kubernetes/kubernetes/pull/109987), [@gnufied](https://github.com/gnufied)) [SIG Node and Storage]
- Apiserver: fix audit of loading more than one webhooks ([#110145](https://github.com/kubernetes/kubernetes/pull/110145), [@sxllwx](https://github.com/sxllwx)) [SIG API Machinery and Auth]
- Do not raise an error when setting a label with the same value, just ignore it. ([#105936](https://github.com/kubernetes/kubernetes/pull/105936), [@zigarn](https://github.com/zigarn)) [SIG CLI]
- EndpointSlices marked for deletion are now ignored during reconciliation. ([#109624](https://github.com/kubernetes/kubernetes/pull/109624), [@aryan9600](https://github.com/aryan9600)) [SIG Apps and Network]
- Etcd: Update to v3.5.4 ([#110033](https://github.com/kubernetes/kubernetes/pull/110033), [@mk46](https://github.com/mk46)) [SIG API Machinery, Cloud Provider, Cluster Lifecycle and Testing]
- Fix JobTrackingWithFinalizers that:
  - was declaring a job finished before counting all the created pods in the status
  - was leaving pods with finalizers, blocking pod and job deletions
  
  JobTrackingWithFinalizers is still disabled by default. ([#109486](https://github.com/kubernetes/kubernetes/pull/109486), [@alculquicondor](https://github.com/alculquicondor)) [SIG Apps and Testing]
- Fix a bug where CRI implementations that use cAdvisor stats provider (CRI-O) don't evict pods when their logs exceed ephemeral storage limit. ([#108115](https://github.com/kubernetes/kubernetes/pull/108115), [@haircommander](https://github.com/haircommander)) [SIG Node]
- Fix a bug where CSI migration doesn't count inline volumes for attach limit. ([#107787](https://github.com/kubernetes/kubernetes/pull/107787), [@Jiawei0227](https://github.com/Jiawei0227)) [SIG Scheduling and Storage]
- Fix a bug where metrics are not recorded during Preemption(PostFilter). ([#108727](https://github.com/kubernetes/kubernetes/pull/108727), [@sanposhiho](https://github.com/sanposhiho)) [SIG Scheduling]
- Fix a data race in authentication between AuthenticatedGroupAdder and cached token authenticator. ([#109969](https://github.com/kubernetes/kubernetes/pull/109969), [@sttts](https://github.com/sttts)) [SIG API Machinery and Auth]
- Fix bug that prevented informer/reflector callers from unwrapping and catching specific API errors by type. ([#110076](https://github.com/kubernetes/kubernetes/pull/110076), [@karlkfi](https://github.com/karlkfi)) [SIG API Machinery]
- Fix bug that prevented the job controller from enforcing activeDeadlineSeconds when set ([#110294](https://github.com/kubernetes/kubernetes/pull/110294), [@harshanarayana](https://github.com/harshanarayana)) [SIG Apps and Scheduling]
- Fix for volume reconstruction of CSI ephemeral volumes ([#108997](https://github.com/kubernetes/kubernetes/pull/108997), [@dobsonj](https://github.com/dobsonj)) [SIG Node, Storage and Testing]
- Fix image pulling failure when IMDS is unavailable in kubelet startup ([#110523](https://github.com/kubernetes/kubernetes/pull/110523), [@andyzhangx](https://github.com/andyzhangx)) [SIG Cloud Provider]
- Fix incorrectly report scope for request_duration_seconds and request_slo_duration_seconds metrics for POST custom resources API calls. ([#110009](https://github.com/kubernetes/kubernetes/pull/110009), [@azylinski](https://github.com/azylinski)) [SIG Instrumentation]
- Fix printing resources with int64 fields ([#110408](https://github.com/kubernetes/kubernetes/pull/110408), [@tkashem](https://github.com/tkashem)) [SIG API Machinery]
- Fix spurious kube-apiserver log warnings related to openapi v3 merging when creating or modifying CustomResourceDefinition objects ([#109880](https://github.com/kubernetes/kubernetes/pull/109880), [@Jefftree](https://github.com/Jefftree)) [SIG API Machinery and Testing]
- Fix the bug that a ServiceIPStaticSubrange enabled cluster assigns duplicate IP addresses when the dynamic block is exhausted. ([#109928](https://github.com/kubernetes/kubernetes/pull/109928), [@tksm](https://github.com/tksm)) [SIG Network]
- Fix the bug that the metrics for the cluster IP allocator are incorrectly reported. ([#110027](https://github.com/kubernetes/kubernetes/pull/110027), [@tksm](https://github.com/tksm)) [SIG Instrumentation]
- Fixed a kubelet issue that could result in invalid pod status updates to be sent to the api-server where pods would be reported in a terminal phase but also report a ready condition of true in some cases. ([#110256](https://github.com/kubernetes/kubernetes/pull/110256), [@bobbypage](https://github.com/bobbypage)) [SIG Node and Testing]
- Fixed a long-standing but very obscure bug involving Services of type LoadBalancer with multiple IPs and a LoadBalancerSourceRanges that overlaps the node IP. ([#109826](https://github.com/kubernetes/kubernetes/pull/109826), [@danwinship](https://github.com/danwinship)) [SIG Network]
- Fixes strict server-side field validation treating metadata fields as unknown fields ([#109268](https://github.com/kubernetes/kubernetes/pull/109268), [@liggitt](https://github.com/liggitt)) [SIG API Machinery and Testing]
- Kube-apiserver: Get, GetList and Watch requests that should be served by the apiserver cacher during shutdown will be rejected to avoid a deadlock situation leaving requests hanging. ([#108414](https://github.com/kubernetes/kubernetes/pull/108414), [@aojea](https://github.com/aojea)) [SIG API Machinery]
- Kubeadm: only taint control plane nodes when the legacy "master" taint is present. This avoids a bug where "kubeadm upgrade" will re-taint a control plane node with the new "control plane" taint even if the user explicitly untainted the node. ([#109840](https://github.com/kubernetes/kubernetes/pull/109840), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Kubeadm: pass the host OS environment variables when executing "crictl" during image pulls. This fixes a bug where *PROXY environment variables did not affect crictl's internet connectivity. ([#110134](https://github.com/kubernetes/kubernetes/pull/110134), [@mk46](https://github.com/mk46)) [SIG Cluster Lifecycle]
- Kubelet: wait for node allocatable ephemeral-storage data ([#101882](https://github.com/kubernetes/kubernetes/pull/101882), [@jackfrancis](https://github.com/jackfrancis)) [SIG Node and Storage]
- Kubernetes now correctly handles "search ." in the host's resolv.conf file by preserving the "." entry in the "resolv.conf" that the kubelet writes to pods. ([#109441](https://github.com/kubernetes/kubernetes/pull/109441), [@Miciah](https://github.com/Miciah)) [SIG Network and Node]
- ManagedFields time is correctly updated when the value of a managed field is modified. ([#110058](https://github.com/kubernetes/kubernetes/pull/110058), [@glebiller](https://github.com/glebiller)) [SIG API Machinery]
- Manual change of a failed job condition status to False does not result in duplicate conditions ([#110292](https://github.com/kubernetes/kubernetes/pull/110292), [@mimowo](https://github.com/mimowo)) [SIG Apps]
- OpenAPI will no longer duplicate these schemas:
  - io.k8s.apimachinery.pkg.apis.meta.v1.DeleteOptions_v2
  - io.k8s.apimachinery.pkg.apis.meta.v1.ObjectMeta_v2
  - io.k8s.apimachinery.pkg.apis.meta.v1.OwnerReference_v2
  - io.k8s.apimachinery.pkg.apis.meta.v1.StatusDetails_v2
  - io.k8s.apimachinery.pkg.apis.meta.v1.Status_v2 ([#110179](https://github.com/kubernetes/kubernetes/pull/110179), [@Jefftree](https://github.com/Jefftree)) [SIG API Machinery and Testing]
- Panics while calling validating admission webhook are caught and honor the fail open or fail closed setting. ([#108746](https://github.com/kubernetes/kubernetes/pull/108746), [@deads2k](https://github.com/deads2k)) [SIG API Machinery]
- Pods will now post their readiness during termination. ([#110191](https://github.com/kubernetes/kubernetes/pull/110191), [@rphillips](https://github.com/rphillips)) [SIG Network, Node and Testing]
- Reduced time taken to sync proxy rules on Windows kube-proxy with kernelspace mode ([#109124](https://github.com/kubernetes/kubernetes/pull/109124), [@daschott](https://github.com/daschott)) [SIG Network, Release and Windows]
- The kube-proxy `sync_proxy_rules_no_endpoints_total` metric now only counts local-traffic-policy services which have remote endpoints but not local endpoints. ([#109782](https://github.com/kubernetes/kubernetes/pull/109782), [@danwinship](https://github.com/danwinship)) [SIG Network]
- The pod phase lifecycle guarantees that terminal Pods, those whose states are Unready or Succeeded, can not regress and will have all container stopped. Hence, terminal Pods will never be reachable and should not publish their IP addresses on the Endpoints or EndpointSlices, independently of the Service TolerateUnready option. ([#110255](https://github.com/kubernetes/kubernetes/pull/110255), [@robscott](https://github.com/robscott)) [SIG Apps, Network, Node and Testing]
- Upgrade Azure/go-autorest/autorest to v0.11.27 ([#110371](https://github.com/kubernetes/kubernetes/pull/110371), [@andyzhangx](https://github.com/andyzhangx)) [SIG Cloud Provider]

### Other (Cleanup or Flake)

- Add missing powershell option to kubectl completion command short description ([#109773](https://github.com/kubernetes/kubernetes/pull/109773), [@danielhelfand](https://github.com/danielhelfand)) [SIG CLI]
- Apimachinery/clock: This deletes the apimachinery/clock package. Please use k8s.io/utils/clock instead. ([#109752](https://github.com/kubernetes/kubernetes/pull/109752), [@MadhavJivrajani](https://github.com/MadhavJivrajani)) [SIG API Machinery]
- Apiserver_longrunning_gauge is removed from the codebase. Please use apiserver_longrunning_requests instead. ([#110310](https://github.com/kubernetes/kubernetes/pull/110310), [@logicalhan](https://github.com/logicalhan)) [SIG API Machinery and Instrumentation]
- Feature gates that graduated to GA in 1.23 or earlier and were unconditionally enabled have been removed: CSIServiceAccountToken, ConfigurableFSGroupPolicy, EndpointSlice, EndpointSliceNodeName, EndpointSliceProxying, GenericEphemeralVolume, IPv6DualStack, IngressClassNamespacedParams, StorageObjectInUseProtection, TTLAfterFinished, VolumeSubpath, WindowsEndpointSliceProxying ([#109435](https://github.com/kubernetes/kubernetes/pull/109435), [@pohly](https://github.com/pohly)) [SIG API Machinery, Architecture and Cloud Provider]
- For resources built into an apiserver, the server now logs at `-v=3` whether it is using watch caching. ([#109175](https://github.com/kubernetes/kubernetes/pull/109175), [@MikeSpreitzer](https://github.com/MikeSpreitzer)) [SIG API Machinery]
- Honor the framework delete timeout for pv ([#109764](https://github.com/kubernetes/kubernetes/pull/109764), [@saikat-royc](https://github.com/saikat-royc)) [SIG Storage and Testing]
- Kube-controller-manager's deprecated `--experimental-cluster-signing-duration` flag is now removed. Adapt your machinery to use the `--cluster-signing-duration` flag that is available since v1.19. ([#108476](https://github.com/kubernetes/kubernetes/pull/108476), [@ialidzhikov](https://github.com/ialidzhikov)) [SIG Auth]
- Kubeadm: perform additional dockershim cleanup. Treat all container runtimes as remote by using the flag "--container-runtime=remote", given dockershim was removed in 1.24 and given kubeadm 1.25 supports a kubelet version of 1.24 and 1.25. The flag "--network-plugin" will no longer be used for new clusters. Stop cleaning up the following dockershim related directories on "kubeadm reset": "/var/lib/dockershim", "/var/runkubernetes", "/var/lib/cni" ([#110022](https://github.com/kubernetes/kubernetes/pull/110022), [@neolit123](https://github.com/neolit123)) [SIG Cluster Lifecycle]
- Kubelet's deprecated `--experimental-kernel-memcg-notification` flag is now removed.  Use `--kernel-memcg-notification` instead. ([#109388](https://github.com/kubernetes/kubernetes/pull/109388), [@ialidzhikov](https://github.com/ialidzhikov)) [SIG Node]
- Kubernetes binaries are now built in module mode instead of GOPATH mode ([#109464](https://github.com/kubernetes/kubernetes/pull/109464), [@liggitt](https://github.com/liggitt)) [SIG Architecture, Node and Testing]
- Remove deprecated kubectl.kubernetes.io/default-logs-container support ([#109254](https://github.com/kubernetes/kubernetes/pull/109254), [@pacoxu](https://github.com/pacoxu)) [SIG CLI]
- Rename apiserver_watch_cache_watch_cache_initializations_total to apiserver_watch_cache_initializations_total ([#109579](https://github.com/kubernetes/kubernetes/pull/109579), [@logicalhan](https://github.com/logicalhan)) [SIG API Machinery and Instrumentation]
- TBD ([#109277](https://github.com/kubernetes/kubernetes/pull/109277), [@MikeSpreitzer](https://github.com/MikeSpreitzer)) [SIG Architecture and Instrumentation]
- Updated cri-tools to [v1.24.2(https://github.com/kubernetes-sigs/cri-tools/releases/tag/v1.24.2) ([#109813](https://github.com/kubernetes/kubernetes/pull/109813), [@saschagrunert](https://github.com/saschagrunert)) [SIG Cloud Provider, Node and Release]
- `apiserver_dropped_requests` is dropped from this release since `apiserver_request_total` can now be used to track dropped requests. `etcd_object_counts` is also removed in favor of `apiserver_storage_objects`. `apiserver_registered_watchers` is also removed in favor of `apiserver_longrunning_requests`. ([#110337](https://github.com/kubernetes/kubernetes/pull/110337), [@logicalhan](https://github.com/logicalhan)) [SIG API Machinery and Instrumentation]

## Dependencies

### Added
- github.com/emicklei/go-restful/v3: [v3.8.0](https://github.com/emicklei/go-restful/v3/tree/v3.8.0)
- github.com/golang-jwt/jwt/v4: [v4.2.0](https://github.com/golang-jwt/jwt/v4/tree/v4.2.0)
- github.com/golangplus/bytes: [v1.0.0](https://github.com/golangplus/bytes/tree/v1.0.0)
- github.com/golangplus/fmt: [v1.0.0](https://github.com/golangplus/fmt/tree/v1.0.0)

### Changed
- bitbucket.org/bertimus9/systemstat: 0eeff89 → v0.5.0
- github.com/Azure/go-autorest/autorest/adal: [v0.9.13 → v0.9.20](https://github.com/Azure/go-autorest/autorest/adal/compare/v0.9.13...v0.9.20)
- github.com/Azure/go-autorest/autorest/mocks: [v0.4.1 → v0.4.2](https://github.com/Azure/go-autorest/autorest/mocks/compare/v0.4.1...v0.4.2)
- github.com/Azure/go-autorest/autorest: [v0.11.18 → v0.11.27](https://github.com/Azure/go-autorest/autorest/compare/v0.11.18...v0.11.27)
- github.com/MakeNowJust/heredoc: [bb23615 → v1.0.0](https://github.com/MakeNowJust/heredoc/compare/bb23615...v1.0.0)
- github.com/antlr/antlr4/runtime/Go/antlr: [b48c857 → ad29539](https://github.com/antlr/antlr4/runtime/Go/antlr/compare/b48c857...ad29539)
- github.com/chai2010/gettext-go: [c6fed77 → v1.0.2](https://github.com/chai2010/gettext-go/compare/c6fed77...v1.0.2)
- github.com/cncf/udpa/go: [5459f2c → 04548b0](https://github.com/cncf/udpa/go/compare/5459f2c...04548b0)
- github.com/cncf/xds/go: [fbca930 → cb28da3](https://github.com/cncf/xds/go/compare/fbca930...cb28da3)
- github.com/container-storage-interface/spec: [v1.5.0 → v1.6.0](https://github.com/container-storage-interface/spec/compare/v1.5.0...v1.6.0)
- github.com/coredns/corefile-migration: [v1.0.14 → v1.0.17](https://github.com/coredns/corefile-migration/compare/v1.0.14...v1.0.17)
- github.com/daviddengcn/go-colortext: [511bcaf → v1.0.0](https://github.com/daviddengcn/go-colortext/compare/511bcaf...v1.0.0)
- github.com/envoyproxy/go-control-plane: [63b5d3c → 49ff273](https://github.com/envoyproxy/go-control-plane/compare/63b5d3c...49ff273)
- github.com/go-logr/logr: [v1.2.0 → v1.2.3](https://github.com/go-logr/logr/compare/v1.2.0...v1.2.3)
- github.com/go-logr/zapr: [v1.2.0 → v1.2.3](https://github.com/go-logr/zapr/compare/v1.2.0...v1.2.3)
- github.com/golangplus/testing: [af21d9c → v1.0.0](https://github.com/golangplus/testing/compare/af21d9c...v1.0.0)
- github.com/google/cel-go: [v0.10.1 → v0.11.2](https://github.com/google/cel-go/compare/v0.10.1...v0.11.2)
- github.com/google/go-cmp: [v0.5.5 → v0.5.6](https://github.com/google/go-cmp/compare/v0.5.5...v0.5.6)
- github.com/pquerna/cachecontrol: [0dec1b3 → v0.1.0](https://github.com/pquerna/cachecontrol/compare/0dec1b3...v0.1.0)
- go.etcd.io/etcd/api/v3: v3.5.1 → v3.5.4
- go.etcd.io/etcd/client/pkg/v3: v3.5.1 → v3.5.4
- go.etcd.io/etcd/client/v2: v2.305.0 → v2.305.4
- go.etcd.io/etcd/client/v3: v3.5.1 → v3.5.4
- go.etcd.io/etcd/pkg/v3: v3.5.0 → v3.5.4
- go.etcd.io/etcd/raft/v3: v3.5.0 → v3.5.4
- go.etcd.io/etcd/server/v3: v3.5.0 → v3.5.4
- golang.org/x/crypto: 8634188 → 3147a52
- google.golang.org/genproto: 42d7afd → 1973136
- google.golang.org/grpc: v1.40.0 → v1.47.0
- gopkg.in/yaml.v3: 496545a → v3.0.1
- k8s.io/kube-openapi: 3ee0da9 → 31174f5

### Removed
- github.com/OneOfOne/xxhash: [v1.2.2](https://github.com/OneOfOne/xxhash/tree/v1.2.2)
- github.com/cespare/xxhash: [v1.1.0](https://github.com/cespare/xxhash/tree/v1.1.0)
- github.com/emicklei/go-restful: [v2.9.5+incompatible](https://github.com/emicklei/go-restful/tree/v2.9.5)
- github.com/google/cel-spec: [v0.6.0](https://github.com/google/cel-spec/tree/v0.6.0)
- github.com/spaolacci/murmur3: [f09979e](https://github.com/spaolacci/murmur3/tree/f09979e)