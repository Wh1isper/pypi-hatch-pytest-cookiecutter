![](https://img.shields.io/github/license/{{ cookiecutter.github_username }}/{{cookiecutter.project_slug}})
![](https://img.shields.io/github/v/release/{{ cookiecutter.github_username }}/{{cookiecutter.project_slug}})
![](https://img.shields.io/docker/image-size/{{ cookiecutter.github_username }}/{{cookiecutter.project_name}})
![](https://img.shields.io/pypi/dm/{{cookiecutter.project_slug}})
![](https://img.shields.io/github/last-commit/{{ cookiecutter.github_username }}/{{cookiecutter.project_slug}})
![](https://img.shields.io/pypi/pyversions/{{cookiecutter.project_slug}})

# {{ cookiecutter.project_slug }}

## Install

`pip install {{ cookiecutter.project_slug }}`

Or use docker image

`docker pull {{ cookiecutter.github_username }}/{{cookiecutter.project_name}}`

## Usage

TBD

## Develop

Install pre-commit before commit

```
pip install pre-commit
pre-commit install
```

Install package locally

```
pip install -e .[test]
```

Run unit-test before PR, **ensure that new features are covered by unit tests**

```
pytest -v
```
