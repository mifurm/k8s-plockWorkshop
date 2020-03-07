User: plstX@chmurowiskolab.onmicrosoft.com

1. Setup VM
https://github.com/djkormo/k8s-AKS-primer/blob/master/install/VM/install-all.ps1

2. K8s Labs
https://github.com/cloudstateu/k8s_24022020.git

3. Additional Labs
https://github.com/djkormo/k8s-AKS-primer.git

4. Add role to K8s to see the dashboard
kubectl create clusterrolebinding kubernetes-dashboard --clusterrole=cluster-admin --serviceaccount=kube-system:kubernetes-dashboard

5. for i in {1..10000}; do curl -I -X GET <PUBLIC IP> | grep Server: ; echo; sleep 1; done
