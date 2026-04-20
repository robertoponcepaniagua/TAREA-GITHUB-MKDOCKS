# Introducción a CSS

CSS significa **Cascading Style Sheets** (Hojas de Estilo en Cascada). Es el lenguaje que define la apariencia visual de los documentos estructurados con HTML.

---

## Estructura Básica

Para dar estilo a un elemento, usamos un "selector" seguido de las propiedades que queremos cambiar:


```
h1 {
  color: navy;
  font-size: 24px;
  text-align: center;
}

p {
  color: darkslategray;
  line-height: 1.5;
}

```

-   **Selectores:** Indican a qué elemento de la página (como h1 o p) le vamos a aplicar el diseño.

-   **Propiedades:** Son las características que cambiamos, como el `color`, el tamaño de fuente (`font-size`) o el alineado (`text-align`).

-   **Valores:** Es el ajuste específico que damos (por ejemplo: `center`, `blue` o `12px`).