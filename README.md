# Controle de GPIO com Teclado Matricial 4x4 e Raspberry Pi Pico
Tarefa 2 - Unidade 4

## Integrantes
- Yasmin Damasceno Cruz (TIC370101610)

Este projeto utiliza um teclado matricial 4x4 para controlar três LEDs RGB e um buzzer conectados a um microcontrolador **Raspberry Pi Pico**. O código é escrito em C, utilizando o **Pico SDK**, e a simulação é realizada com a extensão **Wokwi Simulator**, integrada ao VS Code. O objetivo deste projeto é demonstrar como integrar um teclado matricial com o controle de GPIO no Raspberry Pi Pico, permitindo a interação do usuário com os LEDs e buzzer.

## Requisitos
- VS Code instalado
- Pico SDK configurado
- Wokwi integrado ao VS Code
- Git instalado

## Configuração Inicial
1. Clone o repositório para sua máquina local:
   ```bash
   git clone <URL do Repositório>
   ```
2. Abra o projeto no VS Code.
3. Abra o arquivo `diagram.json` no Wokwi para visualizar a simulação dos componentes.

## Execução
Utilize o teclado matricial para controlar os LEDs e o buzzer conforme a tabela abaixo:

- Tecla 'A': Liga o LED vermelho.
- Tecla 'B': Liga o LED azul.
- Tecla 'C': Liga o LED verde.
- Tecla 'D': Liga todos os LEDs.
- Tecla '#': Ativa o buzzer.
- Para qualquer outra tecla os LEDs são desligados

## Vídeo Demonstrativo  

[Assista aqui](https://drive.google.com/file/d/19fvOIXpC9LnWddD3quGJKDLPbh8MUfL0/view?usp=drive_link)
