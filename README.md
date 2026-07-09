# 🎯 Jogo do Número Secreto

<div align="center">

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/oliverqueenx3/numero-secreto?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/oliverqueenx3/numero-secreto?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/oliverqueenx3/numero-secreto?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/oliverqueenx3/numero-secreto?style=for-the-badge)

</div>

## 📖 Sobre o projeto

O **Jogo do Número Secreto** é uma aplicação web desenvolvida com **HTML**, **CSS** e **JavaScript**. O objetivo é desafiar o jogador a descobrir um número aleatório entre **1 e 50**, recebendo dicas durante a partida.

O projeto também utiliza a biblioteca **ResponsiveVoice**, que faz a leitura das mensagens exibidas na tela, proporcionando uma experiência mais interativa e acessível.

---

## 🚀 Demonstração

> Em breve...

---

## ✨ Funcionalidades

- 🎲 Geração aleatória de números entre **1 e 50**
- 🔄 Evita repetir números já sorteados
- 📢 Dicas informando se o número secreto é maior ou menor
- 🔢 Contador de tentativas
- 🔊 Leitura em voz das mensagens utilizando ResponsiveVoice
- 🧹 Limpeza automática do campo de entrada
- 🔁 Reinício da partida com um novo número secreto

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6)
- ResponsiveVoice.js

---

## 📂 Estrutura do projeto

```text
numero-secreto/
│
├── index.html
├── style.css
├── app.js
├── img/
└── README.md
```

---

## ▶️ Como executar

Clone o repositório:

```bash
git clone https://github.com/oliverqueenx3/numero-secreto.git
```

Acesse a pasta:

```bash
cd numero-secreto
```

Abra o arquivo `index.html` em seu navegador.

Não é necessário instalar dependências ou executar comandos adicionais.

---

## 🎮 Como jogar

1. Digite um número entre **1 e 50**.
2. Clique no botão para verificar seu palpite.
3. Caso erre, o jogo informará se o número secreto é **maior** ou **menor**.
4. Continue tentando até acertar.
5. Ao vencer, clique em **Novo Jogo** para iniciar outra partida.

---

## ⚙️ Funcionamento

### `gerarNumeroAleatorio()`

Responsável por gerar um número aleatório entre 1 e 50, garantindo que ele não tenha sido sorteado anteriormente.

### `verificarChute()`

Compara o número informado pelo jogador com o número secreto e fornece as dicas necessárias.

### `exibirTextoNaTela()`

Atualiza os elementos HTML e utiliza a biblioteca ResponsiveVoice para narrar as mensagens.

### `limparCampo()`

Limpa o campo de entrada após cada tentativa.

### `reiniciarJogo()`

Reinicia a partida, gera um novo número secreto e redefine o contador de tentativas.

---

## 💡 Melhorias futuras

- [ ] Sistema de níveis (Fácil, Médio e Difícil)
- [ ] Cronômetro
- [ ] Ranking de jogadores
- [ ] Histórico de partidas
- [ ] Tema claro/escuro
- [ ] Sons e animações
- [ ] Responsividade aprimorada
- [ ] Modo multiplayer

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas!

1. Faça um Fork do projeto.
2. Crie uma branch para sua feature.

```bash
git checkout -b minha-feature
```

3. Faça o commit das alterações.

```bash
git commit -m "feat: minha nova feature"
```

4. Faça o push.

```bash
git push origin minha-feature
```

5. Abra um Pull Request.

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

---
