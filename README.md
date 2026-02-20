# 📱 Evolução e Transição Tecnológica da Telefonia Móvel no Brasil

## 📌 Sobre o Projeto
Este notebook investiga o histórico de acessos à telefonia móvel no Brasil. A análise tem como foco principal documentar a evolução temporal do volume de linhas ativas e visualizar a transição entre as diferentes gerações de tecnologia (GSM/2G, WCDMA/3G, LTE/4G e M2M). O projeto também traça um panorama geográfico, mapeando a distribuição de acessos por estado em um recorte anual.

## 🗂️ Conjunto de Dados
* **Dados da Anatel:** Base de dados contendo o registro mensal de acessos de telefonia móvel particionado por DDD, tecnologia e ano/mês.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Python 3.12**
* **Pandas:** Conversão de tipos, tratamento de datas e agregações.
* **Seaborn & Matplotlib:** Plotagem de séries temporais e gráficos de barras ordenados.

## 🚀 Metodologia
1. **Engenharia de Features (Séries Temporais):** Transformação das colunas independentes de `ano` e `mes` em um formato unificado de tempo (`datetime`) para viabilizar análises cronológicas.
2. **Evolução Geral:** Agrupamento e soma de todos os acessos mensais no Brasil, ajustando a escala de visualização para "milhões" para facilitar a interpretação.
3. **Filtro Tecnológico:** Seleção das principais tecnologias de rede e plotagem de múltiplas linhas no mesmo eixo temporal para observar a "morte" de tecnologias antigas (ex: GSM) e a ascensão de novas (ex: LTE).
4. **Ranking Estadual:** Recorte transversal dos dados para o ano de 2020, agregando o volume total de acessos por UF e criando um ranking visual decrescente.

## 📊 Principais Resultados
As visualizações produzidas ilustram perfeitamente o ciclo de vida das tecnologias de telecomunicação no Brasil, além de evidenciar a concentração do mercado consumidor nos estados com maior densidade populacional.
