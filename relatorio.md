# Relatório da atividade

## Sumário
1. [Atividade 1](../2025.2-Atividades-04-Tarefas-Estado/relatorio.md#atividade-1)
1. [Atividade 2](../2025.2-Atividades-04-Tarefas-Estado/relatorio.md#atividade-2)
1. [Atividade 3](../2025.2-Atividades-04-Tarefas-Estado/relatorio.md#atividade-3)

## Atividade 1
| tick | SO    | t1         | t2         | t3         | Fila de pr |
| ---- | ----- | ---------- | ---------- | ---------- | ---------- |
| 01   | ex    | --         | --         | --         | --         |
| 02   | ex    | no         | --         | --         | --         |
| 03   | ex    | pr         | no         | --         | t1         |
| 04   | ex    | --         | pr         | no         | t1, t2     |
| 05   | ex t1 | --         | --         | pr         | t2, t3     |
| 06   | --    | ex linha 1 | --         | --         | t2, t3     |
| 07   | ex t2 | su 1       | --         | --         | t2, t3     |
| 08   | --    | su 2       | ex linha 1 | --         | t3         |
| 09   | ex t3 | pr         | su 1       | --         | t1         |
| 10   | --    | --         | su 2       | ex linha 1 | t1         |
| 11   | ex | pr | su 2 | pr | t1, t3 |
| 12   | ex t1 | su 1 | su 2 | pr | t3 |

## Atividade 2
| tick | SO    | t1         | t2         | t3         | Fila de pr |
| ---- | ----- | ---------- | ---------- | ---------- | ---------- |
| 01   | ex    | --         | --         | --         | --         |
| 02   | ex    | no         | --         | --         | --         |
| 03   | ex    | pr         | no         | --         | t1         |
| 04   | ex    | --         | pr         | no         | t1, t2     |
| 05   | ex t1 | --         | --         | pr         | t2, t3     |
| 06   | --    | ex linha 1 | --         | --         | t2, t3     |
| 07   | ex t2 | su 1       | --         | --         | t2, t3     |
| 08   | --    | su 2       | ex linha 1 | --         | t3         |
| 09   | ex t3 | pr         | su 1       | --         | t1         |
| 10   | --    | --         | su 2       | ex linha 1 | t1         |
| 11   | -- | -- |su 2 | ex linha 2 | t1 |
| 12   | -- | pr | su 2 | ex linha 3 | t1 |
## Atividade 3
A tarefa 3 na primeira atividade é interrompida muitas vezes pelo 1 tick para operações, diferentemente na segunda atividade que por poder usar 10 ticks e haver poucas tarefas a serem feitas acaba por executar sem interrupções