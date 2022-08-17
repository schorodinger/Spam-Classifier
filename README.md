# Classificação de Spam - Netlab

Um modelo de detecção de spam usando Tpot.

## Sumário

- [Sobre](#sobre)
- [Requisitos](#requisitos)
- [Diretórios](#diretorios)


### Sobre

Este projeto tem como objetivo classificar mensagens instantâneas como spam ou não. Os requisitos do projeto consiste em um notebook python que utiliza a biblioteca do Scikit-Learn (Tokenizer e Classificadores), e a plataforma Natural Language Toolkit (NLTK) que foi utilizada na análise das mensagens. Também foi utilizado o Tpot que é uma ferramenta de aprendizado de máquina automatizado Python que otimiza pipelines de aprendizado de máquina usando programação genética. Ele automatizará a parte mais custosa de encontrar o melhor modelo de Classifacação do Scikit-learn.

### Requisitos

- Um ambiente de desenvolvimento integrado (IDE) de sua preferência como por exemplo: Pycharm.
- Python 3.10
- Para isntalação dos pacotes que foi utilizados no projeto, use o comando:
```bash
pip install -r requirements.txt
```
## Diretórios

### Pasta data:

- Dados fornecidos:
  - Data_Train.csv - dados de treino com 3 coluanas: id, mensagem e classificações.
  - Data_Test.csv - dados de teste com 2 coluanas:id e mensagem.

### Code:
 
- Notebook escrito em Python para o pré-processamento, análise exploratória e modelagem.

### Pasta model:

- Encontra o melhor classifacador encontrado pelo Tpot no formato .py
