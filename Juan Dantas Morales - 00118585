css
/* Define cor variáveis */
:root {
  --color-light-background: #f9faff;
  --color-light-gray: #ccc;
}

body {
  margin: 0;
  background-color: #f9faff;
}

figure img {
  position: absolute; /* Em vez de absolute, para fixar na tela */
  right: 0px; /* Pequeno espaçamento da borda */
  top: 0px;
  width: 600px; /* Ajuste o tamanho conforme necessário */
  z-index: -1; /* Para garantir que fique acima de outros elementos */
  border-radius: 50%;   
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 120px;
  height: 56px;
}

.header-left span {
  font-size: 18px;
  line-height: 32px;
  color: var(--color-light-title);
  font-weight: bold;
}

.header-right button {
  margin-left: 24px;
  padding: 6px 12px;
  background-color: transparent;
  color: white;
  border: none; /* Remove a borda */
  border-radius: 5px; /* Mantém um leve arredondamento */
  cursor: pointer;
  font-size: 18px;
  text-decoration: none; /* Remove sublinhado, caso apareça */
  transition: color 0.3s, transform 0.3s; /* Adiciona uma transição suave */
}

.header-right button:hover {
  color: #ccc; /* Altere para uma cor de destaque ao passar o mouse */
  transform: scale(1.1); /* Dá um leve efeito de aumento ao passar o mouse */
}

/* Header alterado */

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 12px 120px;
  height: 56px;
}

.header-left h1 {
  font-size: 18px;
  line-height: 32px;
  color: var(--color-light-title);
  font-weight: bold;
}

/* Centraliza os botões na página */
.header-right {
  display: flex;
  justify-content: center; /* Centraliza os itens horizontalmente */
  align-items: center; /* Centraliza os itens verticalmente */
  height: 100vh; /* Faz a navegação ocupar toda a altura da tela */
}

.header-right {
  position: top;
  top: 20px; /* Ajusta a posição verticalmente */
  left: 50%; /* Centraliza na horizontal */
  transform: translateX(-124%); /* Ajusta para centralizar corretamente */
  display: flex;
  gap: 15px; /* Espaço entre os botões */
}

/* Estiliza os botões */
.header-right a {
  background-color: white; /* Fundo preto */
  color: black; /* Texto preto */
  padding: 6px 12px; /* Diminui o tamanho dos botões */
  border-radius: 5px; /* Bordas arredondadas */
  text-decoration: none; /* Remove sublinhado */
  font-size: 18px; /* Diminui o tamanho do texto */
  font-weight: bold;
  text-transform: uppercase;
  transition: background-color 0.3s, transform 0.3s;
  cursor: pointer;

}

/* Efeito ao passar o mouse */
.header-right a:hover {
  background-color: #6e6a6a; /* Tom mais claro no hover */
  transform: scale(1.1); /* Leve aumento */
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
}

nav ul li a {
  text-decoration: none;
  color: #333;
}

/* Style do about section */
.about {
  padding: 54px 120px 42px;
  max-width: 486px;
}

.about h2 {
  font-weight: bold;
  font-size: 64px;
  color: #25282b;
  margin-bottom: 32px;
  margin-top: 0;
}

.about p {
  font-size: 24px;
  line-height: 1.5;
  color: #828282;
  margin-bottom: 32px;
}

.about .buttons {
  display: flex;
  gap: 10px;
}

.about .buttons .primary {
  background-color: #2c2b2b;
  color: white;
  border: none;
  border-radius: 8px;
  padding: 8px 24px;
  height: 42px;
  cursor: pointer;
}

.about .buttons .secondary {
  background-color: transparent;
  border: 2px solid #2c2b2b;
  color: #2c2b2b;
  border-radius: 8px;
  padding: 8px 24px;
  height: 42px;
  cursor: pointer;
}

/* 1. Rotação Leve */
.about .buttons .primary:hover {
  color: #ccc;
  transform: rotate(10deg); /* Aplica uma rotação de 10 graus */
  transition: transform 0.3s ease; /* Suaviza a transição */
}


/* 2. Mudança de Cor e Sombras (hover) */
.about .buttons .secondaryS:hover {
  color: #fff;
  background-color: #2c2b2b; /* Muda o fundo do botão */
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3); /* Adiciona uma sombra suave */
  transform: scale(1.05); /* Um efeito de leve aumento */
  transition: background-color 0.3s, box-shadow 0.3s, transform 0.3s; /* Suaviza a transição */
}

/* 3. Animação de Deslocamento Horizontal */
.about .buttons .secondary:hover {
  transform: translateX(10px); /* Move o botão para a direita */
  transition: transform 0.3s ease-in-out; /* Suaviza o movimento */
}

projects,
.contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 80px;
  margin-bottom: 144px;
  text-align: center;
  font-size: 20px;
  margin-top: 40px;
}


/* Styles para a section dos projects */
.projects h2 {
  display: inline-block;
  position: relative;
  font-size: 36px; /* Ajuste o tamanho conforme necessário */
  font-weight: bold;
  margin-bottom: 16px;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 80px;
  margin-bottom: 144px;
}

