# Renovate Configuration Repo

This repository hosts centralized Renovate configuration for the entire GitHub organization's projects.

## Configuration Details

The repository currently includes:

- `default.json` - The main configuration file that defines how Renovate should manage argocd dependencies

### Current Configuration Features

- **ArgoCD Integration**: Configured to recognize ArgoCD YAML files in specific directories

## How to Use

Other repositories in the can inherit this configuration by referencing it in their own Renovate configuration:

```json
{
  "extends": ["github>giraffacorp/renovate-config"]
}
```

