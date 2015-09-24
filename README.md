# ansible-easybuild-lmod
ansible playbook to deploy EasyBuild and Lmod

Example run:

$> ansible-playbook -i /path/to/inventory install-lmod-easybuild.yml -e hostsvar=192.168.1.33 -e sshuser=root -e prefixvar=/scicore/soft -e ebuser=testuser

