# Python Project Template

This template was created using [copier](https://copier.readthedocs.io/en/stable/).
The idea behind this template is to have a quick way to setup a new python project.

## Structure

The template will produce the following structure

```
src/
  {{package_name}}/
    main.py
tests/
  integration/
    {{package_name}}/
      test_main.py
  unit/
    {{package_name}}/
      test_main.py
.gitignore
pyproject.toml
README.md
noxfile.py
.copier-answers.yml
```

## How to use

First and foremost you need to have **copier** available to use. Please follow the instructions [here](https://copier.readthedocs.io/en/stable/) to install it.

Then you can just use copier directly.

To use the template on the current folder, just run the following command:

```bash
copier copy git@github.com:IceS2/python-project-template.git .
```

You can also define a git reference to copy:

```bash
copier copy git@github.com:IceS2/python-project-template.git . --vcs-ref main
```

### Questions asked

- **project_name**: Defines the name of the project that will be used in `pyproject.toml`.

- **project_description**: Short description used in `pyproject.toml`.

- **package_name**: name for the python package within `src/`. Defaults to **project_name**.

- **python_version_requirement**: Python version requirement used in `pyproject.toml`.

- **owner**: Owner of the project, used in `pyproject.toml` as the name attribute.

- **default_dev_dependencies**: If true, comes with some default dev dependencies and configurations ([nox](https://nox.thea.codes/en/stable/), [pytest](https://docs.pytest.org/en/7.4.x/), [ruff](https://beta.ruff.rs/docs/)).
