# Chrys Portfolio

> Portfólio pessoal de Chrystian Alexandre, criado para apresentar sua trajetória, experiências, projetos, conhecimentos e trabalhos ligados à comunicação visual, criação de conteúdo e design.

## Sobre o projeto

O **Chrys Portfolio** é um site desenvolvido para reunir, em um só lugar, informações sobre minha trajetória e produções. A proposta foi construir uma apresentação digital com identidade visual própria, navegação simples e seções que organizam os conteúdos de forma clara.

A direção visual utiliza uma base escura, com preto e tons próximos como fundo, vermelho como cor de destaque e tipografia de forte presença. Essa escolha busca criar contraste, personalidade e unidade entre as diferentes partes do site.

O conteúdo foi organizado para apresentar primeiro quem sou e meus interesses, depois minha formação e conhecimentos, seguido pelas experiências e projetos. Na seção de experiências, os trabalhos aparecem acompanhados de seus períodos, permitindo acompanhar essa trajetória em ordem cronológica.

## Estrutura do portfólio

- **Início:** apresentação do nome, área de atuação e introdução ao portfólio.
- **Sobre:** texto de apresentação, interesses e habilidades.
- **Educação:** formação e conhecimentos reunidos em cartões.
- **Experiências:** trabalhos e atividades apresentados com descrição, área e período.
- **Projetos:** seleção de produções e iniciativas, como produção de vídeos, Instagram escolar, YouTube, projeto EBAC/Figma, Revista Vértice e PLURAL.
- **Contato:** informações e links para contato.

## Tecnologias utilizadas

- **React:** construção da interface por meio de componentes.
- **JavaScript (ES6+):** lógica, dados e interações da aplicação.
- **JSX:** estruturação dos elementos da interface dentro dos componentes React.
- **HTML5:** estrutura base da página.
- **CSS3:** identidade visual, layouts, responsividade, efeitos e animações complementares.
- **Vite:** ambiente de desenvolvimento e ferramenta de build.
- **Framer Motion:** animações de entrada, transições e interações dos elementos.
- **Lenis:** implementação de rolagem suave.
- **React Icons:** utilização de ícones na interface.
- **Git e GitHub:** versionamento e hospedagem do código-fonte.

## Recursos implementados

- Navegação entre as seções do portfólio.
- Menu adaptado para dispositivos móveis.
- Tela inicial de introdução com animação.
- Barra de progresso conforme a rolagem da página.
- Animações de entrada e transição dos elementos.
- Efeitos de interação em botões, cartões e itens da interface.
- Rolagem suave.
- Layout responsivo para diferentes tamanhos de tela.
- Organização de experiências, formação, habilidades e projetos por meio de estruturas de dados reutilizadas nos componentes.

## Organização dos arquivos

```text
Chrys-Portfolio-main/
├── public/
│   ├── chrystian.png
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── assets/
│   │   └── layout/
│   │       └── main/
│   │           ├── Hero.jsx
│   │           └── style.css
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
├── eslint.config.js
└── README.md
```

O componente `App.jsx` concentra a estrutura principal da página e os dados exibidos nas seções. Os estilos estão organizados em arquivos CSS, enquanto os arquivos públicos guardam imagens e ícones utilizados pelo site.

## Como executar o projeto

É necessário ter o [Node.js](https://nodejs.org/) instalado.

1. Clone este repositório:

   ```bash
   git clone https://github.com/chrysalexx/meu-portfolio.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd meu-portfolio
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:

   ```bash
   npm run dev
   ```

5. Para gerar a versão de produção:

   ```bash
   npm run build
   ```

6. Para visualizar localmente a versão de produção:

   ```bash
   npm run preview
   ```

## Processo de desenvolvimento e aprendizados

Durante o desenvolvimento, trabalhei na definição da identidade visual, na organização das seções e na composição dos conteúdos apresentados no portfólio. A estrutura foi pensada para que a navegação acompanhasse uma sequência de apresentação: introdução, informações pessoais, formação, experiências, projetos e contato.

Na parte técnica, o projeto reúne práticas de desenvolvimento Front-end com React, organização de componentes, estilização com CSS, uso de bibliotecas para animações e ícones, adaptação da interface para diferentes telas e preparação da aplicação com Vite.

O processo também envolveu decisões de composição visual, hierarquia de informações, contraste, tipografia, espaçamento e interação, buscando manter uma identidade consistente ao longo de todo o site.

## Autoria

**Desenvolvido por Chrystian Alexandre Marcelino dos Santos.**

Portfólio pessoal: [chrysportfolio.vercel.app](https://chrysportfolio.vercel.app)  
GitHub: [@chrysalexx](https://github.com/chrysalexx)

---

*Transformando ideias em experiências digitais.*
