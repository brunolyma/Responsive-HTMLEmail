# Modern HTML Email Template

Template de email marketing desenvolvido em **HTML + CSS**, com foco em **compatibilidade entre clientes de email**, especialmente **Outlook Desktop (Windows)**, conhecido por suas limitações de renderização.

Este projeto faz parte do meu portfólio como **Front-End Developer**, com interesse em vagas que envolvem **Email Marketing, HTML Emails e interfaces robustas para ambientes legados**.

---

## 👋 Sobre o Projeto

Diferente do desenvolvimento web tradicional, emails HTML exigem uma abordagem específica devido às limitações dos email clients — principalmente o Outlook, que utiliza o motor de renderização do **Microsoft Word**.

Este template foi desenvolvido respeitando essas limitações, priorizando:

- Estrutura estável
- Previsibilidade visual
- Compatibilidade entre clientes

O objetivo não foi apenas criar um layout visualmente agradável, mas um **email funcional em ambientes reais de produção**.

---

## 🧪 Testes e Compatibilidade

O template foi testado utilizando **Email on Acid**, simulando ambientes reais de leitura de email.

Clientes testados:

- Gmail (Web e Mobile)
- Outlook 2016 (Windows 10)
- Outlook Web
- Apple Mail
- Yahoo Mail

O layout mantém integridade visual mesmo em clientes com suporte limitado a CSS.

---

## 🧱 Estrutura e Abordagem Técnica

- Layout construído com **tabelas**, conforme boas práticas para email marketing
- Estilos essenciais aplicados **inline**
- CSS no `<style>` utilizado apenas como _progressive enhancement_
- Media queries aplicadas somente para clientes que oferecem suporte adequado
- Botões e seções estruturados de forma **bulletproof**, evitando dependência de propriedades não suportadas

---

## 🛠️ Tecnologias Utilizadas

- HTML (XHTML Transitional)
- CSS inline e interno
- Estrutura baseada em `<table>`
- Testes com Email on Acid

---

## ⚠️ Considerações Importantes sobre Outlook

O Outlook Desktop possui suporte limitado a CSS moderno. Algumas propriedades ignoradas incluem:

- `display: flex`
- `inline-block`
- `margin`
- `border-radius`
- media queries

Por esse motivo, o projeto prioriza:

- Estilos inline
- Estrutura simples e previsível
- Layout funcional acima de soluções visuais complexas

---

## 🎯 Objetivo Profissional

Este projeto foi desenvolvido com foco em:

- Prática avançada de **HTML para Email Marketing**
- Demonstração de conhecimento em **compatibilidade cross-client**
- Preparação para vagas de:
  - Front-End Developer
  - Email Developer
  - Email Marketing Developer

O código reflete situações reais encontradas em ambientes corporativos e plataformas de disparo de email.

---

## 🚀 Como Utilizar

1. Clone ou faça o download do repositório
2. Abra o arquivo `index.html`
3. Customize textos, imagens e links
4. Envie o HTML para sua plataforma de email marketing
5. Realize testes antes de disparos em produção

---

## 📌 Próximos Passos (Evolução do Projeto)

- Refatoração completa para versão 100% Outlook-safe
- Criação de variações de layout reutilizáveis
- Documentação de padrões bulletproof
- Implementação de dark mode fallback

---

## 📄 Licença

Projeto desenvolvido para fins de estudo, portfólio e demonstração técnica.
