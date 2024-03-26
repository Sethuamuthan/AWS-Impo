2048 App
Create Fargate profile
eksctl create fargateprofile \
    --cluster demo-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
Deploy the deployment, service and Ingress
kubectl apply -f https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.5.4/docs/examples/2048/2048_full.yaml
![image](https://github.com/Sethuamuthan/AWS-Impo/assets/149596888/5d860501-d4d1-4223-90f3-129b7c6d3a20)
