# Nanoblog

This is a very simple blogging app using Flask and a local database (SQLLite). It is based on the official Flask [tutorial](http://flask.pocoo.org/docs/tutorial/)

## Install

Clone the repository

```shell
git clone https://github.com/magomar/microblog.git
cd microblog
```

create a virtual environment and activate it

```shell
python3 -m venv .venv
source .venv/bin/activate
```

Install the project in editable mode (i.e. setuptools "develop mode"). It will install flask and the other dependencies

```shell
pip install -e .
```