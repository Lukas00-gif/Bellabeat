# 📊 Bellabeat — Estudo de Caso de Análise de Dados

## 📌 Sobre o projeto

Este projeto consiste em um estudo de caso de análise de dados da Bellabeat, uma empresa de tecnologia voltada para produtos inteligentes de saúde e bem-estar. Este estudo de caso foi feito durante o curso da coursera Google Data Analytics.

O objetivo é analisar como consumidores utilizam dispositivos inteligentes de monitoramento físico, identificando tendências e comportamentos que possam contribuir para o desenvolvimento de estratégias de marketing da Bellabeat.

A análise utiliza dados públicos de dispositivos Fitbit disponibilizados na plataforma Kaggle.

## 🎯 Objetivos

* Identificar tendências no uso de dispositivos inteligentes.
* Analisar padrões de atividade física e comportamento sedentário.
* Investigar hábitos e padrões relacionados ao sono.
* Identificar horários de maior atividade dos usuários.
* Transformar os resultados em recomendações estratégicas para a Bellabeat.

## 🛠️ Tecnologias e ferramentas

* R: linguagem utilizada para análise dos dados.
* Tidyverse: manipulação, transformação e visualização dos dados.
* Dplyr: tratamento e manipulação de tabelas.
* Ggplot2: criação de gráficos.
* Lubridate: manipulação de datas e horários.
* Corrplot: análise e visualização de correlações.
* Janitor: limpeza e organização dos dados.
* Patchwork: combinação de múltiplos gráficos.

## 📂 Fonte dos dados

Os dados utilizados foram disponibilizados pelo usuário Mobius no Kaggle:
https://www.kaggle.com/code/lukaslima/bellabeat-estudo-de-caso

O conjunto contém informações de monitoramento de atividades físicas, passos, calorias e sono de usuários de dispositivos Fitbit.

### Limitações dos dados
* Amostra pequena de participantes.
* Período de coleta limitado a aproximadamente dois meses.
* Dados coletados em 2016, portanto não representam necessariamente os hábitos atuais dos consumidores.

## 🔎 Etapas da análise

1. Perguntar — Definição do problema

Identificação das tendências de utilização de dispositivos inteligentes e de como elas podem contribuir para as estratégias de marketing da Bellabeat.

2. Preparar — Coleta dos dados

Seleção dos conjuntos de dados públicos do Fitbit disponibilizados no Kaggle.

3. Processar — Limpeza e tratamento
* Correção dos formatos de datas e horários.
* Padronização e renomeação de colunas.
* Identificação e remoção de registros inválidos.
* Verificação de dados ausentes e duplicados.
* Combinação de diferentes conjuntos de dados.

4. Analisar — Análise exploratória

Exploração dos padrões de atividade física, passos, calorias, sono e comportamento sedentário.
Também foram realizadas análises de correlação entre diferentes variáveis.

5. Visualizar — Apresentação dos resultados

Criação de gráficos para facilitar a interpretação dos dados e identificar padrões de comportamento dos usuários.

6. Agir — Recomendações

Desenvolvimento de recomendações estratégicas para a Bellabeat, considerando os padrões identificados durante a análise.

## 📈 Principais descobertas

### 🏃 Atividade física
* Os usuários registraram aproximadamente 8.000 passos por dia, em média.
* O período entre 17h e 19h apresentou os maiores níveis de atividade.
* As atividades leves representam uma parcela importante da rotina dos usuários.

### 😴 Sono
* A análise identificou oportunidades de melhoria na regularidade e duração do sono.
* Foi observada uma correlação negativa moderada entre tempo sedentário e tempo de sono.

### 🪑 Comportamento sedentário
* O comportamento sedentário representa uma parcela significativa do tempo diário.
* Os resultados indicam oportunidades para incentivar pequenas pausas e movimentações ao longo do dia.

### 🔥 Correlações
* Foi identificada uma forte correlação positiva entre minutos de atividade intensa e calorias queimadas.
* Os resultados sugerem uma relação entre hábitos de atividade física e padrões de sono.

## 💡 Recomendações para a Bellabeat

Com base nos resultados, foram propostas algumas estratégias:

1 - Incentivar atividades físicas nos horários em que os usuários já apresentam maior movimentação.

2 - Desenvolver lembretes e recursos para incentivar uma rotina de sono mais consistente.

3 - Estimular pequenas pausas ativas durante períodos prolongados de sedentarismo.

4 - Oferecer informações personalizadas sobre atividade física, sono e bem-estar.

## ▶️ Como visualizar o projeto

O notebook pode ser visualizado diretamente pelo GitHub ou executado em um ambiente compatível com Jupyter Notebook que ofereça suporte a R.
Para executar a análise, é necessário configurar o ambiente R, instalar os pacotes utilizados e disponibilizar os arquivos CSV originais do conjunto de dados.

## 👨‍💻 Autor
Lucas Lima

Estudante de Análise de Dados, interessado em tecnologia, programação e exploração de dados.

GitHub: https://github.com/Lukas00-gif

LinkedIn: https://www.linkedin.com/in/lucas-limab4/

kaggle: https://www.kaggle.com/lukaslima


