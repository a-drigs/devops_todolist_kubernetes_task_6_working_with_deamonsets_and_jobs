kubectl aplly -f daemonset.yml -n todoapp
kubectl aplly -f cronjob.yml -n todoapp

kubectl logs curl-with-busybox
kubectl logs health-check-4mins