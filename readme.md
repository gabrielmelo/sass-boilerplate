# Sass Boilerplate

> Sass Boilerplate é um pontapé inicial para projetos em [Sass](https://sass-lang.com) e com estrutura baseada no [7-1 architecture pattern](http://sass-guidelin.es/#architecture). Você encontrará várias referências a [SMACSS](https://smacss.com), [Sass Guidelines](https://sass-guidelin.es) e [CSS Guidelines](http://cssguidelin.es).

![](header.png)

## Installation

```sh
git clone https://github.com/gabrielmelo/sass-boilerplate.git
```

[download](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip)

## Organização de arquivos

### The 7-1 pattern

- `abstracts/` Insira suas `variables`, `functions`, `mixins`, `placeholders`, `utils` ou `helpers` nesta pasta.  
  
- `base/` Nesta pasta, podemos considerar a inclusão de todo nosso código padrão de CSS. Devemos considerar código que alteram a estrutura base do nosso projeto. Exemplo: resets, regras de tipografia, animações. Caso seu projeto utilize classes utilitárias(`margin-left-2`), considere incluí-las aqui. Do contrário, se utiliza por meio de placeholders, aconselho utilizar a pasta `abstracts`.

- `components/` Nesta pasta, include todos nossos componentes usados para construir do projeto. São eles: `buttons`, `slides`, `forms` e etcs.

- `layouts/` Contém todas as partes que compõem o layout do projeto. Esta pasta deve ter os principais estilos da página. Como: `header`, `footer`, `navigation`, `sidebar`.  O sistema de `grid`, `user-form` e outros formulários inclusos em páginas, também podem ser armazenados nesta área. 

- `pages/` Nesta pasta, caso seu projeto possua estilo diferente para diferentes páginas, insira seu estilo em `pages`. Exemplos: `blogs`, `single`, `contact`, `404`. 

- `themes/` A maioria dos sites podem ter alguns temas, como: `admin`, `light`, `dark`. Caso seu projeto possua vários temas, esta é a área para ser armazenada o arquivo.

- `vendor/` Caso seu projeto tenha `Font Awesome`, `Bootstrap`, `Jquery UI` e outras `libs`, este é o lugar para eles.


### Arquivo principal

- `main.sass`
