# Projeto 01 - Análise Exploratória Olist

## Objetivo

Analisar o processo logístico dos pedidos da plataforma Olist.

## Principais Descobertas

- A maioria das entregas ocorreu entre 8 e 14 dias.
- Entregas acima de 60 dias representam uma pequena parcela da operação.
- A visualização por faixas de entrega apresentou melhor comunicação dos resultados do que o histograma tradicional.

## Ferramentas Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn

## Evolução da Análise

Durante a exploração inicial foi utilizado um histograma para representar o tempo de entrega dos pedidos.

Apesar de representar corretamente os dados, a visualização dificultava a interpretação dos padrões logísticos devido à concentração das observações em determinadas regiões e à presença de valores extremos.

Por esse motivo foi desenvolvida uma segunda abordagem baseada em faixas de prazo de entrega, tornando a leitura mais intuitiva para usuários técnicos e de negócio.

### Histograma Inicial

![Histograma](images/01_distribuicao_tempo_entrega.png)

### Distribuição por Faixas

![Faixas](images/03_percentual_faixas_entrega.png)