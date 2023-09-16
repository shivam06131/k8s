### Commands

```jsx
kubectl get pod 
```

```jsx
kubectl apply -f mongo-config.yml 
```

```jsx
kubectl apply -f mongo-secret.yml 
```

```jsx
kubectl apply -f mongo.yml 
```

```jsx
kubectl apply -f webapp.yml
```

```jsx
kubectl get all 
```

```jsx
kubectl get configmap 
```

```jsx
kubectl get secret 
```

```jsx
kubectl describe service webapp-service 
```

```jsx
kubectl describe pod mongo-deployment-855b879886-zgc69 
```

```jsx
kubectl logs webapp-deployment-9fccd564d-9b5pl
```

# To access webapp on browser

```jsx
kubectl get svc
```

 => chosse nodeport  => [http://192.168.49.2](http://192.168.49.2/)

```jsx
minikube ip
```

```jsx
kubectl get node -o wide
```

```jsx
minikube dashboard 
```

```jsx
kubectl get deployments 
```

```jsx
kubectl delete deployment webapp-deployment 
```

```jsx
kubectl get configmap kubeclt delete configmap mongo-config
```

```jsx
kubectl get service 
```

IMPORTANT (To open Nodeport on borwser)
```jsx
minikube service <Service Name (webapp-service)> 
```

#acessable => [http://192.168.49.2:30100/](http://192.168.49.2:30100/)

Test