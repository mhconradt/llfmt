# Installation

```shell
pip install llfmt
```

# Usage

Write to `stdout`:

```shell
llfmt file1.py *pattern2*.py directory3/**.py ...
```

Write to clipboard (on supported systems):

```shell
llfmt *.py | pbcopy
```