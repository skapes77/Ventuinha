# Trabalho MCR - MQTT ESP32 2022
Trabalho 4º BIM 2022 MCR 

Alunos: Arthur Zana Côrtes, Eduardo Morilho Moreira e Giovani Verissimo Pereira

O trabalho realizado tem a função de exemplificar a programação e montagem de uma ventoinha automátizada, funcionando com um sensor (simulado ao inserir o valor da temperatura no MQTT) que ao detectar temperatura elevada aciona a ventoinha para resfriar o dispositivo, além de um LED que se aciona em conjunto com a ventoinha.

![image](https://user-images.githubusercontent.com/119462023/204693881-de234143-7472-4fea-8b4a-bd871e4432ca.png)

(simulação realizada no Wokwi // O LED branco representa a ventoinha)

Interface no MQTT

![image](https://user-images.githubusercontent.com/119462023/204694292-5201f81b-cedb-4a5f-9bbb-a82ac5b51c1b.png)

No lado direito, a representação do estado atual da ventoinha (desligada), no esquerdo, a leitura de temperatura efetuada pelo sensor

![image](https://user-images.githubusercontent.com/119462023/204694570-4642101b-50ec-4c3d-9bd3-3fd447be13d4.png)

Representação do estado da ventoinha (ligada) após superar os 38ºC necessários para ativação

![image](https://user-images.githubusercontent.com/119462023/205082485-d8697884-c849-4d7e-b161-c6b8fcae7430.png)
Demonstração do projeto físico funcionando
