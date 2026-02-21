# ✍️ Los Escritos de Dani - Generador de Posts

Proyecto personal para crear y exportar posts visuales estandarizados para Instagram **@losescritosdedani**. Permite diseñar contenido literario con un branding consistente y descargar imágenes de alta calidad optimizadas para Instagram.

## 🎨 Características

* **Diseño Minimalista**: Tipografía elegante con *Playfair Display* serif
* **Colores Consistentes**: Paleta de marca unificada (azul grisáceo `#9ba7b5`)
* **Formato Instagram**: Posts en resolución 1080x1350px (ratio 4:5)
* **Exportación en PNG**: Descarga directa desde el navegador con alta resolución
* **Sistema de Plantillas**: Estructura reutilizable para crear nuevos posts rápidamente

## 🚀 Tecnologías

* **HTML5/CSS3**: Maquetación y estilos responsivos
* **JavaScript (ES6)**: Funcionalidad de exportación
* **html2canvas**: Conversión de DOM a imágenes PNG de alta resolución

## 📁 Estructura del Proyecto

```
losescritosdedani-posts/
├── index.html              # Dashboard con galería de plantillas
├── css/
│   └── styles.css         # Estilos centralizados (color, tipografía, layout)
├── js/
│   └── main.js            # Funciones JavaScript reutilizables
├── posts/
│   ├── post-01.html       # Plantilla 1: "Lo que no se dice"
│   └── post-02.html       # Plantilla 2: "Intensamente fugaz"
└── README.md              # Este archivo
```

## 💻 Cómo Usar

### Opción 1: Abrir en el navegador
1. Navega a la carpeta del proyecto
2. Haz doble clic en `index.html` o usa un servidor local (Live Server en VS Code)
3. Selecciona una plantilla del dashboard

### Opción 2: Modificar una plantilla existente
1. Abre el archivo HTML de la plantilla en `/posts`
2. Edita el texto dentro de `<div class="text">...</div>`
3. Guarda el archivo y recarga en el navegador
4. Haz clic en "Descargar PNG para Instagram"

### Opción 3: Crear una nueva plantilla
1. Copia uno de los archivos de `/posts` (ej: `post-01.html`)
2. Renómbralo como `post-03.html`
3. Edita el contenido (mantén la estructura HTML igual)
4. Actualiza el `index.html` para añadir la nueva tarjeta en la galería

## 📝 Notas de Desarrollo

* Todos los estilos están centralizados en `styles.css` para mantener consistencia
* Los posts usan `id="post-container"` obligatoriamente para que html2canvas funcione
* La tipografía se importa desde Google Fonts
* Asegúrate de que los paths a CSS sean relativos: `../css/styles.css`

## 🎯 Requisitos

* Navegador moderno con soporte para ES6
* Conexión a internet (para Google Fonts y CDN de html2canvas)

## 📧 Contacto

Instagram: **@losescritosdedani**
