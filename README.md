# task
    1  sudo apt-get update
    2  sudo apt-get install -y docker.io
    3  sudo systemctl start docker
    4  sudo systemctl enable docker
    5  sudo apt-get install -y git
   19  git clone https://github.com/SushmaTripathi28/task.git
   20  ls
   21  cd task
   22  ls
   23  sudo docker build -t task .
   41  sudo docker run -p 80:5000 task
