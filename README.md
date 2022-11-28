A fork of [gau](https://github.com/lc/gau) that replaces the blacklist option with a whitelist option.

Usage is exactly the same as gau but allows for the whitelist flag instead of the blacklist flag.
Example: ```gau --whitelist png,jpg,gif example.com```

This will make so everything except these file extensions are filtered.

## Building
You can build the usable binary from source using the go build command:
```go build cmd/gau/main.go```