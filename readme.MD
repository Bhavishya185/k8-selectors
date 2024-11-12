Taint the node

kubectl taint nodes ip-192-168-15-40.ec2.internal hardware=gpu:NoSchedule

untaint:

kubectl taint nodes ip-192-168-15-40.ec2.internal hardware=gpu:NoSchedule-

Label node
---

kubectl label nodes ip-192-168-15-40.ec2.internal hardware=gpu

Ref:  https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes