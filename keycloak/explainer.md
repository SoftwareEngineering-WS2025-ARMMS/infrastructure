# Docker Compose: Keycloak and PostgreSQL

This setup defines a Docker-based deployment for running **Keycloak**, an Identity and Access Management system, with a **PostgreSQL** database as its persistent storage.

## Key Points

- **Services**:
  - `armms-keycloak`: Hosts Keycloak.
  - `keycloakdb`: Provides the database for Keycloak.
- **Configuration**:
  - Secrets and settings are passed as **environment variables**, specified locally in the deployment environment.
- **Network**: Both services communicate over a private Docker bridge network.

## Usage

1. Set the required environment variables (e.g., database credentials, Keycloak admin details) in the deployment environment, for example in our case the KC_HOSTNAME is `https://keycloak-armms.rayenmanai.site` where our Keycloak is deployed.
2. Start the services with `docker-compose up -d`.
3. Access Keycloak at its configured hostname and port.
