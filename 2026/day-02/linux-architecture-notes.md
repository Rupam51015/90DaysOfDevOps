Linux Fundamentals

Linux - It is an open source operating system publicly available on internet for free to use. It is high security multi user OS.
It has multiple flavours or distribution systems 
  - Ubuntu (Local/ Practice)
  - CentOs
  - RedHat Enterprise Linux (Prod)
  - Amazon Linux (AWS)
Linux
  - Application 
    - Shell (Grafical Unit Interfase - Provide and interface so humans can interact with Kernel)
      - Kernel ( Code is Writen of the linux) 
- Docker -
  - docker ps
  - docker ps -a
  - docker run -it ubuntu
  - docker start (container id)
  - docker exec -it (container id) bash

Linux
 - ls (list file)
 - ls -l (list files with details)
 - watch ls -l (it will continew refresh every 2 sec and show if any file is creating or not)
 - ls -a (list all files with hidden files )
 - ls -al (list all files with hidden files with description of properties)
 - mkdir devops/demo
 - mkdir -p devops/demo (this will not give error if already present)
 - pwd ( locate directory)
 - cd / (change root directory)
 - cd ~ (directory main)
 - df -h (show used space)
 - free -h (show free space)
 - du -sh (list files with size)
 -
 - echo “message” (print message)
 - top (show cpu memory utilization)
 - htop
 - mkdir (file name)
 - touch text.txt
 - cat (file name)
 - vim (file name)(esc+!wq for save)
 - head (file name) -n 3 (show first 3 line) (-n show n line and -c show n character)
 - tail (file name) -n 1 (show last 1 line)
 - hostname (show hostname)
 - hostname -V (show hostname version)
 - chmod (changes permission)
 - chown (changes owner)
 - chgrp (change group)
 - whoami (user)
 - which bash
 - which sh
 - printenv
 - sed -i ’s/old word/new word/g’ file_name.txt (find and replace word )
 - sudo lslocks (show running processes)
 - sudo kill -9 process_id
 - sudo apt-get install docker.io -y
 - grep -i text file_name
 - grep -ir text directory_path
 - find -name file_name
 - apt update
 - apt list —upgradable
 - apt upgrade
 - apt install htop
 -
