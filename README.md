# One Enterprise Platform - Microservices

Learning project based on the Day 1-5 microservices exercises.

## Services

- User Service: http://localhost:8081
- Order Service: http://localhost:8082
- API Gateway: http://localhost:8080

## Test endpoints

GET http://localhost:8081/api/users/1001
GET http://localhost:8082/api/orders/5001
GET http://localhost:8080/api/users/1001
GET http://localhost:8080/api/orders/5001

## Run order

1. Start User Service.
2. Start Order Service.
3. Start API Gateway.
4. Test through port 8080.

## Maven

From each service directory:

mvn clean package
mvn spring-boot:run
