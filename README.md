# Controle de GPIO com Teclado Matricial 4x4 e Raspberry Pi Pico

Este projeto utiliza um teclado matricial 4x4 para controlar três LEDs RGB e um buzzer conectados a um microcontrolador Raspberry Pi Pico. A simulação é realizada com a extensão **Wokwi Simulator** integrado ao **VS Code**, e o código é escrito em linguagem C utilizando o **Pico SDK**.

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