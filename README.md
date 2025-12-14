# Portfolio Brutalista V1

Un portfolio personal minimalista y brutalista construido con Astro, enfocándose en diseño limpio, tipografía fuerte y experiencia de usuario fluida.

## 🚀 Características

- **Diseño Brutalista**: Estilo minimalista con bordes definidos, tipografía monoespaciada y paleta de colores neutra.
- **Tema Oscuro/Claro**: Toggle de tema con persistencia.
- **Responsive**: Layout adaptable a móviles y desktop.
- **Performance**: Generado estáticamente con Astro para carga rápida.
- **Componentes Modulares**: Estructura organizada con layouts y componentes reutilizables.

## 🛠️ Tecnologías

- **Framework**: Astro 5.16.3
- **Lenguajes**: HTML, CSS, JavaScript/TypeScript
- **Herramientas**: pnpm, Vite
- **Fuentes**: JetBrains Mono, Space Grotesk (locales)

## 📁 Estructura del Proyecto

```
/
├── public/
│   ├── fonts/          # Fuentes locales
│   └── images/         # Imágenes del portfolio
├── src/
│   ├── components/     # Componentes reutilizables (NavBar, Hero, Content, etc.)
│   ├── layouts/        # Layouts base y específicos (Layout.astro, LayoutContent.astro)
│   ├── pages/          # Páginas del sitio (index.astro)
│   └── styles/         # Estilos globales (global.css)
├── astro.config.mjs    # Configuración de Astro
├── package.json        # Dependencias y scripts
└── tsconfig.json       # Configuración TypeScript
```

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando              | Acción                                      |
| :------------------- | :------------------------------------------ |
| `pnpm install`       | Instala dependencias                        |
| `pnpm dev`           | Inicia servidor de desarrollo en localhost:4321 |
| `pnpm build`         | Construye el sitio para producción          |
| `pnpm preview`       | Previsualiza el build localmente            |
| `pnpm astro check`   | Valida TypeScript y Astro                   |

## 🎨 Personalización

- **Tema**: Edita variables CSS en `src/styles/global.css` para colores y fuentes.
- **Contenido**: Actualiza componentes en `src/components/` para cambiar texto, imágenes o enlaces.
- **Layouts**: Modifica `src/layouts/` para ajustar estructura de páginas.

## 📝 Notas de Desarrollo

- Usa `pnpm` para consistencia con el lockfile.
- El proyecto usa slots en layouts para flexibilidad.
- Imágenes optimizadas con Astro's built-in image handling.

## 👀 Próximos Pasos

- Añadir páginas de proyectos individuales.
- Implementar blog con Markdown.
- Añadir animaciones más avanzadas.
- Integrar con CMS o headless CMS.

---

Creado con ❤️ por Miguel Páez Aguirre.
