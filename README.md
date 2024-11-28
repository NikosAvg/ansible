# Ansible Server Setup

This project is an Ansible automation playbook to set up a web server on an Ubuntu virtual machine. The playbook installs and configures Apache, sets up a UFW firewall to allow SSH and HTTP traffic, and ensures that the server is running correctly.

## Steps performed:
- Set up the **Apache web server**.
- Configured **UFW firewall** to allow SSH and HTTP traffic.
- Ensured the server is running correctly and accessible via SSH and HTTP.

## How to use:
1. Clone this repository.
2. Modify the `hosts.ini` file with your server's IP and SSH credentials.
3. Run the Ansible playbook with the following command:
   ```bash
   ansible-playbook -i hosts.ini setup.yml
