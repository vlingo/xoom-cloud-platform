# xoom-cloud-aws-demo

This demo application shows the utilization of `xoom-cloud` AWS Marketplace product. (TODO link)

## Prerequisites

This demo is deployed on top of `xoom-cloud` AWS infrastructure. (TODO link)

`kubectl` points to EKS cluster.

## EKS deployment of xoom-cloud-aws-demo (3x nodes)

```
kubectl [create | delete] -f nodes.yml
kubectl get pods -n xoom
kubectl logs -f <xoom-cloud-demo-pod-id>
```
