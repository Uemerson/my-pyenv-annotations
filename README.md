# About
My pyenv annotations.

# Annotations

See all available python installations:

```
$ pyenv install --list
```

Install some python versions:
```
$ pyenv install  3.7.5
$ pyenv install  2.7.17
$ pyenv install  3.8.0
```

See all python installations that you have installed:
```
$ pyenv versions
```

Set the default/global from one of the python versions:
```
$ pyenv global 3.8.0
```

In the current directory, set the python version. This creates the file .python-version:

```
$ pyenv local 2.7.17
```

To see which python is currently being used:
```
$ pyenv version
```
