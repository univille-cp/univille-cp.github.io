+++
title = "0001 - Reunião 14/04/2026"
date = 2026-04-10T12:00:00
searchable = true
+++

<!--more-->

Explicação sobre o problema J de 2025.

```python
linha = input()
# 1 3 5 6
# [1, 3, 5, 6]

# Conjunto estrutura de dados
# set
conjunto = {"1","2","3","4"};

lista = linha.split(" ")
for e in lista:
    # Se tentar remover um elemento que não existe
    # lança uma exceção
    if e in conjunto:
        conjunto.remove(e)
    
print(len(conjunto))
```

Estrutura de dados Conjunto - Set

*  Não permite valores duplicados
*  Acesso rápido aos elementos - O(1)



