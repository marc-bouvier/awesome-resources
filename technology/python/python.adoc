# Python

[Back home](README.md)

## Install pip

```
sudo apt-get install python3-pip
```


## Install pipenv 

Pipenv mixes pip and virtualenv in 1 command. It allows using pipfile

```bash
# install pipenv
pip3 install --user pipenv

# upgrade pipenv
 pip3 install --user --upgrade pipenv
```

Add `~/.local/bin` to $PATH

In ~/.zprofile
```
path=(
  /usr/local/{bin,sbin}
  $HOME/.local/bin
  $path
)
```
