# crispy-bootstrap3to5

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/django-crispy-forms/crispy-bootstrap3/blob/main/LICENSE)

Bootstrap 3 to 5 transition template pack for django-crispy-forms.

## Usage

You will need to update your project's settings file to add `crispy_forms`
and `crispy_bootstrap3to5` to your projects `INSTALLED_APPS`. Also set
`bootstrap3to5` as and allowed template pack and as the default template pack
for your project:

```python
    INSTALLED_APPS = (
        ...
        "crispy_forms",
        "crispy_bootstrap3to5",
        ...
    )

    CRISPY_ALLOWED_TEMPLATE_PACKS = "crispy_bootstrap3to5"

    CRISPY_TEMPLATE_PACK = "crispy_bootstrap3to5"
```
