

🚀  # Frontend — Starless Magazine

# Frontend — Starless Magazine

---

## 🛠️  Tecnológias utilizadas


⚙️ Configuración y Tecnologías
Dependencias Principales
El proyecto utiliza las siguientes tecnologías clave:

Astro (^5.16.1): El framework moderno para la construcción de sitios web rápidos y centrados en el contenido.
Tailwind CSS (^4.1.17): Un framework CSS de utilidad para un desarrollo rápido de estilos.
TypeScript
JavaScript (^5.9.3): JavaScript es el lenguaje que añade interactividad a la web.

🏗️ Estructura del Proyecto
El proyecto sigue la estructura estándar de Astro para organizar el código:


/
├── src/
│   ├── components
│   │   └── Carta.astro
│   │   └── CartaLado.astro
│   │   └── CartaLado.astro
│   │   └── Footer.astro
│   │   └── Header.astro
│   │   └── Portada.astro
│   │   └── Suscripcion.astro
│   │   └── Ultimas publicaciones.astro
├── layouts
│   └──  layout.astro
│  
├── lib
│   └── archivos ts y js
│       └── conection.ts
│       └── lista.js
├── pages
│   │── Cine
│   │    └── [slug].astro
│   │
│   │── Musica
│   │  └── [slug].astro
│   │
│   │── Noticias
│   │   └── [slug].astro
│   │
│   │
│   │
│   │
│   └── Cine.astro
│   └── Contacto.astro
│   └── Index.astro
│   └── Musica.astro
│   └── Noticias.astro
│ 
│ 
│ 
└── package.json


```
##  Comandos del Proyecto

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias. |
| `npm run dev` | Inicia el servidor de desarrollo en `localhost:4321`. |
| `npm run build` | Genera la versión final del sitio estático en la carpeta `dist/`. |
| `npm run preview`| Inicia un servidor local para ver el sitio después de hacer `build`. |

## 🚀 Instalación y configuración de Astro

### Requisitos previos
* Tener **Node.js** instalado (incluye npm automáticamente).
* Verifica con: `node --version`
* Si no lo tienes, descárgalo de [nodejs.org](https://nodejs.org/)

### 1. Pegar ruta de cd
```bash
cd nombre-del-proyecto
```
Es necesario ingresar a la carpeta del proyecto para cargar los archivos y el proyecto.

### 2. Crear proyecto Astro
```bash
npm create astro@latest
```
* Este comando indica que se instale la última versión.

Trabajo realizado por Cristofer Sanchez. Bastian Chiguay, Ruben Neguel, Gabriel millan