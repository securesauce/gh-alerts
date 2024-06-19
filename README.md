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
gh alerts

# glob-parent  high severity    package-lock.json    https://github.com/advisories/GHSA-ww39-953v-wcq6
# braces       high severity    package-lock.json    https://github.com/advisories/GHSA-grv7-fg5c-xmjg
# ws           high severity    package-lock.json    https://github.com/advisories/GHSA-3h5v-q93c-6h6q
```
