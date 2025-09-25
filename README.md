> 현재 레포지토리는 Archive될 예정의 레포지토리입니다. 아래의 레포지토리에서 통합된 여러 예제들을 확인하실 수 있습니다.
>
> https://github.com/yulmwu/blog-example-demo
> 
> https://github.com/yulmwu/blog-example-demo/tree/main/aws-eks-fargate-example

```
eksctl create cluster -f cluster-config.yaml
aws eks update-kubeconfig --name eks-fargate-demo --region ap-northeast-2
```
