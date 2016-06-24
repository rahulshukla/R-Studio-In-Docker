# R-Studio-In-Docker

Build image from Dockerfile or use docker hub to pull

  docker pull rocker/rstudio
  
start container using this command
  sudo docker run -d -p 6767:6767 rocker/rstudio

open in web : http://YOUR_IP:6767

username: rstudio
password: rstudio
