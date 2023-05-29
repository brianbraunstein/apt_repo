
# Brian Braunstein's Apt Repo

To use this repository, run the following:

```
wget -O - http://www.example.com/repos/apt/conf/brianbraunstein_apt_repo.gpg.key |
  sudo apt-key add -
wget -O - http://github.com/brianbraunstein/apt_repo/sources.list.d.source |
  sudo tee /etc/sources.list.d/brianbraunstein.sources
```

