# Reinaldo Koch — Portfólio Pessoal

Site pessoal em página única (one-page) desenvolvido com **HTML, CSS e JavaScript puros**, sem frameworks ou build tools. Reúne apresentação profissional, currículo e portfólio de projetos em uma interface escura, moderna e totalmente responsiva.

🔗 **Demo:** _adicione aqui o link do GitHub Pages / Netlify / Vercel, se houver_

## Preview

_adicione aqui um screenshot do site, por exemplo:_
```md
![Preview do site](preview.png)
```

## ✨ Funcionalidades

- **Navegação em abas (SPA-like)** — troca entre as seções *Sobre mim*, *Currículo* e *Portfolio* sem recarregar a página
- **Sidebar de contato retrátil** — em telas menores, os dados de contato ficam ocultos atrás de um botão "Mostrar Contato"
- **Timeline de formação e experiência** — linha do tempo estilizada para educação e histórico profissional
- **Barras de habilidades animadas** — indicadores visuais de nível de competência
- **Filtro de projetos por categoria** — botões para filtrar o portfólio entre Designer e Audiovisual, Marketing e Projetos
- **Formulário de contato com validação nativa** — botão de envio habilitado apenas quando os campos obrigatórios são preenchidos
- **Totalmente responsivo** — layout adaptado para desktop, tablet e mobile

## 🛠️ Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — variáveis CSS (custom properties), Grid e Flexbox, animações e media queries
- **JavaScript (vanilla)** — manipulação de DOM, sem dependências de frameworks
- **[Ionicons](https://ionic.io/ionicons)** — biblioteca de ícones via CDN
- **[Google Fonts](https://fonts.google.com/specimen/Poppins)** — fonte Poppins

## 📁 Estrutura do projeto

```
.
├── index.html      # Estrutura, estilos e scripts do site (arquivo único)
└── README.md       # Este arquivo
```

> O projeto é intencionalmente construído em um único arquivo `index.html`, contendo HTML, CSS (`<style>`) e JavaScript (`<script>`) — ideal para hospedagem simples e sem etapas de build.

## 🚀 Como rodar localmente

Por não depender de nenhuma ferramenta de build, basta:

1. Clonar o repositório
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```
2. Abrir o arquivo `index.html` diretamente no navegador

   **ou**, para evitar eventuais bloqueios de CORS/módulos, servir com um servidor local simples:
   ```bash
   # com Python
   python3 -m http.server 8000

   # ou com Node (npx)
   npx serve .
   ```
3. Acessar `http://localhost:8000` no navegador

## ✏️ Personalização

Para adaptar este site a outro perfil:

- **Dados pessoais e contato**: edite a seção `<aside class="sidebar">` (nome, cargo, e-mail, telefone, endereço)
- **Sobre mim e habilidades**: edite a seção `<article class="about">`
- **Currículo**: edite as listas dentro de `<article class="resume">` (educação, experiência e barras de skill)
- **Projetos do portfólio**: edite os itens de `<ul class="project-list">` dentro de `<article class="portfolio">`, ajustando título, categoria (`data-category`) e imagem
- **Cores e identidade visual**: ajuste as variáveis CSS no topo do arquivo, em `:root`
  ```css
  :root {
    --bg-main: #1e1e20;
    --accent: #ffb100;
    /* ... */
  }
  ```

## 📄 Licença

Este projeto está disponível para uso pessoal. Sinta-se à vontade para usá-lo como base para o seu próprio portfólio, dando os devidos créditos.

## 📬 Contato

**Reinaldo Koch**
Marketing | Design | Comunicação
📧 koch.rei@gmail.com
