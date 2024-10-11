# PHP Docker Extended

A Docker container built with PHP 8.2 configured with FPM and a wide range of libraries and extensions to support various development needs, including GD, LDAP, Memcached, MongoDB, and others. This setup also includes Composer for dependency management and health check scripts for monitoring.

## Features
- **PHP 8.2** with FPM
- Extensions support:
  - GD for image processing
  - LDAP for directory access
  - Memcached for caching
  - MongoDB support via `pecl`
  - Various database drivers (MySQL, PostgreSQL, SQLite, Firebird, MSSQL)
  - Additional extensions like `imap`, `intl`, `curl`, `exif`, `soap`, and many more
- **Composer** for dependency management
- Health check script for container monitoring
- Debian-based environment

## Requirements
- Docker installed on your machine

## Usage
Clone the repository and build the Docker image:

```bash
git clone https://github.com/McHughSecurity/php-docker-extended.git
cd php-docker-extended
docker build -t php-docker-extended .
