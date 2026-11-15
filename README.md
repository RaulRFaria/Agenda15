# Meu Portfólio — Raul Faria

## Tecnologias utilizadas

- HTML5: estrutura da página.
- CSS3: cores, espaçamentos e animações.
- Bootstrap 5.3.3: menu responsivo, grade de projetos, cartões e botões.
- Python: linguagem estudada, apresentada na seção de Habilidades (não é executada por este site).
- SVG: imagens das tecnologias Python, HTML e CSS, salvas na pasta `imagens/`.

## Funcionamento do projeto

A página contém um menu com links para as seções Perfil, Projetos, Habilidades e Contato. Ao clicar em cada item do menu, o navegador vai até a seção correspondente. Na área de Projetos, os trabalhos ficam organizados em cartões. O Bootstrap adapta a disposição dos cartões e do menu ao tamanho da tela. Na seção Contato, há um botão para abrir o programa de e-mail do visitante.

## Recurso novo adicionado

Foram incluídos dois recursos extras:

1. **Animação ao passar o mouse nos cartões dos projetos:** o cartão sobe um pouco e recebe uma sombra.
2. **Nova seção de Habilidades:** mostra as linguagens que estou estudando com imagens locais de Python, HTML e CSS.

## Como os recursos foram implementados

- **Animação:** no arquivo `style.css`, a classe `.projeto-card` utiliza `transition` para suavizar o movimento. Com `.projeto-card:hover`, as propriedades `transform: translateY(-8px)` e `box-shadow` criam o efeito quando o mouse passa sobre o cartão.
- **Seção Habilidades:** foi criada uma seção HTML com `id="habilidades"`, usando cartões do Bootstrap com imagens em SVG das tecnologias Python, HTML e CSS na pasta `imagens/`. Também foi acrescentado o link correspondente no menu de navegação.

## Como executar o projeto

1. Baixe o projeto e extraia o ZIP mantendo `index.html`, `style.css` e a pasta `imagens/` juntos.
2. Abra `index.html` no navegador ou use a extensão Live Server no VS Code.
3. As três imagens funcionam mesmo sem internet. O Bootstrap é carregado de um CDN e precisa de internet para funcionar corretamente.