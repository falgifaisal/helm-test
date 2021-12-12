This is the helm chart to run a front end web page  

Usage

Installation :

To run this chart, we need to install [Docker](https://www.docker.com), [Helm](https://helm.sh) v3 and [Kubernetes](https://kubernetes.io)

I use [K3S](https://k3s.io) for my development

Install docker : https://docs.docker.com/get-docker/

Install helm v3 : https://helm.sh/docs/intro/install/

Install k3s : https://k3s.io/


After all the above technologies are installed, then need to clone this repository

```
git clone https://github.com/falgifaisal/helm-test
```

After cloned, enter the directory and run command 
```
helm install <your-helm-deployment-name> .
```
After run helm install, then type http://localhost:30007 from the browser to see the result
