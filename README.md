# nodelab
Lab for DepOps KPI

Pushed in public Docker Hub as negro228/nodelab

Builded by "docker build -t negro228/nodelab ." - tag latest added automaticaly

Run by "docker run -p 80:8080 negro228/nodelab"

Accesed in browser by http://host.docker.internal:80   (192.168.1.102 in my case)

# Lab CI/CD
Add Lint action for code check in all .js files by default

Add action to run docker build .

Add DockerHub login action for push purpose

Add action for image push as latest


# Lab Kubernetes
Add folder k8s with deployment definition and loadbalancer definition(just apply this folder to minikube/kubernetes)

It might require you to exec a *minikube tunnel* to make it accessible on your local machine(loadbalancer works on port 8765)
