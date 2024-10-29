```sh
kubectl create deployment nginx-deployment --image=nginx --replicas=3
```
##### Verifica el estado de los Pods
```sh
kubectl get pods -o wide
```
##### Verifica el estado del Deployment 
kubectl get deployment