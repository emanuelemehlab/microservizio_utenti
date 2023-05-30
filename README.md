# microservizio_utenti
DOCKER

docker compose up --build --force-recreate



kubernetes

minikube start
kubectl apply -f db_users.yaml
kubectl apply -f microservizi_utenti.yaml
minikube tunnel
