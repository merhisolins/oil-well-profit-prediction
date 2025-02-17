# Oil Well Profit Prediction

**Descrição**
Este projeto tem como objetivo encontrar as melhores regiões para o desenvolvimento de novos poços de petróleo, utilizando modelos preditivos para estimar o volume de reservas e selecionar os locais mais lucrativos.

A análise envolve a previsão do volume de extração, a escolha dos melhores poços e a avaliação de riscos financeiros através da técnica de **Bootstrapping**.

---

##  Conjunto de Dados

Os dados de exploração geológica abrangem três regiões e contêm as seguintes colunas:

- **id**: Identificador único do poço de petróleo.
- **f0, f1, f2**: Três características geológicas do poço.
- **product**: Volume de reservas de petróleo no poço (milhares de barris).

Arquivos utilizados:
- `geo_data_0.csv`
- `geo_data_1.csv`
- `geo_data_2.csv`

---

## Etapas do Projeto

1️⃣ **Leitura e exploração dos dados**  
 Carregamento dos conjuntos de dados e análise das variáveis.  

2️⃣ **Construção do modelo preditivo**  
 Desenvolvimento de um modelo de Machine Learning para prever a reserva de petróleo.  

3️⃣ **Seleção dos poços mais lucrativos**  
 Identificação dos locais com maior potencial de extração.  

4️⃣ **Análise de lucro e risco**  
 Aplicação de **Bootstrapping** para estimar o lucro e avaliar riscos.  

---

## Tecnologias Utilizadas

- **Python 3.8+** - Linguagem principal
- **Pandas / NumPy** - Manipulação e análise de dados
- **Matplotlib / Seaborn** - Visualização de dados
- **Scikit-Learn** - Modelagem preditiva
- **Bootstrap Sampling** - Análise de incerteza e risco
