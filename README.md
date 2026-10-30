# Open Remote - WSL

> **About this fork**
>
> This is a fork of [jeanp413/open-remote-wsl](https://github.com/jeanp413/open-remote-wsl). Many thanks to [jeanp413](https://github.com/jeanp413) for creating the original extension, and to [whoami730](https://github.com/whoami730) for the [WSL scripts contribution](https://github.com/ponces/open-remote-wsl/commit/aca5c2a948c400d7452c9c07220adc63cf736b20).
>
> This fork is published to [Open VSX](https://open-vsx.org/extension/ponces/open-remote-wsl) as `ponces.open-remote-wsl`.

![Open Remote WSL](docs/images/open-remote-wsl.gif)

Uninstall the upstream extension before installing this fork: both provide the same commands and WSL remote resolver.

**Supported**:

- Windows 11 with WSL 2
- Windows 10, May 2021 Update, version 21H1

## Requirements

- `wget` or `curl` needs to be installed in the WSL distro

**Activation**

> NOTE: Not needed in VSCodium since version 1.82

Enable the extension in your `argv.json`


```json
{
    ...
    "enable-proposed-api": [
        ...,
        "ponces.open-remote-wsl",
    ]
    ...
}
```
which you can open by running the `Preferences: Configure Runtime Arguments` command.
The file is located in `~/.vscode-oss/argv.json`.

## Acknowledgments

- [jeanp413](https://github.com/jeanp413) for the original Open Remote - WSL extension.
- [whoami730](https://github.com/whoami730) for the [WSL scripts contribution](https://github.com/ponces/open-remote-wsl/commit/aca5c2a948c400d7452c9c07220adc63cf736b20).
