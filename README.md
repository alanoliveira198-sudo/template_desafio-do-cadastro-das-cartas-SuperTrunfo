# Super Trunfo em C: desenvolvendo a lógica do jogo

Bem-vindo ao desafio de programação onde você construirá um jogo Super Trunfo em C! Imagine que você foi contratado pela TechNova, uma empresa inovadora de desenvolvimento de jogos, para aprimorar a versão digital do clássico Super Trunfo. Seu objetivo é criar um jogo dinâmico e envolvente, utilizando estruturas de decisão para implementar a lógica de comparação entre as cartas e menus interativos para aprimorar a experiência do jogador.

## 🎮 Nível Novato

No nível Novato, você deverá desenvolver um programa em C que simule o jogo Super Trunfo. O programa deverá: Implementar a lógica de comparação entre duas cartas, considerando diferentes atributos numéricos. Permitir ao jogador escolher entre diferentes atributos para a comparação através de menus interativos. Evoluir em complexidade ao longo dos três desafios. Comparação de cartas com base em um único atributo utilizando if e if-else.

### 🚩 Objetivo:
Seu programa em C deverá:
 
Receber os dados de duas cartas: O programa deve receber os dados de duas cartas do Super Trunfo. Utilize o código desenvolvido no desafio anterior para o cadastro das cartas. As cartas devem conter os seguintes atributos:
 Estado (string)
 Código da carta (string)
 Nome da cidade (string)
 População (int)
 Área (float)
 PIB (float)

## 🧩 Como compilar e executar

No terminal (CMD ou PowerShell), dentro da pasta do projeto:

```bash
gcc super_trunfo_novato.c -o novo super trunfo -Wall -Wextra -std=c11
novo super trunfo

  
### ⚙️ Funcionalidades do Sistema:
- O sistema permitirá exibir de forma clara, qual carta venceu a comparação, incluindo o atributo utilizado na comparação e os valores das duas cartas para aquele atributo, inserindo manualmente os dados via terminal de comando.
- Após o cadastro, o sistema exibirá os dados de cada cidade de forma clara e organizada.

### 📥 Entrada e 📤 Saída de Dados:
- O usuário insere os dados de cada carta interativamente.
- Após o cadastro, os dados são exibidos com todas as propriedades, uma por linha.

---

## 🛡️ Nível Aventureiro

Neste desafio, o Super Trunfo fica mais interessante! Você implementará um menu interativo usando switch para que o jogador possa escolher o atributo de comparação entre duas cartas de países. Além disso, você usará estruturas de decisão aninhadas (if-else dentro de if-else) para criar uma lógica de comparação mais complexa, considerando regras específicas para cada atributo. Este desafio é uma continuação do desafio anterior, onde você implementou o cadastro das cartas.

### 🆕 Diferença em relação ao Nível Novato:
  - Menu Interativo: Criar um menu interativo no terminal usando a estrutura switch que permita ao jogador escolher qual atributo será usado para comparar as cartas. O menu deve ser claro e fácil de usar.
  - Comparação de Atributos: Implementar a lógica de comparação entre duas cartas com base no atributo selecionado pelo jogador.

### ⚙️ Funcionalidades do Sistema:
- O sistema agora calculará automaticamente com base nos dados inseridos.

### 📥 Entrada e 📤 Saída de Dados:
- O usuário continua inserindo os dados de cada carta interativamente.
- O sistema exibirá os dados, incluindo as novas propriedades calculadas, de forma clara e organizada.

---

## 🏆 Nível Mestre

**No nível Mestre, o operador escreve uma função if-else em três partes:** 
Uma condição
Um valor se a condição for verdadeira
Um valor se a condição for falsa

### 🆕 Diferença em relação ao Nível Aventureiro:
- **Comparação de Cartas:**
  - Para um bom desenvolvedor é importante saber combinar diferentes estruturas de decisão para criar programas com lógica mais robusta e eficiente. As estruturas if, if-else e switch são fundamentais para tomar decisões baseadas em condições variadas.
  
### ⚙️ Funcionalidades do Sistema:
- O sistema utilizará operadores relacionais para determinar a carta vencedora com base nas propriedades comparadas.
- A comparação considerará:
  - Exibição Clara do Resultado: Mostre o resultado da comparação de forma clara e organizada, incluindo:
 O nome dos dois países.
 Os dois atributos usados na comparação.
 Os valores de cada atributo para cada carta.
 A soma dos atributos para cada carta.
 Qual carta venceu (ou se houve empate).

### 📥 Entrada e 📤 Saída de Dados:
- O usuário insere as cartas a serem comparadas.
- O sistema exibe os resultados das comparações, indicando a carta vencedora para cada propriedade.

---
