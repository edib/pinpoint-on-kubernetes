# Pinpoint Helm Chart for Kubernetes  

Git repository of containerized components of the Pinpoint Application Monitoring for Kubernetes
Installing Pinpoint on Kubernetes cluster with a single command.

```
git clone https://github.com/edib/pinpoint-on-kubernetes.git
cd pinpoint-on-kubernetes/pinpoint

helm install pinpoint-apm . -n  <pinpoint-ns>
```

Supported version: 2.5.1

zookeepers and hbase uses pvs. You have to have at least hostpath-pv in your environment.
