[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tro2Z-6l)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23170896&assignment_repo_type=AssignmentRepo)
# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:** [Diego Souza Pepe]
**Matrícula:** [20261100035]
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 10). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 10.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 10, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*

## 2. Evidência Visual (Screenshot)
Subi a imagem da print na pasta imagens.

## 3. Estratégia Utilizada
5 loops de avançar 50 e virar para a direita em 144° para formar apenas uma estrela e coloquei para o loop ser na cor amarela.
3 loops que além de incluir o loop acima também envolve ações de movimento como levantar a caneta, avançar em 150 para chegar na altura correta, abaixar a caneta e virar a direita em 120° para formar as 3 estrelas.
coloquei a cor branca.
virei a esquerda em 90° a partir do ultimo ponto que meu desenho havia chego para projetar o desenho da lua do lado esquerdo, levantei a caneta e  coloquei avançar 100 com a intenção de alcançar o ponto de origem da lua e abaixei a caneta.
criei um loop de repetição de 360 vezes avançando 50 e retornando 50 para voltar ao ponto de origem, porém sempre virando um 1° para esquerda com a finalidade de desenhar uma lua cheia.
agora para redesenhar a lua em sua forma crescente, coloquei a cor preta, virei a direita em 120° e avançar 20 e repliquei o loop da lua cheia para assim criar um circulo menor e com isso formar uma lua crescente.
## 4. Desafio:
**A)** 6 repetições do loop que desenha o hexágono e utilizando o ângulo de 60°
  
**B)** Para que se crie 4 hexágonos distruibuidos em um círculo precisa separar um a cada 90°
  
**C)** Para resolver a primeira dividi 360° pela quantidade de lados do hexágono:360/6=60°, para resolver a segunda dividi 360° de círculo completo pelo número de hexágonos totais da solitação que eram 4: 360/4=90°

---
