# scoop-oliver — Scoop bucket for Oliver (Windows)

Scoop bucket for **Oliver (AskWashU APIM Explorer)**. The manifest
(`bucket/oliver.json`) is kept current by `release-to-pkgs.sh` and points at the
Windows zip mirrored on `ta-tools/oliver-release`.

## Install

```powershell
scoop bucket add ta-tools https://github.com/ta-tools/scoop-oliver
scoop install oliver
```

## Update / uninstall

```powershell
scoop update oliver
scoop uninstall oliver
```
