# O.S Prime

Sistema desktop enxuto para abertura, acompanhamento, recebimento e entrega de ordens de serviço.

## Versão atual

0.8.16

## Distribuição

- Código-fonte/pacote de continuidade publicado neste repositório.
- Builds de portal devem usar a variante ZERADA, sem dados de teste.
- Builds internos podem usar a variante COM DADOS.

## Licenciamento

- Produto: PRIME_OS
- Ativação por chave.
- Limite comercial configurável de 1 a 5 máquinas, nunca acima de 5.
- Cada instalação usa installation_id persistente e fingerprint hash.
- A ativação registra dispositivo por produto e respeita o limite da licença.
- Desativar a instalação libera a vaga da máquina sem apagar os dados operacionais locais.

## Segurança

O desktop usa apenas configuração pública de conexão e snapshot assinado. Chaves privadas de assinatura e credenciais administrativas não pertencem ao repositório nem ao pacote distribuível.
