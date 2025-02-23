# Results Summary Component

Este es un componente de resumen de resultados, creado como parte de un desafío de [Frontend Mentor](https://www.frontendmentor.io). El diseño es responsive y está construido utilizando HTML y CSS.

## Vista previa

![Vista previa del componente de resumen de resultados](./design/desktop-preview.jpg)

## Características

- Diseño responsive que se adapta a diferentes tamaños de pantalla.
- Uso de gradientes para el fondo de la sección de resultados.
- Iconos SVG para representar cada categoría de puntuación.
- Efectos de hover en el botón de "Continue".
- Colores de fondo y texto específicos para cada categoría (Reaction, Memory, Verbal, Visual).

## Estructura del proyecto

- `index.html`: Contiene la estructura HTML del componente.
- `styles.css`: Contiene los estilos CSS para el componente.
- `assets/images/`: Carpeta que contiene las imágenes utilizadas en el proyecto, incluyendo el ícono de favorito y los iconos SVG para cada categoría.

## Cómo usar

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en tu navegador para ver el componente en acción.

## Estilos

Los estilos están diseñados para ser simples y modulares. Se utilizan gradientes y colores específicos para cada sección del componente.

```css
.result-card {
  background: linear-gradient(to bottom, #4e21ca, #2e2be9);
  color: white;
  text-align: center;
  padding: 30px;
  flex: 1;
  border-radius: 20px 0 0 20px;
}

.continue-btn {
  background: linear-gradient(to right, #6743ff, #3f2ef8);
  color: white;
  font-size: 16px;
  font-weight: bold;
  border-radius: 25px;
  cursor: pointer;
  transition: 0.3s;
}
