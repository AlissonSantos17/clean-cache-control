# Gravar Compras no Cache

> ## Caso de sucesso

1. X Sistema executa o comando "Salvar Compras"
2. X Sistema cria data uma data para ser armazenada no Cache
3. X Sistema apaga os dados do Cache atual
4. X Sistema grava os novos dados do Cache
5. X Sistema não retorna nenhum erro

> ## Exceção - Erro ao apagar dados do Cache

1. X Sistema não grava os novos dados do Cache
2. X Sistema retorna erro

> ## Exceção - Erro ao gravar dados do Cache

1. X Sistema retorna erro
