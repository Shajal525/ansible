1. Install ssh and sshpass(sudo apt install ssh sshpass)
2. Run the createuser_playbook as root user and password.
3. Run the generate_ssh_localhost as the new user and password.
4. Run the basic_setup_playbook as new user and password.
5. Run the main_playbook as root with ssh.
3. After that, all the playbooks will be ran using ssh
