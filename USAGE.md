# gha-v.0.0.1 - GitHub Actions Reusable Workflow

This workflow is designed to be reusable by other repositories. To use it, reference this workflow in your own repository's workflow YAML file as follows:

```yaml
jobs:
  call-hello-world:
    uses: hawaii-in-paradise/github-actions-learning/.github/workflows/hello-world.yml@gha-v.0.0.1
    with:
      # Add any required inputs here
    secrets: inherit
```

## How to use
- Make sure the `dev` branch is pushed and a tag `gha-v.0.0.1` is created on it.
- In your consuming repository, reference the workflow using the tag as shown above.

## Changelog
- Initial reusable workflow setup for Python Hello World.
