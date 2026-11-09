# SSH - System Engineering & DevOps

This project covers the fundamentals of SSH (Secure Shell), public/private key pairs, client configuration files, and managing remote access on Ubuntu Linux servers.

## Tasks

* **0. Use a private key (`0-use_a_private_key`)**
  * Bash script that connects to the server using the private key `~/.ssh/school` as user `ubuntu`.

* **1. Create an SSH key pair (`1-create_ssh_key_pair`)**
  * Bash script that creates an RSA key pair (`school` and `school.pub`) of 4096 bits protected by the passphrase `betty`.

* **2. Client configuration file (`2-ssh_config`)**
  * SSH client configuration file configured to use `~/.ssh/school` and refuse password authentication.

* **3. Let me in!**
  * Added Sylvain Kalache's public SSH key to the server's `~/.ssh/authorized_keys`.

