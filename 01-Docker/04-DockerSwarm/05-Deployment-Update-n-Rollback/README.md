```
109  docker service ls
  110  docker service scale visual_web=1
  111  docker service ls
  112  docker service create --name tiny-web --replicas 3 --publish published=8001,target=80 amitvashist7/k8s-tiny-web:latest
  113  docker service ls
  114  docker service ps tiny-web
  115  docker service inspect tiny-web
  116  docker service ps tiny-web
  117  docker service update tiny-web --image amitvashist7/k8s-tiny-web:2
  118  docker service ps tiny-web
  119  docker service update tiny-web --image amitvashist7/k8s-tiny-web:3
  120  docker service ps tiny-web
  121  docker service update --rollback --update-delay 0s tiny-web
  122  docker service ps tiny-web
```
