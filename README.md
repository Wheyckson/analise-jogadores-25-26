## ✏ About

Análise de Performance de Jogadores – Temporada 2025/2026

Projeto de Análise Exploratória de Dados (EDA) aplicado ao futebol europeu, utilizando estatísticas de jogadores da temporada 2025/2026.

Projeto de Análise Exploratória de Dados (EDA) aplicado ao futebol europeu, utilizando estatísticas de jogadores da temporada 2025/2026.

Dataset: Kaggle – Players Data 2025/2026

## 🛠 Technologies and Libs:

- [Python]
- [pandas]
- [numpy]
- [matplotlib]
- [seaborn]
- [scikit-learn]

## 🔭 Objetivos da análise

* Identificar diferenças de estilo entre ligas europeias.
* Avaliar o impacto de passes chave na produção ofensiva.
* Identificar o pico de performance por idade.
* Construir um índice heurístico de performance de jogadores.
* Identificar perfis de jogadores através de clusterização.

## 🔭 Principais análises realizadas

[Comparação entre ligas]
A análise mostrou diferenças estatísticas entre as principais ligas europeias.
A Premier League apresentou maior intensidade defensiva e criação de chances, enquanto ligas como La Liga demonstraram perfil mais técnico.

[Correlação entre criação e produção ofensiva]
Foi observada uma correlação positiva moderada entre Key Passes (KP) e contribuição ofensiva (G+A).
Isso indica que jogadores que criam mais oportunidades também tendem a participar diretamente de gols.

[Pico de performance por idade]
A produção ofensiva média apresenta crescimento progressivo até aproximadamente 24–29 anos, faixa associada ao pico físico e maturidade tática.

[Índice de Performance]
Foi criado um índice heurístico combinando:

 * Gols
 * Assistências
 * Passes chave
 * Ações defensivas

Esse índice permite identificar jogadores com contribuição equilibrada em diferentes fases do jogo.

[Clusterização de perfis]
Utilizando o algoritmo K-Means, os jogadores foram agrupados em perfis estatísticos:

 * Finalizadores
 * Criadores
 * Defensivos 
 * Jogadores equilibrados

A técnica de clusterização permite identificar padrões sem rótulos pré-definidos.

[Exemplos de visualizações]
O projeto inclui diversas visualizações exploratórias:

 * comparação de ligas
 * correlação entre métricas
 * distribuição de performance por idade
 * radar charts de jogadores
 * segmentação de perfis com clusterização