# n.eko

n.eko is a self-hosted virtual browser that runs in Docker and uses WebRTC. It allows you to run a browser in a container and access it remotely through a web interface.

## Features

- Remote browser access via WebRTC
- Supports multiple users
- Low-latency video and audio streaming
- Customizable browser (using Ungoogled Chromium in this configuration)

## Usage

1. Access the n.eko interface by navigating to `https://your-domain.com` or `https://neko.local-domain`.
2. Log in using the user or admin password you set during installation.
3. You can now use the browser remotely as if it were running on your local machine.

## Configuration

- The user password is set using the `NEKO_PASSWORD` environment variable.
- The admin password is set using the `NEKO_PASSWORD_ADMIN` environment variable.
- Browser data is preserved between restarts and stored in the `${APP_DATA_DIR}/browser-data` directory.

For more advanced configuration options, please refer to the [official n.eko documentation](https://neko.m1k1o.net/#/).

## Note

This configuration uses the Ungoogled Chromium package. If you need a different browser or have specific requirements, you may need to modify the Docker image in the `docker-compose.yml` file.
