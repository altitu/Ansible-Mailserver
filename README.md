# Ansible Mailserver

An Ansible project to deploy a Debian mailserver with MariaDB, Postfix, Dovecot, OpenDKIM, Let's Encrypt
and Fail2Ban. Fully fonctional and Trusted by Gmail (assuming correct DNS & PTR records of `yourdomain` and `mail.yourdomain`).

### Prerequisite:

- Change the ip provided in the Ansible inventory file with your own server ip.
- In the Ansible configuration file, change the location of the `private_key_file` with yours.
