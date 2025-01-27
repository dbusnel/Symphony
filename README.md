![app-icon](https://i.ibb.co/0FBnqKf/Symphony.png)
# Symphony - Find friends to go to concerts with!

The application utilizes 3 Docker containers: 
1. A MySQL 8 container for data storage.
1. A Python Flask container to implement a REST API
1. A Local AppSmith Server

## How to setup and start the containers
**Important** - you need Docker Desktop installed

1. Clone this repository.  
1. Create a file named `db_root_password.txt` in the `secrets/` folder and put inside of it the root password for MySQL. 
1. Create a file named `db_password.txt` in the `secrets/` folder and put inside of it the password you want to use for the a non-root user named webapp. 
1. In a terminal or command prompt, navigate to the folder with the `docker-compose.yml` file.  
1. Build the images with `docker compose build`
1. Start the containers with `docker compose up`.  To run in detached mode, run `docker compose up -d`. 

## Video Demo: https://drive.google.com/file/d/1lUYP0-r0fqaGfZfGSpuTDU0bCTYXUE6g/view?usp=sharing




