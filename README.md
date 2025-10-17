# Projeto Arduino: LED Pisca-Pisca 🎄🎄🎄

### Autora: Nicole Zanin

Este projeto tem como objetivo aprender a controlar LEDs utilizando o Arduino Uno, tanto o LED interno da placa quanto um LED externo, criando efeitos de acendimento e apagamento (blink) de forma contínua. O projeto também inclui a simulação do circuito no TinkerCad.

## Índice

- [Parte 1 - LED Interno](#parte-1---led-interno)
- [Parte 2 - LED Externo](#parte-2---led-externo)
- [Referências](#referências)

## Parte 1 - LED Interno

Nesta etapa, o objetivo foi controlar o LED interno do Arduino (LED embutido no pino 13), fazendo-o acender e apagar de forma contínua, gerando o efeito de "pisca-pisca".

*Passos:*
- Conecte o Arduino Uno ao computador usando o cabo USB;
- Abra o Arduino IDE no computador;
- No código, configure o pino do LED interno como saída;
- Faça o upload do código para o Arduino.
- Observe o LED interno piscando conforme o tempo definido no delay.
  
*Código:*
<div align="center">
  <img src="![apagado](https://github.com/user-attachments/assets/5129a2d5-9cca-428b-b845-4682067567d0)
" alt="Imagem led apagado" width="80%">
  <br>
</div>

*LED interno acesso:*  
<div align="center">
  
  <sub>Figura 2 - Canvas da proposta de valor</sub>  
  
  <img src="../assets/negocios/modelo_crisp.png" alt="Imagem do Canvas da Proposta de Valor" width="80%">
  <br>
  <sup>Fonte: produzido pelo grupo (Ceraza)</sup>

*LED interno apagado:*  
<div align="center">
  <img src="![apagado](https://github.com/user-attachments/assets/5129a2d5-9cca-428b-b845-4682067567d0)
" alt="Imagem led apagado" width="80%">
  <br>
</div>

*Vídeo de demonstração:*  
[(Clique aqui para ver o vídeo)](https://drive.google.com/file/d/14J4JPs8piSadmOHkiO8YieosZoITQ7t6/view?usp=sharing)

## Parte 2 - LED Externo

Para aprofundar o aprendizado, adicionamos um LED externo ao projeto. Ele será controlado pelo Arduino usando um pino digital (ex.: pino 6), utilizando um resistor para proteger o LED.

*Componentes necessários:*
- Arduino Uno;
- LED externo;
- Resistor de 220Ω ou 330Ω;
- Protoboard;
- Jumpers;

*Passos:*
- Conecte o terminal positivo (ânodo) do LED à linha correspondente ao pino 6 do Arduino na protoboard.
- Conecte o terminal negativo (cátodo) do LED ao resistor.
- Conecte o outro terminal do resistor ao GND do Arduino.
- No Arduino IDE, configure o pino digital 6 como saída e faça o LED piscar.
- Faça o upload do código para o Arduino.
- Observe o LED externo piscando junto com ou independente do LED interno.

*Vídeo de demonstração:*  
[[(Clique aqui para ver o vídeo)](https://drive.google.com/file/d/1jjHQ-Rm7n6ewad-mSmWAy89WTXF_atNX/view?usp=sharing)

*Projeto no TinkerCad:*  
[(Clique aqui para ver o projeto no TinkerCad)](https://www.tinkercad.com/things/57HKhpRaEwN/editel 
)

## Referências

ARDUINO. Arduino Official Documentation. Disponível em: <https://www.arduino.cc/>. Acesso em: 16 out. 2025.  
TINKERCAD. TinkerCad Circuits. Disponível em: <https://www.tinkercad.com/circuits>. Acesso em: 16 out. 2025.
