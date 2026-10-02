# O.S Prime

O.S Prime é o sistema do ecossistema Prime voltado para assistência técnica e gerenciamento de ordens de serviço.

## Versão atual

**v1.0.0 — FINAL / PRODUCTION / liberado para venda**

Principais recursos:
- ordens de serviço com fluxo guiado e edição completa;
- clientes e aparelhos/equipamentos;
- produtos e serviços;
- orçamentos com conversão para O.S.;
- prestadores/funcionários;
- caixa, pagamentos e histórico;
- impressão e acompanhamento da O.S.;
- backup, importação/migração e exclusão seletiva de dados;
- licenciamento online em Production, de 1 a 5 máquinas;
- licença temporária de avaliação de 15 ou 30 dias;
- instalador Windows preservando o banco do cliente em atualizações.

## Licenciamento

Produto: `PRIME_OS`.

A v1.0.0 aceita:
- licença própria do O.S Prime;
- O.S Prime concedido como produto vinculado a uma licença PrimeSystem;
- licença temporária independente, sem cliente/e-mail obrigatório, cujo prazo começa na primeira ativação.

## Código-fonte

O pacote fonte oficial da versão está em `releases/OS_PRIME_v1_0_0_FINAL_SOURCE.zip`.

Python 3.11 + PySide6. Para executar pelo código-fonte, instale `requirements.txt` e execute `main.py`.

Para gerar o instalador comercial no Windows, use `GERAR_INSTALADOR_PRODUCAO_FINAL.bat`. O build usa PyInstaller e Inno Setup 6.

## Dados

O banco SQLite do cliente não é versionado no Git. Instalações e atualizações preservam `data/os_prime.db`.
