# docker-project-1

In this project i had integrated mysql and wordpress .

Wordpress will help user to create a blog and it store information in the database so that data will be safe.\

Database is mounted to a permanent storage so that data will not lost if ,mysql O.S crash.

Install docker compose using commands:

# sudo curl -L "https://github.com/docker/compose/releases/download/1.25.5/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose

# sudo chmod +x /usr/local/bin/docker-compose

Code to launch this environment is in docker compose.yml file

To start the environment we have to run the command  
# docker-compose up
in the folder where my docker-compose.yml file is created

