# Dotfiles

Personal Dotfiles Repository

Uses [Dotbot](https://github.com/anishathalye/dotbot) to manage and version `.dotfiles`.

### Install

Clean install:

```
git clone https://github.com/CodeZwei/dotfiles.git
cd dotfiles
git checkout ${hostname -s} # checkout machine specific version
sh ./install
```

### Private Credentials

GitHub Personal Access Token is stored in an untracked credentials file at `~/.git-creds/zwei`.

Mint a new access token for the host and login with it to set the file.
