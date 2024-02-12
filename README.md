# Kattleya Plasma Image

Containerfile for building Kattleya, an unofficial Vanilla OS Plasma image.

This image is based on top of [`vanillaos/core`](https://github.com/Vanilla-OS/core-image/pkgs/container/core) and offers the default
Unofficial Vanilla OS Desktop experience with Plasma.

## Build

```bash
vib build recipe.yml
podman image build -t kattleya/plasma .
```
