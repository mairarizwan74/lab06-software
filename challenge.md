
# Lab 06 Challenge

## 1. Install and run htop
Command: sudo apt install -y htop
Observation: htop displays CPU usage, memory usage and running processes.
Removal: sudo apt remove -y htop
Verification: htop reports command not found after removal.

## 2. Apache2 version
Command: apt show apache2 | grep Version
Version: [Write the version shown by your server]

## 3. Installed packages
Command: apt list --installed | wc -l
Result: [Write the number shown by your server]

## 4. Run Alpine
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Output: Hello from Alpine

## 5. Docker file paths
Key: /etc/apt/keyrings/docker.asc
Sources: /etc/apt/sources.list.d/docker.sources

## 6. Remove htop
Commands: sudo apt remove -y htop, hash -r, htop
Result: The htop command is not found after removal.
