# Logging & Monitoring:
This helm chart contains:
    Loki,
    Grafana,
    Prometheus,
    Blackbox,
    Alertmanager,
    Kube-state-metrics
    Promtail.

## Command to run the file:
`helm install lgpab LGPAB --values env/demo/lpg-values.yaml`

Note: 
1. This is working directory.
2. Kindly update the slackWebhookUrl and channel name accordingly.
