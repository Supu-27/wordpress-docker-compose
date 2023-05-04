# WordPress Docker Compose Project

 This is a sample project that uses Docker Compose to deploy a WordPress website with a MySQL database.

### Prerequisites

Before you begin, you'll need to have the following software installed on your machine:

Docker
Docker Compose

### Usage

To use this project, follow these steps:

1. Clone the repository to your local machine:

```
 git clone https://github.com/Supu-27/wordpress-docker-compose.git
```

2. Navigate to the project directory:

,,,
cd wordpress-docker-compose
,,,

3. Start the containers:

'''
docker-compose up -d
,,,

4. Visit http://54.160.199.0 in your web browser to access the WordPress installation page. Follow the on-screen instructions to complete the installation process

5. Once you have completed the installation process, you can start customizing your WordPress website by installing themes and plugins.

### Configuration:

This project uses a docker-compose.yml file to configure the containers. You can modify this file to customize your WordPress installation.

The uploads.ini file in the project directory contains configuration options for file uploads and memory limits.

### License:

This project is licensed under the MIT License

