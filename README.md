# Projetos de Machine Learning

[![Python](https://img.shields.io/badge/python-3.9%2B-brightgreen.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/jupyter-notebook-orange.svg)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/colab-ready-yellow.svg)](https://colab.research.google.com/)

Repositório dedicado aos exercícios e projetos práticos de **Machine Learning** desenvolvidos durante a faculdade, cobrindo aprendizado supervisionado e não supervisionado. As atividades vão desde a implementação manual de algoritmos ("do zero", sem bibliotecas prontas) até o uso prático de Scikit-Learn, visão computacional com OpenCV e simulações.

---

## 📌 Índice

- [Visão Geral das Aulas](#-visão-geral-das-aulas)
- [Funcionalidades e Tópicos Abordados](#-funcionalidades-e-tópicos-abordados)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Pré-requisitos e Dependências](#-pré-requisitos-e-dependências)
- [Como Executar o Projeto](#-como-executar-o-projeto)
  - [Opção 1: Diretamente no Google Colab](#opção-1-diretamente-no-google-colab-sem-instalação-local)
  - [Opção 2: Localmente via Jupyter](#opção-2-localmente-via-jupyter-notebook)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)

---

## 📚 Visão Geral das Aulas

Cada notebook contém os exercícios práticos e experimentos desenvolvidos para uma aula da faculdade:

| Notebook | Tópico Central | Algoritmos / Técnicas | Executar |
| :--- | :--- | :--- | :---: |
| [**Aula 1**](Aula1_MachineLearning.ipynb) | Regressão Linear Simples | Implementação manual do zero (cálculo de coeficientes e função de custo sem bibliotecas) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula1_MachineLearning.ipynb) |
| [**Aula 2**](Aula2_MachineLearning.ipynb) | Regressão Linear Simples Avançada | Ajustes de hiperparâmetros, análise de resíduos e formulação matricial | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula2_MachineLearning.ipynb) |
| [**Aula 3**](Aula3_MachineLearning.ipynb) | Regressão de Preços Imobiliários | `LinearRegression`, `DecisionTreeRegressor`, `RandomForestRegressor`, validação com MAE, MAPE e R² | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula3_MachineLearning.ipynb) |
| [**Aula 4**](Aula4_MachineLearning.ipynb) | Classificação de Dígitos (MNIST) | `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier` e inferência de imagens reais com OpenCV | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula4_MachineLearning.ipynb) |
| [**Aula 5**](Aula5_MachineLearning.ipynb) | Agrupamento Não Supervisionado | `K-Means`, redução de dimensionalidade com PCA e visualização 3D | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula5_MachineLearning.ipynb) |
| [**Aula 6**](Aula6_MachineLearning.ipynb) | Simulação e Previsão da Copa do Mundo | `KNeighborsClassifier` (KNN), `StandardScaler` e modelagem combinatória de confrontos | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula6_MachineLearning.ipynb) |
| [**Aula 7**](Aula7_MachineLearning.ipynb) | Satisfação de Clientes em Restaurantes | `RandomForestClassifier`, `LogisticRegression`, validação cruzada (`cross_val_score`) e matriz de confusão | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GLzanetti/Projetos-de-Machine-Learning/blob/main/Aula7_MachineLearning.ipynb) |

---

## 🚀 Funcionalidades e Tópicos Abordados

- **Modelagem Matemática "From Scratch":** Construção analítica dos cálculos de regressão linear para fixação da base teórica antes do uso de frameworks.
- **Modelos Supervisionados de Regressão e Classificação:** Uso comparativo de múltiplos estimadores do Scikit-Learn com avaliação de desempenho através de matrizes de confusão e métricas consolidadas (Acurácia, F1-Score, R², MAE e MAPE).
- **Visão Computacional Aplicada:** Pipeline de processamento de imagem (`OpenCV`) para carregar, converter escala de cinza, redimensionar e classificar desenhos manuscritos próprios sobre modelos treinados no MNIST.
- **Aprendizado Não Supervisionado:** Clusterização e identificação de padrões ocultos com K-Means, utilizando PCA para redução dimensional e visualização interativa em 3D.
- **Automação de Obtenção de Dados:** Coleta e preparação automatizada de conjuntos de dados via `kagglehub`.

