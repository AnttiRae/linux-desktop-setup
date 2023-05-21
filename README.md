# linux-desktop-setup
Ansible playbook to setup linux desktop (Fedora)

This ansible playbook is meant to setup a fedora workstation for general use. (coding, gaming, etc)
vagrant is used to create VM for dev and testing purposes before using on actual hardware

## Running the playbook (needs sudo)
`ansible-playbook main.yml -K`

## requirements
- ansible

### todo
- [x] wallpapers
- [ ] nextcloud sync
- [x] git global config
	- [x] name
	- [x] email
- [x] media keys
- [x] gnome DE config
- [ ] notes from git
- [ ] flatseal perms
- [ ] RPM fusion rpm
