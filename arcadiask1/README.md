# arcadiask-1

> A GitHub App built with [Probot](https://github.com/probot/probot) that Probot app powering the citizen-science application of Signal-K&#x27;s Arcadia

## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t arcadiask-1 .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> arcadiask-1
```

## Contributing

If you have suggestions for how arcadiask-1 could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 GitHub <liam@skinetics.tech>
