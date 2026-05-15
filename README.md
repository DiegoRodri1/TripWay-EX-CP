# TripWay

## Integrantes

- Artur Esteves - RM569450
- Diego Barbosa - RM568829
- João Fontenele - RM570783

## Turma

1TDSPX-2026

## Descrição

Projeto desenvolvido para a disciplina de Front-End, com o objetivo de criar um site multipágina para uma empresa fictícia de viagens.

## Evolução do Projeto

No Checkpoint 1, o foco foi a estrutura HTML, páginas, navegação, formulário e colaboração com GitHub.

No Checkpoint 2, o projeto foi evoluído com CSS externo, identidade visual baseada em Azul Royal e Branco, layout com Flexbox, uso de variáveis CSS, pseudo-classes (`:hover` e `:focus`), transições suaves e responsividade completa para Desktop, Tablet e Celular.

### Principais melhorias do Checkpoint 2:

- Folha de estilos externa em `tripway/css/style.css`
- Remoção de todo o CSS interno (`<style>` no head e `style="..."` inline) das 4 páginas
- Reset de margens/paddings e `box-sizing: border-box`
- Variáveis CSS no `:root` para cores, fontes, espaçamentos e sombras
- Tipografia profissional com Google Fonts (Poppins e Montserrat)
- Layout com Flexbox para header, menu, cards e formulário
- Cards de destinos e pacotes responsivos
- Formulário de contato estilizado com `:focus` e validação visual
- Media queries para Tablet (≤768px) e Mobile (≤480px)
- Transições suaves nos elementos interativos
- Substituição das imagens externas por imagens locais da pasta `images/`
- Adição de `alt` em todas as imagens

## Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Variáveis CSS, Media Queries)
- Git
- GitHub

## Páginas

- Home
- Destinos
- Pacotes ou Serviços
- Contato ou Reserva

## Estrutura de Pastas
tripway/
├── index.html
├── pages/
│   ├── destinos.html
│   ├── pacotes.html
│   └── contato.html
├── css/
│   └── style.css
└── images/
├── banner.png
├── logo.png
├── praia.png
├── lugardetrilhadosEUA.png
├── londres-nuit.jpg
└── pacote de viagens.png
## Como executar

1. Clone o repositório:
   `git clone https://github.com/DiegoRodri1/TripWay-EX-CP.git`
2. Abra o arquivo `tripway/index.html` no navegador.