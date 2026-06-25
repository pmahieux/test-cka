# test-cka

## Wordpress, db
kubectl create namespace test

## NodeExporter, Prometheus, Grafana
kubectl create namespace monitoring

## Lancer tous les yaml d'un dossier (appel à kustomizarion.yaml)
kubectl apply -k node-exporter/
