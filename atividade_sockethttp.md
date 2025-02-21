# Resultados da Execução do Servidor

## Quais foram os resultados observados ao executar o servidor sem thread?
- O servidor processa as requisições de forma sequencial.
- O tempo de resposta aumenta conforme o número de clientes simultâneos.

## Quais foram os resultados observados ao executar o servidor com thread?
- O servidor processa múltiplas requisições simultaneamente.
- O tempo de resposta permanece constante mesmo com vários clientes.

## Houve alguma diferença no tempo de resposta entre os dois servidores?
- Sim, o servidor sem thread apresenta tempos de resposta maiores com múltiplos clientes.
- O servidor com thread mantém um tempo de resposta mais rápido e constante.

## O que acontece quando vários clientes tentam acessar o servidor sem thread ao mesmo tempo?
- As requisições são processadas uma por vez, causando filas e atrasos.

## O que acontece quando vários clientes tentam acessar o servidor com thread ao mesmo tempo?
- O servidor cria uma thread para cada requisição, permitindo atendimento simultâneo.