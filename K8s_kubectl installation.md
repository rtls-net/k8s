## Install Kubectl in Ubuntu:

-Get KubeCtl repo:

        curl -LO https://dl.k8s.io/release/v1.28.2/bin/linux/amd64/kubectl

         sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl

-if not working ,Add group membership for the default ec2-user so you can run all docker 
 
 
      sudo usermod -a -G docker ec2-user

## installing minikube 

- curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64

- sudo install minikube-linux-amd64 /usr/local/bin/minikube
