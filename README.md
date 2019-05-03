# Ansible
 
 Commands for operation
 
 #For creating user
 ansible-playbook user_management.yml --tag add_new_user
 
 #For generating SSH Keys
 ansible-playbook user_management.yml --tag generate_ssh_keys
 
 #For copying SSH Keys
 ansible-playbook user_management.yml --tag copy_pub_key
 
 #For Removing user
 ansible-playbook user_management.yml --tag remove_user
 
 
 
