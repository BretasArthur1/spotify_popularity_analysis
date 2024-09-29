

---
# Análise de Popularidade de Músicas no Spotify

Este projeto tem como objetivo prever a popularidade de músicas no Spotify utilizando técnicas de Machine Learning. Através de uma abordagem completa, desde a análise exploratória dos dados até a construção e avaliação de modelos preditivos, buscamos identificar os fatores que influenciam o sucesso das músicas na plataforma.

## 📊 Sumário

1. [Descrição](#descrição)
2. [Tecnologias Utilizadas](#tecnologias-utilizadas)
3. [Estrutura do Projeto](#estrutura-do-projeto)
4. [Como Executar](#como-executar)
5. [Resultados](#resultados)
6. [Contribuições](#contribuições)
7. [Licença](#licença)
8. [Contato](#contato)

## 📝 Descrição

A popularidade de uma música no Spotify pode ser influenciada por diversos fatores, como características acústicas, gênero musical, presença de conteúdo explícito, entre outros. Este projeto utiliza algoritmos de classificação para identificar quais desses fatores são mais determinantes para o sucesso das músicas.

### Objetivos Principais

- **Análise Exploratória de Dados (EDA):** Entender a distribuição e correlação das variáveis presentes no dataset.
- **Feature Engineering:** Criar novas features que possam capturar interações relevantes entre as variáveis.
- **Modelagem Preditiva:** Construir e avaliar modelos de Machine Learning para prever a popularidade das músicas.
- **Ajuste de Hiperparâmetros:** Otimizar os modelos para melhorar seu desempenho.
- **Submissão de Resultados:** Gerar um arquivo de submissão compatível com a plataforma de competição (Kaggle).

## 🛠 Tecnologias Utilizadas

- **Linguagem de Programação:** Python
- **Bibliotecas:**
  - `pandas` para manipulação e análise de dados
  - `numpy` para operações numéricas
  - `matplotlib` e `seaborn` para visualização de dados
  - `scikit-learn` para construção e avaliação de modelos de Machine Learning

## 📂 Estrutura do Projeto


spotify_popularity_analysis/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── spotify_popularity_analysis.ipynb
│
├── submissions/
│   └── submission.csv
│
├── README.md
└── requirements.txt


- data/: Contém os datasets de treino e teste.
- notebooks/: Notebook Jupyter com todo o processo de análise e modelagem.
- submissions/: Arquivo de submissão gerado para a competição.
- requirements.txt: Lista das dependências do projeto.
- README.md: Documentação do projeto.

 🚀 Como Executar

 1. Clone o Repositório

bash
git clone https://github.com/BretasArthur1/spotify_popularity_analysis
cd spotify_popularity_analysis


### 2. Crie um Ambiente Virtual

```bash
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. Instale as Dependências

```bash
pip install -r requirements.txt
```

### 4. Execute o Notebook

Abra o notebook Jupyter e execute todas as células:

```bash
jupyter notebook
```

## 🏆 Resultados

Após a construção e ajuste dos modelos, o **Stacking Classifier** alcançou uma acurácia de **81.5%** no conjunto de validação, atendendo ao critério mínimo de 70% de acurácia. As métricas de precisão, recall e F1-score também foram analisadas para uma interpretação completa do desempenho do modelo.

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar este projeto.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📫 Contato

Para qualquer dúvida ou sugestão, entre em contato:

- **Email:** arthurbretas1@gmail.com
- **LinkedIn:** [Meu LinkedIn](https://www.linkedin.com/in/arthur-bretas-b2a6a82b9/)
- **GitHub:** [Meu GitHub](https://github.com/BretasArthur1)

---
