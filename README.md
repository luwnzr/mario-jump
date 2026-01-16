# 🍄 Mario Jump - Jogo em JavaScript

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🎮 Sobre o Projeto

Este é um mini-game estilo *Endless Runner* desenvolvido com **HTML, CSS e JavaScript**. O objetivo é controlar o Mario para pular sobre os tubos que se movem em direção ao jogador.

O projeto foca na manipulação do **DOM**, tratamento de eventos de teclado e, principalmente, na lógica de colisão entre elementos animados.

## 🕹️ Como Jogar

1.  Abra o jogo no navegador.
2.  Pressione **qualquer tecla** do teclado para fazer o Mario pular.
3.  Evite tocar no tubo verde.
4.  Se colidir, o jogo acaba (Game Over).

## 🚀 Tecnologias e Conceitos Aplicados

### 🎨 CSS3 (Animações)
O movimento do jogo é criado inteiramente com CSS:
* **`@keyframes pipe-animation`**: Move o tubo da direita para a esquerda infinitamente.
* **`@keyframes jump`**: Controla a altura e suavidade do pulo do Mario.
* **`@keyframes clouds-animation`**: Move as nuvens lentamente para criar efeito de paralaxe/profundidade.

### ⚙️ JavaScript (Lógica do Jogo)
* **Event Listener (`keydown`):** Captura a interação do usuário para ativar a função de pulo.
* **Loop de Verificação (`setInterval`):** Um loop roda a cada **10ms** para verificar a posição dos elementos.
* **Manipulação de Classes:** Adiciona e remove a classe `.jump` para ativar a animação CSS apenas quando necessário.

💻 Como Executar
Clone este repositório.

Certifique-se de que as imagens estão na pasta ./imagens.

Abra o arquivo index.html no seu navegador.

🤝 Autor
Desenvolvido por Luane.

Projeto desenvolvido para fins de estudo de lógica de programação e animações web.

![Preview do Jogo](imagens/gameplay.JPG) <!-- Adicione uma imagem de preview se tiver -->


