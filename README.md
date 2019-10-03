# kube-jenkins
Jenkins deployment with Kubernetes

Prerequisits:
1. Install Docker (used Docker desktop for mac)

2. Install Kubernetes (used Docker desktop for mac)

3. Install helm (optional) this is quite useful to install K8s addons

4. Install metallb using (https://metallb.universe.tf/installation/)
	helm install --name metallb stable/metallb
5. Install nginx to setup reverse proxy
     brew install nginx

6. Setup reverse proxy to point to specified nodeport using instructions below
	https://kirillplatonov.com/2017/11/12/simple_reverse_proxy_on_mac_with_nginx/
