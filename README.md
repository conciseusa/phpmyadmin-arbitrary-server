# phpmyadmin-arbitrary-server
Docker compose to run phpmyadmin in arbitrary server mode.

`git clone https://github.com/conciseusa/phpmyadmin-arbitrary-server.git`

Run in the dir with docker-compose.yml to run:<br>
`docker compose up --detach`

Command to run in dir with docker-compose.yml to stop:<br>
`docker compose down`

Update image:<br>
`docker compose down`<br>
`docker pull phpmyadmin/phpmyadmin:latest`

When accesing a DB server installed directly on the host,
get IP address of the host (ifconfig -a) and use that for the Server: field.<br>
localhost may go to the container, not the host.<br>
