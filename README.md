# SonarQube

This repository contains a Docker Compose file to run SonarQube server locally using Docker.

## Prerequisites
- Docker installed on your machine

## Usage
1. Clone this repository to your local machine.

2. Navigate to the root of the repository.

3. Run the following command to start SonarQube server:

```bash
docker-compose up -d
```

## Accessing SonarQube

Once the services are up and running, you can access SonarQube at http://localhost:9000 using your web browser.

Defaul credentials:
- Username: admin
- Password: admin

## Notes
If you change the database credentials, make sure to update them in the SonarQube service environment as well.

