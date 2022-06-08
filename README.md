I have created web servers in citycloud using the ssh key-gen such that the Bastion acts as the jump host and the HAproxy acts as the load balancer.The tasks are accomplished using the ansible and further, I have deployed the Flask app and additionally, installed SNMPd daemon onto the dev servers.

In this case, HAproxy takes care of the flask app while Nginx takes care of SNMP. 
