# gh alerts

[GitHub CLI](https://github.com/cli/cli) extension for viewing security alerts. 

## Installation
```bash
gh extension install securesauce/gh-alerts
```

## Usage
```bash
gh alerts [-h] [-o ORG_NAME] [PACKAGE_NAME]
```

## Examples
```bash
gh alerts pyyaml
PACKAGE  SEVERITY       MANIFEST
pyyaml   high severity  requirements.txt
pyyaml   high severity  requirements.txt
```
