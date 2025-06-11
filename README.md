# 📈 Portfólio de Estudos de Caso em Ciência de Dados

Bem-vindo(a) ao meu portfólio de projetos e estudos de caso em Ciência de Dados! Este repositório reúne análises e modelos desenvolvidos em Python, utilizando ferramentas como Pandas, NumPy, Scikit-learn, Matplotlib e Seaborn. Os projetos abordam diferentes desafios, desde detecção de fraudes até previsão de óbitos e valores de aluguel, demonstrando habilidades em pré-processamento de dados, modelagem preditiva e avaliação de desempenho.

---

## 📁 Estrutura do Repositório

Os estudos de caso estão disponíveis como arquivos Jupyter Notebook (com extensão `.ipynb`) diretamente na raiz deste repositório. Os datasets utilizados em cada projeto são referenciados abaixo.

---

## 🚀 Estudos de Caso

### 1. Detecção de Transações Fraudulentas

* **Objetivo:** Desenvolver um modelo de Machine Learning capaz de prever se uma transação financeira é fraudulenta.
* **Modelos Utilizados:** K-Nearest Neighbors (KNN), Árvore de Decisão e Regressão Logística.
* **Resultados Principais:** A **Árvore de Decisão** demonstrou o melhor equilíbrio entre precisão e recall para identificar transações fraudulentas, sendo a opção mais viável para este problema. Embora a Regressão Logística tenha tido um alto recall, sua precisão foi muito baixa, enquanto o KNN apresentou a menor performance geral.
* **Notebook:** Detecção de Transações Fraudulentas
* **Dataset Original:** [Fraud Transaction Detection Dataset](https://www.kaggle.com/code/llabhishekll/fraud-transaction-detection/input)

---

### 2. Previsão de Cancelamento de Reservas em Hotéis

* **Objetivo:** Desenvolver um modelo de Machine Learning para prever o cancelamento de reservas em hotéis, auxiliando na gestão e otimização de recursos.
* **Modelo Utilizado:** Regressão Logística.
* **Resultados Principais:** O modelo alcançou uma acurácia geral de **82%**. Embora tenha demonstrado alta capacidade de identificar reservas que *não* seriam canceladas (recall de 91%), a detecção de cancelamentos reais (recall de 67%) ainda apresenta espaço para melhoria. Recomenda-se explorar ajustes de *threshold*, técnicas de balanceamento de dados ou outros modelos para otimizar a sensibilidade para a classe de cancelamento.
* **Notebook:** Previsão de Cancelamento de Reservas em Hotéis.ipynb
* **Dataset Original:** [Hotel Booking Demand Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand/data)

---

### 3. Previsão de Aluguel de Imóveis

* **Objetivo:** Criar um modelo de Machine Learning capaz de prever o valor de aluguel de imóveis, com base em suas características.
* **Modelo Utilizado:** Regressão Linear.
* **Resultados Principais:** O modelo obteve uma acurácia de **93%**, indicando uma boa capacidade preditiva para o valor de aluguel. As features mais importantes para essa previsão incluíram a **área do imóvel, o número de banheiros e o número de quartos**. Este modelo pode ser uma ferramenta valiosa tanto para proprietários que desejam precificar seus imóveis quanto para inquilinos em busca de avaliações justas.
* **Notebook:** previsao_aluguel_imoveis
* **Dataset:** `dados_apartamentos.csv` (disponível neste repositório)

---

### 4. Previsão de Óbitos por COVID-19

* **Objetivo:** Desenvolver modelos preditivos para estimar o número de óbitos por COVID-19.
* **Modelos Utilizados:** Regressão Linear, Árvore de Decisão e Random Forest.
* **Resultados Principais:** O modelo de **Random Forest** demonstrou o melhor desempenho, alcançando uma acurácia de **97.6%** e o menor Erro Médio Absoluto (MAE), o que sugere uma excelente capacidade de generalização e precisão nas previsões de óbitos.
* **Notebook:** previsao_obitos_covid
* **Dataset:** `Dados_Covid_-_Regress_o_Linear.csv` (disponível neste repositório)

---

## 🛠 Tecnologias Utilizadas

* `Python`
* `Pandas`
* `NumPy`
* `Scikit-learn`
* `Matplotlib`
* `Seaborn`
* `Jupyter Notebook / Google Colab`

---

## ✉️ Contato

Para qualquer dúvida ou colaboração, sinta-se à vontade para entrar em contato:

* **Lucas David:** [LinkedIn](https://www.linkedin.com/in/lucas-david-carvalho-vieira-de-matos-9a461524a/)

---
