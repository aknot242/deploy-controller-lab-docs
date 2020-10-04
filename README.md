Deploy NGINX Controller 3.x Lab Docs
====================================

Used on the Ansible host in the UDF Controller lab to download and host the lab guide.


How to Use
------------

To use this playbook just run this command.

	1. SSH Into the Ansible instance in the UDF blueprint
	2. Run `git clone <this repo>`
	3. Run `cd deploy-controller-lab-docs`
	4. Run `ansible-playbook master.yml -e @vars/all_vars.yml -i hosts/udf`

Requirements
------------

Ansible 2.9 and Python 3 must be installed on the Ansible host. Docker must be installed on the target instance, as well as internet access available.

Variables
------------

See the `vars/all_vars.yml` and `var/vault.yml` files for all of the needed variable values to fill out.
