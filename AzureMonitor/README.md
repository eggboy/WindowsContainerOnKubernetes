### Enable Prometheus Metrics for Windows on AKS

https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-enable?tabs=azure-portal#enable-windows-metrics-collection[https://learn.microsoft.com/en-us/azure/azure-monitor/containers/prometheus-metrics-enable?tabs=azure-portal#enable-windows-metrics-collection]

$ kubectl apply -f windows-exporter-daemonset.yaml
$ kubectl apply -f ama-metrics-settings-configmap.yaml

