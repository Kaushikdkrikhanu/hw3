# Images
kaushikdkrikhanu/sentinent-analysis-frontend:uuu
kaushikdkrikhanu/sentiment-analysis-logic:latest
kaushikdkrikhanu/sentiment-analysis-web-app:latest

# How to reproduce:
```
kubectl apply -f .\sa-logic-deployment.yaml
Kubectl apply -f .\service-sa-logic
Kubectl apply -f .\sa-web-app-deployment.yaml
Kubectl apply -f .\service-sa-web-app-lb
Kubectl apply -f .\sa-frontend-deployment-green.yaml
Kubectl apply -f .\service-sa-frontend-lb.yaml
```