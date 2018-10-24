# DirectusConfigurator
A simple script that sets up Directus based on a configuration file.

## Usage:

     node index.js [options]

## Available Options:

`-a` Directus API Hostname to use (defaults to localhost)

`-p` or `--port` Directus API Port to use (defaults to 8080)

`-c` or `--config` Configuration file to use

`-e` or `--env` Environment variables file to use (uses default email and password if no .env file or email and password provided)

`--email` Email to connect with into the API (defaults to `admin@admin.com` or use the email found on .env )

`--email` Password to connect with into the API (defaults to `admin` or use the password found on .env )