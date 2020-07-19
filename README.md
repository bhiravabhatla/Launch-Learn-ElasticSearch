# Launch-Learn-ElasticSearch

Run - Vagrant up - to provision 3 Elastic Search Nodes.

Run ansible to install ES and Kibana

ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook -i hosts.yml all.yml
