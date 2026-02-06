 # ASIX1_0373_AE1c_ApuntesDocumentación_FreixaPau
## Repositorio del Curso 2025-2026 ASIX1
### Mi primera toma de contacto con GitHub
#### Alumno: Pau Freixa Matos

# 📘 Apuntes completos de **Lenguajes de Marcas y Sistemas de Gestión de la Información (ASIX1)**

## 🧩 0. Introducción a los lenguajes de marcas

### ¿Qué es un lenguaje de marcas?
Un **lenguaje de marcas** es un sistema que permite estructurar, describir y organizar información mediante **etiquetas o símbolos** llamados **marcas**. Estas marcas aportan **significado semántico** al contenido, permitiendo que:

- Los humanos entiendan la información.
- Las máquinas la procesen correctamente.

**NO** es un lenguaje de programación, ya que no contiene lógica ni algoritmos.

### Ejemplos de lenguajes de marcas

| Lenguaje | Uso principal |
|----------|---------------|
| HTML     | Estructura de páginas web |
| XML      | Almacenamiento e intercambio de datos |
| Markdown | Documentación técnica |
| CSS      | Presentación visual (lenguaje de estilo) |

---

## 🛠️ 1. GIT — Sistema de control de versiones

### ¿Qué es Git?
Git es un **sistema de control de versiones distribuido** que permite guardar el historial completo de un proyecto. En lugar de guardar solo archivos, Git guarda **versiones completas** llamadas **commits**.

### Para qué sirve:
- Volver a estados anteriores.
- Comparar cambios.
- Trabajar en equipo sin conflictos.
- Mantener historial detallado.

### Repositorio Git
Lugar donde Git almacena:
- Archivos del proyecto.
- Cambios realizados.
- Historial de versiones.

Puede ser:
- **Local**: en tu ordenador.
- **Remoto**: en servidores como GitHub.

### Áreas internas de Git

| Área | Función |
|------|---------|
| **Working Directory** | Archivos reales en tu ordenador. |
| **Staging Area** | Zona de preparación antes de guardar. |
| **Local Repository** | Historial de versiones (carpeta `.git`). |

### Comandos básicos de Git

| Comando | Función |
|---------|---------|
| `git init` | Inicializa un repositorio. |
| `git status` | Muestra el estado de los archivos. |
| `git add .` | Añade todos los cambios al staging. |
| `git commit -m "mensaje"` | Guarda una versión en el historial. |
| `git log` | Muestra el historial de commits. |
| `git branch` | Lista las ramas. |
| `git merge` | Une ramas. |
| `git clone URL` | Clona un repositorio remoto. |
| `git pull` | Descarga cambios del remoto. |
| `git push` | Sube cambios al remoto. |

---

## 🧭 2. GITHUB — Plataforma de alojamiento

### ¿Qué es GitHub?
GitHub es una **plataforma web** que permite:
- Alojar repositorios Git.
- Colaborar en proyectos.
- Publicar páginas web.

### README.md
Archivo principal del repositorio que:
- Explica el proyecto.
- Muestra documentación.
- Guía al usuario.

GitHub lo muestra automáticamente.

### GitHub Pages
Servicio para publicar páginas web estáticas directamente desde un repositorio.

📍 **Activación**:
```
Settings → Pages → Branch → main
```

---

## ✍️ 3. MARKDOWN — Lenguaje de documentación

### ¿Qué es Markdown?
Lenguaje de marcas ligero para crear documentos estructurados usando **texto plano**.

- **Extensión**: `.md`
- **Usado en**: GitHub, GitLab, documentación, foros.

### Encabezados

| Símbolo | Nivel |
|---------|-------|
| `#`       | H1    |
| `##`      | H2    |
| `###`     | H3    |
| `####`    | H4    |
| `#####`   | H5    |
| `######`  | H6    |

### Sintaxis principal

| Elemento | Sintaxis | Ejemplo |
|----------|----------|---------|
| **Negrita** | `**texto**` | **Hola** |
| *Cursiva* | `*texto*` | *Mundo* |
| Código en línea | \`código\` | `console.log()` |
| Enlace | `[texto](url)` | [Google](https://google.com) |
| Imagen | `![alt](url)` | ![Logo](logo.png) |
| Lista desordenada | `- item` | - Elemento |
| Lista ordenada | `1. item` | 1. Paso 1 |
| Cita | `> texto` | > Esto es una cita |
| Separador | `---` | --- |
| Código en bloque | \`\`\`lang`<br>código<br>\`\`\` | Ver abajo |

### Bloques de código

````markdown
```html
<!DOCTYPE html>
<html>
  <body>
    <h1>Hola</h1>
  </body>
