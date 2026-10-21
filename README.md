# Criando-seu-Primeiro-Site-Completo-com-HTML.
# 🏥 Projeto Clínica Médica "Cuidar +" — Desafio de HTML/CSS (DIO) do Curso: "Formação HTML Web Developer".

Olá! 👋 Este repositório contém o meu projeto desenvolvido para o desafio de HTML5 e CSS3. 

O objetivo principal foi construir o site funcional de uma clínica médica com 4 páginas conectadas, aplicando na prática os conceitos essenciais do desenvolvimento web básico.

---

## 🎨 O Que Foi Desenvolvido?

O site foi estruturado com um layout clássico de **Menu Lateral (Sidebar)**, dividindo a tela entre uma navegação fixa à esquerda e uma área principal à direita contendo cabeçalho com imagem, área de conteúdo e rodapé padronizado.

### Páginas do Projeto:
1. **`index.html` (Página Principal):** Apresentaçã e boas-vindas à clínica com uma imagem da recepção e uma introdução aos serviços.
2. **`sobre.html` (Sobre a Clínica):** Conta a história, missão e valores da instituição, acompanhada de uma imagem da equipe médica.
3. **`horario.html` (Horários de Atendimento):** Traz uma tabela organizada com o quadro de horários e especialidades oferecidas durante os dias da semana, sábados e feriados.
4. **`contato.html` (Contato e Localização):** Possui as informações de telefone/WhatsApp, formulário para envio de mensagens e um mapa interativo (**Google Maps**) apontei para uma localização na **Ilha de Páscoa** 🗿!

---

## 🛠️ O Que Aprendi e Quais Tags Utilizei?

Durante o desenvolvimento, priorizei o uso de **HTML Semântico** (para dar significado às partes do site) e um **CSS separado e organized**, ideal para quem está iniciando.

### 📝 Tags HTML Utilizadas:
* **Estrutura Semântica:** 
  * `<nav>`: Para organizar a barra lateral de navegação.
  * `<header>`: Para destacar o cabeçalho no topo da área principal.
  * `<main>`: Para englobar o conteúdo exclusivo de cada página.
  * `<footer>`: Para o rodapé com informações de contato padrão.
* **Tabelas (`horario.html`):**
  * `<table>`: O contêiner da tabela.
  * `<thead>` e `<tbody>`: Para dividir o cabeçalho e o corpo dos dados.
  * `<tr>`, `<th>` e `<td>`: Para criar as linhas, títulos de colunas e células com os horários.
* **Formulários (`contato.html`):**
  * `<form>`: Estrutura do formulário de envio.
  * `<label>`: Rótulo explicativo para cada campo.
  * `<input type="text">` e `<input type="email">`: Caixas para digitação de texto simples e e-mail.
  * `<textarea>`: Caixa para mensagens mais longas.
  * `<button type="submit">` e `<button type="reset">`: Botões de envio e limpeza do formulário.
* **Mídias e Recursos:**
  * `<img>`: Imagens temáticas cortadas para o cabeçalho (usando o banco de imagens *Unsplash*).
  * `<iframe>`: Incorporação do Google Maps na página de contato.

---

## 🎨 Estilização com CSS (`style.css`)

O CSS foi criado em um **único arquivo externo** e importado em todas as páginas via `<link rel="stylesheet">`. 

### Destaques do CSS:
* **Layout Flexbox (`display: flex`):** Utilizado na `.wrapper` para posicionar o menu lateral à esquerda (20%) e a área principal à direita (80%).
* **Menu Interativo:** O fundo do menu recebeu um tom de azul claro e suave (`#ebf8ff`), enquanto os links foram estilizados como **botões em azul escuro** com efeito ao passar o mouse (`:hover`), dando destaque visual sem cansar a vista.
* **Efeito Zebra em Tabelas:** Uso da regra `table tr:nth-child(even)` para alternar as cores das linhas da tabela, facilitando a leitura dos horários.
* **Formulários Organizados:** Uso de `flex-direction: column` para alinhar os campos do formulário em fila com espaçamentos regulares (`gap`).

---

## 📁 Estrutura de Arquivos

```text
├── index.html       # Página Principal
├── sobre.html       # Sobre a Clínica
├── horario.html     # Horários de Atendimento (Tabela)
├── contato.html     # Contato (Formulário + Google Maps)
└── style.css        # Folha de estilo unificada e comentada
