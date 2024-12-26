1. Install ssh and sshpass(sudo apt install ssh sshpass)
2. Run the wifi_setup playbook to setup wifi as root user and password
3. Run the createuser_playbook as root user and password.
4. Run the generate_ssh_localhost as the new user and password.
5. Run the basic_setup_playbook as new user and password.
6. From this point, run everything with ssh.
7. Run the main_playbook
8. Run add_user_to_pveum.yml to add new user to proxmox with admin access.

