# Ladybird Flatpak

This repo does a nightly build of ladybird so you can easily test it out. Do note that Ladybird is still in early development.

## Installing (remove the --user argument to install system-wide)
``` bash
flatpak remote-add --user ladybird-flatpak https://kichirouhoshino.github.io/org.ladybird.ladybird/index.flatpakrepo
flatpak install ladybird-flatpak org.ladybird.ladybird
```
## ToDo
- Improve manifest to use cmake-ninja buildsystem instead of simple
- Test sandbox (see if portal works, expose necessary file paths)
- Add additional dbus permissions if needed
- Add cleanup commands (Ladybird leaves some static libraries behind)
