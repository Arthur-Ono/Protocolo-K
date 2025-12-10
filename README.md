# 🔐 Protocolo K

> **Um Serious Game de Dedução, Estratégia e Criptografia Assimétrica.**

![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Plataforma](https://img.shields.io/badge/Plataforma-Tabletop_Simulator-blue)
![Gênero](https://img.shields.io/badge/Gênero-Puzzle_%7C_Educacional-green)

**Protocolo K** é um jogo de tabuleiro digital que simula uma "Escape Room" competitiva. Um grupo de investigadores deve lutar contra o tempo e contra um vilão humano (o Criptomaníaco) para quebrar códigos manuais clássicos e escapar de uma instalação industrial de alta segurança.

---

## 🕵️ Sobre o Jogo

Os investigadores da cidade caíram na armadilha do **Criptomaníaco** e agora devem completar seu desafio para escapar!

A mecânica central é baseada em **"Perícia Real"** (*Skill-based*): o jogo não resolve os enigmas por você. Os jogadores devem utilizar lápis, papel e ferramentas virtuais (como a Roda de César e a Tabela de Vigenère) para decifrar mensagens criptografadas na vida real.

### Destaques
* **1 vs Todos (Assimétrico):** Um jogador controla o sistema e as armadilhas, enquanto os outros cooperam para escapar.
* **Corrida de Decifração:** Resolva puzzles em tempo real competindo contra o vilão. Quem decifrar primeiro, ganha o controle da sala.
* **Educacional:** Aprenda a lógica por trás de 10+ métodos históricos de criptografia.
* **Atmosfera Imersiva:** Ambientação de thriller investigativo com documentos confidenciais e tensão constante.

---

## 🛠️ Instalação (Tabletop Simulator)

Para jogar **Protocolo K**, você precisa ter o jogo *Tabletop Simulator* instalado na Steam.

### Método 1: Arquivos Locais (Deste Repositório)
1.  Baixe este repositório (clique em `Code` > `Download ZIP`) e extraia os arquivos.
2.  Copie o arquivo `.json` (o save do jogo) da pasta `Build`.
3.  Cole o arquivo na sua pasta de saves do Tabletop Simulator:
    * **Windows:** `C:\Users\SEU_USUARIO\Documents\My Games\Tabletop Simulator\Saves\`
4.  Abra o jogo, vá em **Singleplayer/Multiplayer** > **Save & Load** e selecione o **Protocolo K**.

*(Se você planeja publicar na Steam Workshop, adicione o link aqui futuramente)*

---

## 🎮 Como Jogar (Resumo)

O jogo ocorre em um ciclo de turnos entre a **Equipe de Investigadores** e o **Criptomaníaco**.

### 1. O Objetivo
* **Investigadores:** Devem descobrir o **MÉTODO** e a **SENHA** da carta oculta "Protocolo Final". Para isso, precisam resolver cartas de "Confidencial" espalhadas pelo mapa para ganhar dicas.
* **Criptomaníaco:** Deve impedir a fuga até que o tempo (10 rodadas) acabe ou fazer os investigadores errarem o palpite final.

### 2. O Loop de Gameplay
1.  **Exploração:** Investigadores movem-se pelas salas e coletam recursos.
2.  **O Confronto:** Ao revelar uma carta de enigma, inicia-se uma **Corrida em Tempo Real**. Investigador e Vilão tentam resolver a cifra ao mesmo tempo usando papel e caneta.
    * *Investigador Vence:* Ganha uma DICA sobre o segredo final.
    * *Vilão Vence:* A sala é trancada e os jogadores são expulsos.
3.  **Sabotagem:** O Criptomaníaco usa cartas para criar armadilhas e acelerar o relógio.

---

## 🧩 Criptografias Inclusas

O jogo ensina e utiliza os seguintes métodos, divididos por dificuldade:

| Nível | Tipo | Exemplos |
| :--- | :--- | :--- |
| **Fácil** | Substituição Simples | Cifra de César, Atbash, A1Z26, T9, Inversão. |
| **Médio** | Transposição | Rail Fence (Cerca de Trilhos), Políbio, Transposição Colunar. |
| **Difícil** | Polialfabética | Cifra de Vigenère, Playfair, Auto-Chave. |

---

## ✒️ Autores

* Arthur Vicente Ono - Game Design e Game Mechanics
* Aiam Rodrrigo Barbosa Maia - Game Design e Game Mechanics
* Igor Gonçalves da Veiga - Game Design e Game Mechanics
* Vitor Lourenço Silva Monteiro - Game tester e Game Mechanics

---

## 📄 Licença

Este projeto está sob a licença CC BY-NC-SA 4.0 (LICENSE).
