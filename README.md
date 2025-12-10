# Resultados F1 - Temporada 2025

## 🏎️ Resumen del Proyecto
Sitio web sencillo e informativo que presenta los resultados de la temporada 2025 de Fórmula 1, incluyendo clasificaciones de pilotos y constructores.
---

## 📋 Descripción

Este proyecto es un sitio web estático desarrollado con HTML y CSS que muestra:

- Resultados actualizados de la temporada 2025 de F1
- Top 5 de pilotos con sus respectivos equipos y puntuaciones
- Top 3 de constructores
- Enlaces directos a las tablas oficiales completas de Formula1.com
- Formulario de contacto para interacción con los visitantes

El sitio está publicado en GitHub Pages, con el siguiente enlace:
https://cantuuuu.github.io/proyecto-final-modulo1/

---

## ✨ Características

- **HTML**: Uso de etiquetas como `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>` y `<form>`
- **Diseño Responsive básico**: Imágenes adaptables con `max-width: 100%` y contenedores con anchos máximos
- **Navegación Interna**: Anclajes que permiten saltar entre secciones
- **Enlaces Externos**: Acceso directo a tablas oficiales de F1.
- **Formulario de Contacto**: Campos validados (nombre, email y mensaje)
- **Paleta de Colores Temática**: Colores inspirados en F1 (rojo `#e10600`, negro `#15151e`)
- **Imágenes Ilustrativas**: Fotos de pilotos, equipos y eventos de la temporada

---

## 🚀 Pasos de Despliegue en GitHub Pages

Para desplegarlo en GitHub Pages seguí estos pasos: 
### 1. Preparar el Repositorio

Crear el repositorio y clonarlo localmente. 

### 2. Diseñar

Diseñar el sitio de manera local, haciendo commits según el progreso.

### 3. Hacer Marge con Main

Todo se desarrolló en la rama `develop`

### 4. Activar GitHub Pages

1. En el repositorio en GitHub
2. Entrar en **Settings**
3. En el menú lateral, seleccionar **Pages**
4. En **Source**, selecciona la rama `main` y la carpeta `/ (root)`
5. Hacer click en  **Save** 
6. Esperar unos minutos y recargar la página
7. La URL del sitio es: `https://cantuuuu.github.io/proyecto-final-modulo1/`

### 5. Verifiqué el Despliegue

- Abrí la URL generada en mi navegador
- Verifique que todas las secciones funcionan correctamente
- Pruebé los enlaces internos y externos
- Compruebé que las imágenes se carguen correctamente

---

## 📁 Estructura del Proyecto

```
proyecto-final-modulo1/
├── index.html                 # Página principal del sitio
├── README.md                  # Este archivo
├── EVIDENCIAS.md              # Capturas y aprendizajes
└── src/                       # Carpeta de recursos
    ├── css/
    │   └── style.css          # Estilos globales del sitio
    ├── images/
    │   ├── formula1.jpg       # Imagenes generales
    └── icons/
        └── icons8-f1-100.png  # Favicon del sitio
```

---

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura y contenido semántico
- **CSS3**: Estilos, layout y diseño responsive basico
- **GitHub Pages**: Hosting y despliegue del sitio estático

---

## 📸 Capturas de Pantalla

Consulta el archivo `EVIDENCIAS.md` para ver capturas de pantalla del sitio en funcionamiento y la configuración de GitHub Pages.

---

## 🎯 Funcionalidades Principales

### Navegación
- Menú de navegación fijo con enlaces a 4 secciones: Inicio, Pilotos, Constructores y Contacto
- Anclajes internos para navegación fluida

### Secciones de Contenido
- **Inicio**: Introducción y foto destacada de la temporada
- **Pilotos**: Top 5 con puntuaciones y enlace a tabla completa oficial
- **Constructores**: Top 3 con puntuaciones y enlace a tabla completa oficial
- **Contacto**: Formulario con validación de campos requeridos

### Diseño Visual
- Encabezado y pie de página con fondo oscuro (`#15151e`)
- Títulos en rojo F1 (`#e10600`)
- Secciones alternas con fondo gris claro (`#f5f5f5`)
- Imágenes centradas

---

## ⚠️ Límites 

- **Formulario sin backend**: No envía datos reales, solo valida en el cliente
- **Contenido estático**: Los resultados requieren edición manual del HTML
- **Sin JavaScript**: No hay interactividad dinámica
- **Responsive básico**: Funciona en distintos tamaños pero sin optimizaciones específicas
- **Imágenes sin optimizar**: No usa formatos modernos ni lazy loading
- **Accesibilidad limitada**: Falta atributos ARIA y mejor contraste, pero que sea similar a los colores oficiales de F1.

---

## 🚀 Próximos Pasos

- Media queries para móviles y tablets
- Optimizar y comprimir imágenes (WebP)
- Añadir JavaScript para validación y animaciones
- Integrar backend para formulario (Formspree/EmailJS)
- Implementar CSS Grid/Flexbox
- Más secciones: calendario, estadísticas, galería, etc.
