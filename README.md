# DevOps Coursework

Hands-on notes and code for the DevOps module, one folder per topic. Each folder has its own
README with the commands that were run, the output, and screenshots from the run.

| Folder | Topic |
|---|---|
| `Linux Fundamentals/` | Hard vs soft links, `useradd` vs `adduser`, `journalctl`, command cheat sheet |
| `Shell Scripting/` | `sysinfo.sh`: variables, user input, `mkdir`/`touch`, output redirection |
| `Networking Fundamentals/` | `ping`, `ip`, `ss`, `curl`, `wget`, `nslookup`, `traceroute`, `hostname` |
| `Git and Github/` | `git commit -a` vs `-m`, `git cherry-pick` |
| `Docker Fundamentals/` | Six Hello World containers: Node.js, Python, Java, Apache, React, Nginx |
| `DockerFiles and Images/` | Multi-stage Go build, 365 MB toolchain to a 7 MB image |
| `Docker Networks/` | Multi-network containers, host network, bind mounts, overlay networks |
| `Kubernetes Fundamentals/` | Cluster architecture, kube-system Pods, node capacity, first Pod, namespaces |
| `Kubernetes Workloads/` | Pods, ReplicaSets, Deployments, rolling updates and rollback, DaemonSets |
| `Kubernetes Services/` | The five Service types on Minikube: ClusterIP, NodePort, LoadBalancer, Headless, ExternalName |
| `Kubernetes Ingress and Config/` | ConfigMaps, Secrets, and NGINX Ingress routing by host and path |

Environment: macOS with Docker Desktop; Linux-only commands were run in Ubuntu 24.04 containers.
The Kubernetes exercises run on a single-node Minikube cluster using the Docker driver.

Submitted by **Parv Mehta** (Roll No. 24BCS10301).
