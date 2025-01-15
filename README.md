# lunch bytes

## Development

To install the dependencies, run

```bash
uv sync
```

## Updating the template

This repository was created from template repository.
Template can change over time, and you can update it by running in the root of the repository:

```bash
uv run copier update . \
    --skip-answered \
    --skip-tasks \
    --answers-file .copier-answers.main.yaml \
    --trust \
    --conflict inline \
    --skip .ruff.toml \
    --skip .github/workflows \
    --skip lunch_bytes
    
```
