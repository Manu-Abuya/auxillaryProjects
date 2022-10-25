 This script will read a CSV file that contains Linux users.
 The script will create each user on the sever and add to an existing group called 'Developers'.
 This script will first check for the existence of the user on the system, before it will attempt to create
 The user that is being created also must have a default home folder
 Each user should have a .ssh folder within its HOME folder. if it does not exist, then it will be created. 
 For each user's SSH configuration, We will create an authorized_keys file and add a public key.
