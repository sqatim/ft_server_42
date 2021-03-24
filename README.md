# ft_server_42
This topic is intended to introduce us to system administration. It will make us aware of the importance of using scripts to automate our tasks. For that, we will discover the "docker" technology and use it to install a complete web server. This server will run multiples services: Wordpress, phpMyAdmin, and a SQL database.

## Subject
+ [ft_server_subject](/ft_server_subject.pdf)

## How To Use
1. Clone this repo.
2. CMD build:
    ```
    docker build -t "tag" . 
    ```
3. CMD run:
    ```
    docker run -it -p 80:80 -p 443:443 "tag" 
    ```
