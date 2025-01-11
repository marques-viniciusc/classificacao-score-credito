# Projeto: Classificação de Score de Crédito

## Descrição

Este projeto busca automatizar e melhorar a análise de perfis de clientes para auxiliar instituições financeiras na tomada de decisão sobre crédito e serviços financeiros. A classificação dos clientes em diferentes níveis de confiabilidade permite maior precisão e eficiência, reduzindo riscos e melhorando o planejamento operacional.

## Funcionalidades

- Construção de um modelo de Machine Learning para classificação de crédito em três categorias: baixo, médio e alto risco.
- Identificação das variáveis mais importantes que influenciam na classificação.
- Tratamento de classes desbalanceadas utilizando a técnica SMOTE.
- Visualização dos dados e dos resultados através de gráficos informativos.
- Predição personalizada de score de crédito para novos clientes.

## Requisitos

- Python 3.8+

### Pacotes necessários:

- pandas
- numpy
- matplotlib
- seaborn
- pycaret
- scikit-learn
- imbalanced-learn

## Como Usar

1. Clone o repositório e acesse o diretório do projeto:
```bash
git clone https://github.com/marques-viniciusc/classificacao-score-credito.git
cd classificacao-score-credito
```

2. Instale os pacotes necessários:
```bash
pip install -r requirements.txt
```

3. Coloque o arquivo Credit_Score_Classification_Dataset.csv na pasta data.

4. Execute o notebook ou script Python principal para carregar os dados, treinar o modelo e visualizar os resultados.

## Estrutura do Código
```bash
├── data/
│   └── Credit_Score_Classification_Dataset.csv  # Dataset utilizado no projeto
├── credit-score-classification.py                 # Análise e desenvolvimento do modelo
└── README.md                                    # Documentação do projeto
```

## Observações

- Certifique-se de que o arquivo Credit_Score_Classification_Dataset.csv está no caminho correto.
- O modelo principal utiliza o algoritmo KNN, ajustado e avaliado através do PyCaret.
- Caso encontre problemas ao usar pacotes como pycaret, verifique a compatibilidade da versão instalada.

## Resultados

O modelo apresentou desempenho satisfatório, classificando clientes com alta precisão. Os principais insights obtidos foram:
- 69% dos clientes possuem score alto, indicando confiabilidade para oferta de serviços e produtos premium.
- Existe uma forte correlação entre renda, idade e outros fatores demográficos.
- A técnica de balanceamento SMOTE foi essencial para evitar enviesamento do modelo.
- Os resultados demonstram que o modelo pode auxiliar instituições financeiras na análise de crédito, otimizando recursos e reduzindo riscos.
