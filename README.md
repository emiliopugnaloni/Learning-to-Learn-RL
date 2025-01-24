# Implementacion de: "Learning to Reinforcement Learn"

Este repositorio contiene la implementación de los tres primeros experimentos descritos en el paper Learning to Reinforcement Learn de Wang et al. (2017). 

### Archivos

* **A2C_Meta_Bandit.ipynb**: Implementación de los Experimentos 1 y 2, donde se entrenan y evalúan los bandits utilizando el algoritmo Advantage Actor-Critic (A2C) con LSTM.

* **A2C Meta-Dependent-Bandit II.ipynb**: Implementación del Experimento 3, donde se entrenan y evalúan bandits utilizando el algoritmo Advantage Actor-Critic (A2C) con LSTM.

* **Results Exp1-2.ipynb**: Notebook para generar las gráficas de los resultados obtenidos en los Experimentos 1 y 2.

* **UCB Exp1-2.ipynb** :   Implementación para generar los resultados de la estrategia UCB (Upper Confidence Bound), necesarios para los Experimentos 1 y 2 como base de comparación.


## Cómo Usar los Archivos

1. Ejecutar UCB *Exp1-2.ipynb* para obtener los resultados necesarios de UCB.
2. Usar *A2C_Meta_Bandit.ipynb* para entrenar y probar los bandits en los Experimentos 1 y 2.
3. Usar *Results Exp1-2.ipynb* para generar las gráficas asociadas.
3. Ejecutar *A2C Meta-Dependent-Bandit II.ipynb* para realizar el Experimento 3.
