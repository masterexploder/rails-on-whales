# Part 2 Reference Files

All the files in this folder are in the state that they should be upon
successfully completing all the steps described in Part 2 of the series.

## File & Folder Reference

| Name                                  | Description                                                                                                |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| `docker/Aptfile`                      | A list of dependencies to be installed via `apt-get install` when building the container for the Rails app |
| `docker/Dockerfile.development`       | A universal Dockerfile for Rails apps in a development environment container                               |
| `docker/Dockerfile.nginx.development` | A Dockerfile for an nginx proxy that serves a containerized Rails app and Webpack dev server behind SSL    |
| `docker/nginx/nginx.development.conf` | The configuration file used by the nginx proxy                                                             |
| `docker-compose.yml`                  | The docker compose file for the example Rails app                                                          |
