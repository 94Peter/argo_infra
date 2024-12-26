# argo_infra


admin
password




k3d cluster create my-cluster --api-port 6443 -p 8080:80@loadbalancer --agents 2 --volume "$HOME/k3d/data:/data@agent:*"