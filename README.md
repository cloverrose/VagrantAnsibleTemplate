# My Vagrant Ansible Template

## Preliminaries

At first, modify some configurations followed by [TODO].

Then put right id_rsa for github and bitbucket in roles/gitsetup/files/github_id_rsa and roles/gitsetup/files/bitbucket_id_rsa.

Finally, add bellow config in your ~/.ssh/config (modify private ip).

    Host 192.168.33.10  # [TODO]
        IdentityFile ~/.vagrant.d/insecure_private_key
        User vagrant
