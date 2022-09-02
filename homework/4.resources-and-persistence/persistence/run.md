#clear
kubectl delete all --all
kubectl delete configmap postgres-cfg
kubectl delete secrets pg-secret

kubectl apply -f persistence/
