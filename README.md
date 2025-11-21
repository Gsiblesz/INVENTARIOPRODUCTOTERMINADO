# FORMULARIOS LA TATA

Formulario web simple para registrar inventario y sincronizar el catálogo de productos de La Tata de la Libertad.

## Contenido del proyecto
- `index.html`: estructura principal del formulario.
- `styles.css`: estilos del sitio.
- `script.js`: lógica de interacción, comunicación con Apps Script y manejo de productos.
- `GOOGLE_APPS_SCRIPT.md`: instrucciones para configurar el backend en Google Apps Script.
- `vercel.json`: configuración mínima para desplegar el sitio como app estática en Vercel.

## Requisitos
Este proyecto es completamente estático, por lo que no necesita dependencias adicionales. Solo asegúrate de actualizar `SCRIPT_URL` en `script.js` con la URL de tu Web App de Google Apps Script.

## Desarrollo local
1. Clona el repositorio.
2. Abre la carpeta del proyecto en tu editor.
3. Usa cualquier servidor estático (por ejemplo, la extensión Live Server de VS Code) o simplemente abre `index.html` en tu navegador para probar.

## Despliegue en Vercel
1. Crea un nuevo proyecto en [Vercel](https://vercel.com) conectado a este repositorio.
2. Acepta la configuración predeterminada (Framework preset: **Other**). Vercel detectará automáticamente `index.html` como punto de entrada.
3. `vercel.json` está incluido para forzar el uso del builder estático y redirigir todas las rutas a `index.html`.
4. Después del primer despliegue, cada push a `main` actualizará automáticamente el sitio.

> Nota: Si necesitas variables de entorno (por ejemplo, para `SCRIPT_URL`), puedes definirlas en la sección *Environment Variables* de tu proyecto en Vercel.
