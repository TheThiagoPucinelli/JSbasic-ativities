# Exercícios de Linguagem de Programação II

Este repositório contém os exercícios realizados para a disciplina de Linguagem de Programação II do Curso Técnico de Desenvolvimento de Sistemas.

---

## Exercícios Desenvolvidos

### 1. Letreiro de Hotel
- Criação de um letreiro em HTML e CSS que exibe o nome do hotel e a indicação de vagas.
- Ao passar o cursor do mouse sobre o letreiro, a disponibilidade de vagas muda.
- Ao retirar o cursor, a disponibilidade retorna ao estado original.
- Uso de JavaScript para manipulação dos eventos de mouse, identificando-os pela propriedade `event.type`.
- Sem uso de imagens, apenas HTML, CSS e JS.

### 2. Lâmpada e Interruptor
- Estrutura HTML contendo uma lâmpada e um interruptor.
- Ao clicar no interruptor, a lâmpada acende e o interruptor muda de posição.
- Ao clicar novamente, a lâmpada apaga e o interruptor retorna à posição inicial.
- Manipulação de eventos de clique para alternar o estado da lâmpada e do interruptor.

### 3. Galão de Água com Torneira
- Galão de água representado por um elemento `<div>` com imagem de fundo ilustrando a água.
- Torneira representada por uma imagem.
- Ao pressionar a torneira, a imagem muda para uma torneira pingando e o nível da água diminui progressivamente.
- Ao soltar a torneira, o nível para de diminuir e a torneira volta à imagem original.
- Uso de intervalos e animações para simular o esvaziamento da água e bolhas.

### 4. Validação de CPF
- Formulário com campo de CPF.
- Validação para aceitar apenas números, utilizando a propriedade `keyCode` no evento de teclado.
- Prevenção da digitação de caracteres inválidos.
- Exibição de alerta caso o usuário tente digitar caracteres não numéricos.

### 5. Campo Nome com Maiúsculas
- Formulário com campo para nome.
- Após o usuário preencher o campo, todas as letras são convertidas para maiúsculas automaticamente.
- Utilização do método JavaScript `toUpperCase()` para conversão.

### 6. Estilização de Campos Nome e CPF
- Ao focar nos campos de nome e CPF, a cor da borda e o fundo são alterados para destacar o campo ativo.
- Ao perder o foco, a formatação retorna ao estado original.
- Uma única função trata os dois eventos (`focus` e `blur`), utilizando `event.target` e `event.type` para identificar o campo e o evento acionado.

---

## Estrutura do Projeto

- `/1.letreiro.html` — Letreiro interativo
- `/2.lampada.html` — Lâmpada com interruptor
- `/3.agua.html` — Galão de água com torneira
- `/4.formulario.html` — Formulário com validação de CPF
- `/5.uppercase.html` — Campo de nome que converte texto para maiúsculas
- `/6.target_type.html` — Estilização dinâmica dos campos Nome e CPF
- `/menu.html` — Menu principal com links para todos os exercícios
- `/menu.css` — Estilos utilizados no menu e nos cards de exercícios

---

## Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox e Transitions)
- JavaScript (DOM, Eventos, Manipulação de Estilos)


