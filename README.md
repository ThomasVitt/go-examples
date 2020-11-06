# YAML Dateien über den kubernetes go-client verarbeiten
Dieses kleine Schnipselchen pumpt die Daten gegen die REST API von Kubernetes, unabhängig davon, welcher Typ es ist.

Laufen lassen mit 
```
go build apply.go
./apply -f example.yaml --kubeconfig=$HOME/.kube/config 
```
