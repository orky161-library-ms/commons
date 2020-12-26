# Library

#### Example library project that run on AWS with eks (k8s)
##### micro-services are:
* clients - nodeJS
* employees - nodeJS
* books - nodeJS
* authors - nodeJS
* auth - nodeJS
* initialize - python

##### k8s base on:
* nginx-ingress (network-lb)
* helm charts 

##### aws diagram
![AWS](./assets/k8s-diagram.png)

##### DB
* mysql sitting on RDS

![Tabels](./assets/tables.png)


##### Locally
* How to run => base on docker-compose

```
docker-compose --env-file .env up
```



