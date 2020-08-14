# Pequi
URL shortener using Cloud Firestore

[![Go Report Card](https://goreportcard.com/badge/github.com/noverde/pequi)](https://goreportcard.com/badge/github.com/noverde/pequi)
## setup

```
go mod tidy
```

## run

**var envs:**
- HTTP_PORT _default: 8080_
- FIRESTORE_PROJECT
- FIRESTORE_COLLECTION

```
go run main.go
```

## Supported Databases

- [ ] In Memory (in development)
- [ ] Redis (open a Pull Request)
- [x] Firestore
- [ ] DynamoDB (open a Pull Request)
- [ ] MySQL (open a Pull Request)
- [ ] Postgres (open a Pull Request)
- [ ] SQLite (open a Pull Request)
