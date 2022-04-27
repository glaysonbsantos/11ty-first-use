# Seção de blog construída com Eleventy

### O 11ty é um gerador de site estático que utiliza uma engine de template indepente. Em minhas palavras, peguemos o exemplo:

Imagine um site com mais de um arquivo .html. Iniciantes na programação tendem a pensar que todo arquivo .html deverá conter o mesmo head da página principal (comumente denominada index.html). O 11ty traz uma solução que torna desnecessária essa repetição de código. Isso serve para quaisquer elementos que se repitam no seu DOM. Tens uma navbar presente em várias páginas? Um footer também? O 11ty é uma solução para que você não precise repetir esses elementos em todas as páginas .html que os utilizem.

### Para rodar o site use os seguintes comandos:

```
npm install --save-dev @11ty/eleventy
npm run dev
```