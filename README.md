# Alex Sander — Portfólio frontend

Site: [Abrir portfólio](https://alexmanhes.github.io/portfolio/)

Portfólio estático em português com a bio e os textos fornecidos por Alex Sander. Apresenta trajetória, repertório técnico, três projetos e formas de contato.

## Conteúdo

- Bio e apresentação para oportunidades de desenvolvimento frontend júnior.
- Sobre mim, preservando os três parágrafos enviados.
- Resolve Chamados, Simulados ENEM e Nexo CRM, com descrições completas, tecnologias, prévias ampliáveis e links para aplicação e código.
- Contato por e-mail, LinkedIn e GitHub; botão para copiar o e-mail.
- Menu adaptado para celular, navegação por âncoras, indicação de seção atual, links de salto, foco visível e respeito à preferência por redução de movimento.

As imagens são capturas das aplicações com dados fictícios, feitas em prévias locais isoladas. Nenhum registro do armazenamento local do navegador foi incorporado. React, Angular e Figma são apresentados como repertório informado pelo autor; as três aplicações destacadas são identificadas como HTML, CSS e JavaScript.

## Executar

```sh
node serve.cjs
```

Abra `http://127.0.0.1:8796`. No GitHub Pages, publique a branch `main` pela raiz (`/`). Não há dependências, formulário de envio, rastreamento ou processamento de dados no servidor. O link de e-mail abre o aplicativo de e-mail do visitante; o botão de copiar usa a área de transferência quando permitida.

## Organização

```text
index.html
css/styles.css
js/app.js
assets/           # Prévias e favicon locais
serve.cjs
```

As fontes Space Grotesk e DM Sans são carregadas do Google Fonts, com alternativas do sistema. Contatos profissionais e links externos foram fornecidos pelo usuário. Edite os conteúdos no HTML e, ao alterar links das aplicações, ajuste também o mapa de prévias em `js/app.js`.
