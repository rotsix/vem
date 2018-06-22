# venv

> "A manager to manage them all."

`venv` is an ultra-simple python's virtual environments manager (see [here](https://virtualenv.pypa.io/en/stable/) for more).

## Installation

More than simple, just copy this to your `$PATH`.

## Usage

```
venv <command>
  list: display all disponible environments
  get: display current environment
  set <env>: set current environment
  gen <env>: generate new environment
  del <env>: delete given environment
  help: display help
```

## Configuration

`venv` uses a virtual environment folder, located at `$HOME/.virtual-env`.

## Q/A

> Why not using <env>/bin/activate?

I was reading [this](https://gist.github.com/datagrok/2199506), and realized that this script is useless, and complicated. Doing a separate sub-shell for our environment is simpler, quicker, and safer.

> How to desactivate current environment?

Just exit, or `^D`!

