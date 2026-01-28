# Carteira no Bitcoin Core (Regtest)

## O que é uma carteira

Uma carteira no Bitcoin não é uma conta bancária.
Ela é um conjunto de chaves privadas que permitem
controlar bitcoins (UTXOs).

A carteira:
- gera endereços
- recebe bitcoins
- assina transações

No regtest, a carteira existe apenas localmente
e serve para estudo e testes.

---

## Comandos utilizados

Ver saldo da carteira:
```bash
bitcoin-cli -regtest getbalance
