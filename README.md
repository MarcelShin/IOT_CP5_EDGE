# CP05 - Edge Computing
# Projeto de Monitoramento de Sensores com DHT-11 e Ultrassônico

Este projeto visa a criação de um sistema de monitoramento utilizando dois sensores distintos, o DHT11 e o sensor ultrassônico, integrados em um dispositivo IoT. O sistema realizará a leitura dos sensores a cada 3000ms e disponibilizará as leituras na porta serial no formato JSON, identificando os sensores e seus respectivos valores. Além disso, haverá comunicação com um broker MQTT para o envio das informações dos sensores e a criação de dashboards na plataforma TAGO.IO para visualização e controle dos dados.

O monitoramento de sensores IoT é essencial em diversas aplicações, desde o controle de ambientes até a gestão de processos industriais. Neste projeto, utilizaremos dois sensores populares, o DHT11 para medição de temperatura e umidade e o sensor ultrassônico para medição de distância.

## Sensores Utilizados

DHT11: é utilizado para medir temperatura e umidade relativa do ar.
Sensor Ultrassônico: é empregado para medir distâncias entre objetos. Ele emite ondas sonoras de alta frequência e mede o tempo que essas ondas levam para refletir de volta em um objeto, calculando assim a distância.

## Funcionalidades

Leitura dos sensores DHT11 e ultrassônico a cada 3000ms.
Disponibilização das leituras na porta serial no formato JSON, com identificação dos sensores e valores correspondentes.
Comunicação com um broker MQTT para envio das informações dos sensores.
Criação de tópicos MQTT para publicação das leituras dos sensores.
Desenvolvimento no Node-RED com o Arduino para integração do dispositivo IoT com o broker MQTT.
Criação de dashboards na plataforma TAGO.IO para visualização e controle dos dados.

## Ferramentas Utilizadas

Este projeto foi construído com as seguintes ferramentas:

- [Node-RED](https://nodered.org/)
- [TAGO.IO](https://tago.io/)


## Conclusão

O sistema desenvolvido permite o monitoramento em tempo real das leituras dos sensores DHT11 e ultrassônico, possibilitando uma gestão eficiente de ambientes e processos. A integração com um broker MQTT facilita a comunicação entre dispositivos IoT, enquanto os dashboards na plataforma TAGO.IO oferecem uma interface intuitiva para visualização e controle das informações coletadas. Este projeto demonstra uma aplicação prática de IoT e sensores em um contexto de monitoramento e controle.

## Colaboradores

Felipe Salazar, Lucas Reis, Marcelo Vieira, Rayara Figueiredo e Victor Rodrigues
