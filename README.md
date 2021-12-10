# keycloak-docker
Experimenting with Keycloak 

The keycloak-postgres.yml template creates a volume for PostgreSQL and starts Keycloak connected to a PostgreSQL instance.

Run the example with the following command:

    docker-compose -f keycloak-postgres.yml up

Open http://localhost:8080/auth and login as user 'admin' with password 'Pa55w0rd'.