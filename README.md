# gadalang-samples

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/gadalang/gada/issues)

Collection of sample nodes for [gada](https://github.com/gadalang/gada).

## Install

Using pip:

```bash
pip install gadalang-samples
```

## Usage

Install [gada](https://github.com/gadalang/gada) using pip:

```bash
$ python -m pip install gada
```

Run `helloworld` sample:

```bash
$ python -m gada gadalang_samples.helloworld
hello world !
```

## Testing

The `test` directory contains many tests that you can run with:

```python
$ python setup.py test
```

Or with coverage:

```python
$ coverage run --source=gadalang_samples setup.py test
```
