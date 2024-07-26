Installation
------------
## Docker
```bash
  sudo apt install docker.io
  sudo systemctl status docker
  sudo apt update
```

## Clone git
```bash
  git clone https://github.com/silarhi/php-hello-world.git
cd php-hello-world
```

### Create docker file in php-hello-world

## Build Docker Image
```bash
    docker build -t saujan12/php-hello-world .
```

### Create docker-compose.yml file

## Push in Github
```bash
    git init
git add .
git commit -m "Initial commit with Dockerfile and docker-compose.yml" 
git branch -M main 
git remote add origin https://github.com/saujan415/powerworkshop-DevOps.git
git push -u origin main
```
#### Create you PAT in git and use as password for your github login
    
