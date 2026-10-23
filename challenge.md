## Question 1
Answer: htop shows CPU usage, memory usage and the list of running processes live.
Commands: sudo apt install -y htop, htop

## Question 2
Answer: apache2 version is 2.4.66-2ubuntu2.6 (not installed).
Commands: apt show apache2 | head -4

## Question 3
Answer: 731 packages are installed.
Commands: apt list --installed | wc -l

## Question 4
Answer: It printed Hello from Alpine.
Commands: sudo docker run --rm alpine echo "Hello from Alpine"

## Question 5
Answer: Key file is /etc/apt/keyrings/docker.asc. Sources file is /etc/apt/sources.list.d/docker.sources
Commands: ls -l /etc/apt/keyrings/, ls /etc/apt/sources.list.d/

## Question 6
Answer: htop is removed. It now says Command 'htop' not found.
Commands: sudo apt remove -y htop, hash -r, htop
