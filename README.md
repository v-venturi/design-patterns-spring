# design-patterns-spring

## Sobre a API
API desenvolvida com cadastro de clientes e consulta de CEP usando API externa "ViaCep" (https://viacep.com.br/)

### Tecnologias utilizadas

This project was developed with:

* **Java 17 LTS  2021-09-14 (versão 11 no deploy do Heroku devido à incompatibilidade)**
* **Spring Boot 2.6.2**
* **Spring DATA-JPA 2.6.2**
* **Spring Doc Open-API 3.0.0 (Swagger)**
* **Maven**
* **H2 DataBase**


### Execução
-bash/

git clone https://github.com/v-venturi/design-patterns-spring.git

mvn spring-boot:run

### Testar a API

* **Swagger** http://localhost:8080/swagger-ui/