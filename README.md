# linux-desktop-setup
Ansible playbook to setup linux desktop (Fedora)

This ansible playbook is meant to setup a linux desktop envinronment for general use. (coding, gaming, etc)
vagrant is used to create VM for dev and testing purposes before using on actual hardware

## running (needs sudo)
'ansible-playbook main.yml -K'

## requirements
- python
- pip (or pipenv)
- ansible
- vagrant
