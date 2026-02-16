# Docker-commands
    2  ls
    3  sudo apt-get update
    4  sudo apt-get install ca-certificates curl gnupg lsb-release
    5  sudo mkdir -p /etc/apt/keyrings
    6  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
    7  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
    $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
    8  sudo apt-get update
    9  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
   10  clear
   11  dolcker version
   12  docker version
   13  which docker
   14  which dockerd
   15  which containerd
   16  ps -eaf
   17  lear
   18  clear
   19  docker info
   20  clear
   21  ls
   22  docker ps
   23  docker ps -a
   24  docker images
   25  docker pull httpd
   26  docker images
   27  clear
   28  ls
   29  docker create httpd
   30  docker ps
   31  docker ps -a
   32  docker create --name raj1 httpd
   33  docker ps -a
   34  docker create httpd
   35  docker ps -a
   36  docker start 9b294ab57cba
   37  docker ps -a
   38  docker start raj1
   39  docker ps -a
   40  docker stop 9b294ab57cba
   41  docker ps -a
   42  docker restart 05f6c329193b
   43  docker ps -a
   44  clear
   45  docker ps -a
   46  docker start 9b294ab57cba
   47  docker ps -a
   48  docker pause 05f6c329193b
   49  docker ps -a
   50  docker stats
   51  docker ps -a
   52  docker unpause 05f6c329193b
   53  docker ps -a
   54  docker kill 9b294ab57cba
   55  docker stop 05f6c329193b
   56  docker ps -a
   57  docker rm 9b294ab57cba
   58  docker rm 05f6c329193b
   59  docker ps
   60  docker ps -a
   61  clear
   62  docker ps -a
   63  docker start 96a5327d4882
   64  clear
   65  ls
   66  docker ps -a
   67  ps -eaf | grep container
   68  ps -eaf | grep containerd
   69  clear
   70  docker ps
   71  docker exec 96a5327d4882 ps -eaf
   72  docker inspect 96a5327d4882
   73  docker inspect 96a5327d4882 | grep -i user
   74  clear
   75  ls
   76  docker ps
   77  ps -eaf | grep containerd
   78  docker ps
   79  docker exec -it 96a5327d4882
   80  docker exec -it 96a5327d4882 /bin/bash
   81  ps -eaf
   82  clear
   83  docker ps
   84  docker inspect 96a5327d4882
   85  clear
   86  docker exec -it 96a5327d4882 /bin/bash
   87  df -kh
   88  docker exec -it 96a5327d4882 /bin/bash
   89  ls /
   90  df -kh
   91  cd /var/lib/docker/overlay2/b011c58e3530b49f359d0779fb60153e9622970b601034f035ec881cabbea92f/merged
   92  ls
   93  clear
   94  ls
   95  cd
   96  ls
   97  docker ps
   98  history
   99  ip a
  100  history
