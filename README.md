# Examples for Red Hat's Advanced Cluster Management

Some application and policy samples for Red Hat's Advanced Cluster Management.


## Installation

Install ACM according the [product documentation](https://access.redhat.com/documentation/en-us/red_hat_advanced_cluster_management_for_kubernetes/2.0/html/install/installing).

Optional: You can use the provided [multiclusterhub_multiclusterhub.yaml](multiclusterhub_multiclusterhub.yaml) to deploy a MultiClusterHub in its basic variant to save resources.


## Usage

Adapt the cluster placement in [sample-app.yaml on line 30](sample-app.yaml#L30) and in [sample-policy.yaml on line 96](sample-policy.yaml#L96) to your setup.

Logged in on the hub cluster, apply the [sample-app.yaml](sample-app.yaml) and [sample-policy.yaml](sample-policy.yaml):

```
oc apply -f sample-app.yaml
oc apply -f sample-policy.yaml
```


## References

* [Product documentation](https://access.redhat.com/documentation/en-us/red_hat_advanced_cluster_management_for_kubernetes/)
* [Blog posts](https://www.openshift.com/blog/tag/red-hat-advanced-cluster-management)
