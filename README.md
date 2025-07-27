# home-services

Configuration for personal services.

Setup:

- Copy `env.in` to `.env` and fill out variables.

- Generate a Pi-hole API key.

    * Settings > Web interface/API (Expert mode)
    * Configure app password

- Generate a Speedtest-tracker API key:

    * `echo -n 'base64:'; openssl rand -base64 32;`
    * Settings > API Tokens > Create API Token
    * Use the key as the name.

- Enter a FreshRSS API key.

    * Settings > Profile > API management.

- `docker-compose up -d`

Shutdown:

- `docker-compose down`
