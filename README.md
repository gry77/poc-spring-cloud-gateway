# poc-spring-cloud-gateway
my self-testing on spring cloud gateway



eureka : http://localhost:8085/eureka-server/

service1: http://localhost:8100

service2: http://localhost:8101

gateway: http://localhost:8105


problem:

when I hit http://localhost:8105/service, it returned 404


expectation:

when I hit http://localhost:8105/service, it will round robin between service1 and service2
