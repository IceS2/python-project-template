# {{project_name}}

This project was generated from a [copier](https://copier.readthedocs.io/en/stable/) template.
Some explanation on how to use the generated code is given below.

## How to Install the project

In order to install the project you can simply run the following command:

```bash
pip install .
```

To install in edit mode

```bash
pip install -e .
```

{{%- if default_dev_dependencies %}}
To install with the dev dev dependencies

```bash
pip install .[dev]
```

## About Tests

We use the following stack:

- [Ruff](https://beta.ruff.rs/docs/) - Static Checked
- [Pytest](https://docs.pytest.org/en/7.4.x/) - Test Framework
- [Nox](https://nox.thea.codes/en/stable/) - Runner

In order to run the tests you can just run the following command:

```bash
nox
```
{{%- endif %}}
