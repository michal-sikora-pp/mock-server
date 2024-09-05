# Mock Server

A mock server using JSON Server with a custom `/callback` endpoint.

## Installation

1. Clone the repository and navigate to the project directory.
2. Install dependencies:

   ```bash
   yarn install
   ```

3. Start the server:

   ```bash
   yarn start
   ```

## Endpoints

- **POST /callback**: Returns a `201` status with `{ "status": "OK" }`.

  Example request:

  ```bash
  curl -X POST http://localhost:4000/callback \
  -H "Content-Type: application/json" \
  -d '{"name": "Sample Callback"}'
  ```

The server runs on [http://localhost:4000](http://localhost:4000).
