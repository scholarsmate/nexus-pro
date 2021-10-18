# Script the setup of a Nexus Repository service in a VM

## Setup

Install the required roles:

```{shell}
cd ./ansible/ && ansible-galaxy install -r requirements.yml --roles-path=./roles && cd ..
```

## Create the desired VM

### RHEL 7

```{shell}
cd RHEL7 && vagrant up
```

### RHEL 8

```{shell}
cd RHEL8 && vagrant up
```
