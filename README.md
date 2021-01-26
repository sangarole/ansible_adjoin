# adjoin-ansible
This repository consist of multiple playbooks related to configuration operations related to OS

Prerequistes:
Runs on Amazon Linux 2.
Ansible should be installed locally.

Use below command to run 

ansible-playbook adjoin.yml -e "host_name=XXXX join_user_pass=XXXX join_user_id=XXXX DC_PRIMARY_IP_REVERSE=d.c.b.a DC_SECONDARY_IP_REVERSE=d.c.b.a DOMAIN_NAME_UPPER=XYZ.LOCAL DOMAIN_NAME_LOWER=xyz.local DC_PRIMARY_IP=a.b.c.d DC_SECONDARY_IP=a.b.c.d DC_PRIMARY_NAME=abc.xyz.local DC_SECONDARY_NAME=def.xyz.local ad_users=user1,user2 ad_groups=group1,group2"
