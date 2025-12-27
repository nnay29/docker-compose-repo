### What is this ? 📂
These are yml files useful for a couled installation of jenkins and prometheus.
The jenkins service particularly enables DinD (Docker in Docker) which will enable the user to run Docker commands from their jenkins instance, which is itself a docker container 

### How to use this ?

1. Copy the both yml files in a directory of your computer
2. Navigate to the directory containing the docker-compose.yml and prometheus.yml files.
3. Run docker-compose up -d
4. Open _localhost:8185_ to install plugins and configure Jenkins [How to unlock and configure Jenkins](https://www.youtube.com/watch?v=Zdxko2bPAAw&t=343s). 
5. Open _localhost:9090_ to access Prometheus.