
**Endava Devops Challenge**

**Dependencies**

- ansible
- python3
- python3-pip
- boto, boto3, 

For the mysql_secure_installation module - [mysql_secure_installation module](https://github.com/eslam-gomaa/mysql_secure_installation_Ansible)


**Description**

1. Upload of SSH public key to AWS.
2. Creating security group and adding rules for TCP ports 22 and 80.
3. Creating EC2 instances for web and database servers. 
4. Adding instances to webserver and database server host groups.
5. Waiting for SSH connection to the instances.
6. Creating Load balancer and adding the web server instance to it.
7. Creating alarms to recover instances in case of system failure. 
8. Installing Nginx web server.
9. Installing MariaDB server with dependancies.
10. Securing MariaDB installation and setting root password.
