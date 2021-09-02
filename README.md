# gh alerts

[GitHub CLI](https://github.com/cli/cli) extension for viewing security alerts. 

## Installation
```bash
gh extension install ericwb/gh-alerts
```

## Usage
```bash
gh alerts [-h | --help] [<package>]
```

## Examples
```bash
gh alerts pyyaml
PACKAGE  SEVERITY       MANIFEST
pyyaml   high severity  requirements.txt
pyyaml   high severity  requirements.txt
```
