# Proyecto: Sitio Temático con Flexbox - "Matías Núñez"

Este repositorio contiene el desarrollo de un **sitio web estático** construido con HTML y CSS utilizando **Flexbox** como sistema principal de diseño. El propósito es crear una interfaz atractiva, semántica y responsiva, con navegación lateral fija y una galería temática.

**Autores:** [Tu nombre] y Matías Núñez  
**Correo de contacto:** tunombre@ejemplo.com

---

## 🎯 Temática del sitio

La temática del sitio es **Matías Núñez**, una representación creativa de sus intereses, personalidad y estilo. Elegimos esta temática porque permite destacar elementos únicos y visualmente interesantes, además de reflejar a una persona real de forma entretenida y significativa.

---

## 🧱 Estructura del diseño

El sitio se compone de dos secciones principales organizadas con Flexbox:

- **Menú lateral izquierdo** (`nav`) fijo, con un `min-width` de 200px, donde se ubican los enlaces de navegación.
- **Contenido principal** (`main`) que contiene la galería de tarjetas, dispuestas con `flex-wrap`, `gap`, y diferentes proporciones (`flex: 1`, `flex: 2`, `flex: 3`) para crear dinamismo visual.

---

## 🧰 Uso de Flexbox

Se utilizaron las siguientes propiedades de Flexbox:

- `display: flex` en el contenedor general y la galería de tarjetas.
- `flex-wrap: wrap` para permitir que las tarjetas se acomoden automáticamente.
- `gap` para separación entre tarjetas.
- `flex: x` para aplicar proporciones diferentes:
  - Tarjetas grandes (`flex: 3`)
  - Tarjetas medianas (`flex: 2`)
  - Tarjetas pequeñas (`flex: 1`)

---

## 🎨 Diseño visual

- **Paleta de colores**: rojo (#e53935), azul (#1e88e5), blanco (#ffffff), y negro (#212121).
- **Tipografía**: `Segoe UI`, moderna y legible.
- **Estilo de tarjetas**: con sombra (`box-shadow`), bordes redondeados y efecto `hover` para interacción básica.
- **Interacción**: Al pasar el mouse sobre una tarjeta, esta se agranda suavemente (`transform: scale(1.05)`).

---

## 🧠 Decisiones de diseño

- Elegimos un diseño limpio, con bloques visuales claros y jerarquía tipográfica sencilla.
- Los colores representan la identidad de Matías: rojo para la energía, azul para el estilo, negro para la elegancia y blanco para el balance.
- Las tarjetas están diseñadas para ser legibles en cualquier dispositivo gracias a su comportamiento flexible.

---

## ⚙️ Tecnologías utilizadas

- **HTML5** para la estructura semántica.
- **CSS3** con Flexbox para el layout responsivo.
- No se utilizó JavaScript ni librerías externas, en cumplimiento con los requisitos de la actividad.

---

## 🗣️ Presentación oral

En la exposición explicaremos:

1. **Temática**: ¿Quién es Matías Núñez y qué lo hace interesante para un sitio?
2. **Estructura**: Cómo distribuimos la navegación y las tarjetas.
3. **Flexbox**: Dónde se aplicó y con qué proporciones.
4. **Diseño**: Elección de colores, estilo visual y organización.
5. **Dificultades**: Cómo logramos que la galería se vea mejor estructurada que el ejemplo base.

---

✅ Trabajo realizado con dedicación y atención al detalle para lograr una experiencia visual mejor que el ejemplo proporcionado.
