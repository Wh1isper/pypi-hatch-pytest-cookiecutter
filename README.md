# pypi-hatch-pytest-cookiecutter

```bash
cookiecutter https://github.com/Wh1isper/pypi-hatch-pytest-cookiecutter.git
```

cookiecutter template for python package

- pytest support
- hatch for build
- read-the-docs support
- github CI
- pre-commit
- docker build

refer to [audreyr/cookiecutter-pypackage](https://github.com/Nekroze/cookiecutter-pypackage)

## Configuration for github action:

### Secrets

`PAT`: for GitHub Container Registry and versioning
`DOCKERHUB_TOKEN`: for pushing image to DockerHub

### Variables

`DOCKERHUB_USERNAME`: for pushing image to DockerHub
