# Abenojur Package Registry

Este repositório guarda os pacotes distribuídos pelo ecossistema do Aben.

Estrutura atual:

- `repolist.json`: índice oficial de pacotes e versões
- `packages/`: arquivos `.zip` prontos para instalação

Formato de versão:

- `1-0-0`

Importação no projeto:

- o pacote `harborweb` instala com alias `harbor`
- depois do install, o projeto pode usar `import "harbor/harbor.abj";`
