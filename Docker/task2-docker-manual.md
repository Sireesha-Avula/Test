# Create an Ubuntu base container from ubuntu image

```
docker run --name 25AZv01 -p 8080:80 -it ubuntu
apt-get update
apt-get install nginx
service nginx status
service nginx start
```
- visit localhost:8080 in browser and default nginx details

# custom website

```
cd /var/www/html
apt-get install vim
y
5. asia
44. kolkata
```

# vi editor
to add some code 
- vi index.html
- i - insert mode
- ESC - come out of insert mode
- add below html code
- :w - save the data
- :q - quit the vi text editor
```
<html>
 <h1> This is Srish website </h1>
 <h2> This is srish container created from ubuntu file </h2>
</html>
```