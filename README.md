# 🚀 **Starless Magazine — Frontend**

Frontend oficial del proyecto **Starless Magazine**, un sitio web cultural enfocado en Cine, Música y Noticias.  
Desarrollado con **Astro** para garantizar máxima velocidad, SEO y rendimiento, utilizando **Tailwind CSS** para un diseño moderno y responsivo.

---

## 🛠️ **Tecnologías Utilizadas**

El proyecto está construido sobre un stack moderno y eficiente:

| Tecnología | Versión | Descripción |
| :--- | :--- | :--- |
| **Astro** | ^5.16.1 | Framework principal para contenido estático y dinámico. |
| **Tailwind CSS** | ^4.1.17 | Framework de utilidad para estilos rápidos y responsivos. |
| **TypeScript** | ^5.x | Superset de JavaScript para un código tipado y seguro. |
| **Node.js** | 20+ | Entorno de ejecución requerido. |

---

## 🏗️ **Estructura del Proyecto**

Organización de archivos siguiendo la arquitectura de Astro basada en islas y rutas dinámicas:

text
/
├── public/               # Archivos estáticos
├── src/
│   ├── components/       # Componentes UI reutilizables
│   │   ├── Carta.astro
│   │   ├── CartaLado.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Portada.astro
│   │   ├── Suscripcion.astro
│   │   └── UltimasPublicaciones.astro
│   │
│   ├── layouts/          # Plantillas base
│   │   └── Layout.astro
│   │
│   ├── lib/              # Lógica y conexión a datos
│   │   ├── connection.ts # Cliente API (Strapi/CMS)
│   │   └── lista.js      # Helpers auxiliares
│   │
│   ├── pages/            # Rutas y páginas del sitio
│   │   ├── Cine/
│   │   │   ├── [slug].astro   # Página dinámica de artículo
│   │   │   └── Cine.astro     # Listado de categoría
│   │   │
│   │   ├── Musica/
│   │   │   ├── [slug].astro
│   │   │   └── Musica.astro
│   │   │
│   │   ├── Noticias/
│   │   │   ├── [slug].astro
│   │   │   └── Noticias.astro
│   │   │
│   │   ├── Contacto.astro
│   │   └── index.astro        # Página de inicio
│
└── package.json



##  Comandos del Proyecto

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando | Acción |
| :--- | :--- |
| npm install | Instala todas las dependencias. |
| npm run dev | Inicia el servidor de desarrollo en localhost:4321. |
| npm run build | Genera la versión final del sitio estático en la carpeta dist/. |
| npm run preview| Inicia un servidor local para ver el sitio después de hacer build. |

## 🚀 Instalación y configuración de Astro

### Requisitos previos
Tener **Node.js** instalado (incluye npm automáticamente).
Verifica con: node --version
Si no lo tienes, descárgalo de [nodejs.org](https://nodejs.org/)

### 1. Pegar ruta de cd
bash
cd nombre-del-proyecto


Es necesario ingresar a la carpeta del proyecto para cargar los archivos y el proyecto.

### 2. Crear proyecto Astro
bash
npm create astro@latest


Este comando indica que se instale la última versión.
## 👥 **Equipo de Desarrollo**

Este proyecto fue realizado con la colaboración de:

**Cristofer Sánchez** — *Full Stack Developer *
**Ruben Neguel** — Full Stack Developer
**Bastian Chiguay** — Desarrollo Frontend
**Gabriel Millan** — Diseño