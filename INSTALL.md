# Install

## Arch Linux

```bash
sudo pacman -S nginx nginx-mod-headers-more
```

## Ubuntu

```bash
sudo apt install nginx libnginx-mod-http-headers-more-filter
```

# Start

```bash
systemctl enable --now nginx.service
```
