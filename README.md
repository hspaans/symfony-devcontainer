# Devcontainer for Symfony

## Using within you project

Add `.devcontainer/devcontainer.json` to your repository.

```json
{
  "image": "ghcr.io/hspaans/symfony-devcontainer:latest",
  "name": "Symfony",
  "settings": {
    "terminal.integrated.shell.linux": "/bin/bash"
  },
  "appPort": [8000],
  "postCreateCommand": "",
  "remoteUser": "vscode",
  "extensions": [
    "github.vscode-pull-request-github",
    "editorconfig.editorconfig",
    "felixfbecker.php-debug",
    "felixfbecker.php-intellisense",
    "ikappas.composer",
    "redhat.vscode-yaml"
  ]
}
```
