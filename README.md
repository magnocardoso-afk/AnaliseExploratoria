## Definições de medidas de tendência central e dispersão

Supondo que foram observados os valores x1, x2, ..., xn, as principais medidas são:

- **Média:** soma de todos os valores dividida pelo número total de observações.
  
  \[
  \bar{x} = \frac{x_1 + x_2 + ... + x_n}{n}
  \]

- **Mediana:** valor que separa a metade inferior da metade superior dos dados.
  
- **Variância:** medida da dispersão dos valores em relação à média, calculada como a média dos quadrados das diferenças entre cada valor e a média.
  
  \[
  s^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2
  \]

- **Desvio padrão:** raiz quadrada da variância; indica quanto os valores se afastam, em média, da média.
  
  \[
  s = \sqrt{s^2}
  \]

- **Amplitude:** diferença entre o maior e o menor valor observado.
  
  \[
  \text{Amplitude} = x_\text{máx} - x_\text{mín}
  \]

# Análise Exploratória

Este projeto faz parte da disciplina **Prática Estatística I** e tem como objetivo explorar uma base de dados utilizando o **RStudio** e o **GitHub**.

## Resultados Gráficos

Foram criadas as seguintes visualizações:

- **Histograma da variável Idade:** mostra a distribuição das idades na base de dados.
- **Boxplot da variável Tempo Preso:** exibe a variação e possíveis outliers no tempo de prisão.
- **Boxplot do Score de Periculosidade por Escolaridade:** permite comparar a periculosidade média entre diferentes níveis de escolaridade.
- **Gráfico de Barras da variável Reincidente:** apresenta a frequência de reincidentes e não reincidentes.

As figuras estão salvas na pasta do projeto como arquivos `.png`.

---

## Próximas análises

O próximo passo é criar o script de **análises exploratórias** com medidas descritivas e correlação entre as variáveis.

