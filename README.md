# Building and Testing Locally

```
git submodule update --init
flatpak install org.gnome.Sdk
flatpak-builder --force-clean --user --install build-dir net.christianbeier.Gromit-MPX.yml
flatpak run net.christianbeier.Gromit-MPX
```
