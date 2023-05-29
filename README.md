
# Brian Braunstein's Apt Repo

## Instructions

To use this repository, run the following:

```
wget -O - http://brianbraunstein.github.io/apt_repo/brianbraunstein.sources |
  sudo tee /etc/apt/sources.list.d/brianbraunstein.sources
sudo apt update
```

Then just install things:

```
sudo apt install configo
```

### Manually Installing Keys

If you need to manually install the key it's available here in both ascii and
binary formats:

- [`repo_key.asc`](repo_key.asc)
- [`repo_key.gpg`](repo_key.gpg)

See the `DEPRECATION` warning in `man apt-key` for the proper way to manually
install keys.
