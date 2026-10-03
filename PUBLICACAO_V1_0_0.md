# Publicação do O.S Prime v1.0.0

Estado preparado para lançamento comercial.

- Produto: `PRIME_OS`
- Versão: `1.0.0`
- Ambiente: `production`
- Canal: `stable`
- Tag: `v1.0.0`
- Instalador esperado: `OSPrime_1.0.0_Setup.exe`

## Publicação

1. Gerar o instalador pelo `GERAR_INSTALADOR_PRODUCAO_FINAL.bat` do pacote-fonte final.
2. Testar instalação limpa, ativação, limite de máquinas, funcionamento offline e atualização preservando `data/os_prime.db`.
3. Criar a GitHub Release `v1.0.0` com título `O.S Prime v1.0.0`.
4. Anexar `OSPrime_1.0.0_Setup.exe`, `SHA256_OSPrime_1.0.0.txt` e `release_manifest.json`.
5. Marcar como latest release e não marcar como pre-release.
6. Somente depois do asset estar disponível, ativar o registro `PRIME_OS` `1.0.0` em `app_releases` com o SHA-256 final.

URL esperada do instalador:

`https://github.com/wctechouse-ctrl/O.S-Prime/releases/download/v1.0.0/OSPrime_1.0.0_Setup.exe`

> O arquivo `OSPrime_0.9.4_RC_Setup.exe` é apenas a candidata anterior e não deve ser publicado como a versão final 1.0.0.
