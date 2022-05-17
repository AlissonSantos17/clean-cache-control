# Carregar Compras do Cache

> ## Caso de sucesso

1. X Sistema executa o comando "Carregar Compras"
2. X Sistema carrega os dados do Cache
3. X Sistema valida se o Cache tem menos de 3 dias
4. X Sistema cria uma lista de compras a partir dos dados do Cache
5. X Sistema retorna a lista de compras

> ## Exceção - Erro ao carregar dados do Cache

1. X Sistema limpa o Cache
2. X Sistema retorna uma lista vazia

> ## Exceção - Cache expirado

1. X Sistema limpa o Cache
2. X Sistema retorna uma lista vazia

> ## Exceção - Cache vazio

1. X Sistema retorna uma lista vazia
