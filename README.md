Vault
=====

## Links
- https://hub.docker.com/_/vault/
- https://hub.docker.com/_/vault/tags
- http://localhost:8200

## Usage
```bash
docker compose up -d

# status
docker compose exec vault sh
vault status

# init
vault operator init -key-shares=1 -key-threshold=1 -format=json > init.json
cat init.json

# visit
# http://localhost:8200
```
