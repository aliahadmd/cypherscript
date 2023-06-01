# hello world


# active virtual env

```bash
source venv/bin/activate
```

# The following command creates a file called requirements.txt that enumerates the installed packages.

```bash
pip freeze > requirements.txt
```

# This file can then be used by collaborators to update virtual environments using the following command.

```bash
pip install -r requirements.txt
```