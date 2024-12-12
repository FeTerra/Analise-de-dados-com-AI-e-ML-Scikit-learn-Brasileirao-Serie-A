# Aluno: Felipe Masera Terra de Almeida
# RM: 99405
# Análise do Brasileirão Série A

Este projeto realiza uma análise exploratória de dados do Campeonato Brasileiro Série A, utilizando Python e bibliotecas como Pandas, Seaborn e Matplotlib. A análise inclui cálculos estatísticos, visualização de dados e exploração de correlações entre variáveis relacionadas às partidas.

## Estrutura do Projeto

- `data/` - Diretório onde está o arquivo de dados compactado (`brasileirao_serie_a.csv.gz`).
- `notebooks/` - Contém os notebooks Jupyter com o código e a análise.
- `requirements.txt` - Arquivo com as dependências necessárias para o projeto.

## Funcionalidades

- **Análise de Público:** Descobrir o time com maior média de público durante o campeonato.
- **Análise de Gols:** Determinar se o fator casa influencia na quantidade de gols marcados.
- **Idade Média e Faltas:** Explorar a relação entre a idade média dos jogadores e o número de faltas cometidas.
- **Mapa de Correlação:** Gerar um heatmap para visualizar as correlações entre variáveis numéricas do dataset.

## Pré-requisitos

Certifique-se de ter instalado:

- Python 3.7+
- Jupyter Notebook ou Jupyter Lab

As bibliotecas necessárias podem ser instaladas utilizando o comando:

```bash
pip install -r requirements.txt
```

## Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/FeTerra/analise-brasileirao.git
cd analise-brasileirao
```

2. Certifique-se de que o arquivo `brasileirao_serie_a.csv.gz` está no diretório `data/`.

3. Abra o Jupyter Notebook:

```bash
jupyter notebook notebooks/analise_brasileirao.ipynb
```

4. Execute as células do notebook para realizar a análise.

## Exemplos de Visualizações

### Mapa de Correlação

![Heatmap de Correlação](assets/heatmap_correlacao.png)

### Gráficos de Tendências

Exemplo de visualizações que podem ser geradas durante a análise:

- Média de público por time.
- Comparação entre gols marcados em casa e fora de casa.

## Possíveis Erros

### Arquivo Não Encontrado

Certifique-se de que o arquivo `brasileirao_serie_a.csv.gz` está no diretório `data/`.

### Colunas Não Encontradas

O dataset deve conter as seguintes colunas para o correto funcionamento do código:

- `mandante`, `visitante`
- `publico`
- `gols_mandante`, `gols_visitante`
- `mandante_idade_media`, `mandante_faltas`

Se alguma coluna estiver faltando, atualize o dataset ou ajuste o código.
