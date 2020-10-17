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
  "appPort": [],
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

## Available version

| Symfony CLI |PHP Version | Container Tag | Status    |
|:-----------:|:----------:|:-------------:|:---------:|
| 4.20.0      | 7.3.23     | 4.20.0        | Published |
