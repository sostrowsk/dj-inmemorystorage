# CHANGELOG

## 2.1.0 - March 30, 2020

- Add support for Django class serialization by adding a `@deconstruct` decorator to `InMemoryStorage`
  - See: https://docs.djangoproject.com/en/3.0/topics/migrations/#adding-a-deconstruct-method
- Adds an `__eq__` method to `InMemoryStorage` for Django migrations.
- Adds the `path` argument when `PathDoesNotExist` is raised, which helps with stack traces.

## 2.0.0 - December 17, 2019

- Stop testing Python 2.6, 3.2, 3.3, 3.4.
- Stop testing Django < 1.11
- Start testing Python 3.7, 3.8
- Start testing Django 2.2, 3.0
