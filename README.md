# Ansible module extras

The intention of this repository is to keep (backported) ansible modules separate from other
ansible code I am using.

You may customize ansible's lookup for modules in your `~/.ansible.cfg`

```
# ~/.ansible.cfg
[defaults]
# Lookup custom modules
library = ~/Development/projects/ansible/ansible-modules-extras
```
