# CARL: Forest Fire with DQN

[ToC]

Este documento es un registro de avances y modificaciones respecto al proyecto CARL, el cuál consiste en utilizar técnicas de Reinforcement Learning (DQN, PPO, A2C) en la optimización de problemas relacionados con Automatas Celulares (CA). Actualmente se estudian dos ambientes principales: BullDozer y Helicoptero.

## Ambiente

Los ambientes consisten principalmente en una Grid de tamaño variable cuyas celdas tienen ciertos estados y las transiciones de estado están definidas por la dinámica del sistema. Existe un agente externo que puede modificar el estado de las celdas para obtener un comportamiento deseable en la evolución del ambiente y optimizar una función de costo arbitraria.

<img src="https://i.imgur.com/QzV4Jxs.png" alt="drawing" width="50%"/>

<img src="https://i.imgur.com/gZnLBQw.png" alt="drawing" width="60%"/>







## DQN

### Double DQN (DDQN)


### Prioritized Experience Replay


### Dueling Q-Networks