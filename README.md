# vehicle-locator

Proof of concept microservices arhictecuture using Spring Cloud. Developed event driven system that transmitted current location of vehicle
to various microservices in realtime. The entire system is deployed on AWS EC2 instances using Docker Swarm.

Demonstrated concepts:
* Service Discovery using Netflix Eureka
* Polyglot persistence using MySQL, MongoDB, Redis
* Distributed Tracing using Spring Cloud Sleuth
* Centralised Logging using Elastic Stack(Elastic Search, Logstash and Kibana)
* Caching using Redis
* Monitoring using Promethesus/Graffana
* Container orchestration using Docker Swarm
* Websockets using broker relay(ActiveMQ)
* PubSub model using Spring Cloud Stream and RabbitMQ
* Angular application to plot vehicle's location on HERE Maps. Also developed simulator application to generate  sample routes

### Subprojects

Consists of following microservices:

* [Polyglot Persistence with Spring Cloud and Docker](http://www.kennybastani.com)
* [spring-cloud-publisher](https://github.com/akshayabp/spring-cloud-publisher)
* [websocket-spring-cloud-subscriber](https://github.com/akshayabp/websocket-spring-cloud-subscriber)
* [vehicle-locator-websocket](https://github.com/akshayabp/vehicle-locator-websocket)
* [route-service-spring-cloud-subscriber](https://github.com/akshayabp/route-service-spring-cloud-subscriber)
* [route-service](https://github.com/akshayabp/route-service)
* [vehicle-locator-management-rest](https://github.com/akshayabp/vehicle-locator-management-rest)
* [cache-service](https://github.com/akshayabp/cache-service)
* [discovery-server](https://github.com/akshayabp/discovery-server)
* [vehicle-locator-simulator](https://github.com/akshayabp/vehicle-locator-simulator)
* [vehicle-locator-angular-app-here-maps](https://github.com/akshayabp/vehicle-locator-angular-app-here-maps)

### Architecure

![https://github.com/akshayabp/vehicle-locator/blob/master/architecture.jpg?raw=true](https://github.com/akshayabp/vehicle-locator/blob/master/architecture.jpg?raw=true) 