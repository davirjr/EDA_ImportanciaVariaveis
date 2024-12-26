# EDA_ImportanciaVariaveis_EntregaMedicamentos

## Descrição do Projeto

Este projeto visa aprimorar o indicador e a análise crítica do tempo de entrega de medicamentos urgentes em um hospital, alinhando-o ao pensamento data-driven para aumentar a eficiência operacional e melhorar a experiência do paciente. A análise inicial revelou limitações significativas no método atual, que utiliza a mediana para avaliar os tempos de entrega, resultando em análises superficiais e pouco detalhadas.

Para solucionar esse problema, foi implementado um modelo que associa LightGBM e a análise do terceiro quartil com EWMA. O LightGBM é utilizado para identificar as variáveis críticas que influenciam o processo, determinando sua importância com base na variação que elas causam no tempo de entrega. Essas variáveis incluem horários de geração e entrega dos pedidos, setor de prescrição e usuário responsável pela entrega. A análise do terceiro quartil com EWMA fornece uma visão clara dos horários e dias críticos, permitindo discussões mais informadas com a equipe.

Com essa abordagem, os dados são transformados em insights acionáveis, promovendo um ciclo contínuo de melhorias e elevando o processo à maturidade analítica. O indicador evoluiu de um estado de maturidade inicial, onde se media apenas a mediana do tempo de entrega, para um estado avançado, incluindo variáveis críticas, análises estatísticas detalhadas, e uso de técnicas avançadas de machine learning, proporcionando uma visão mais completa e precisa do desempenho e permitindo uma gestão mais eficaz e proativa dos processos.


## Etapas do Projeto

1. **Coleta e Preparo dos Dados:** Os dados foram extraídos do sistema Tasy e passaram por um processo de limpeza e transformação.
2. **Análise Exploratória de Dados (EDA):** Foi realizada uma análise exploratória dos dados para entender a distribuição, tendências e relações entre as variáveis, utilizando técnicas como histogramas, boxplots e testes de normalidade.
3. **Modelagem com LightGBM:** O algoritmo LightGBM foi utilizado para treinar um modelo preditivo para o tempo de entrega, identificando as variáveis mais importantes que influenciam o processo.
4. **Avaliação do Modelo:** O modelo foi avaliado utilizando métricas de desempenho, como R² e RMSE.
5. **Visualização e Interpretação:** Os resultados da análise exploratória e da modelagem foram visualizados em gráficos e interpretados para identificar insights e oportunidades de otimização.


## Resultados

* As variáveis mais importantes que influenciam o tempo de entrega foram identificadas, como horários de geração e entrega dos pedidos, setor de prescrição e usuário responsável pela entrega.
* Insights sobre a relação entre as variáveis e o tempo de entrega foram obtidos, permitindo uma melhor compreensão do processo.
* Oportunidades de otimização do processo de entrega de medicamentos foram identificadas, como a otimização dos horários de entrega e a alocação de recursos.


## Conclusões

Este projeto demonstrou o potencial da análise exploratória de dados e da modelagem preditiva com LightGBM para otimizar o tempo de entrega de medicamentos urgentes em um hospital. Os resultados obtidos podem ser utilizados para melhorar a eficiência operacional, reduzir atrasos e aprimorar a experiência do paciente.


## Próximos Passos

* Implementar as otimizações identificadas no projeto em conjunto com a equipe do hospital.
* Monitorar os resultados e realizar ajustes conforme necessário.
* Expandir a análise para outros tipos de medicamentos e setores do hospital.
* Desenvolver um dashboard interativo para visualização dos dados e insights.

### **Contato**
- Nome: Davi
- Email: davirjr@gmail.com
- LinkedIn: [https://linkedin.com/in/seu-perfil](https://www.linkedin.com/in/davi-rodrigues-junior-b1b822b4/)
