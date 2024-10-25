# Previsão de Preços de Propriedades do Airbnb

## Introdução

Este projeto tem como objetivo prever o preço de propriedades listadas no Airbnb utilizando técnicas de aprendizado de máquina. A previsão é feita com base em várias características das propriedades, como tipo, localização e comodidades disponíveis.

## Índice

- [Introdução](#introdução)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#instalação)
- [Uso](#uso)
- [Metodologia](#Metodologia)
- [Resultados](#resultados)
- [Instruções Finais](#Instruções-Finais)

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Statsmodels

## Instalação

Para executar este projeto, você precisará instalar as seguintes bibliotecas. Você pode usar o `pip` para instalar as dependências:


```bash 
pip install pandas numpy matplotlib seaborn plotly scikit-learn statsmodels
```


## Uso
1 - Clone o repositório para a sua máquina local:
```bash 
git clone <URL do repositório>

```

2 - Navegue até o diretório do projeto:
```bash 
cd <nome do diretório>

```

3 - Execute o script principal (por exemplo, previsao_precos_airbnb.py):
```bash 
python previsao_precos_airbnb.py

```


## Metodologia

### Pré-processamento de Dados:
A base de dados do Airbnb foi limpa e preparada. Colunas com outliers foram removidas e categorias de texto foram transformadas em variáveis numéricas.

### Análise Exploratória:
Foram realizadas análises estatísticas e visualizações para entender a distribuição das características e como elas influenciam o preço.

### Modelo de Machine Learning:
Três modelos de regressão foram testados:

Random Forest
Regressão Linear
Extra Trees
O modelo Extra Trees foi selecionado como o melhor, alcançando um R² de 97.49% e um RMSE de 41.99.

## Resultados
O modelo final é capaz de prever os preços das propriedades com alta precisão. As características mais relevantes para a previsão foram identificadas e os resultados podem ser visualizados em gráficos de importância de recursos.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou relatar problemas.


### Instruções Finais
- Substitua `<URL do repositório>` e `<nome do diretório>` com as informações relevantes do seu projeto.
- Sinta-se à vontade para adicionar qualquer detalhe extra que considere importante.

Se precisar de mais alguma coisa, é só avisar!