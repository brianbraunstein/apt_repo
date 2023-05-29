
# Brian Braunstein's Apt Repo

To use this repository, run the following:

```
wget -O - http://brianbraunstein.github.io/apt_repo/brianbraunstein_apt_repo.gpg.key |
  sudo apt-key add -
wget -O - http://brianbraunstein.github.io/apt_repo/sources.list.d.sources |
  sudo tee /etc/apt/sources.list.d/brianbraunstein.sources
```

