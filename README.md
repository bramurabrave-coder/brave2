# Brave Salud & Rendimiento — Sitio web (Paipa, Boyacá)

Landing page del centro clínico deportivo Brave Salud & Rendimiento: presentación de programas (Senior, Rehab, RX), formulario de contacto, calculadora de IMC/TMB/macros, test de tipo de cuerpo, sistema de referidos y agendamiento por WhatsApp.

Todo el sitio vive en un único archivo `index.html` (HTML + CSS + JS).

## Estructura

```
.
├── index.html      # El sitio completo
├── vercel.json      # Configuración mínima de despliegue
├── .gitignore
└── README.md
```

## Subir a GitHub (repositorio NUEVO)

1. Crea un repositorio vacío en https://github.com/new (sin README ni .gitignore).
2. En GitHub, en la página del repo recién creado, clic en **"uploading an existing file"** (o "Add file → Upload files").
3. **Importante:** sube los archivos sueltos (`index.html`, `vercel.json`, `.gitignore`, `README.md`) directamente — no subas ninguna carpeta ni ningún .zip. Deben quedar visibles en la raíz del repo.
4. Commit changes.

La página principal del repo debe verse así, sin carpetas ni zip:
```
.gitignore
README.md
index.html
vercel.json
```

## Desplegar en Vercel

1. Entra a vercel.com → **Add New Project**
2. Selecciona este repositorio
3. Deploy (no necesita build command, es un sitio estático)

## Actualizaciones futuras

Cada vez que edites `index.html`, sube el cambio a GitHub (con `git push` o volviendo a subir el archivo por la web) y Vercel despliega la nueva versión automáticamente, sin pasos adicionales.
