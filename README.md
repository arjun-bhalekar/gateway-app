# gateway-app
Service for Spring Cloud Gateway

![](job-service-architecture-Gateway.png)


## Gateway Routing :

Properties E.g. - 

        spring.clout.gateway.routes[0].id=company-micro-service
        spring.clout.gateway.routes[0].uri=http://localhost:8081
        spring.clout.gateway.routes[0].predicates[0]=Path=/company/**


