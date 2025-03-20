# EDA: Análise do Desempenho das Escolas de NYC no SAT 🎓📊

## Objetivo 🎯

O objetivo deste projeto é analisar o desempenho das escolas públicas de Nova York (NYC) no exame SAT, abordando as melhores escolas em matemática, as 10 principais escolas com base nas pontuações combinadas do SAT e o borough com o maior desvio padrão nas notas do SAT.

## Descrição do Dataset 📋

O conjunto de dados `schools.csv` contém informações sobre o desempenho das escolas de NYC em várias áreas de avaliação do SAT: matemática, leitura e escrita. Cada linha representa uma escola e inclui informações como o nome da escola, pontuação média em matemática, leitura e escrita, além de informações sobre o bairro.

## Etapas da Análise 🔍

1. **Melhores Resultados em Matemática 📐**: Identificamos as escolas com os melhores resultados em matemática, considerando uma pontuação mínima de 80% do total possível (800 pontos).
   
2. **Top 10 Escolas com as Melhores Notas Combinadas no SAT 🏫**: Calculamos a pontuação total combinada do SAT para cada escola (soma das pontuações de matemática, leitura e escrita) e selecionamos as 10 escolas com as maiores pontuações.
   
3. **Borough com Maior Desvio Padrão nas Notas Combinadas do SAT 🌍**: Analisamos a dispersão das notas combinadas do SAT para cada borough e identificamos qual possui o maior desvio padrão, o que indica uma maior variação nas pontuações dentro daquele bairro.

## Resultados 📈

### Melhores Escolas em Matemática 📊
- As escolas selecionadas com base na pontuação mínima de 640 em matemática (80% do máximo de 800) foram ordenadas pela pontuação média de matemática.

### Top 10 Escolas com as Maiores Notas Combinadas no SAT 🥇
- As 10 escolas com as maiores pontuações totais no SAT (soma das notas de matemática, leitura e escrita) foram selecionadas e ordenadas de acordo com o `totalSAT`.

### Borough com Maior Desvio Padrão nas Notas Combinadas do SAT 📉
- O borough com o maior desvio padrão foi identificado, indicando uma maior variação nos resultados das escolas dentro daquele distrito.

## Conclusão 🏁

Essa análise permite observar quais escolas em NYC têm os melhores desempenhos individuais em matemática e como as pontuações combinadas no SAT se distribuem em toda a cidade. Além disso, ao identificar o borough com o maior desvio padrão, podemos entender melhor as disparidades de desempenho nas escolas dentro de diferentes regiões de NYC.
