# Cloud-Init

## Debian
- cloud-init_debian-00.yaml = Auto install zsh & oh my zsh
- cloud-init_debian-01.yaml = Auto install docker, samba, wsdd, zsh & oh my zsh

## Reminder
- apt install cloud-init
- nano /etc/cloud/cloud.cfg
- rm /etc/machine-id
- touch /etc/machine-id
- rm /var/lib/dbus/machine-id
- ln -s /etc/machine-id /var/lib/dbus/machine-id
- ls -l /var/lib/dbus/machine-id
- nano /var/lib/vz/snippets/cloud-init_debian-XX.yaml
- qm set XXX --cicustom "user=local:snippets/cloud-init_debian-XX.yaml"