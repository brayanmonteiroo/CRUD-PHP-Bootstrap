# CRUD-PHP-Bootstrap
CRUD feito com PHP, MySQL e Bootstrap
## Criação do Banco de dados e a tabela:
* 1º Para funcionar na sua máquina, seguindo o meu exemplo, crie uma base de dados no phpMyAdmin chamada 'crud-php-bootstrap'.
* 2º Crie a tabela com seguinte código:
```
CREATE TABLE students (
    id INT(6) AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(191) NOT NULL,
    email VARCHAR(191) NOT NULL,
    phone VARCHAR(191) NOT NULL,
    course VARCHAR(191) NOT NULL
)
```
