# 🧩 Projeto de Segmentação de Clientes

Este projeto tem como objetivo aplicar **técnicas de clusterização** para segmentar clientes da Olist, possibilitando uma melhor **tomada de decisão em estratégias de marketing** e personalização de campanhas.

---

## 🎯 Objetivos
- Explorar e tratar dados reais de clientes da Olist.  
- Aplicar técnicas de **Machine Learning não supervisionado** (ex.: K-Means, DBSCAN, etc.).  
- Gerar insights sobre os diferentes **perfis de clientes**.  
- Apoiar estratégias de **marketing orientado a dados**.  

---

## 📂 Estrutura do Projeto

   ```├── LICENSE
   ├── Makefile
   ├── data
   │ ├── external <- Dados de terceiros
   │ ├── interim <- Dados intermediários processados
   │ ├── processed <- Dados finais prontos para modelagem
   │ └── raw <- Dados brutos originais
   ├── docs <- Documentação
   ├── models <- Modelos treinados e serializados
   ├── notebooks <- Jupyter Notebooks de exploração e modelagem
   ├── references <- Dicionários de dados, manuais, relatórios
   ├── reports
   │ └── figures <- Gráficos e visualizações geradas
   ├── requirements.txt <- Dependências necessárias
   ├── setup.py <- Script de instalação do projeto
   └── src <- Código fonte do projeto
   ├── data <- Scripts para download e tratamento dos dados
   
   
   ---
   ```
   
   ## ⚙️ Como Rodar o Projeto
   
   1. **Clone o repositório**
      ```bash
      git clone https://github.com/Maria-Navarro-MN/customer_segmentation.git
      cd customer_segmentation
   
   ```python -m venv venv
      source venv/bin/activate   # Linux/Mac
      venv\Scripts\activate      # Windows
   ```
   ```
      pip install -r requirements.txt
   ```
   
   ```jupyter notebook
   
   ├── features <- Scripts para engenharia de atributos
   ├── models <- Scripts de treinamento e predição
   └── visualization <- Scripts para visualização
   ```
   - Tecnologias Utilizadas
   
   ```Python 3
   
   Pandas / NumPy – manipulação de dados
   
   Scikit-learn – algoritmos de clusterização e métricas
   
   Matplotlib / Seaborn / Plotly – visualização
   
   Jupyter Notebook – experimentação e análise
   ```
   - Próximos Passos
   
    ```Análise exploratória dos dados (EDA)
   
    Pré-processamento e normalização
   
    Testes com diferentes algoritmos de clusterização
   
    Interpretação dos clusters e recomendações de negócio