</html>
```
````

### Tablas en Markdown

```markdown
| Campo | Descripción |
|-------|-------------|
| HTML  | Estructura  |
| CSS   | Estilo      |
```

---

## 🏗️ 4. HTML5 — Estructura del contenido

### ¿Qué es HTML?
**HTML** (HyperText Markup Language) define la **estructura y contenido** de una página web. No se encarga del diseño.

### Elementos y etiquetas
Un elemento HTML se compone de:

```html
<etiqueta atributo="valor">Contenido</etiqueta>
```

Ejemplo:
```html
<p class="texto">Hola mundo</p>
```

### Estructura básica de un documento HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi página</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Contenido visible -->
</body>
</html>
```

### Etiquetas básicas

| Etiqueta | Uso |
|----------|-----|
| `<h1>` a `<h6>` | Encabezados |
| `<p>` | Párrafo |
| `<a href="...">` | Enlace |
| `<img src="..." alt="...">` | Imagen |
| `<ul>` / `<ol>` | Listas |
| `<div>` | Contenedor genérico |
| `<span>` | Contenedor en línea |
| `<strong>` / `<em>` | Negrita / Cursiva semántica |

### Formularios

```html
<form action="/submit" method="POST">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <button type="submit">Enviar</button>
</form>
```

### Tablas

```html
<table border="1">
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Edad</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ana</td>
      <td>25</td>
    </tr>
  </tbody>
</table>
```

### Elementos semánticos (HTML5)

| Etiqueta | Uso |
|----------|-----|
| `<header>` | Cabecera |
| `<nav>` | Navegación |
| `<main>` | Contenido principal |
| `<section>` | Sección |
| `<article>` | Artículo independiente |
| `<aside>` | Contenido lateral |
| `<footer>` | Pie de página |

---

## 🎨 5. CSS — Hojas de estilo en cascada

### 5.1 ¿Qué es CSS?
**CSS** (Cascading Style Sheets) define la **presentación visual** del HTML. Separa:
- **Estructura** → HTML
- **Diseño** → CSS

### 5.2 Anatomía de una regla CSS

```css
selector {
  propiedad: valor;
}
```

Ejemplo:
```css
p {
  color: blue;
  font-size: 16px;
}
```

### 5.3 Tipos de selectores

| Selector | Ejemplo | Qué selecciona |
|----------|---------|----------------|
| Universal | `*` | Todos los elementos |
| Etiqueta | `p` | Todos los `<p>` |
| Clase | `.clase` | Elementos con `class="clase"` |
| ID | `#id` | Elemento con `id="id"` |
| Atributo | `[type="text"]` | Inputs de tipo texto |
| Descendente | `div p` | `<p>` dentro de `<div>` |
| Hijo directo | `div > p` | `<p>` hijo directo de `<div>` |

### 5.4 Modelo de Caja (Box Model)
Cada elemento es una caja con:

1. **Content**: contenido real.
2. **Padding**: espacio interior.
3. **Border**: borde.
4. **Margin**: espacio exterior.

```
┌─────────────────────────┐
│        margin           │
│  ┌───────────────────┐  │
│  │      border       │  │
│  │  ┌─────────────┐  │  │
│  │  │   padding   │  │  │
│  │  │  ┌───────┐  │  │  │
│  │  │  │content│  │  │  │
│  │  │  └───────┘  │  │  │
│  │  └─────────────┘  │  │
│  └───────────────────┘  │
└─────────────────────────┘
```

### 5.5 Propiedades de caja

```css
div {
  width: 300px;
  height: 200px;
  padding: 20px;
  border: 2px solid black;
  margin: 10px;
  box-sizing: border-box; /* Incluye padding y border en el width/height */
}
```

### 5.6 Unidades de medida

| Unidad | Tipo | Ejemplo |
|--------|------|---------|
| `px` | Absoluta | `10px` |
| `%` | Relativa al contenedor | `50%` |
| `em` | Relativa al tamaño de fuente del padre | `1.5em` |
| `rem` | Relativa al tamaño de fuente raíz | `2rem` |
| `vw` / `vh` | % del viewport | `50vw` |

### 5.7 Posicionamiento

