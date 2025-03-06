# Controlador PI  para uma mini estufa

## Sobre o projeto

Este projeto implementa um controlador Proporcional-Integral (PI) para uma pequena estufa com um elemento aquecedor em seu interior, no caso uma lâmpada, a qual fica permanente ligada, operando em conjunto com um cooler, responsável pelo controle da temperatura dentro da estufa, podendo esta grandeza ser definida e alterada pelo usuário.

## Componentes utilizados

- Microcontrolador Arduino UNO;
- Sensor de temperatura (NTC 10kΩ);
- Cooler 12V - 4 fios;
- Lâmpada halógena 12V - 20W;
- Transistor Darlington TIP 120;
- Diodo 1N4007;
- Resistor de 1kΩ;
- Resistor de 10kΩ;
- Fonte 12V DC.

## Funcionamento

- O sensor de temperatura monitora a temperatura interna da estufa em tempo real.

- A lâmpada se mantém ligada permanentemente, aquecendo o ambiente da estufa;

- O controlador PI ajusta a potência do cooler para manter a temperatura no setpoint desejado.

- O sistema pode ser ajustado para diferentes valores de KP e KI para otimizar a resposta do controlador.
  
## Etapas

- Desenvolvimento do circuito eletrônico e esquemático elétrico;
- Desenvolvimento da PCB;
- Programação do Arduino para coleta de dados de temperatura;
- Montagem da planta (Hardware);
- Coleta de dados;
- Identificação da planta (via MATLAB);
- Desenvolvimento do projeto do controlador (via MATLAB);
- Implementação do controlador;
- Análise dos resultados.

## Registros

**Arranjo físico:**

![Planta Pronta](https://github.com/kellyfmachado/Projeto---Controlador-PI/assets/134961117/c250b579-cdf8-4ff5-ad95-c4241d2d8081)

**Dados de temperatura em relação à referência:**

![Resultado do Controlador](https://github.com/kellyfmachado/Projeto---Controlador-PI/assets/134961117/e15a21b0-9622-49e2-8b2f-bb53ce823a3b)
