# home-services

Configuration for personal services.

Setup:

- Copy `env.in` to `.env` and fill out variables.

- Generate a Speedtest-tracker API key:
```
echo -n 'base64:'; openssl rand -base64 32;
```

- Enter a FreshRSS API key in: FreshRSS web > Settings > Profile >
  API management then update in `.env`.

- `docker-compose up -d`

Shutdown:

- `docker-compose down`
