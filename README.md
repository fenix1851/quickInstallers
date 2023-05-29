# Quick Installers

This repository contains quick installer script files for various tools and services.

## Databases

* `mysql` - Quick installer for MySQL Server. Includes instructions for installing the server, optionally securing the installation, and starting the service. [View File](./databases/mysql/mysql_latest.txt)

* `mongodb` - Quick installer for MongoDB. This script will import the MongoDB public GPG key, add the MongoDB repository, update system packages, install MongoDB, and start the service. [View File](./databases/mongodb/mongodb_latest.txt)

* `postgresql` - Quick installer for PostgreSQL. This script installs PostgreSQL and starts the service. [View File](./databases/postgresql/postgresql_latest.txt)

## Docker

* `alternative_docker_cocker_compose` - Quick installer for Docker and Docker Compose. This script installs Docker and Docker Compose using the official Docker installation script. [View File](./docker/alternative_docker_cocker_compose.txt)

* `docker_and_docker_compose` - Another quick installer for Docker and Docker Compose. This script installs Docker and Docker Compose using the package manager. [View File](./docker/docker_and_docker_compose.txt)

## Nginx

* `install_plus_port_mapping` - Quick installer for Nginx with a basic server configuration. This script installs Nginx and sets up a basic server configuration that redirects from port 80 to localhost:3000. [View File](./nginx/install_plus_port_mapping.txt)

## Node.js

* `nvm_npm_latest` - Quick installer for Node.js and npm using NVM. This script installs NVM, reloads the terminal configuration, installs the latest version of Node.js, sets it as the default, and verifies the installation. [View File](./nodejs/nvm_npm_latest.txt)

## Python

* `3.8` - Quick installer for Python 3.8. This script updates system packages, installs build essentials, downloads and extracts the source code for Python 3.8, configures and compiles Python 3.8, and verifies the installation. [View File](./python/3.8.txt)

* `3.9` - Quick installer for Python 3.9. This script updates system packages, installs build essentials, downloads and extracts the source code for Python 3.9, configures and compiles Python 3.9, and verifies the installation. [View File](./python/3.9.txt)

## Zsh

* `ohmyzsh` - Quick installer for Oh My Zsh. This script updates system packages, installs Zsh, downloads and installs Oh My Zsh, sets Zsh as the default shell, and starts Zsh. [View File](./zsh/ohmyzsh.txt)


## Alacritty

* `install_plus_drakula` - Quick installer for Alacritty with Dracula theme. This script installs Alacritty and sets up the Dracula color scheme in the configuration file. [View File](./apps/terminals/alacritty/install_plus_drakula.txt)
