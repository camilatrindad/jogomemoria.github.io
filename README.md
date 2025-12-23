# 🐹 Jogo da Memória - Hamtaro Edition

Um jogo da memória clássico, responsivo e temático, desenvolvido com foco em interatividade e experiência do usuário (UX). O projeto apresenta uma estética "fofa" inspirada no universo Hamtaro, com animações suaves e efeitos visuais dinâmicos.

##  Tecnologias Utilizadas

* **HTML5:** Estruturação semântica.
* **CSS3:** Design responsivo (Mobile First), Variáveis CSS, Flexbox, Grid e Animações complexas (`@keyframes`).
* **JavaScript (ES6+):** Lógica do jogo, manipulação de DOM, gerenciamento de estados (cards virados, travas de clique) e cronômetro.

## ✨ Funcionalidades

* **Pré-visualização:** Ao iniciar, as cartas são reveladas por 2 segundos para o jogador memorizar.
* **Sistema de Pontuação:** Contador de tentativas e cronômetro em tempo real.
* **Feedback Visual:** Efeito de brilho animado (*flame-glow*) nas cartas viradas.
* **Responsividade:** Interface adaptável para diferentes tamanhos de tela (desktop, tablets e smartphones).
* **Áudio:** Música de fundo ambiente que inicia após a primeira interação do usuário (respeitando as políticas de autoplay dos navegadores).

## 🛠️ Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone  [https://github.com/camilatrindad/jogomemoria.github.io](https://github.com/camilatrindad/jogomemoria.github.io)

   Abra o arquivo index.html em qualquer navegador.

Desafios Técnicos Implementados

Lógica de Match: Verificação de igualdade entre as cartas com "lock" temporário para evitar múltiplos cliques simultâneos.

Perspectiva 3D: Uso de perspective e backface-visibility no CSS para criar o efeito realista de virada de carta.

Shuffle: Algoritmo de ordenação aleatória para garantir que cada partida seja única.
