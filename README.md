# lab-week5-ansible

## Required commands:

## Create new keys:

```bash
ssh-keygen -t rsa -b 4096 -f ~/.ssh/aws
```
This command would create a key named "aws" in ~/.ssh folder.


## Run included scripts to import and delete keys:

```bash
# To run import script, so EC2 instances can use it for SSH 
./import_key.sh
# To run delete script, remove key when no longer needed
./delete_key.sh
```

## Terraform commands:


## Ansible commands: