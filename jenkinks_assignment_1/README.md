# ASSIGNMENT-1 Create an ansible role for Jenkins

## Prerequisites 

'''

Prerequisites

1- master node - Python 3.10.6 | pip | ansible [core 2.13.3]

2- remote server - Python 3.10.6 | 

3- ssh master node to remote server 

4-Inventory file content 
'''

[ ex-1 ansible_host=34.217.108.95 ansible_user=ubuntu ansible_ssh_private_key_file=/home/priyank/Downloads/ansible_key.pem ]

'''

## Steps to create role for jenkins installation

1-ansible-galaxy init jenkins_role

2-cd jenkins_role

3-cd tasks/

4-vim jenkins_installation_role.yml | main.yml

5- vim main.yml 

## Modules used in jenkins_role

1-apt to download java 11-jdk | update cache | jenkins 

2-apt_key to add repository key 

3- apt_repository add jenkin repo 





## playbook for jenkins_role

'''
ansible-playbook jenkins_installation_role.yml

'''



## Output of the plabook after deploying the jenkins service on the remote server

<img src=./snapshot/1.1.png>

