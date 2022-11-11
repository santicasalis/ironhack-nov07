<h1 align="center">
  <a href="https://github.com/dzc1/ironhack-nov07">
    <img src="./assets/imgs/banner.png" alt="Vue Conforcat Class">
  </a>
</h1>
  <p align="center">
  Este repositorio sirve como una guia para la clase de FE Dev - Vue Conforcat. Done estaremos apendiendo acerca de HTML, CSS3, Javascript, Vue & Supabase.
</p>
 <p align="center" style="font: 16px">
 Creado con ❤️ por Diego Zito, Carlos Garrido & Aleix Abuli.
</p>

## Link a Zoom

[Zoom Link](https://ironhack.zoom.us/j/93120423452)

## Estructura de Carpetas

- [Html Basics](https://github.com/dzc1/ironhack-nov07/tree/main/section-01-html)
  - [Basic Layout](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/01-basic-layout.¡html)
  - [Meta Tags](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/02-meta-tags.html)
  - [Typography, Headings, Paragraphs](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/03-typography.html)
  - [Anchor Tags / Links](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/04-links.html)
  - [Images](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/05-images.html)
  - [Ordered & Unordered Lists](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/06-list.html)
  - [Semantic & Non Semantic Elements - Layout](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/07-layout.html)
  - [Layout Example - Basic Website Structure](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/08-layout-example.html)
  - [Html Tables](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/09-tables.html)
  - [HTML Forms](https://github.com/dzc1/ironhack-nov07/blob/main/section-01-html/14-forms.html)
- [Css Basics](https://github.com/dzc1/ironhack-nov07/tree/main/section-02-css)
  - [CSS Basics](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/01-basics.html)
  - [CSS Selectors](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/02-selectors.html)
  - [Fonts](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/03-fonts.html)
  - [Text Properties](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/04-text-properties.html)
  - [Colors](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/05-colors.html)
  - [Borders & Backgrounds](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/06-borders-background.html)
  - [Box Model](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/07-box-model.html)
  - [Layout - Floats](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/08-float-algin.html)
  - [Links & Buttons](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/09-links-buttons.html)
  - [Menu Styling](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/10-menu-styling.html)
  - [Position](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/11-position.html)
  - [Inline vs Block](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/12-inline-vs-block.html)
  - [Media Queries](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/13-media-queries.html)
  - [Media Queries Extended](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/14-media-queries-extended.html)
  - [Media Query Example](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/15-media-query-example.html)
  - [Flex Basics](https://github.com/dzc1/ironhack-nov07/blob/main/section-02-css/16-flex-basics.html)

## Links de Ayuda

- [Chuletas](#Chuletas)
  - [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)
  - [Git Cheatsheet](https://education.github.com/git-cheat-sheet-education.pdf)
  - [Html Cheatsheet](https://devhints.io/html)
  - [Css Cheatsheet](https://devhints.io/css)
- [Videos](#videos)
  - [Welcome to the Internet - Bo Burnham](https://www.youtube.com/watch?v=k1BneeJTDcU)

## Comandos de Git

Sigue estos pasos para hacer cambios en tu repositorio:

Para subir tus cambios al stream de git tienes que `añadir` tus cambios recientes mediante el siguiente comando:

`Añadir` todos tus cambios:

```bash
git add .
```

`Añadir` cambio individual por nombre de archivo:

```bash
git add "nombre de archivo ej: 01-bsaic-layout.html"
```

`Añadirle` un `comentario` al `commit` que estaremos empujando a tu repositorio en la web.

```bash
git commit -m "Texto descriptivo de los cambios recientes"
```

`Empujar` los cambios recientes a tu repositorio en la web. `Extended`.

```bash
git push origin "nombre del branch/rama que estaremos apuntando"
```

`Empujar` los cambios recientes a tu repositorio en la web. `Simplified`.

```bash
git pushs
```

### Combinations

#### Combination #1 - Extended

Hace una combinacion de `git add commit push` usando estos comandos de `git` y usando un un operador logico `AND` con el syntax `&&`

```bash
git add . &&
git commit -m "Texto descriptivo de los cambios recientes" &&
git push origin "nombre del branch/rama que estaremos apuntando"
```

#### Combination #2 - Simplified

Hace una combinacion de `git add commit push` usando estos comandos de `git` y usando un un operador logico `AND` con el syntax `&&`

```bash
git add . &&
git commit -m "Texto descriptivo de los cambios recientes" &&
git push
```

Ver los `branches` asociados al repositorio.

```bash
git branch
```

Hacer un `pull` de los ultimos cambios de un repositorio git en gitHub a tu repo local

```bash
git pull origin "nombre del branch/rama que estaremos apuntando"
```
