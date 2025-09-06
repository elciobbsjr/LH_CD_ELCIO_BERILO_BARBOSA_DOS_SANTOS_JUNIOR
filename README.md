
# 💡 Desafio de Ciência de Dados – Indicium (2025-11)

Este repositório contém a entrega completa do desafio proposto pela **Indicium Tech** para a vaga de **Cientista de Dados**, com foco na análise de dados de filmes da base IMDb e construção de um modelo de previsão de notas.

---

## 📁 Conteúdo do Repositório

- [`eda_modelagem.ipynb`](eda_modelagem.ipynb): Notebook com a **análise exploratória de dados (EDA)**, pré-processamento, modelagem, avaliação e salvamento do modelo final.
- [`modelo_imdb_predictor.pkl`](modelo_imdb_predictor.pkl): Arquivo do modelo treinado e salvo com `joblib`, pronto para ser utilizado em aplicações Python.
- [`requirements.txt`](requirements.txt): Lista completa de bibliotecas e suas versões utilizadas no projeto.
- [`README.md`](README.md): Este arquivo, com todas as instruções de instalação, execução e detalhes sobre o projeto.

---

## ⚙️ Como Instalar

Siga os passos abaixo para executar o projeto localmente:

### 1. Clone o repositório

```bash
git clone https://github.com/elciobbsjr/LH_CD_ELCIO_BERILO_BARBOSA_DOS_SANTOS_JUNIOR.git
cd LH_CD_ELCIO_BERILO_BARBOSA_DOS_SANTOS_JUNIOR
```

### 2. Crie um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate   # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

---

## ▶️ Como Executar

### Passo 1: Abra o notebook

Execute o Jupyter Notebook com o seguinte comando:

```bash
jupyter notebook eda_modelagem.ipynb
```

O notebook contém todas as etapas do projeto, desde a exploração dos dados até o treinamento, avaliação e salvamento do modelo final.

### Passo 2: Usar o modelo salvo

O modelo treinado (`modelo_imdb_predictor.pkl`) pode ser carregado com `joblib` para fazer previsões em outros scripts ou APIs Python:

```python
import joblib

# Carregar o modelo
modelo = joblib.load('modelo_imdb_predictor.pkl')

# Exemplo de previsão
exemplo = [[...]]  # substitua pelos dados no mesmo formato usado no treinamento
predicao = modelo.predict(exemplo)
print(predicao)
```

---

## 📌 Observações

- O projeto foi desenvolvido utilizando Python 3.10 e bibliotecas amplamente utilizadas como `pandas`, `numpy`, `matplotlib`, `scikit-learn` e `joblib`.
- As decisões de modelagem, seleção de variáveis e métricas de avaliação estão todas documentadas no notebook.

---

## 📫 Contato

**Elcio B. B. dos Santos Júnior**  
GitHub: [@elciobbsjr](https://github.com/elciobbsjr)  
LinkedIn: www.linkedin.com/in/elciobsjrhttps://www.linkedin.com/in/seu-perfil  
E-mail: elcio.junior@discente.ufma.br

---
