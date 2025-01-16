# Container Template for Docker-compose MariaDB PHP-apache
### Description
Example of a container template for MariaDB created during the DWWM formation.

## Structure
```
config/
    mariadb/
        init.sql
src/
    app/
        classes/
            .gitignore

docker-compose.yml
README.md
```
### Clone the project 
```git clone https://github.com/Kurocodil/Template-MariaDB.git```
## Prerequisites
- Docker
- MariaDB
## Commands to use


### Accessibilities
- Launch project : ```docker-compose up -d```
- Accessing MariaDB container :``` docker exec -it mariadb-container mysql -u root -p ```
- Verify data :
1. ``` SHOW DATABASE; ```
1. ``` USE templateDB; ```
1. ``` SHOW TABLES; ```
## Procedure
1. Install Docker (Docker Desktop)
2. VSCODE : install Docker extension from Microsoft
3. Clone the project
4. Launch services