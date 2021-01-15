# Library

#### Example library project that run on AWS with eks (k8s)
##### micro-services are:
* clients - nodeJS
* employees - nodeJS
* books - nodeJS
* authors - nodeJS
* auth - nodeJS
* messenger - nodeJS
* sessions - nodeJS
* initialize - python

##### k8s base on:
* nginx-ingress (network-lb)
* helm charts 

##### aws diagram
![AWS](./assets/k8s-all.png)


##### Services communication
![AWS](./assets/services.png)


##### DB
* mysql sitting on RDS

![Tabels](./assets/tables.png)



### Chat

* Messages, rooms => cassandra
* Connections => redis
 
##### Cassandra

![Tabels](./assets/cassandra.png)


##### Locally
* How to run => base on docker-compose

```
docker-compose --env-file .env up
```



