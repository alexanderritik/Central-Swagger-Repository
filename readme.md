# Central Swagger Repository

Welcome to the Central Swagger Repository! This project aims to provide a centralized solution for managing and deploying Swagger documentation for multiple microservices.

## Overview

In a microservices architecture, each service typically has its own Swagger documentation. Managing and accessing these documents can become cumbersome as the number of services grows. This repository provides a centralized location where all Swagger documents can be easily accessed and deployed.

## Features

- **Centralized Documentation**: Aggregate Swagger docs from multiple microservices into a single repository.
- **Easy Deployment**: Simplify the deployment process with a CI pipeline that automatically collects and updates Swagger docs.
- **Consistent Access**: Ensure all team members have access to the latest API documentation.

## How It Works

1. **Microservices**: Each microservice contains its own Swagger documentation.
2. **CI Pipeline**: A CI pipeline is configured in each microservice to find and push Swagger docs to the central repository.
3. **Central Repository**: This repository collects all Swagger docs and provides a single access point for all API documentation.

## Getting Started

To get started, follow these steps:

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/central-swagger-repo.git
    cd central-swagger-repo
    ```

2. Configure the CI pipeline in each microservice to push Swagger docs to this repository.

3. Deploy the central repository to your preferred hosting service.
# Central-Swagger-Repository
