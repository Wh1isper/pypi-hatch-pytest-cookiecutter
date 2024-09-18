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

- `PAT`: for GitHub Container Registry and versioning
- `DOCKERHUB_TOKEN`: for pushing image to DockerHub
- `PYPI_API_TOKEN`: for uploading to PyPI

> **It's recommended to upgrade pypi release to Trusted Publishing**
> Upgrade to Trusted Publishing
> Trusted Publishers allows publishing packages to PyPI from automated environments like GitHub Actions without needing to use username/password combinations or API tokens to authenticate with PyPI. Read more: https://docs.pypi.org/trusted-publishers

### Variables

- `DOCKERHUB_USERNAME`: for pushing image to DockerHub
