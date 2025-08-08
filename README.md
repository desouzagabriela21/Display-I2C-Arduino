# Medidor de Distância Ultrassônico com Display LCD 16x2 I2C e Arduino R3

Este projeto utiliza um sensor de distância ultrassônico (HC-SR04 ou similar) junto com um display LCD 16x2 com interface I2C para medir e exibir a distância de objetos em centímetros.

Componentes:
Arduino Uno R3

Sensor de Distância Ultrassônico (4 pinos: VCC, GND, Trigger, Echo)

Display LCD 16x2 com interface I2C

Cabos jumper e protoboard

Descrição do Funcionamento:
O Arduino envia um pulso ultrassônico pelo pino Trigger do sensor, que reflete ao encontrar um objeto e retorna para o pino Echo. A partir do tempo medido para o eco, o Arduino calcula a distância do objeto.

Essa distância é exibida em tempo real no display LCD 16x2 utilizando a biblioteca Adafruit_LiquidCrystal, que facilita o uso do display com interface I2C.

<img width="1920" height="848" alt="ImagemCircuito" src="https://github.com/user-attachments/assets/edf56a63-0f40-4233-bff8-9dec12afdcd2" />
