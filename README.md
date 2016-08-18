# OVERVIEW:  
  This project contains integration of two roles namely mysql and nova-controller in ansible.  

# DESCRIPTION:  
  The main.yml is the initial file which is to be run for building/running the project.  
  The command to be used is " ansible-playbook -i hosts main.yml "  
  The mysql role is downloaded from ansible-galaxy using the command " ansible-galaxy install -r requirements.yml -p {the installing directory}"      
  All the hosts are taken from the hosts file.  
 
