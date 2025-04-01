# e220-stm32 🚀

This repository contains an integration project between a LoRa SMD radio [E220-900M22S](https://www.cdebyte.com/products/E220-900M22S/1) and an STM32 microcontroller. The main objective was to develop a driver for communication between the LoRa chip [LLCC68](https://www.semtech.com/products/wireless-rf/lora-connect/llcc68) and the STM32 using SPI communication.

## 📌 Project Overview

This project is part of a prototype for a communication subsystem, responsible for sending data from an embedded system that collects and fuses sensory data. In addition to the development of the embedded software, the physical layer (schematic and PCB design) was also designed to integrate the LoRa radio with the STM32.

The main challenge faced was the integration of the driver for the LLCC68 chip into the STM32 environment, using the [LLCC68 driver from LibDriver](https://github.com/libdriver/llcc68/tree/main) in the STM32CubeIDE environment.

🔹 **This project was developed for the Propulsion and Aerospace Technology Team of the Federal University of Uberlândia (UFU), of which I am a member.**

## 🛠 Technologies and Tools Used

- **Microcontroller**: STM32
- **LoRa Radio**: E220-900M22S (LLCC68 Chip)
- **Development IDE**: STM32CubeIDE
- **Communication**: SPI
- **Library/Driver**: LLCC68 LibDriver

## 📁 Repository Structure

```
/
├── Core/ # Main source code
├── Drivers/ # STM32 drivers
├── LLCC68/ # LoRa radio driver implementation
├── Inc/ # Files header
├── Src/ # Implementation of source files
├── README.md # This file
└── ...
```

## 🚀 How to Configure and Compile

1. Clone the repository:
```bash
git clone https://github.com/GuilhermeAsura/e220-stm32.git
```

2. Open the project in STM32CubeIDE.

3. Configure SPI communication in STM32CubeMX according to the hardware used.

4. Compile and upload the firmware to the STM32 board.

## 🤝 Contributions

Contributions are welcome! If you want to suggest improvements or report problems, feel free to open an issue or a pull request.

---

PT-BR
# e220-stm32 🚀

Este repositório contém um projeto de integração entre um rádio LoRa SMD [E220-900M22S](https://www.cdebyte.com/products/E220-900M22S/1) e um microcontrolador STM32. O objetivo principal foi desenvolver um driver para comunicação entre o chip LoRa [LLCC68](https://www.semtech.com/products/wireless-rf/lora-connect/llcc68) e o STM32 utilizando comunicação SPI.

## 📌 Visão Geral do Projeto

Este projeto faz parte de um protótipo para um subsistema de comunicação, responsável pelo envio de dados de um sistema embarcado que realiza a coleta e fusão de dados sensoriais. Além do desenvolvimento do software embarcado, a camada física (esquemático e design da PCB) também foi projetada para integrar o rádio LoRa ao STM32.

O principal desafio enfrentado foi a integração do driver para o chip LLCC68 ao ambiente STM32, utilizando o [driver LLCC68 da LibDriver](https://github.com/libdriver/llcc68/tree/main) no ambiente STM32CubeIDE.

🔹 **Este projeto foi desenvolvido para a Equipe de Propulsão e Tecnologia Aeroespacial da Universidade Federal de Uberlândia (UFU), da qual faço parte.**

## 🛠 Tecnologias e Ferramentas Utilizadas

- **Microcontrolador**: STM32
- **Rádio LoRa**: E220-900M22S (Chip LLCC68)
- **IDE de Desenvolvimento**: STM32CubeIDE
- **Comunicação**: SPI
- **Biblioteca/Driver**: LLCC68 LibDriver

## 📁 Estrutura do Repositório

```
/
├── Core/               # Código-fonte principal
├── Drivers/            # Drivers do STM32
├── LLCC68/             # Implementação do driver do rádio LoRa
├── Inc/                # Arquivos de cabeçalho
├── Src/                # Implementação dos arquivos fonte
├── README.md           # Este arquivo
└── ...
```

## 🚀 Como Configurar e Compilar

1. Clone o repositório:
   ```bash
   git clone https://github.com/GuilhermeAsura/e220-stm32.git
   ```

2. Abra o projeto no STM32CubeIDE.

3. Configure a comunicação SPI no STM32CubeMX de acordo com o hardware utilizado.

4. Compile e faça o upload do firmware para a placa STM32.

## 🤝 Contribuições

Contribuições são bem-vindas! Caso queira sugerir melhorias ou reportar problemas, sinta-se à vontade para abrir uma issue ou um pull request.
