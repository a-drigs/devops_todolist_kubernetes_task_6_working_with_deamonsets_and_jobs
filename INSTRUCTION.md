kubectl apply -f daemonset.yml -n mateapp
kubectl apply -f cronjob.yml -n mateapp

kubectl logs curl-with-busybox
kubectl logs health-check-4mins