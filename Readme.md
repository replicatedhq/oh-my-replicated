# Oh My Replicated

This repository aggregates [custom plugins](https://github.com/ohmyzsh/ohmyzsh/#custom-plugins-and-themes) for [Oh My Zsh](https://ohmyz.sh/) and other useful scripts maintained by engineers at Replicated that we find useful. In general this repository will be for plugins which are customized and unlikely to be of wider user by the community. If a plugin is mature and generic to be of general use we should be committing it back upstream instead of carrying it here.

Each plugin should be prefaced with `replicated-` to avoid unintentional overrides of other plugins. Additionally plugins should be focused, split unrelated items into individual plugins to allow users to choose which ones they want to enable.

To install a plugin copy (or symlink!) the plugin to your custom folder `~/.oh-my-zsh/custom/plugins` and enable it in your `~/.zshrc` plugin list. Ex:

```zsh
plugins=(
        replicated-gcommands
        )
```
