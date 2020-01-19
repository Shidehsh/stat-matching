# Building a new docker image from Dockerfile

 docker build . -t shideh/stat-matching

# Run this code to start docker image

  docker run -p 8888:8888 -v /Users/shidehshamsamiri/Project/stat-matching/:/home/jovyan/work shideh/stat-matching 