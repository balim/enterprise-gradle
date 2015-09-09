# Docker

To simplify building an integrated toolchain this project uses docker, and docker compose.

## Running the tools

You can directly run the toolchain. There’s no need to install a Servlet container. In a terminal
window execute the following command from the root level of the project:

    docker-compose up -d

After a few moments, you will find the following output:

    ...
    Creating docker_sonarqube_1...
    Creating docker_db_1...
    Creating docker_jenkins_1...

Open your browser of choice and navigate to the URL.