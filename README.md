# FreeCodeCamp PHP OOP Course
### By Peter Fisher

    -Requirements
    -Installation
    
    ## Installation
    Creating Docker  Machine (Optional)
    ```
        $ docker-machine create  code-oop-php
        $ docker-machine env code-oop-php
        $ docker-machine  regenerate-certs  code-oop-php
        $ eval $(ocker-machine env code-oop-php)
        $ docker ps -a
        $ docker --version
        $ docker-machine  --version
        $ docker-compose  --version
        $ docker-machine active
        $ docker-compose up -d
        $ docker login if urnt logged in  help to build the images
        $ docker ps -a
        $ docker exec
        $ docker exec opp-projectgit_web_1 bash
        $ docker exec it opp-projectgit_web_1 bash
     
        $ ls
    ```   
    Create the containers and build the images
    ```   
        $ docker composer up -d --build
        $docker-machine active
        
    ```
    Find IP OF Docker Machine
    ```
    $docker-machine  ip opp-project 192.168.99.100
   
    ```
    
    Put the IP in a browser
    ```$docker ps -a
    ```
    
    ## Requirements
     - Docker 18.09.2
     - Docker Machine 0.16.1 (optional)
     - Docker Compose 1.23.2 