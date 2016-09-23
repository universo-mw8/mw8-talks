Nosso boilerplate utiliza o [Reveal.JS](http://lab.hakim.se/reveal-js/) com [Gulp](http://gulpjs.com/), [Jade](http://jade-lang.com/) e [Stylus](http://learnboost.github.io/stylus/) e é baseado no boilerplate do nosso amigo
[Willian Justen](https://github.com/willianjusten)

Para saber mais sobre o Reveal JS , [você pode achar a documentação aqui](https://github.com/hakimel/reveal.js).


## Como começar

### Demo

Veja a demonstração rolando [aqui](http://qualy-org.github.io/qualy-presenter/)

### Instalação
Antes de tudo, instale as dependências deste projeto.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)

```sh
# Clone este repositório
$ git clone git@github.com:clucasalcantara/universomw8-talks.git new_project
$ cd new_project

# Instale as dependencias
$ npm install
# E execute o gulp
$ gulp
```

Após isso, tá tudo lindo :)

```sh
├── Readme.md
├── build
│   ├── css
│   │   └── main.css
│   ├── img
│   ├── index.html
│   └── js
│       ├── main.js
│       └── vendor
├── gulp
│   ├── index.js
│   ├── paths.js
│   └── tasks
├── gulpfile.js
├── package.json
└── src
    ├── img
    ├── js
    │   ├── main.js
    │   └── vendor
    ├── slides
    ├── styl
    │   ├── highlight-themes
    │   ├── main.styl
    │   ├── reveal-themes
    │   └── vendor
    └── templates
        ├── inc
        │   ├── head.jade
        │   └── scripts.jade
        └── index.jade
```

### Como usar

- Escreva os seus slides na pasta `src/slides` em arquivos separados usando a sintaxe do jade (Relaxe, é bem fácil) [jade syntax](http://jade-lang.com/) adicione os templates aqui `templates/index.jade`.

- Caso use scripts ou css customizados insira-os na pasta `templates/inc/` e injete-os aqui `templates/index.jade`.


### License

Assim como o seu boilerplate de origem, este també é opensource, fiquem a vontade para utilizar mas por favor, mantenham os devidos créditos, agradeçam no twitter, everything.
