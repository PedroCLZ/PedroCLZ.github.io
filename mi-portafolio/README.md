# Portafolio de Pedro Centeno López

Sitio estático personal construido con HTML, CSS y JavaScript vanilla. No requiere dependencias ni proceso de compilación; está preparado para GitHub Pages.

## Abrir en Visual Studio Code

1. Descarga o clona el repositorio `PedroCLZ/PedroCLZ.github.io`.
2. En Visual Studio Code, selecciona **Archivo > Abrir carpeta...** y elige la carpeta del proyecto.

## Ejecutar localmente

Abre `index.html` directamente en un navegador. También puedes hacer clic derecho sobre el archivo desde Visual Studio Code y elegir **Show Preview** si tienes una extensión de vista previa instalada; no es necesaria para que el sitio funcione.

## Subir los archivos a GitHub

Desde una terminal abierta en la carpeta del proyecto, ejecuta:

```bash
git init
git add .
git commit -m "Crear portafolio personal"
git branch -M main
git remote add origin https://github.com/PedroCLZ/PedroCLZ.github.io.git
git push -u origin main
```

Si ya clonaste el repositorio, no ejecutes `git init` ni `git remote add origin`; copia los archivos a esa carpeta y utiliza:

```bash
git add .
git commit -m "Actualizar portafolio personal"
git push
```

## Activar GitHub Pages

1. Abre el repositorio `PedroCLZ/PedroCLZ.github.io` en GitHub.
2. Ve a **Settings > Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama `main` y la carpeta `/ (root)`; pulsa **Save**.
5. Espera a que termine la publicación. El sitio estará disponible en [https://PedroCLZ.github.io](https://PedroCLZ.github.io).

## Personalización

- Actualiza el texto del perfil en `index.html`.
- Añade los enlaces reales de LinkedIn y correo cuando estén disponibles.
- Para un proyecto nuevo, duplica una tarjeta `<article class="project-card">` y cambia su descripción, estado, tecnologías y enlace únicamente cuando exista un repositorio.
- Cambia la URL de Google Fonts o elimínala si prefieres no cargar tipografías desde un servicio externo. Se utilizan fuentes de respaldo si no hay conexión.
- Las previsualizaciones actuales son conceptuales y locales; no representan capturas de proyectos terminados.
