# Ladybird Flatpak

This repo does a nightly build of ladybird so you can easily test it out.

## Installing (remove the --user argument to install system-wide)
``` bash
flatpak remote-add --user ladybird-flatpak https://kichirouhoshino.github.io/org.ladybird.ladybird/index.flatpakrepo
flatpak install roddy-flatpak org.ladybird.ladybird
```

## Issues
- Ladybird requires network during build time, which is not allowed for Flathub. This is a dev build, so it doesn't matter, really.
