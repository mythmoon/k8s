# k8s

k8s Containers 

dockerfile 

from quay.io/coreos/etcd:v3.2.4
from quay.io/coreos/flannel:v0.9.1
from quay.io/coreos/flannel-cni:v0.3.0
from quay.io/calico/ctl:v1.6.1
from quay.io/calico/node:v2.6.2
from quay.io/calico/cni:v1.11.0
from quay.io/calico/kube-controllers:v1.0.0
from quay.io/calico/routereflector:v0.4.0
from quay.io/coreos/hyperkube:v1.9.3_coreos.0
from gcr.io/google_containers/pause-amd64:3.0
from xueshanf/install-socat:latest
from quay.io/l23network/k8s-netchecker-agent:v1.0
from quay.io/l23network/k8s-netchecker-server:v1.0
from weaveworks/weave-kube:2.2.0
from weaveworks/weave-npc:2.2.0
from contiv/netplugin:1.1.7
from contiv/auth_proxy:1.1.7
from docker.io/cilium/cilium:v1.0.0-rc4
from nginx:1.13
from andyshinn/dnsmasq:2.78
from gcr.io/google_containers/k8s-dns-kube-dns-amd64:1.14.8
from gcr.io/google_containers/k8s-dns-dnsmasq-nanny-amd64:1.14.8
from gcr.io/google_containers/k8s-dns-sidecar-amd64:1.14.8
from gcr.io/google_containers/cluster-proportional-autoscaler-amd64:1.1.2
from gcr.io/google_containers/elasticsearch:v2.4.1
from gcr.io/google_containers/fluentd-elasticsearch:1.22
from gcr.io/google_containers/kibana:v4.6.1
from lachlanevenson/k8s-helm:v2.8.1
from gcr.io/kubernetes-helm/tiller:v2.8.1
from vault:0.8.1

###
from gcr.io/google_containers/kubernetes-dashboard-amd64:v1.8.3
from gcr.io/google_containers/defaultbackend:1.4
from quay.io/kubernetes-ingress-controller/nginx-ingress-controller:0.11.0
 
###
from quay.io/external_storage/local-volume-provisioner:v2.0.0
from registry:2.6
from gcr.io/google_containers/kube-registry-proxy:0.4
from busybox:latest
from
