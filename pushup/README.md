Для деплоя pushup сервиса надо зайти на мастер ноду кластера под рутом
Далее скомандовать
cd pushup
kubectl apply -f deployment.yaml
kubectl apply -f ingress.yaml

