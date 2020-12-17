# Note

## Docker

```bash
./gradlew build

docker build -t twcrone/note .

docker run -p 9080:8080 twcrone/note

docker image rm -f twcrone/note
```

## K8s

```bash
kubectl apply -f deployment.yml

kubectl port-forward svc/note 8080:8080
```


