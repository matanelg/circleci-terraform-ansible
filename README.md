# circleci-terraform-ansible
## Terraform

## Ansible (configure private instance)
1. Generate ssh key with ssh-keygen for github.
2. Add public key to github.
3. Add/Create ~/.ssh/config hostkey
```bash
Host github.com
    IdentityFile ~/.ssh/private_key
```
