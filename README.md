# Todos with GraphQL

See [https://gqlgen.com/getting-started](https://gqlgen.com/getting-started/).

## Steps

```sh
go mod init github.com/xsnout/gqlgen-todos
touch tools.go
# Edit tools file according to the getting-started instructions
go mod tidy
go run github.com/99designs/gqlgen init
# Edit schema.resolvers.go
go run server.go
```
