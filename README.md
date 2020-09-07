# Mediawiki

This code will create an infrastructure to deploy mediawiki in it

The cft is written such a way that it can do ami deployment. We have to run the below command to create infra for mediawiki in aws
ansible-playbook create_infra.yml

in the variable file we can use media wiki instance and once the infrastructure is ready we can hit the public dns to brows the meadi wiki
