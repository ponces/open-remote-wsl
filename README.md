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

## Activation

> [!IMPORTANT]
> Unlike the upstream extension, this fork requires you to explicitly enable proposed APIs for `ponces.open-remote-wsl`, including on VSCodium 1.82 and later.

Run **Preferences: Configure Runtime Arguments** and add this fork's extension ID to `enable-proposed-api` in your `argv.json`, preserving any existing entries:

```json
{
    "enable-proposed-api": [
        "ponces.open-remote-wsl"
    ]
}
```

Restart the editor after saving the file.

## Acknowledgments

- [jeanp413](https://github.com/jeanp413) for the original Open Remote - WSL extension.
- [whoami730](https://github.com/whoami730) for the [WSL scripts contribution](https://github.com/ponces/open-remote-wsl/commit/aca5c2a948c400d7452c9c07220adc63cf736b20).
