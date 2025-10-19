API gateway is a single entry and exit point through which all the requests are directed to te relevant microservice
It internally uses eureak server to know which microservice to redirect to.
It is made as a amicroservice that gets registers in eureka i.e. its mai class is annotated with @EnableDiscoveryClient
