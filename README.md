# Helm chart for platform-service

to update/publish:

Bump version of src/Chart.yaml

helm package src -d charts

helm repo index charts