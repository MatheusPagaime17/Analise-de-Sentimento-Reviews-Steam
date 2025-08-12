# Análise de Sentimentos de Reviews do Jogo Elden Ring (Steam)

Este projeto utiliza Processamento de Linguagem Natural (PLN) para construir um modelo de Inteligência Artificial capaz de classificar reviews do jogo Elden Ring da Steam como positivas ou negativas.

## Tecnologias Utilizadas
- Python
- Pandas e Matplotlib para manipulação e visualização de dados
- Scikit-learn
- Nlpaug para aumento de dados (Data Augmentation)
- Transformers (Hugging Face) para o modelo BERT
- PyTorch

## Como Executar
1. Clone este repositório.
2. Abra o arquivo `.ipynb` no Google Colab ou Jupyter Notebook.
3. O notebook já está configurado para carregar o dataset diretamente do repositório.
4. Execute todas as células em ordem.

## Estrutura do Projeto
- `elden_ring_steam_reviews.csv`: O dataset original com as reviews.
- `AnaliseSentimentoSteam.ipynb`: O notebook com todo o código, desde a limpeza dos dados até o treinamento e avaliação do modelo.
