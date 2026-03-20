# Lab 01: Lógica de Programação com Blockly 🐢

Bem-vindo(a) à sua atividade prática de Lógica Computacional! Siga os passos abaixo para completar o desafio.

**Nome do Aluno:** Arthur Monteiro Pereira
**Matrícula:** 20261100046
---

## 🎯 Objetivo
Demonstrar capacidade de resolução de problemas algorítmicos completando o **Nível 10** do jogo da Tartaruga (Turtle). 

## 📝 Instruções

**Passo 1: Jogue e Resolva**

Acesse o jogo da Tartaruga no [Blockly Games](https://blockly.games/turtle) e complete as etapas até vencer o **nível 10**.

**Passo 2: Registre sua Solução**

Tire um screenshot (captura de tela) da sua solução final (mostrando os blocos que você usou para passar do nível 9). Faça o upload (envio) dessa imagem **dentro da pasta /imagens** que já existe neste repositório.

**Passo 3: Explique sua Estratégia**

Escreva um pequeno texto explicando qual foi a sua linha de raciocínio e a estratégia que você usou para resolver o nível 9.
*(Exemplo: "Criei uma função para desenhar uma estrela, depois usei um loop para repetir essa função 3 vezes girando 120 graus.")*

**Passo 4: Pergunta Desafio**

Olhando para os blocos que você usou para resolver o jogo no nível 9, imagine que o problema mudou. A sua nova missão agora é desenhar um **hexágono regular** (uma figura geométrica de 6 lados iguais) e repetir esse hexágono **4 vezes**, formando um padrão circular (como as pétalas de uma flor).

**Sem precisar montar os blocos** no jogo, responda por escrito:
* **A)** Quantas repetições o seu loop principal (que desenha o hexágono) precisaria ter e qual seria o ângulo (em graus) que a tartaruga deve virar a cada linha desenhada?
* **B)** Depois de desenhar um hexágono completo, qual deve ser o ângulo de giro (em graus) antes de começar a desenhar o próximo hexágono, para que os 4 fiquem distribuídos igualmente em um círculo completo?
* **C)** Explique brevemente qual foi a lógica (ou o cálculo) que você usou para descobrir os ângulos das questões A e B.

---

## ✍️ Suas Respostas

*(Edite este arquivo e escreva suas respostas dos Passos 3 e 4 aqui embaixo. Lembre-se de colocar a imagem do Passo 2 dentro da pasta **/imagens** deste repositório)*

## 2. Evidência Visual (Screenshot)
*Pronto

## 3. Estratégia Utilizada
*Usei um código que repete 3 vezes um código para gerar a estrela (que cria 5 linha em um angulo de 144º e que se move para a ponta da próxima estrela a ser desenhada), centralizei a tartaruga no centro da Lua, criei um grande círculo branco (indo e voltando criando linhas em um ângulo de 1º 360 vezes) e movi a tartaruga para a diagonal direita superior para criar um círculo preto, fazendo com que ele obstruisse parte do círculo branco e fazendo eles formarem uma Lua.

## 4. Desafio:
**A)** O loop que desenha o hexágono precisaria repetir 6 vezes um comando que cria uma linha e move a tartaruga a 60º para desenhar a próxima linha do hexágono
  
**B)** 90º
  
**C)** Para descobrir o ângulo para desenhar o hexágono, basta considerar que os angulos internos de uma forma (exceto o triângulo) somados dão 360º, como um hexagono tem 6 lados, basta dividir o angulo interno total pelos lados para descobrir o angulo de cada linha. Depois, sabendo que formar 4 hexagonos juntos como pétalas formaria um quadrado no meio, bastou fazer o mesmo para fazer a base do próximo hexágono ficasse posicionada perfeitamente para unir os hexagonos da forma pedida.

---
