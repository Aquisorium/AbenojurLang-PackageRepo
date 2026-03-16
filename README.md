# Abenojur Package Registry

Este repositorio guarda os pacotes distribuidos pelo ecossistema do Aben.

Estrutura:

- `repolist.json`: indice oficial de pacotes e versoes
- `packages/`: arquivos `.zip` prontos para instalacao

Formato de versao:

- `1-0-0`

Pacotes iniciais:

- `harborweb` -> alias `harbor`
- `stdcore` -> alias `stdcore`
- `stdsystem` -> alias `stdsystem`
- `stdnet` -> alias `stdnet`
- `cryptokit` -> alias `cryptokit`
- `winbridge` -> alias `winbridge`

Exemplos de uso:

- `aben get harborweb`
- `aben get stdcore`
- `aben get winbridge 1-0-0`

Depois da instalacao, o projeto pode importar:

- `import "harbor/harbor.abj";`
- `import "stdcore/prelude.abj";`
- `import "stdnet/http.abj";`
- `import "cryptokit/crypto.abj";`
- `import "winbridge/winapi.abj";`