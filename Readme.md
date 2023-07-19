# Oh My Replicated

This repository aggregates [custom plugins](https://github.com/ohmyzsh/ohmyzsh/#custom-plugins-and-themes) for [Oh My Zsh](https://ohmyz.sh/) and other useful scripts maintained by engineers at Replicated that we find useful. In general this repository will be for plugins which are customized and unlikely to be of wider user by the community. If a plugin is mature and generic to be of general use we should be committing it back upstream instead of carrying it here.

Each plugin should be prefaced with `replicated-` to avoid unintentional overrides of other plugins. Additionally plugins should be focused, split unrelated items into individual plugins to allow users to choose which ones they want to enable.

## Oh My Zsh

To install a plugin copy (or symlink!) the plugin to your custom folder `~/.oh-my-zsh/custom/plugins` and enable it in your `~/.zshrc` plugin list. Ex:

```zsh
plugins=(
        replicated-gcommands
        )
```

## Manually Sourcing

Alternatively if you don't want to use [Oh My Zsh](https://ohmyz.sh/) (eg. for performance reasons) you can just source in the ZSH commands (assuming a clone into `~/git/replicatedhq/oh-my-replicated`).

Add to your `~/.zshrc`:

```zsh
source ~/git/replicatedhq/oh-my-replicated/replicated-gcommands/replicated-gcommands.plugin.zsh
```

Ensure you read the [`replicated-gcommands/README.md`](replicated-gcommands/README.md) for adding required environment variables also.
