# Using eksctl tool

In this serie of exercises we will learn how to use the eksctl tool to create eks clusters in AWS.

## Requirements:
  - Install eksctl tool
``` bash
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
sudo mv /tmp/eksctl /usr/local/bin
```
  - Install helm https://helm.sh/docs/intro/install/
```bash
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
chmod 700 get_helm.sh
./get_helm.sh
```

  - Read documentation of https://eksctl.io/ , to understand the concepts of the tool.

  - Read documentation of helm  https://helm.sh/docs/intro/using_helm/, to understand the concepts of the tool

### Exercises:


- Create an EKS cluster using eks, using a configuration file. make sure the max of nodes is set to two.

- Install helm in the cluster.

- translate the docker-compose file ( the one that you created when you were doing the docker exercises ) into deployment and services files.

### Deliveries

- Make the endpoints public so we can test them.

- push, commit and document your code.

- Show in a call that you can access to the EKS cluster, and that you are able to use it successfully.
