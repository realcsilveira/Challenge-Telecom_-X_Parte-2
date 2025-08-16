## Challenge Telecom X: Análise de Evasão de Clientes - Parte 2

Este repositório apresenta a solução desenvolvida para o Challenge Telecom X: Análise de Evasão de Clientes - Parte 2 , com foco na análise preditiva de evasão de clientes. O projeto utiliza técnicas de Machine Learning para identificar os principais fatores que influenciam o cancelamento dos serviços, apoiando na tomada de decisões estratégicas para retenção de clientes.

<br/>

## Objetivo

A Telecom X enfrenta um elevado índice de cancelamentos e tem como objetivo:

- Coletar, tratar e preparar os dados de clientes para garantir consistência e qualidade da informação;
- Analisar e explorar os dados a fim de compreender padrões e comportamentos relevantes;
- Desenvolver modelos preditivos capazes de identificar clientes com maior probabilidade de evasão;
- Gerar insights estratégicos que auxiliem na redução da evasão e no fortalecimento da retenção de clientes.

<br/>

## Preparação e Tratamento de Dados

As principais etapas do projeto envolveram a importação e tratamento dos dados, incluindo a transformação de variáveis categóricas e numéricas, além da remoção de valores ausentes e padronização das informações. Em seguida, foi realizada uma análise de correlação para identificar e excluir variáveis redundantes, garantindo maior eficiência na modelagem. Por fim, os dados foram devidamente preparados para a construção dos modelos preditivos.

<br/>

## Análise Exploratória de Dados e Modelagem Preditiva

- Proporção de evasão: aproximadamente 25,8% dos clientes cancelaram os serviços.
- Modelos avaliados: Regressão Logística, Random Forest e um modelo de referência (Random).
- Melhor desempenho: o modelo de Regressão Logística apresentou acurácia de 79,96%, precisão de 65,44%, recall de 52,14% e F1-score de 58,04%.
- Variáveis mais relevantes para previsão de evasão:
  - Tempo de contrato: clientes com contratos mais curtos apresentam maior risco de cancelamento;
  - Valor mensal: mensalidades mais elevadas estão associadas a maior probabilidade de evasão;
  - Serviços adicionais: recursos como segurança online e backup também exercem influência significativa.

<br/>

## Ações Estratégicas Sugeridas

- Implementar ações de retenção personalizadas, especialmente voltadas a clientes com contratos de curta duração e mensalidades mais elevadas;
- Oferecer pacotes promocionais e descontos progressivos, incentivando maior fidelização e permanência no serviço;
- Adotar o modelo de Regressão Logística em monitoramento contínuo, permitindo identificar clientes com maior risco de evasão e realizar intervenções proativas.

<br/>

## Stack Tecnológico

- Linguagem de Programação: Python 3.10+
- Manipulação e Análise de Dados: Pandas, NumPy
- Machine Learning: Scikit-learn
- Visualização de Dados: Matplotlib, Seaborn
- Ambientes de Desenvolvimento: Google Colab, VSCode

