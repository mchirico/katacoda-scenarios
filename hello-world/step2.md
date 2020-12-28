This is your first step.

## Install kubectl

Install kubectl

`curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl" \
&& chmod +x kubectl && \
cp kubectl /usr/local/bin/kubectl && \
mv kubectl /usr/local/bin/k `{{execute}}




