# Starter para sitio de writeups — GitHub Pages

Esta es una **plantilla mínima** para levantar tu página personal de writeups en GitHub Pages.

## Estructura
- `index.html` — página principal (ya lista).
- `assets/styles.css` — estilos.
- `assets/avatar.png` — avatar placeholder.
- `writeups/` — carpeta para tus writeups (añadir archivos .html o .md)

## Pasos rápidos para publicar en GitHub Pages (opción recomendada: sitio de usuario)
1. Crea un nuevo repositorio en GitHub llamado exactamente: `TU_USUARIO.github.io`  
   (ejemplo: `p1r4t3h00k.github.io`).
2. En tu máquina local:
```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_USUARIO.github.io.git
git push -u origin main
```
3. GitHub Pages para repositorio `username.github.io` se activará automáticamente y tu sitio estará disponible en `https://TU_USUARIO.github.io` (puede tardar unos minutos).

### Alternativa: desplegar en rama `gh-pages` o usar repositorio normal
Si no quieres usar `TU_USUARIO.github.io`, crea repo normal y en Settings → Pages elige la rama `gh-pages` o `main` / `docs` según prefieras.

## Personalización rápida
- Reemplaza `{{YOUR_HANDLE}}` en los archivos por tu handle real.
- Sustituye `assets/avatar.png` por tu foto.
- Añade writeups en la carpeta `writeups/` como .html o .md (si quieres usar Jekyll u otro generador, lo podemos configurar).

## Próximos pasos que puedo automatizar por ti
- Reemplazar marcadores con `p1r4t3h00k` y tu nombre real.
- Generar plantillas de writeup (Markdown con front-matter).
- Añadir soporte Jekyll (config y layouts) si prefieres escribir en Markdown.
- Cambiar paleta al estilo más 'hacker' (tipografía monospace, fondo pixelado).

Dime qué quieres ahora: ¿reemplazo los marcadores por tu handle y nombre? ¿Subo plantillas de writeups?