| Valor | Comportamiento |
|-------|----------------|
| `static` | Posición normal (por defecto) |
| `relative` | Relativo a su posición original |
| `absolute` | Relativo al ancestro posicionado más cercano |
| `fixed` | Fijo en la pantalla |
| `sticky` | Se comporta como `relative` hasta un scroll, luego `fixed` |

### 5.8 Flexbox

```css
.contenedor {
  display: flex;
  flex-direction: row; /* row, column */
  justify-content: center; /* align horizontalmente */
  align-items: center; /* align verticalmente */
  flex-wrap: wrap;
}
```

### 5.9 Grid

```css
.contenedor {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 10px;
}
```

### 5.10 Media Queries (Responsive)

```css
/* Escritorio */
body {
  background: blue;
}

/* Tablet */
@media (max-width: 768px) {
  body {
    background: green;
  }
}

/* Móvil */
@media (max-width: 480px) {
  body {
    background: yellow;
  }
}
```

### 5.11 Variables CSS

```css
:root {
  --color-principal: #3498db;
  --espaciado: 20px;
}

.elemento {
  color: var(--color-principal);
  margin: var(--espaciado);
}
```

### 5.12 Pseudoclases y pseudoelementos

```css
/* Pseudoclases */
a:hover {
  color: red;
}

/* Pseudoelementos */
p::first-line {
  font-weight: bold;
}
```

---

## 🔍 6. Validación W3C

### 6.1 ¿Qué es el W3C?
El **World Wide Web Consortium** define los estándares oficiales de la web.

### 6.2 Validadores oficiales

| Lenguaje | Enlace |
|----------|--------|
| HTML | [https://validator.w3.org](https://validator.w3.org) |
| CSS | [https://jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator) |

### 6.3 ¿Por qué validar?
- Detectar errores.
- Asegurar compatibilidad.
- Cumplir estándares.
- Mejorar accesibilidad.

---

## 📄 Ejemplo completo: HTML + CSS

### `index.html`
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi página</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Bienvenido</h1>
  </header>
  <main>
    <p>Este es un párrafo de ejemplo.</p>
    <button class="boton">Click aquí</button>
  </main>
</body>
</html>
```

### `style.css`
```css
:root {
  --color-fondo: #f4f4f4;
  --color-texto: #333;
  --color-boton: #007bff;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: var(--color-fondo);
  color: var(--color-texto);
  line-height: 1.6;
}

header {
  background: #333;
  color: white;
  padding: 20px;
  text-align: center;
}

.boton {
  background: var(--color-boton);
  color: white;
  border: none;
  padding: 10px 20px;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s;
}

.boton:hover {
  background: #0056b3;
}

@media (max-width: 768px) {
  body {
    font-size: 14px;
  }
}
```

## 🔤 7. **GOOGLE FONTS**

**¿Qué es?** Servicio gratuito de Google con +1,000 fuentes web optimizadas.

**Cómo usarlo:**
1. Ve a **fonts.google.com**
2. Elige fuente y estilos
3. Copia enlace generado
4. Pega en `<head>` de HTML:
```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
```
5. Aplica en CSS:
```css
body { font-family: 'Roboto', sans-serif; }
```

**Fuentes recomendadas:**
- Textos: `'Open Sans'`, `'Roboto'`, `'Lato'`
- Títulos: `'Montserrat'`, `'Poppins'`, `'Raleway'`

**Ventajas:** Gratis, rápido, fácil, compatible.

**Regla:** Máximo 2-3 fuentes por proyecto. Legibilidad primero.

---

# 🧠 8. Conclusión

Gracias a este proyecto he aprendido a:

- Usar **Git** para controlar versiones y colaborar en equipo.
- Publicar proyectos en **GitHub Pages** y crear repositorios profesionales.
- Crear documentación técnica en **Markdown** con todos sus elementos (listas, tablas, código, etc.).
- Diseñar páginas **HTML** estructuradas y semánticas usando elementos modernos de HTML5.
- Aplicar **CSS** avanzado con selectores, pseudoclases, Flexbox, Grid y diseño responsive.
- Implementar **diseño responsive** con media queries para adaptar contenido a todos los dispositivos.
- Validar código con **W3C** para asegurar estándares web y compatibilidad entre navegadores.
- Organizar proyectos web con estructuras de archivos limpias y mantenibles.
- Implementar Google Fonts para tipografía web profesional y optimizada.

---

📅 Curso 2025-2026  
✏️ Autor: Pau Freixa Matos  
🏫 Módulo: 0373 — Llenguatges de marques i sistemes de gestió d'informació  
👨‍🏫 Profesor: Alberto de Santos Ontoria

