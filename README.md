## Template docker php

esse template foi feito visando facilitar o uso de um servidor LAMP em docker.

### serviços
* web: Dockerfile - local
* db: mysql
* phpmyadmin: phpmyadmin


### rodar
para rodar o projeto, rode:
    ```
    docker-compose up
    ```

### acessar
* http://localhost:8000 -> site (apache)  
* http://localhost:8080 -> phpmyadmin (phpmyadmin)
* mysql://admin:password@localhost:3306 -> mysql (db)
 
### Criadores
Flávio Vitoriano ->  [github](https://www.github.com/flavioVitoriano).  
José Clovis -> [github](https://www.github.com/JoseClovis).  
