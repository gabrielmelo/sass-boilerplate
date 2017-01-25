# Sass Boilerplate

Sass Boilerplate é um pontapé inicial para projectos feitos em Sass. Nele traremos referencias as boas práticas abordadas em [SMACSS](https://smacss.com), (Sass Guidelines)[https://sass-guidelin.es] e [CSS Guidelines](http://cssguidelin.es). Essa abordagem é flexível e passa por contastante mudança, evolução e correção quando necessário para o desenvolvimento Front-end diário.


## Install

```$ git clone https://github.com/gabrielmelo/sass-boilerplate.git``` ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip)

## Use

Use o Sass Boilerplate no diretório de recursos do seu projeto após o clone do projeto ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip).

Para pré-processar o arquivo Sass em CSS execute: ``` sass --watch path/main.sass:path/main.css ```

Observação: Antes de útilizar o Sass como pré-processador para CSS, é necessário instalá-lo em sua máquina por meio de programas ou linha de comanado. Mais informações do processo [acesse](http://sass-lang.com/install)

## Sass Directories
1. Abstracts
2. Bases
  São os arquivos de predefinições para o projeto. Eles quase sempre serão aplicados a todas as páginas do projetos. O diretório base pode conter o seguinte tipo de arquivos Sass:
  - Reset
  - Fonts
  - Anchor
  - Animation
  - Typography
  - Utils
  
3. Components
  Componentes são formados por elementos que compões o layout, são eles:
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

4. Elements
  Elementos são itens que compões um componente. Exemplo de elementos:
  - Badge
  - Logo
  - Rating
  - Tag

5. Layouts
  Layouts peças formadas por componentes aplicados repedidamente no template da página. São eles:
  - Article
  - Main Content
  - Footer
  - Grid
  - Header
  - Section
  - Sidebar

6. Pages


7. Themes
