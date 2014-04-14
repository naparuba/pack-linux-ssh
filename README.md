pack-linux-ssh
===============

Configuration pack for Linux hosts based on SSH checks

Based on https://github.com/naparuba/check-linux-by-ssh

For Authorized_keys, you have to put in your resource.d files :

$SSH_KEY$=/etc/shinken/id_dsa
$SSH_KEY_PASSPHRASE$=''
$SSH_USER$=sup_user


TODO
===============

Only Disks and Memory are defined in this pack
All others should be done, soon.
