# My Homelab is a work in progress

Note: Please bear in mind that every script here is to be considered **unsafe** as I not only lack the knowledge necessary to build a safe infrastructure,
but I also just recently migrated from libvirt/KVM based to docker/kubernetes environment so this is pretty much pre-alpha to say the least.

## Mainserver using Docker-Compose for nearly everything except NFS-Server

Currently running:
* Ghost
* Gitea
* Grafana
* Mariadb
* Minio
* Nextcloud
* Pi-Hole
* Redis
* Samba
* Statping
* Traccar
* Valheim

## Kubernetes Playground based on amd64 / arm64 mixed architecture 

Currently running:
* Pi-Hole HA stateless 
* Prometheus statefull

The Cluster uses NFS as primary (default) storage backend as its mainly based on Raspberries, Metallb as Loadbalancer and relies on microk8s as implementation base.

While I'm still learning all the concepts behind Containers and Orchestration I hope to add some more services in the future.
