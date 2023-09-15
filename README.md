# Análise de Dados Pokémon

Este projeto se concentra na análise dos dados da Pokedex, que incluem informações sobre vários Pokémon. O código em Python realiza várias etapas de análise exploratória de dados (AED) e gera visualizações para entender melhor as características dos Pokémon. Abaixo estão as principais etapas e resultados da análise.

## Instruções de Uso

1. Certifique-se de que você tenha o arquivo de dados `pokedex.csv` na mesma pasta em que este código está localizado.

2. Execute o código em um ambiente Python, como Jupyter Notebook ou IDE Python.

3. O código carregará os dados da Pokedex, realizará a limpeza e executará as análises. Os resultados serão exibidos na saída padrão ou em gráficos, dependendo das análises realizadas.

## Etapas de Análise

### Limpeza de Dados

- O código começa carregando os dados da Pokedex de um arquivo CSV.
- É realizada uma verificação para identificar e remover linhas com dados ausentes.

### Análise Exploratória de Dados (AED)

- A análise de correlação é realizada para entender as relações entre diferentes variáveis, como Ataque e Velocidade.
- Um gráfico de dispersão é gerado para visualizar a diferença entre Ataque e Velocidade para Pokémon dos tipos "Grass Poison" e "Fire". Uma regressão linear é aplicada para determinar a tendência.

### Resultados

- Os resultados da análise são exibidos na saída padrão.
- Os gráficos, quando gerados, podem ser visualizados na interface gráfica do ambiente Python.

## Requisitos

- Python 3.x
- Bibliotecas: pandas, numpy, matplotlib, scipy

## Autor

JVictor011
