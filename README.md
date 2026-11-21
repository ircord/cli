# IRCord CLI

`ircordctl` is the standalone command-line administration client for IRCord.
Use the latest stable Go release to build and check it.

```sh
go build ./cmd/ircordctl
go test -race ./...
go vet ./...
```

Download the binary for your platform from
[Releases](https://github.com/ircord/cli/releases).
See the [development environment](https://github.com/ircord/dev-environment)
for configuration and examples.

Run `sh generate.sh` when the backend contract changes. It reads
`../backend/openapi.json` by default. Set `IRCORD_OPENAPI` to the absolute path
of a different OpenAPI file.
