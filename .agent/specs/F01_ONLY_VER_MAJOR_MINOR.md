## Feature 01 - Support only MAJOR-MINOR version elements

When deploy project documentation i want that only version element major and minor must be taken in consideration.

This means that when a tag `v1.0.5` is created the deployed version must be `1.0` and the content will be replaced by `v1.0.5` one.

Update `deploy-docs.yml` github action accordly
