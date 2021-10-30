# README!
* Name: `Python`
* Designed by: `Guido van Rossum` at `Centrum Wiskunde & Informatica (CWI)`
* First appeared: `1991`
* Developer: `Python Software Foundation`
* Paradigm: `imperative`, `functional`, `procedural`, `object-oriented`
* Typing and types discipline: `dynamic` and `strong`
* Package manager: `pip`
* Total keywords in Python 3.9: `36`
* Official sites: `https://www.python.org`

## Python, Pros & Cons
Pros & Cons in Python 2021

### Pros
* Easy to Read, Learn and Write
* Improved Productivity
* Interpreted Language
* Dynamically Typed
* Free and Open-Source
* Vast Libraries Support
* Portability

### Cons
* Slow Speed
* Not Memory Efficient
* Weak in Mobile Computing
* Database Access
* Runtime Errors

## Python, Linux Installationss
Many Unix-compatible operating systems, such as macOS and some Linux distributions, have Python installed by default; it's included in the base installation.

Check python version by following this command `python3 --version` and show default pre-install libraries with `pip3 list` then check location of python program using `whereis python3`

Install interpreted python, put this command on terminal
```zsh
sudo apt install ipython3
```

Put on `~/.zshrc` for use python3 by default
```zsh
alias python="python3"
alias pip="pip3"
alias ipython="ipython3"
```

## Python, Commands
* `python3 main.py`

## Python, PIP Commands
* `python3 -m venv my-venv`
* `source my-venv/bin/activate`
* `deactivate`
* `pip list`
* `pip freeze > requirements.txt`