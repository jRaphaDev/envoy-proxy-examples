Run the api fake:

  ```json-server --port 3000 users-api.json```

  ```json-server --port 3001 users-api.json```

Run the Envoy configuration:

  ```envoy --config-path envoy.yaml```