---

## 🏗️ Estrutura do Repositório

```text
Projetos-de-Machine-Learning/
├── Aula1_MachineLearning.ipynb        # Regressão linear simples feita do zero
├── Aula2_MachineLearning.ipynb        # Regressão linear simples (aprofundamento)
├── Aula3_MachineLearning.ipynb        # Regressão de preços de imóveis
├── Aula4_MachineLearning.ipynb        # Classificação de dígitos manuscritos (MNIST) + OpenCV
├── Aula5_MachineLearning.ipynb        # Clusterização K-Means e PCA
├── Aula6_MachineLearning.ipynb        # Simulação e previsão de torneio com KNN
├── Aula7_MachineLearning.ipynb        # Análise de satisfação de clientes e validação cruzada
├── .gitignore                         # Arquivos e diretórios ignorados pelo Git
└── README.md                          # Documentação principal do repositório
```

---

## ⚙️ Pré-requisitos e Dependências

Para executar os notebooks localmente, certifique-se de possuir:

- **Python:** Versão 3.9 ou superior
- **Gerenciador de Pacotes:** `pip`

As principais bibliotecas necessárias são:
- `notebook` ou `jupyterlab`
- `pandas` e `numpy`
- `matplotlib`
- `scikit-learn`
- `opencv-python`
- `tensorflow` (para importação do dataset MNIST)
- `kagglehub` (para download automático dos datasets)

---

## 💻 Como Executar o Projeto

### Opção 1: Diretamente no Google Colab (Sem instalação local)

1. Navegue até a tabela na seção [Visão Geral dos Módulos](#-visão-geral-dos-módulos).
2. Clique no badge **Open in Colab** correspondente à aula desejada.
3. No Google Colab, execute as células sequencialmente (`Shift + Enter`).

---

### Opção 2: Localmente via Jupyter Notebook

#### 1. Clonar o repositório
```bash
git clone https://github.com/GLzanetti/Projetos-de-Machine-Learning.git
cd Projetos-de-Machine-Learning
```

#### 2. Criar e ativar um ambiente virtual (recomendado)
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# Linux / macOS
python3 -m venv .venv
source .venv/bin/activate
```

#### 3. Instalar as dependências
```bash
pip install notebook pandas numpy matplotlib scikit-learn opencv-python tensorflow kagglehub
```

#### 4. Iniciar o servidor Jupyter
```bash
jupyter notebook
```
Uma aba abrirá no seu navegador. Escolha qualquer notebook `AulaX_MachineLearning.ipynb` para iniciar os experimentos.

---

## 🛠️ Tecnologias Utilizadas

- **[Python](https://www.python.org/)** — Linguagem base de todos os estudos.
- **[Scikit-Learn](https://scikit-learn.org/)** — Algoritmos de aprendizado de máquina, métricas e transformações.
- **[Pandas](https://pandas.pydata.org/)** & **[NumPy](https://numpy.org/)** — Manipulação, limpeza e análise matricial/tabular de dados.
- **[Matplotlib](https://matplotlib.org/)** — Geração de visualizações gráficas 2D e 3D.
- **[OpenCV](https://opencv.org/)** — Processamento de imagens digitais.
- **[TensorFlow / Keras](https://www.tensorflow.org/)** — Obtenção do benchmark MNIST.
- **[KaggleHub](https://github.com/Kaggle/kagglehub)** — Carregamento automático de datasets do Kaggle.

---

Desenvolvido por [Gabriel Zanetti](https://github.com/GLzanetti) 🚀
