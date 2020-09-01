# 🎁 Challenge CSS 16

Subgrid

> NOTA IMPORTANTE: **Subgrid** en este momento solo es compatible con **Firefox**, por lo que te recomiendo realizar el reto en este navegador. Puedes revisar la compatibilidad de este valor [haciendo click aquí](https://caniuse.com/#search=subgrid). (Sí, es un valor, no una propiedad)

## 🎁 ¿En qué consiste?

La idea de este reto es lograr replicar el siguiente resultado: 

<kbd>
<img width="300" src="https://i.ibb.co/BjT1Mmc/Screen-Shot-2020-09-01-at-2-50-04-PM.png" />
</kbd>

</br>

Requerimiento principal:

* Tener en el HTML 3 elementos: Padre (`container`), Hijo (`element`) y Nieto (`subelement`). Así:

```
<div class="container">
  <div class="element">
    <div class="subelement"></div>
  </div>
</div>
```

Requerimientos para el elemento Padre (`container`):

* Que sea un contenedor de cuadrícula (`display: grid`).
* Que tenga 8 columnas de 1 fr.
* Que tenga 4 filas con un tamaño mínimo de `100px` y un tamaño máximo `auto`.
* Que tenga un color de background diferente a los elementos Hijo y Nieto.

Requerimientos para el elemento Hijo (`element`):

* Que sea un sub-contenedor de cuadrícula (`display: grid`).
* Que ocupe de la columna 3 a la columna 8 de su padre (`container`).
* Que ocupe de la fila 2 a la fila 4 de su padre (`container`).
* Que tenga 4 columnas de 1 fr.
* Que tenga la misma cantidad de filas que las que ocupa (`subgrid`).
* Que tenga un color de background diferente a los elementos Padre y Nieto.

Requerimientos para el elemento Nieto (`subelement`):

* Que ocupe de la columna 3 a la columna 4 de su padre (`element`).
* Que ocupe de la fila 1 a la fila 2 de su padre (`element`).
* Que tenga un color de background diferente a los elementos Padre e Hijo.

Te dejo la siguiente documentación útil para resolver el reto:

* [Subgrid | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Subgrid)

## 🎁 Pasos a seguir:

1. Hacer un "Fork" de este proyecto.
2. Revolver el reto.
3. Crear un Pull Request hacia este repositorio.

## 🎁 ¿Cómo contribuir?

Si quieres agregar o mejorar algo, te invito a colaborar directamente en este repositorio: [challenge-css-16](https://github.com/platzimaster/challenge-css-16/)

## 🎁 Licencia

challenge-CSS-16 se lanza bajo la licencia [MIT](https://opensource.org/licenses/MIT).
