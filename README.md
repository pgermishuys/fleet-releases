# Fleet

Installable Fleet server builds.

## Install

### macOS/Linux

```bash
curl -fsSL https://github.com/pgermishuys/fleet-releases/releases/latest/download/install.sh | sh
export PATH="$HOME/.weave/fleet/bin:$PATH"
fleet version
```

### Windows

```powershell
irm https://github.com/pgermishuys/fleet-releases/releases/latest/download/install.ps1 | iex
fleet version
```

## Run

`fleet` starts the server on `http://127.0.0.1:5000`

## Common commands

- `fleet version`
- `fleet update`
- `fleet uninstall`
