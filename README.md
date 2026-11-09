# Glitch Art's static hub

`hub.json`, served at https://glitchr-studio.github.io/hub.json, lists Glitch Art's open Unity packages for
[Forge Store](https://github.com/glitchr-forge/unity-store) (Window ▸ Forge Store ▸ Sources ▸ add this URL). Each
source is a Git package, installed by its URL; the format is in Forge Store's
[docs/sources.md](https://github.com/glitchr-forge/unity-store/blob/main/docs/sources.md).

The catalogue's master is now the `"hub"` section of
[io.glitchr.studio's package.json](https://github.com/glitchr-studio/unity-studio/blob/main/package.json): add
`https://github.com/glitchr-studio/unity-studio.git#v0.2.0` as a Git source instead. This file is a copy, kept for the
sources that already point here.
