
# Install
Install docker from  https://www.docker.com/community-edition

Open terminal or cmd and cd to wordpress-mysql-alpine folder. Run:
```
docker-compose up
```
Install any MySQL client, connect to `localhost` (default port 3306), create user and DB for wordpress.

Download WP from https://wordpress.org/download/ extract content to ./www/htdocs folder.

Open http://localhost in browser and finish installation.

Edit docker-compose.yml file for customization.