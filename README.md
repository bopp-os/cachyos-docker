<div align="center">
  <img src="https://github.com/CachyOS/calamares-config/blob/grub-3.2/etc/calamares/branding/cachyos/logo.png" width="64" alt="CachyOS logo"></img>
  <br/>
  <h1 align="center">CachyOS Docker (Fork)</h1>
  <p align="center">Custom CachyOS Docker Images for bopp-os</p>
</div>

This repository is a fork of [CachyOS/docker](https://github.com/CachyOS/docker) maintained by the **bopp-os** organization. It is a personal/organizational build, not the upstream official CachyOS Docker builds.

## Image Variant

This fork builds and maintains the **znver4** optimized image variant of CachyOS. Other variants (like standard, v3, and v4) are built and maintained by upstream CachyOS, and can be found on Docker Hub under `cachyos/cachyos`.

## Registry

The `znver4` optimized images are published to the GitHub Container Registry (GHCR):

- **Image Location**: `ghcr.io/bopp-os/cachyos-docker/cachyos-znver4`
- **Tags**: `znver4`, `znver4-latest`, `latest`

To pull the image:
```bash
docker pull ghcr.io/bopp-os/cachyos-docker/cachyos-znver4:latest
```
