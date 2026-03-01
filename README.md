# 🌿 Mi Descanso | Resort & Restaurante Campestre

Este es el repositorio oficial del sitio web para **Club Campestre Mi Descanso**, un refugio rodeado de naturaleza ubicado en el distrito de Ate, Lima. El proyecto es una landing page moderna, rápida y optimizada, diseñada para mostrar los servicios del club y facilitar las reservas directas a través de WhatsApp.

## 🚀 Tecnologías Utilizadas (Tech Stack)

El proyecto está construido con herramientas modernas enfocadas en el rendimiento y la experiencia de desarrollador:

*   **[Astro](https://astro.build/):** Framework web (v5) ultrarrápido ideal para sitios estáticos orientados al contenido.
*   **[Tailwind CSS](https://tailwindcss.com/):** Framework CSS de utilidad (v4), usando la nueva arquitectura basada en `@theme` dentro de `global.css`.
*   **[Lucide Icons](https://lucide.dev/):** Conjunto de iconos limpios y modernos.
*   **JavaScript (Vanilla):** Para la interactividad de modales, animaciones y el widget flotante de WhatsApp, sin necesidad de cargar pesados frameworks de UI.

## ✨ Características Principales

*   **Secciones Integradas:**
    *   **Restaurante:** Promoción de gastronomía criolla y platos a la carta.
    *   **Club de Piscinas:** Información sobre las piscinas y toboganes.
    *   **Hospedaje (Bungalows):** Estancias para descansar en familia.
    *   **Experiencias (Shows):** Cartelera dinámica de eventos de fin de semana.
*   **Integración Directa con WhatsApp:** Botones de CTA estratégicamente ubicados en cada sección que generan mensajes pre-llenados listos para enviar al equipo de ventas del club.
*   **Widget Flotante Animado:** Un botón de WhatsApp que aparece inteligentemente (basado en el scroll) con animaciones personalizadas para captar la atención del usuario sin ser intrusivo.
*   **Diseño Premium y Responsive:** Uso de colores cálidos (`forest`, `copper`, `cream`) y tipografías elegantes (Outfit y Playfair Display) adaptables a móviles, tablets y escritorio.
*   **Modales Accesibles:** Sistema de modales personalizados para la carta/menú y los formularios de pre-reserva.

## 📁 Estructura del Proyecto

```text
/
├── public/               # Archivos estáticos accesibles públicamente (ej: imágenes en /img, favicon)
├── src/
│   ├── components/       # Componentes modulares de la UI (Navbar, Hero, Services, Shows, etc.)
│   ├── layouts/          # Plantilla principal (Layout.astro) que envuelve las páginas
│   ├── pages/            # Rutas del sitio (index.astro es la página principal)
│   └── styles/           # Estilos globales, incluyendo la configuración de Tailwind v4 (global.css)
├── README.md             # Este archivo
├── package.json          # Dependencias y scripts del proyecto
└── astro.config.mjs      # Configuración del framework Astro
```

## 🧞 Comandos de Desarrollo

Asegúrate de tener [Node.js](https://nodejs.org/) instalado. Ejecuta estos comandos desde la raíz del proyecto en tu terminal:

| Comando | Acción |
| :--- | :--- |
| `npm install` | Instala todas las dependencias necesarias. |
| `npm run dev` | Inicia el servidor local de desarrollo en `localhost:4321`. |
| `npm run build` | Construye el sitio óptimo para producción en la carpeta `./dist/`. |
| `npm run preview` | Previsualiza el build de producción localmente. |
| `npm run astro check` | Verifica errores y tipado en el proyecto. |

## 📍 Ubicación
El negocio físico se encuentra en: **Asociación El Descanso, Ate 15479 · Lima, Perú**. El sitio web incluye un mapa embebido real de Google Maps para facilitar la llegada de los clientes.
