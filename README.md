# Simon Vanilla Desktop Image

Containerfile for building a Simon Vanilla Desktop Simon.

This image is based on top of [`vanillaos/desktop`](https://github.com/Vanilla-OS/core-image/pkgs/container/desktop) and offers the default
Vanilla OS Desktop experience with GNOME.

## Build

```bash
sh prepare.sh
podman image build -t simon511000/simon-vanilla-desktop .
```
