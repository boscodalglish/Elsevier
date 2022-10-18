## Maven Build

> Import existing Maven Project in your IDE

```
Run Config commands:

clean Install

mvn package
```


## Docker Build

> Dockerise the Java Application

```
cd Elsevier/kubernetes-minikube/demo-backend-ev/

docker build --file=Dockerfile --tag=demo-backend:app --rm=true .

```


## Helm chart Install

```
cd Elsevier/Helm/java-app

helm upgrade -i demo-backend .
```
