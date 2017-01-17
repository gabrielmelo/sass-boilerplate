# Sass Boilerplate

Sass Boilerplate é um pontapé inicial para projectos feitos em Sass. Nele, traremos referencias as boas práticas abordadas em [SMACSS](https://smacss.com), (Sass Guidelines)[https://sass-guidelin.es] e [CSS Guidelines](http://cssguidelin.es). Essa abordagem é flexível e passa por contastante mudança, evolução e correção quando necessário para o desenvolvimento Front-end diário.


## Install

```$ git clone https://github.com/gabrielmelo/sass-boilerplate.git``` ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip)

## Use

Use o Sass Boilerplate no diretório de recursos do seu projeto após o clone do projeto ou [download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip).

Para pré-processar o arquivo Sass em CSS execute: ``` sass --watch path/main.sass:path/main.css ```

Observação: Antes de útilizar o Sass como pré-processador para CSS, é necessário instalá-lo em sua máquina por meio de programas ou linha de comanado. Mais informações do processo [acesse](http://sass-lang.com/install)

## Sass Directories

```
sass/
|
|– abstracts/
|   |– _variables.scss    # Sass Variables
|   |– _functions.scss    # Sass Functions
|   |– _mixins.scss       # Sass Mixins
|   |– _placeholders.scss # Sass Placeholders
|
|– base/
|   |– _reset.scss        # Reset/normalize
|   |– _typography.scss   # Typography rules
|   …                     # Etc.
|
|– elements/
|   |– _buttons.scss      # Buttons
|   |– _carousel.scss     # Carousel
|   |– _cover.scss        # Cover
|   |– _dropdown.scss     # Dropdown
|   …    
|– components/
|   |– _buttons.scss      # Buttons
|   |– _carousel.scss     # Carousel
|   |– _cover.scss        # Cover
|   |– _dropdown.scss     # Dropdown
|   …                     # Etc.
|
|– layout/
|   |– _navigation.scss   # Navigation
|   |– _grid.scss         # Grid system
|   |– _header.scss       # Header
|   |– _footer.scss       # Footer
|   |– _sidebar.scss      # Sidebar
|   |– _forms.scss        # Forms
|   …                     # Etc.
|
|– pages/
|   |– _home.scss         # Home specific styles
|   |– _contact.scss      # Contact specific styles
|   …                     # Etc.
|
|– themes/
|   |– _theme.scss        # Default theme
|   |– _admin.scss        # Admin theme
|   …                     # Etc.
|
`– main.scss              # Main Sass file
```