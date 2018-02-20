# Ansible Ec2 spin up, Jenkins creation and LAMP Stack Playbooks
Ec2 spin up with new *.pem file and updateting the hosts file aswell.
Jenkins installation with Java8
This is a Ansible Playbook to deploy a LAMP Stack infrastructure on ubuntu hosts. 

### Ec2
* ec2
### Jenkins
* Jenkins
### Stack - 
* apache2
* mysql 
* php7.0-fpm 

### Pre-requisites
Boto (Aws Acccess/Secret key)
python 2
You must have Ansible 2.3 installed.


### Setup
* Add host in /etc/ansible/hosts file. See the given hosts file to add hosts.  
  cd lamp/
* Run command `sudo ansible-playbook -i hosts lamp-playbook.yml`
 
* Run command `sudo ansible-playbook -i hosts playbook.yml`
  cd jenkins/
* Run command `sudo ansible-playbook -i inventory/jenkins-servers playbook`



### Database Configuration
* USERNAME: root
* PASSWORD: rajendra@75


Note:
test -e /usr/bin/python || (sudo apt -y update && sudo apt install -y python-minimal)


