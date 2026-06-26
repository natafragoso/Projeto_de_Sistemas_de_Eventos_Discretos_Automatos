# Projeto_de_Sistemas_de_Eventos_Discretos_Automatos
## Descrição Geral
O projeto propõe a modelagem de um cenário usando autômatos. O cenário em questão trata-se de um aeroporto constituído por três gates, um segmento de taxiamento e uma pista, desde as etapas de solo até as de vôo no aeroporto, considerando as etapas de saída e chegada nos gates, taxiamento e decolagem e pouso nas pistas.
## Objetivos
O objetivo do projeto é desenvolver um modelo que represente um sistema de controle de tráfego aeroportuário de um aeroporto utilizando autômatos finitos com o software Supremica, procurando:
- Desenvolver um modelo com todas as etapas do sistema;
- Buscar cumprir todas as regras operacionais, evitando estados indesejados e/ou proibidos;
- Simular e verificar a funcionalidade do sistema.
## Funcionamento do sistema
### Principais componentes
- 3 gates (G1, G2 e G3);
- 1 pistas de taxiamento (T1);
- 1 pistas de decolagem e pouso (P1).
### Regras dos operacionais
- Rota dos aviões
  - Fluxo de saída: Saída de um dos gates (G1 - G3) →  Pista de taxiamento (T1) → Pista de decolagem (P1);
  - Fluxo de chegada: Pouso na pista (P1) → Pista de taxiamento (T1) → chegada ao gate( G1 - G3);

- Prioridade de acesso
  - Apenas um avião pode entrar ou sair dos gates (G1 - G3) por vez;
  - Aviões que estão nos gates tem prioridade de deslocamento;
  - Aviões não podem pousar caso as pistas de taxiamento (T1) ou todos os gates (G1 - G3) estejam ocupados.
## Eventos
### Eventos controláveis
### Eventos não controláveis
