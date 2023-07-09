# orange-echo
home server settings

# usage

```
ansible-playbook -i inventory/hosts.ini --ask-become-pass site.yml [-e reboot=true]
```

you can skip the existing playbooks using `debug-skip` tag when debugging a new playbook.

```
ansible-playbook -i inventory/hosts.ini --ask-become-pass site.yml --skip-tags "debug-skip"
```
