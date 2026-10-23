# Estilos y SCSS: ejercicio Ionic-Angular

Página `home` de un proyecto Ionic-Angular maquetada con Sass:

- Título en rojo, mayúsculas y centrado.
- Botón (`ion-button`) a la derecha en azul.
- Imagen centrada con borde verde de 3px.

## Archivos principales

- `src/theme/_abstracts.scss`: variables y mixins (como `1-abstracts` del patrón 7-1).
- `src/app/home/home.page.html`: plantilla.
- `src/app/home/home.page.scss`: estilos de la página (importa los abstracts con `@use`).
- `docs/Entrega_Ejercicio_Sass.pdf`: respuestas a las preguntas y código comentado.

## Ejecutar

```bash
npm install
ionic serve
```

No hace falta `npm run watch:sass`: `ionic serve` compila el SCSS automáticamente.
