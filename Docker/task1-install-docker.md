# Install
https://docs.docker.com/desktop/

https://docs.docker.com/desktop/setup/install/windows-install/

# PreRequisites
- Install wsl
- Win 10 or 11
```
wsl --install
```

# Install docker
- https://docs.docker.com/desktop/setup/install/windows-install/
```
docker --version
```
- If error message like "Docker is not a valid command, not recognized", add an environment variable like the way we did for AZ CLI

# Create an account in app.docker.com
- visit app.docker.com
- sign up with personal account
- log in 

# Download Ubuntu Image
```
docker pull ubuntu
```

# Create an Ubuntu base container from ubuntu image

```
docker run --name sireeshacontainer -p 8080:80 -it ubuntu
apt-get update
apt-get install nginx
service nginx status
service nginx start
```
- visit localhost:8080 in browser
