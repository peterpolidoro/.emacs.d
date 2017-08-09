# .emacs.d

Authors:

    Peter Polidoro <polidorop@janelia.hhmi.org>

License:

    BSD

## Install

### emacs

```shell
sudo apt-get remove emacs
sudo apt-get autoremove
sudo add-apt-repository ppa:ubuntu-elisp/ppa
sudo apt-get update
sudo apt-get install emacs-snapshot
```

### git

```shell
sudo apt-get install git
```

## .emacs.d

```shell
rm -rf ~/.emacs.d
git clone https://github.com/peterpolidoro/.emacs.d.git ~/.emacs.d
```
