# Stat Renderer

[![GoDoc](https://pkg.go.dev/badge/github.com/kayteh/stat-renderer)](https://pkg.go.dev/github.com/kayteh/stat-renderer)

A Go library for building images of stat sheets.

```
go get -u github.com/kayteh/stat-renderer
```

Alternatively, you can use the CLI tool with JSON input

```
go get -u github.com/kayteh/stat-renderer/cmd/stat-renderer

echo '{"title": "My Cool Stats", "stats": [{ "name": "Health", "value": 10, "max": 10 }]}' | stat-renderer > stats.png
```
