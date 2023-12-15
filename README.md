# local-kind-cluster

CRDs to spin up a local Kind cluster with NGINX for Ingress and MetalLB as LoadBalancer implementation.

# Instructions

Just run `./create-cluster` from the root of this repository and hack away!

You can also apply the `guestbook-ui` app after the cluster is created with the following command

```bash
kubectl apply -f guestbook-ui.yaml
```

The app should be accessible at `localhost:80` afterwards.
