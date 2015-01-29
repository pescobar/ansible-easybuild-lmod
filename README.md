# ansible-easybuild-lmod
ansible playbook to deploy EasyBuild and Lmod

To use this playbook add the machine to your ansible inventory and execute like this:

$> ansible-playbook -i /path/to/inventory -e hostsvar=machine-to-deploy install-lmod-easybuild.yml

