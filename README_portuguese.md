# Previsão do Tempo de Entrega de Alimentos em Delhi com XGBoost

## Descrição do Projeto

Este projeto tem como objetivo determinar fatores que influenciam o tempo de entrega de alimentos em Delhi, Índia, utilizando o algoritmo XGBoost. O modelo é treinado com um conjunto de dados do Kaggle contendo informações sobre pedidos de alimentos, como valor do pedido, taxa de entrega, comissões, custos de processamento de pagamento, reembolsos, descontos e tempo de entrega.

## Problema

O projeto original focava em um contexto hospitalar, mas este projeto expande a análise para o cenário de entrega de alimentos em Delhi. O objetivo é entender os fatores que influenciam o tempo de entrega e construir um modelo que ajude a gerar insights para melhorar o desempenho no tempo de entrega com maior precisão.

## Abordagem

O projeto utiliza o algoritmo XGBoost para construir um modelo preditivo. Os dados são pré-processados e divididos em conjuntos de treinamento e teste. O modelo é avaliado com base em métricas como R² e RMSE.

## Resultados

O modelo XGBoost apresentou um desempenho promissor na previsão do tempo de entrega, com um R² de 0.45 na validação. As features mais importantes para o modelo foram a hora da entrega, o valor do pedido e a taxa de comissão.

## Limitações

O projeto possui algumas limitações, como a falta de dados sobre o trânsito e as condições climáticas, que podem influenciar o tempo de entrega. Além disso, o modelo foi treinado com um conjunto de dados específico de Delhi e pode não ser generalizável para outras cidades.

## Como usar

1. Clone o repositório: `git clone <url_do_repositorio>`
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o notebook: `jupyter notebook`

### **Contato**
- Nome: Davi
- Email: davirjr@gmail.com
- LinkedIn: [https://linkedin.com/in/seu-perfil](https://www.linkedin.com/in/davi-rodrigues-junior-b1b822b4/)
