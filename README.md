# crispy-bootstrap3

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/django-crispy-forms/crispy-bootstrap3/blob/main/LICENSE)

Bootstrap3 template pack for django-crispy-forms. This template pack was 
included with the core django-crispy-forms package until version 2.0.

## Installation

Install this plugin using `pip`:

```bash
    $ pip install crispy-bootstrap3
```

## Usage

You will need to update your project's settings file to add `crispy_forms`
and `crispy_bootstrap3` to your projects `INSTALLED_APPS`. Also set
`bootstrap3` as and allowed template pack and as the default template pack
for your project:

```python
    INSTALLED_APPS = (
        ...
        "crispy_forms",
        "crispy_bootstrap3",
        ...
    )

    CRISPY_ALLOWED_TEMPLATE_PACKS = "bootstrap3"

    CRISPY_TEMPLATE_PACK = "bootstrap3"
```
