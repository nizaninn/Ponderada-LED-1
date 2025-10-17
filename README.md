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
[(Clique aqui para ver a imagem)](https://drive.google.com/file/d/1WHKURspqDho4qbmVEQxuIOZcpgebYO6X/view?usp=sharing)


*LED interno acesso:*  
[(Clique aqui para ver a imagem)](https://drive.google.com/file/d/1MdupAiECvXivs9LkE5WP5ZnoDskdqnNz/view?usp=sharing)


*LED interno apagado:*  
[(Clique aqui para ver a imagem)](https://drive.google.com/file/d/1rm1bDYRCX5ixvYLM4HCwS3Tcv992ERTt/view?usp=sharing)

*Vídeo de demonstração:*  
[(Clique aqui para ver o vídeo)](https://drive.google.com/file/d/14J4JPs8piSadmOHkiO8YieosZoITQ7t6/view?usp=sharing)

## Parte 2 - LED Externo

Para aprofundar o aprendizado, adicionamos um LED externo ao projeto. Ele será controlado pelo Arduino usando um pino digital (ex.: pino 10), utilizando um resistor para proteger o LED.

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
- No Arduino IDE, configure o pino digital 10 como saída e faça o LED piscar.
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
