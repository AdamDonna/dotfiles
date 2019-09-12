Pyenv virtualenv is good for managing python versions.
It can run an inital version and run commands through another version if need be.

### Setup run
```
$ brew install pyenv
$ brew install pyenv-virtualenv
```

##### After installation, you'll still need to add
```
$ eval "$(pyenv init -)"
$ eval "$(pyenv virtualenv-init -)"
```
Or run 
```
$ pyenv init
```
And run
```
$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
$ echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
```

### Installing new versions of python
```
$ pyenv install X.X.X
```

### Creating an environment
```
$ pyenv versions
3.4.3 (set by /home/adam/.pyenv/version)
X.X.X
$ pyenv virtualenv X.X.X venvName
```

### You can activate and deactivate a pyenv virtualenv manually
```
$ pyenv activate <venvName>
$ pyenv deactivate
```

### Listing virtualenvs
```
$ pyenv virtualenvs
```

### Using Multiple Versions (not verified as working)
```
$ pyenv virtualenv 3.5.6 envName 2.7.6
```

### Delete virtualenvs
```
$ pyenv virtualenv-delete my-virtual-env
```
