# Kubernetes Homelab Automation

Automated Kubernetes cluster deployment using Ansible.

Cluster topology:

k8s-master 192.168.*.*
k8s-worker1 192.168.*.*  
k8s-worker2 192.168.*.*

Run deployment:

ansible-playbook playbooks/site.yml