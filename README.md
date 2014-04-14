pack-linux-ssh
===============

Configuration pack for Linux hosts based on SSH checks

Based on https://github.com/naparuba/check-linux-by-ssh

For Authorized_keys, you have to edit the /etc/shinken/resource.d/ssh.cfg file if need:

$SSH_KEY$=~/.ssh/id_rsa
$SSH_KEY_PASSPHRASE$=''
$SSH_USER$=shinken


TODO
===============

Only Disks and Memory are defined in this pack
All others should be done, soon.
