[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---

# Python

<details><summary>resources</summary>

---

- [Python.org](https://www.python.org)

---

</details>

## Basic commands

### Environment variables

``` python
""" lists environment variables, and splits elements in path variable """
import os

for k, v in sorted(os.environ.items()):
    print(k+':', v)
print('\n')
# list elements in path environment variable
[print(item) for item in os.environ['PATH'].split(';')]
```

This script has been saved in [print_env_var.py](/scripts/python/utils/print_env_var.py) and can be run directly from GitHub using

```bash
curl -sSL https://raw.githubusercontent.com/dMLTquant/dMLTresearch/main/scripts/python/utils/print_env_var.py | python3 -
```

### Help

```bash
python -h
```

### List Python Packages

#### List globally installed packages and their version

```bash
pip list
```

#### List locally installed packages

By default pip installs packages globally. In order to list packages that have been installed locally with the `–user` option can also be listed using the same `–user` option

```bash
pip list --user
```

### Poetry

#### Install

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

#### Uninstall

```bash
curl -sSL https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python - --uninstall
```

### Run module `-m` 

Python can import a module or package when you use the `-m` [command-line flag](https://docs.python.org/2/using/cmdline.html#cmdoption-m)

```bash
python -m pip list
```