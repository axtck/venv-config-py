# Python virtualenv config

Python and pip should be installed.
```bash
$ pip install virtualenv
($ pip3 install virtualenv)
```
Export $PATH (Linux)
```bash
# Add to ~/.zshrc
export PATH="$HOME/.local/bin:$PATH"

# Run
$ source ~/.zshrc
```

---

# Commmands

## Create:
```bash
$ virtualenv ENV_NAME
```

## Activate:
```bash
$ source PATH_TO_ENV_NAME/bin/activate

# Install packages
# For example:
$ pip3 install paho-mqtt
```
## Deactivate:
```bash
$ deactivate
```

## Export requirements
```bash
$ pip freeze > requirements.txt
```
