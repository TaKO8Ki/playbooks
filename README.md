# Playbooks

## Usage

### Kubernetes
```sh
# playbooks/kubernetes

# add hosts
$ cp hosts.example hosts
$ vim hosts

# install dependencies
$ ansible-playbook -i hosts config.yml -v

# setup master nodes
$ ansible-playbook -i hosts master.yml -v

# setup worker nodes
$ ansible-playbook -i hosts worker.yml -v
```
