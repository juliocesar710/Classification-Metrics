# Projeto de Cálculo de Métricas de Avaliação de Classificação

## 📚 Descrição

Este projeto tem como objetivo calcular e visualizar as principais métricas de avaliação de modelos de classificação, como Acurácia, Sensibilidade (Recall), Precisão, Especificidade e F-Score. As métricas são calculadas a partir de uma matriz de confusão, utilizando valores de Verdadeiros Positivos (VP), Falsos Negativos (FN), Falsos Positivos (FP) e Verdadeiros Negativos (VN).

## 📝 Justificativa

A avaliação de modelos de classificação é uma etapa crucial em projetos de aprendizado de máquina. Compreender como o modelo se comporta nas diferentes classes, incluindo os falsos positivos e falsos negativos, é fundamental para sua eficácia. Este projeto visa fornecer as ferramentas para realizar essas avaliações de maneira eficiente e visualmente clara.

## ⚙️ Tecnologias Utilizadas

- Python 3.x
- Bibliotecas:
  - matplotlib: Para visualização gráfica das métricas.
  - seaborn: Para criação de heatmaps.
  - ipywidgets: Para interação no Colab.
  - scikit-learn: Para métricas de avaliação e matriz de confusão.
- Ambiente de Desenvolvimento:
  - Google Colab

## 📁 Estrutura de Pastas

```
Classification-Metrics/
│
├── src/
│   ├── __init__.py
│   ├── metrics.py  # Funções para calcular as métricas de avaliação
│   ├── visualizations.py # Funções para gerar gráficos (métricas, heatmaps, matrizes de confusão)
│   └── utils.py # Ainda se encotra vazio
│
├── data/
│   ├── raw/            # Ainda se encotra vazio
│   ├── processed/      # Ainda se encotra vazio
│   └── external/       # Ainda se encotra vazio
│
├── outputs/
│   ├── figures/        # Gráficos gerados
│   └── logs/           # Ainda se encotra vazio
│
├── notebooks/           # Notebooks do projeto
├── requirements.txt     # Dependências do projeto
└── .gitignore           # Arquivos e pastas a serem ignorados pelo git

```

## 🔎 Funcionalidades

- *Cálculo das Métricas:* Implementa funções para calcular Acurácia, Sensibilidade, Precisão, Especificidade e F-Score.
- *Visualizações:* Gráficos das métricas e matriz de confusão em formato de heatmap.
- *Interatividade:* Opção de salvar gráficos e logs, além de permitir ajustes nas métricas e visualizações.

## 🖥️ Instalação

1. Clone o repositório:
```
git clone https://github.com/seu-usuario/projeto-metricas.git
cd projeto-metricas
```
2. Instale as dependências:
```
pip install -r requirements.txt
```

## 🚀 Como Usar

1. Abra o notebook `notebooks/metricas.ipynb` no Google Colab.
2. Execute as células para calcular e visualizar as métricas de avaliação.
3. Utilize os widgets interativos para salvar gráficos e logs conforme necessário.

## 🛠 Como Acessar os Gráficos, Funções e o Notebook 📝
### 📊 Acessando os Gráficos

Os gráficos gerados podem ser acessados na pasta `outputs/figures/`. Para visualizar os gráficos interativos, basta abrir os arquivos gerados com extensão `.jpeg`. Ou clicando [Aqui](./outputs/figures)

### 🔧 Funções do Projeto

As funções de métricas e visualizações estão localizadas no arquivo `src/metrics.py` e `src/visualizations.py`. Para usá-las, basta importar os módulos necessários e chamar as funções diretamente em seu código. Ou clicando [Aqui](./src) 

### 📒 Acessando o Notebook

Você pode explorar o notebook interativo em `notebooks/`. Clique no arquivo desejado para abrir e acompanhar a execução das células. Ou clicando [Aqui](./notebooks)

## 🏁 Contribuições

Sinta-se à vontade para contribuir com o projeto. Envie um pull request com melhorias ou novas funcionalidades.


## 🎄 Mensagem de Natal 🎄

Neste projeto, desenvolvido durante o período natalino, aproveitei a oportunidade para não apenas melhorar minhas habilidades técnicas, mas também refletir sobre o espírito de colaboração, aprendizado e crescimento. Que este Natal seja repleto de paz, alegria e sucesso em todos os seus projetos, assim como no caminho do desenvolvimento!

Feliz Natal e um próspero Ano Novo! 🎅🎁
