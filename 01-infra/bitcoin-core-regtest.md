# Bitcoin Core em Regtest

Este documento registra a configuração inicial do Bitcoin Core
rodando em modo regtest.

## Objetivo

Usar um ambiente local e controlado para:
- entender blockchain
- entender mineração
- entender UTXOs
- evitar dependência de rede externa

## Estado inicial do nó

No regtest, o blockchain começa vazio (blocks = 0).

Exemplo:

```json
{
  "chain": "regtest",
  "blocks": 0
}
