# Actividad de recuperación · Segundo parcial

Ishikawa, ruta crítica y cadena de valor — 15 ejercicios con reporte individual para Brightspace.
Profesora: Tania Rivera Lozano · Universidad Anáhuac Cancún.

Es una página estática de un solo archivo (`index.html`), sin dependencias ni servidor.

## Funciones
- Acceso con clave personal (grupo y nombre se asignan solos).
- Guardado automático y botón **Guardar avance**.
- **Cambiar de usuario** y **Cerrar sesión** (guardan antes de salir y limpian la pantalla).
- **Generar reporte** → **Guardar como PDF** para subir a Brightspace.
- Respaldo `.json` por alumno y **Control docente** (plazo, prórroga, registros, CSV).

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en https://github.com/new.
2. Sube `index.html`, `README.md`, `.gitignore` y `.nojekyll`.
3. En **Settings → Pages**, elige *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
4. Tu enlace será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Para fijar el plazo para los alumnos, agrega al final del enlace el texto que genera
**Control docente** (por ejemplo `#cierre-20261110-2359-p0`).

## Notas
- El avance de cada alumno se guarda en el navegador del dispositivo (`localStorage`).
- Un repositorio público expone `index.html`, que contiene nombres, matrículas y claves en hash.
  Usa un repositorio **privado** (requiere plan con Pages privado) o no publiques datos reales.
