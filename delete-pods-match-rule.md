## Remove pods in bundle by rules
kubectl get pods -n namespace | grep 'Completed\|Error' | awk '{print $1}' | xargs kubectl -n namespace delete pod