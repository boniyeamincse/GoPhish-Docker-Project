# GoPhish Docker Project

Author: Boni Yeamin

Email: boniyeamin.cse@gmail.com

---
This project aims to set up a GoPhish phishing simulation platform using Docker containers. It includes configurations for GoPhish, NGINX as a reverse proxy, and Docker Compose to orchestrate the services.

## Project Structure

The project has the following file structure:


gophish-docker/
|- nginx/
| |- nginx.conf
|- gophish/
| |- Dockerfile
|- docker-compose.yml
|- README.md
|- .gitignore




- **nginx/nginx.conf**: NGINX configuration file defining server settings and behavior.
- **gophish/Dockerfile**: Dockerfile for building the GoPhish Docker image.
- **docker-compose.yml**: Docker Compose file defining services and configurations for Docker containers.
- **README.md**: This file, providing information about the project.
- **.gitignore**: Specifies which files and directories should be ignored by Git.

## Setup Instructions

1. Ensure Docker is installed on your system.
2. Clone this repository: `git clone https://github.com/your-username/gophish-docker.git`
3. Navigate to the project directory: `cd gophish-docker`
4. Customize NGINX and GoPhish configurations as needed.
5. Build and run the Docker containers: `docker-compose up --build`
6. Access GoPhish via: `http://localhost:3333`
7. Access NGINX via: `http://localhost`

## Additional Notes

- Make sure to customize NGINX and GoPhish configurations according to your requirements.
- Ensure proper security measures are implemented, especially when dealing with phishing simulations.
- For any issues or suggestions, feel free to open an issue on GitHub.

