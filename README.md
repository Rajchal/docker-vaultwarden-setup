# Vaultwarden Docker Compose Setup

This repository contains a `docker-compose.yml` configuration for hosting a self-hosted password manager, **Vaultwarden**, behind a reverse proxy using **Nginx**. It is designed for personal or family use.
You can visit my site for your safe password aswell.

## Features
- Self-hosted Vaultwarden server.
- Reverse proxy powered by Nginx.
- SSL support for secure connections.
- WebSocket notifications enabled.

## Requirements
- Docker and Docker Compose installed.
- A domain name (optional but recommended).
- SSL certificates (can be generated using Let's Encrypt).

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/Rajchal/vaultwarden-docker-setup.git
   cd vaultwarden-docker-setup
   ```

2. Configure the `docker-compose.yml` file:
   - Replace `your_admin_token_here` with a secure admin token.

3. Configure the Nginx reverse proxy:
   - Edit `nginx.conf` and set your domain name.

5. Start the services:
   ```bash
   docker-compose up -d
   ```

6. Access Vaultwarden:
   - Navigate to `http://rajchalvault.space` or `https://www.rajchalvault.space`.

