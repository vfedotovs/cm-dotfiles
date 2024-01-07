# cm-dotfiles

# Set up a new machine with a single command
You can install your dotfiles on new machine with a single command:

```bash
$ chezmoi init --apply https://github.com/$GITHUB_USERNAME/cm-dotfiles.git

If you use GitHub and your dotfiles repo is called dotfiles then this can be shortened to:
$ chezmoi init --apply $GITHUB_USERNAME
```

More info:
https://www.chezmoi.io/quick-start/
