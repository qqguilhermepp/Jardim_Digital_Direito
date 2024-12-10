# Variáveis
Variáveis são etiquetas as quais se atribuem valores. Portanto, variáveis são referências a certos valores armazenados na memória.

Variáveis não podem começar com um número.

Variáveis convencionalmente são sempre minúsculas, e se compostas por frases os espaços são substituídos por underscore ("\_")

# String
Combinação de caracteres:

```python
\t  # Adiciona um tab
\n  # Adiciona uma nova linha
```

### Remover prefixo
As strings possuem o método `.removeprefix()` o qual é capaz de remover parte do início da string especificado. Útil para remover um `https:\\` de um link


# Lista
Convencionalmente, listas são nomeadas no plural.

O método `.insert(index, value)` insere um valor em uma lista no index especificado, sem sobrepor os outros itens já presentes, movendo os subsequentes 1 índice para a direita.

E o método `.remove(value)` remove o valor especificado da lista, se encontrado. Se não encontra, resulta em `ValueError`.
Tal método remove apenas a primeira aparição do valor. Se deseja remover todos, será necessário usar um loop.

### `.sort()` e `Sorted()`
O método `.sort()` não retorna nada e organiza a lista, modificando-a permanentemente.
Já a função `Sorted()` retorna a lista organizada, mas sem modificá-la.