# Minimal `nginx`

Simple `nginx.conf`.

## Features

- Arch Linux & Ubuntu support [out of the box](INSTALL.md).
- Removed HTTP `Server:` header by default.
- Cloudflare 1.1.1.1 as the default DNS resolver.
- Default server loads from `/srv/http/default/`.
- Extra servers can be configured by dropping their configs in the corresponding directory inside `/srv/http/www/*/*.conf`.
