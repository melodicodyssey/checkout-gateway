# checkout-gateway
A Controller/Gateway repo for handling requests from the frontend; layer between frontend and backend services.

# checkout-gateway

## Overview

The `checkout-gateway` is the API Gateway responsible for handling gateway logic.

## Responsibilities

- Authenticate API requests from the frontend
- Route validated requests to backend services
- Act as a facade for Stripe and event publishing

## API (WIP)

This service exposes REST endpoints which will be documented as the application evolves.

## Development

Each service will be containerized with a `Dockerfile` and configured for local development via `docker-compose`.

## License

Licensed under the [MIT License](./LICENSE).

---

> Tagged with: `#1 Scope out Checkout app project`
