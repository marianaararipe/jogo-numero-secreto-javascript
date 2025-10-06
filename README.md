# 🎲 Jogo do Número Secreto  

Projeto desenvolvido durante o curso **"Lógica de programação: mergulhe em programação com JavaScript"** da [Alura](https://www.alura.com.br).  

## 📌 Sobre o projeto  
Este é um jogo interativo simples, onde o computador gera um **número secreto aleatório** entre 1 e 10, e o jogador deve tentar adivinhar.  
A cada tentativa, o jogo informa se o número secreto é **maior ou menor** que o chute. 
Além disso, o sistema **fala as mensagens em voz feminina em português** (via [ResponsiveVoice](https://responsivevoice.org/).

Quando o jogador acerta, o jogo exibe o número de tentativas e libera o botão de "**Novo jobo**", sorteando um novo número para continuar jogando.


## 🚀 Tecnologias utilizadas  
- **HTML** - estrutura da página
- **CSS3* - layout moderno, responsivo e estilização
- **JavaScript** - lógica do jogo e manipulação do DOM
-  **ResponsiveVoice** - síntese de voz em português brasileiro


## 🎮 Como jogar  
1. Abra o arquivo `index.html` no navegador.  
2.  Digite um número entre **1 e 10** no campo de input.
3.  Clique em “**Chutar**” para enviar sua tentativa.
4.  O jogo informará, por texto e voz, se o número secreto é **maior** ou **menor** que o chute.
5.  Continue tentando até acertar! 🎉
6.  Ao acertar, clique em “**Novo jogo**” para jogar novamente.


## 🧠 Lógica principal
- `gerarNumeroAleatorio()` → gera um número aleatório único entre 1 e 10, sem repetir até todos os números serem sorteados.
- `verificarChute()` → verifica se o chute está certo, exibe mensagens e conta tentativas.
- `exibirTextoNaTela()` → atualiza o texto na tela e aciona a voz sintetizada.
- `reiniciarJogo()` → reseta variáveis e sorteia um novo número.
- `limparCampo()` → limpa e foca o input após cada tentativa.



## ✨ Créditos 
Projeto desenvolvido com base no curso da [Alura](https://www.alura.com.br), com adaptações visuais e funcionais.
