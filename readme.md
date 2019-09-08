# Sass Boilerplate

> Sass Boilerplate é um pontapé inicial para projetos em [Sass](https://sass-lang.com) e com estrutura baseada no [7-1 architecture pattern](http://sass-guidelin.es/#architecture). Você encontrará várias referências a [SMACSS](https://smacss.com), [Sass Guidelines](https://sass-guidelin.es) e [CSS Guidelines](http://cssguidelin.es).

![](header.png)

## Installation

```sh
git clone https://github.com/gabrielmelo/sass-boilerplate.git
```

[download as ZIP](https://github.com/gabrielmelo/sass-boilerplate/archive/master.zip)

## Organização de arquivos

### The 7-1 pattern

The abstracts folder gathers all Sass tools and helpers used across the project. Every global variable, function, mixin and placeholder should be put in here.

The rule of thumb for this folder is that it should not output a single line of CSS when compiled on its own. These are nothing but Sass helpers.
