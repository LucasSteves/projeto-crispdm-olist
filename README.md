# 🛒 Análise Preditiva - E-commerce Brasileiro (Olist)

Este repositório contém o projeto desenvolvido para a disciplina de Ciência de Dados. O objetivo principal é aplicar de ponta a ponta a metodologia **CRISP-DM** (Cross-Industry Standard Process for Data Mining) utilizando um conjunto de dados reais do mercado brasileiro.

## 📊 Sobre o Dataset
O conjunto de dados escolhido foi o **Brazilian E-Commerce Public Dataset by Olist**, disponível publicamente no Kaggle. Ele contém informações de cerca de 100.000 pedidos realizados entre 2016 e 2018 em diversos marketplaces no Brasil.

- **Fonte:** [Kaggle - Olist Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Área:** Mercado / E-commerce
- **Tarefa Principal:** Classificação preditiva (ex: prever atrasos de entrega ou notas de avaliação dos clientes).

## ⚙️ Metodologia: O Ciclo CRISP-DM
O projeto está estruturado de acordo com as 6 fases do modelo CRISP-DM:

1. **Entendimento do Negócio (Business Understanding):** Definição do problema, objetivos do projeto e critérios de sucesso.
2. **Entendimento dos Dados (Data Understanding):** Coleta, exploração inicial, análise de qualidade e identificação de padrões.
3. **Preparação dos Dados (Data Preparation):** Limpeza, tratamento de valores nulos, integração das tabelas relacionais e engenharia de features.
4. **Modelagem (Modeling):** Seleção de algoritmos de Machine Learning, separação de dados de treino/teste e ajuste de hiperparâmetros.
5. **Avaliação (Evaluation):** Análise dos resultados do modelo frente aos objetivos de negócio (Métricas: Acurácia, F1-Score, Matriz de Confusão, etc.).
6. **Implantação (Deployment):** Conclusões finais, relatórios e possíveis aplicações práticas dos resultados.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python
- **Manipulação e Análise de Dados:** Pandas, NumPy
- **Visualização de Dados:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn

## 📁 Estrutura do Repositório
- `/data`: Diretório para os datasets originais e processados.
- `/notebooks`: Cadernos Jupyter contendo o código e a análise passo a passo de cada fase do CRISP-DM.
- `/docs`: Documentação adicional e apresentações do grupo.
