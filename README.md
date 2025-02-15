# **AI Candlestick – Previsão de Altas e Baixas no Mercado Financeiro**

Este projeto aplica técnicas de **Inteligência Artificial** para identificar e prever possíveis movimentos de alta e baixa no mercado financeiro, oferecendo insights valiosos para a tomada de decisões de compra e venda de ativos, com base em dados históricos e na análise de padrões de candlestick.

---

## **Sumário**

1. [Descrição do Projeto](#descrição-do-projeto)  
2. [Principais Funcionalidades](#principais-funcionalidades)  
3. [Tecnologias e Ferramentas](#tecnologias-e-ferramentas)  
4. [Como Executar](#como-executar)  
5. [Organização dos Arquivos](#organização-dos-arquivos)  
6. [Contribuições](#contribuições)  
7. [Licença](#licença)  
8. [Agradecimentos](#agradecimentos)

---

## **Descrição do Projeto**

O **AI Candlestick** tem como foco o estudo de dados de mercado (abertura, fechamento, máxima, mínima e variações de cada candle) para prever possíveis ciclos de alta e baixa. Através de algoritmos de Machine Learning, métodos de clustering (K-Means e GMM) e modelagem de Markov, o projeto contribui para:
- **Detecção de reversões** de tendência.  
- **Minimização de riscos** em operações financeiras.  
- **Identificação de oportunidades** de compra e venda.  

---

## **Principais Funcionalidades**

- **Coleta & Pré-Processamento**: Limpeza, normalização e tratamento de dados históricos de mercado.  
- **Análise de Candles**: Uso de indicadores técnicos (Body, Sombras, Máxima, Mínima, etc.) para entender padrões dos candles.  
- **Clustering & Modelagem de Markov**: Segmentação de comportamentos em clusters e uso de probabilidades de transição para prever estados de mercado.  
- **Visualização**: Gráficos interativos (Plotly, Seaborn, Matplotlib) para identificação imediata de padrões e reversões.  
- **Detecção de Pontos Críticos**: Indicação de possíveis pontos de reversão (altas/baixas) para reforçar decisões de investimento.

---

## **Tecnologias e Ferramentas**

- **Python**: Linguagem principal para manipulação de dados e desenvolvimento de algoritmos de IA.  
- **Bibliotecas de Data Science**:  
  - **pandas**, **numpy**, **scikit-learn** para pré-processamento, modelagem de Machine Learning e estatística.  
  - **matplotlib**, **seaborn**, **plotly** para criação de visualizações e gráficos interativos.  
- **Algoritmos de Machine Learning**:  
  - **K-Means**, **GMM** para clustering.  
  - **Modelo de Markov** para analisar transições de estados de mercado.  
- **Git/GitHub**: Gerenciamento de versionamento e colaboração no desenvolvimento do projeto.

---

## **Como Executar**

1. **Clonar o repositório**  
   ```bash
   git clone https://github.com/Leticia-Gobbi88/candlestick.git
   cd candlestick
   
2. **Criar ou ativar o ambiente virtual (opcional, mas recomendado)**  
   ```bash
   python -m venv venv
   source venv/bin/activate     # Linux/Mac
   venv\Scripts\activate        # Windows
   
 3. **Instalar as dependencias**  
    ```bash
    pip install -r requirements.txt

 4. **Executar o script principal (exemplo)**  
    ```bash
    python main.py

  5. **Verificar resultados:**
    -  O script pode gerar gráficos interativos e relatórios estatísticos.
    - Analise clusters, probabilidades de transição (Markov), e pontos de reversão destacados.


## **Organização dos Arquivos**

   - main.py: Script principal que orquestra toda a análise (pode variar conforme sua estrutura).
   - src/: Possíveis módulos e funções para limpeza de dados, modelagem e visualização.
   - notebooks/: Jupyter Notebooks (se aplicáveis), usados para prototipagem de algoritmos e análises exploratórias.
   - requirements.txt: Lista de pacotes e dependências necessários para execução do projeto.
   - README.md: Este arquivo, contendo instruções de uso e detalhes gerais

## **Contribuições**

  Contribuições são bem-vindas! Para participar:

1. Faça um *fork* deste repositório.
2. Crie um *branch* para sua nova feature ou correção (ex.: *feature/melhoria-graficos*).
3. Faça *commit* das suas mudanças.
Abra um *pull request* descrevendo suas alterações.

## **Licença**

 Este projeto é disponibilizado sob os termos da **Licença MIT.** Sinta-se à vontade para usar, modificar e distribuir o software conforme necessário.

## **Agradecimentos**

A DATA H e ao Evandro Barros, que conduziu um processo intensivo de Inteligência Artificial por seis meses, pautado em desafios semanais.
Meus agradecimentos por ter alcançado a última semana desse processo, consolidando conhecimentos em Machine Learning e aplicações práticas de IA.
À comunidade open source, que fornece suporte incansável em bibliotecas e documentações essenciais para projetos de dados.
### **Desenvolvido por Letícia Gobbi**
