# final-ex-k8s

## requirements

minikube


helm


## howto
this repo holds basic objects for minikube cluster; clone this repo than execute:
> cd final-ex-k8s 

than:

> kubectl apply -f .

to download grafana:

> helm install [RELEASE_NAME] oci://ghcr.io/prometheus-community/charts/kube-prometheus-stack
