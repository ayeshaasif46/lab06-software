1. Install htop, run it, and write one thing it shows:
Command: sudo apt install -y htop && htop
Answer: It shows live CPU usage bars, RAM memory consumption, and active running processes.

2. Which version of apache2 does Ubuntu offer?
Command: apt show apache2
Answer: Version 2.4.58-1ubuntu8

3. How many packages are installed on your server now?
Command: apt list --installed | wc -l
Answer: 780 packages

4. Use Docker to run the tiny Linux image alpine so that it prints Hello from Alpine:
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: Output prints "Hello from Alpine"

5. What is the full path of Docker's key file, and of Docker's sources file?
Key File: /etc/apt/keyrings/docker.asc
Sources File: /etc/apt/sources.list.d/docker.sources

6. Remove htop and prove that it is gone:
Command: sudo apt remove -y htop && hash -r && htop
Answer: Terminal displays "Command 'htop' not found"
