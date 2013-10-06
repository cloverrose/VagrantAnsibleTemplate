# My Vagrant Ansible Template

Before use this template,

1. Modify some configurations followed by [TODO].
2. Put right id_rsa for access github (roles/gitsetup/files/github_id_rsa),
   and right id_rsa for access bitbicket (roles/gitsetup/files/bitbucket_id_rsa).
3. Add bellow config in your ~/.ssh/config (modify priate ip).

    Host 192.168.33.10  # [TODO]
        IdentityFile ~/.vagrant.d/insecure_private_key
        User vagrant
