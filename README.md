![alt](./images/1.png)
![alt](./images/2.png)
![alt](./images/3.png)

## Mongodb
* how to install
```php
$ docker pull mongo
$ docker run -d -p 2718:27017 -v ~/localPath:/data/db --name mongo-test mongo:latest
# 2718 - port of localhost
```