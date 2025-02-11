# Jadson de Jesus Santos - Tarefa de PWM

## 📚 Apresentação

Com o emprego do módulo PWM presente no microcontrolador RP2040, 
projete um sistema com a ferramenta Pico SDK para simular o controle do ângulo de um
servomotor, de modo que a posição do servomotor será de 180°, 90° e depois 0° por cinco segundos cada posição. 
A seguir, o servomotor transiciona sua posição suavemente de 0° a 180° e novamente de 108° a 0°.
Esta simulação contemplará o motor micro servo padrão, presente no simulador de eletrônica online Wokwi. Para
condução desta prática, será necessário simular os componentes listados abaixo.
1) Microcontrolador Raspberry Pi Pico W.
2) Servomotor – motor micro servo padrão – Wokwi.

## 🎯 Objetivo

- Compreender o funcionamento e a aplicação do PWM (modulação por largura de pulso);
- Entender o funcionamento de servomotor;
- Controlar o movimento de um servomotor por meio do PWM;
- Verificar o funcionamento do PWM no LED RGB da placa BitDogLab.

## 📑 Requisitos

- Visual Studio Code;
- Extensões C/C++, CMAKE e Raspberry Pi Pico no VSCode;
- Plataforma de Simulação Wokwi Online;
- Plataforma de Desenvolvimento BitDogLab.

## 📋 Funcionamento

- 1º) O Servomotor assume a posição de 180° por 5 segundos;
- 2º) O Servomotor assume a posição de 90° por 5 segundos;
- 3°) O Servomotor assume a posição de 0° por 5 segundos;
- 4º) O Servomotor faz uma varredura de forma suave pelos ângulos de 0° a 180° (repetindo o passo infinitamente).

## 📷 GIF Ilustrativo
![Servo](https://github.com/user-attachments/assets/22e0a252-5e8f-4ba2-a5bc-6b93c458ac49)



## ▶️ Link do Vídeo: https://youtu.be/eXOC95rQ3Pg
