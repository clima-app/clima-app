# CORRECCIÓN.md

## Problema encontrado:
No había comentarios en el archivo `index.html`.

## ¿Por qué esto no está bien?
El archivo tiene muchas secciones y sin comentarios se hace difícil entender qué hace cada parte del código. Esto puede complicar el trabajo en grupo o si más adelante alguien (o yo misma) quiere hacer cambios.

## ¿Qué hice para mejorarlo?
Agregué comentarios en el HTML para explicar qué hace cada parte. Por ejemplo:

```html
<!-- Sección con la tarjeta del clima actual -->
<div class="weather-card">
    ...
</div>

<!-- Sección con el pronóstico para los próximos días -->
<section class="forecast">
    ...
</section>

<!-- Sección con alertas del clima -->
<section class="alerts">
    ...
</section>
