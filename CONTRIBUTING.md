# Contributing

You can contribue in multiple ways to this role :
- Creating issues to warn about a bug or suggest a change
- Improving role code and creating Pull Requests

## Improving role code

This role uses ansible-lint to ensure a minimum quality of its sources.

Please [install pre-commit](https://pre-commit.com/#install), and install pre-commit hooks into your local repository :

```shell
pre-commit install
```

Now, ansible-lint will be executed against your commit content before validating commit.

