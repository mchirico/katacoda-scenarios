This is your first step.

## Install KinD

Install KinD

`GO111MODULE="on" go get sigs.k8s.io/kind@v0.9.0`{{execute}}


Install kubectl

`curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"` {{execute}}

Change kubectl to "k"

`chmod +x kubectl && mv kubectl /usr/local/bin/k` {{execute}}








