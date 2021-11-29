# ECK Helm Chart based on Elastic operator pattern

This Helm chart is based on Elastic operator pattern.


## Requirements

As described [here](https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-deploy-eck.html), ECK's custom resource definitions have to be installed in the cluster first :

```bash
kubectl apply -f https://download.elastic.co/downloads/eck/1.3.0/all-in-one.yaml
```

## Helm install

```bash
helm install --namespace namespace_name eck chart
```


The helm chart will deploy elastic search with 9 nodes in the k8s cluster.
