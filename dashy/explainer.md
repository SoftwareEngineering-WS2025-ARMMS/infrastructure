Dashy

Dashy is an open-source project for plugin-based dashboard creation.

## Key Points

- **Set up**:
  - `conf.yml`: Definition of the style, plugins and authentication mechanisms.
  - `docker-compose.yml`: Used to spin up the container
- **New Configuration**:
  - In order to define your own configuration, please check [Dashy Docs](https://dashy.to/docs/)
- ## Usage
  

1. Define your own `conf.yml`file. The current configuration is used for the [ARMMS-Dashboard](https://armms-dashboard.aorief.com) project
2. Start the services with `docker-compose up -d`.
3. Access Dashy through `http://localhost:400`
