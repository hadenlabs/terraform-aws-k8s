<!-- Space: Projects -->
<!-- Parent: TerraformAwsK8s -->
<!-- Title: TerraformAwsK8s Releasing -->

<!-- Label: TerraformAwsK8s -->
<!-- Label: Project -->
<!-- Label: Releasing -->
<!-- Include: docs/disclaimer.md -->
<!-- Include: ac:toc -->

# Releasing

## Bump a new version

Make a new version of terraform-aws-k8s in the following steps:

### Generate version major

```bash
task version:major
```

### Generate version minor

```bash
task version:minor
```

### Generate version patch

```bash
task version:patch
```

## Generate Changelog

### Generate Changelog Next Tag

```bash
task changelog:next APP_TAG={{tag}}
```

#### Parameters

| Name     | Description   | sample | Required |
| -------- | ------------- | ------ | :------: |
| tag name | Name next tag | 0.1.0  |   yes    |

### Generate Changelog Tag Now

```bash
task changelog:tag
```