.projects h2::after {
  content: "";
  position: absolute;
  bottom: -10px; /* Distância da linha do texto */
  left: 50%; /* Alinha a linha no centro */
  transform: translateX(-50%); /* Ajusta para centralizar perfeitamente */
  width: 50%; /* Largura da linha */
  height: 2px; /* Espessura da linha */
  background-color: black; /* Cor da linha */
}

.container {
  display: flex;
  flex-direction: column; /* Mantém os elementos empilhados verticalmente */
  align-items: center; /* Centraliza na horizontal */
  gap: 40px; /* Garante um bom espaçamento entre os elementos */
  width: 100%;
  margin: 0 10px;
  text-decoration: none;
  background-color: white;
 
}

.card { 
  display: flex;
  flex-direction: row;
  background: white;
  width: 992px;
  height: 524px;
  border-radius: 24px;
  border: solid 1px black;
  overflow: hidden;
}

.card-reverse {
  flex-direction: row-reverse;
}

.card-left, .card-right {
  flex: 1;
  padding: 132px 24px;
  border-radius: 24px 0 0 24px;


}

.card-right img {
 
  object-fit: cover;
  border-radius: 0 24px 24px 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  flex: 1;
  display: flex;
  align-items: center;
  justify-content: center;
}

/* Garante que a seção de contato fique abaixo dos cards */
.contato {
  text-align: center;
  font-size: 20px;
  margin-top: 40px;
}

.card-left h3 {
  font-size: 48px; /* Aumenta o tamanho do título */
  font-weight: bold;
  margin-bottom: 24px;
  margin-top: 0;
}

.card-left p {
  font-size: 18px; /* Tamanho do texto */
  color: #828282; /* Cor do texto */
  margin-bottom: 24px; /* Espaçamento abaixo do parágrafo */
}



.card-left button {
  background-color: white; /* Cor de fundo do botão */
  color: black; /* Cor do texto */
  padding: 8px 10px; /* Ajusta o tamanho do botão */
  font-size: 14px; /* Tamanho do texto */
  border: none;
  border-radius: 24px; /* Deixa o botão arredondado */
  border: 2px solid black;
  cursor: pointer;
  transition: 0.3s;
  font-weight: 138px 43px;
  padding-top: 8px;
}

.card-left button:hover {
  background-color: #403d3d; /* Escurece o botão no hover */
}

.contato-container {
  width: 100%;
  max-width: 600px;
  margin: 0 auto;
  padding: 50px 20px;
  text-align: center;
  font-size: x-large;
  
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px; /* Espaçamento entre os elementos */
}

input, textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

button {
  width: 150px; /* Define uma largura menor */
  height: 40px; /* Define uma altura menor */
  padding: 8px 12px; /* Ajusta o espaço interno */
  background: black;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px; /* Ajusta o tamanho da fonte */
  margin-left: auto; /* Empurra para a direita */
  display: block; /* Garante que o margin-left funcione corretamente */
}

/* Coloca no final da página */
footer {
  display: flex;
  justify-content: center;
  align-items: center;
  background: #f8f8f8;
  padding: 50px 0;
}

form label {
  display: block; /* Faz o label ocupar toda a largura disponível */
  text-align: left; /* Alinha o texto à esquerda */
  font-weight: bold; /* Deixa em negrito (opcional) */
  margin-bottom: 5px; /* Adiciona um pequeno espaçamento abaixo */
}

textarea {
  height: 150px; /* Define a altura do campo */
  resize: vertical; /* Permite redimensionar apenas na vertical */
}


footer {
  text-align: center;  /* Centraliza o conteúdo */
  padding: 20px;
  background-color: #f8f8f8; /* Cor opcional */
  display: flex;
  flex-direction: column; /* Coloca os elementos em coluna */
  align-items: center; /* Centraliza horizontalmente */
  justify-content: center; /* Centraliza verticalmente */
}

.social {
  display: flex;
  justify-content: center; /* Centraliza as imagens na horizontal */
  align-items: center; /* Garante alinhamento vertical */
  gap: 20px; /* Espaço entre as logos (ajuste conforme necessário) */
  width: 100%;
}
.redes-sociais img {
  width: 50px;  /* Tamanho das logos */
  height: auto; /* Mantém a proporção */
  gap: 20px;
  transition: transform 0.3s ease-in-out;
  margin: 0 10px; /* Ajuste o valor para definir o espaçamento desejado */
  gap: 15px; /* Define um espaçamento entre os ícones */

  
}

.social img:hover {
  transform: translateY(-8px); /* Move levemente para cima */
}

.footer-text {
  font-size: 16px;
  color: #333; /* Cor do texto */
  font-weight: bold;
  margin-top: 60px; /* Espaçamento entre as logos e o texto */
}

.footer {
  position: relative;
  width: 100%;
  height: auto;
  background-color: #222; /* Cor do fundo do rodapé */
  text-align: center;
}

.footer img {
  width: 100%; /* Faz a imagem cobrir toda a largura */
  height: auto;
  display: block; /* Evita espaços em branco abaixo da imagem */
}
