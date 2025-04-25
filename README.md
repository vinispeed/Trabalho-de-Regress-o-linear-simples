# Projeto de Regressão Linear Simples

Este projeto tem como objetivo prever salários com base na experiência profissional utilizando um modelo de regressão linear simples. A análise inclui a exploração inicial dos dados, ajuste do modelo, avaliação de desempenho e comparação de resultados por gênero.

## Estrutura do Projeto

- **`dados_regressao.csv`**: Arquivo contendo os dados utilizados no projeto.
- **`regrecao_linear_simples.ipynb`**: Notebook principal com a implementação do modelo e análise.

## Etapas do Projeto

1. **Exploração Inicial dos Dados**:
   - Verificação de tipos de dados, valores ausentes e duplicados.
   - Análise estatística descritiva e visualização gráfica.

2. **Escolha da Variável Explicativa**:
   - Análise de gráficos de dispersão para identificar a variável com maior correlação linear com o salário.
   - A variável `experiencia` foi escolhida como preditora.

3. **Ajuste do Modelo**:
   - Divisão dos dados em conjuntos de treino e teste.
   - Treinamento do modelo de regressão linear simples.

4. **Avaliação do Modelo**:
   - Cálculo de métricas de desempenho: EQM, MAE e MAPE.
   - Análise dos erros e interpretação dos coeficientes do modelo.

5. **Comparação por Gênero**:
   - Ajuste de modelos separados para homens e mulheres.
   - Comparação de métricas de desempenho entre os dois grupos.

6. **Interpretação e Conclusões**:
   - Identificação de pontos fortes e limitações do modelo.
   - Sugestões para melhorias futuras, como a inclusão de outras variáveis explicativas.

## Resultados

- O modelo apresentou um **MAPE** de aproximadamente 10%, indicando um desempenho razoável.
- A variável `experiencia` mostrou-se um bom preditor do salário, mas com limitações devido à alta variabilidade dos dados.
- Diferenças nos coeficientes e interceptos entre os modelos para homens e mulheres sugerem diferenças estruturais nos salários.

## Requisitos

- Python 3.7 ou superior
- Bibliotecas utilizadas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## Como Executar

1. Certifique-se de que o arquivo `dados_regressao.csv` está no mesmo diretório do notebook.
2. Abra o arquivo `regrecao_linear_simples.ipynb` em um ambiente como Jupyter Notebook ou JupyterLab.
3. Execute as células sequencialmente para reproduzir os resultados.

## Autor

Este projeto foi desenvolvido por Marcos Vinicius da Silva como parte de um estudo sobre regressão linear simples para análise de salários.
