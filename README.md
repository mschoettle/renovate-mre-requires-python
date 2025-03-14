# 34793

MRE for discussion https://github.com/renovatebot/renovate/discussions/34793#discussioncomment-12493550

## Current behavior

The Python version in `.python-version` gets updated, the pinned version in `requires-python` in `pyproject.toml` does not.

## Expected behavior

The `requires-python` version should be updated as well.
It is also possible to write other expressions, such as `==3.12.*` in which case it would be great to get an update to `3.13.*`.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/34793#discussioncomment-12493550
