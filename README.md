# Abenojur Package Registry

This repository stores public packages for the Abenojur ecosystem.

## Structure

- `repolist.json`: official package and version index
- `packages/`: installable `.zip` archives

## Version Format

- `1-0-0`

## Published Packages

- `harborweb` -> alias `harbor`
- `stdcore` -> alias `stdcore`
- `stdsystem` -> alias `stdsystem`
- `stdnet` -> alias `stdnet`
- `cryptokit` -> alias `cryptokit`
- `winbridge` -> alias `winbridge`

## Usage

```powershell
aben get harborweb
aben get stdcore
aben get winbridge 1-0-0
```

After installation, a project can import packages like:

```abj
import "harbor/harbor.abj";
import "stdcore/prelude.abj";
import "stdnet/http.abj";
import "cryptokit/crypto.abj";
import "winbridge/winapi.abj";
```
