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
