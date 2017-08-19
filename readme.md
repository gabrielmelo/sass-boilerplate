# Sass Boilerplate

Sass Boilerplate é um pontapé inicial para projectos feitos em Sass. Nele traremos referencias as boas práticas abordadas em [SMACSS](https://smacss.com), [Sass Guidelines](https://sass-guidelin.es) e [CSS Guidelines](http://cssguidelin.es). Essa abordagem é flexível e passa por contastante mudança, evolução e correção quando necessário para o desenvolvimento Front-end diário.


## Instalação

```$ git clone https://github.com/gabrielmelo/sass-boilerplate.git``` ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip)

## Uso

Use o Sass Boilerplate no diretório de recursos do seu projeto após o clone do projeto ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip).

Para pré-processar o arquivo Sass em CSS execute: ``` sass --watch path/main.sass:path/main.css ```

Observação: Antes de útilizar o Sass como pré-processador para CSS, é necessário instalá-lo em sua máquina por meio de programas ou linha de comanado. Mais informações do processo [acesse](http://sass-lang.com/install)

## Sass Diretórios
1. Abstracts

2. Bases são os arquivos de predefinições para o projeto. Eles quase sempre serão aplicados a todas as páginas do projetos. O diretório base pode conter o seguinte tipo de arquivos Sass:

  - Reset
  - Fonts
  - Anchor
  - Animation
  - Typography
  - Utils

3. Componentes são formados por grupos de elementos que podem compor várias partes de um layout, sendo eles:

  - Alert
  - Avatar
  - Bredcrumb
  - Button
  - Carousel
  - Collapse
  - Slider
  - Hero
  - Tab
  - Pagination
  - Widgets

4. Elementos são itens ou pequena parte de estilo para compor um ou mais componentes. Exemplo de elementos:
  - Badge
  - Logo
  - Rating
  - Tag
  - Label

5. Layouts peças formadas por componentes aplicados repedidamente no template da página, são eles:
  - Article
  - Main Content
  - Footer
  - Grid
  - Header
  - Section
  - Sidebar

6. Pages contém um estilo específico à página em questão
  - Blog
  - Contact
  - Home

7. Themes
