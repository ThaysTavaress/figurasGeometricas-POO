# Cálculo de Áreas - Figuras Geométricas Planas com Programação Orientada a Objetos

Este repositório tem como objetivo demonstrar, de forma clara e didática, como aplicar os conceitos de **Programação Orientada a Objetos (POO)** no desenvolvimento de um sistema para o **cálculo de áreas de figuras geométricas planas**. O projeto é composto por diversas classes representando figuras geométricas, evidenciando princípios como:

---

## Objetivo

Implementar, em Java, o cálculo de áreas de diferentes figuras geométricas planas utilizando os fundamentos da orientação a objetos. O sistema oferece duas formas de cálculo:
- Métodos que **imprimem** o resultado diretamente.
- Métodos que **retornam** o valor calculado.

---

## Organização do Projeto
A estrutura do projeto está dividida em dois pacotes principais para garantir clareza e separação de responsabilidades:

### 📁 `br.edu.principal`
Contém a **classe principal** com o método `main`, responsável por:
- Instanciar as figuras geométricas.
- Executar os métodos de cálculo.
- Exibir os resultados.

### 📁 `br.edu.figurasgeometricasplanas`
Reúne todas as classes que representam as **figuras geométricas planas**. Cada classe possui:
- Atributos privados (ex: base, altura, raio, lado).
- Construtor para inicializar os atributos.
- Métodos de cálculo:
  - `calcArea()`

---

## Figuras Geométricas Implementadas

O projeto contempla as seguintes figuras, cada uma com sua própria classe:

- Triângulo
- Quadrado
- Retângulo
- Círculo
- Losango
- Trapézio
- Paralelogramo
- Hexágono
- Pentágono

Cada classe segue uma estrutura padronizada, com atributos e comportamentos específicos da figura representada.

## Diagrama UML

Abaixo, o diagrama de classes UML representa visualmente a estrutura do projeto, destacando os pacotes, classes e métodos:

![image](https://github.com/user-attachments/assets/68e588d0-1bd8-4d9a-a9b5-54f031407364)
