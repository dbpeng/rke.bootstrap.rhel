# rke.bootstrap.rhel
this is for setting up environment for running RKE

# steps
1. download rke to the proejct root
2. write inventory file in this root
3. make sure contorl machien can ssh into all the k8s node candidates with proper settings
4. run `ansible-playbook --private-key=<your private key file> -i <your inventory file> bootstrap.yml`
