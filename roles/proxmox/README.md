# xhiroga/proxmox

## Prerequisite

```shell
make --directory molecule/docker-image
```

## Run

```
molecule test
```

## References

- [lae/ansible\-role\-proxmox: Deploys and configures Proxmox VE 6\.x/7\.x clusters\.](https://github.com/lae/ansible-role-proxmox) - certification, management repo, access, storage and etc
- [ironicbadger/ansible\-role\-proxmox\-nag\-removal: Removes Proxmox nag screen](https://github.com/IronicBadger/ansible-role-proxmox-nag-removal) - Mange repo and no nag message
- [ansible\-collection\-proxmox/roles/pve at develop · maxhoesel/ansible\-collection\-proxmox](https://github.com/maxhoesel/ansible-collection-proxmox/tree/develop/roles/pve) - Configure password and repos
- [manala/ansible\-role\-proxmox: \[READ\-ONLY\] Ansible role dealing with the setup of Proxmox](https://github.com/manala/ansible-role-proxmox) - mange instances
