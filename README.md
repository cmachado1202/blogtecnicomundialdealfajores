# Blog técnico – Mundial de Alfajores

Este repositorio contiene una entrada de blog lista para publicar con **GitHub Pages** como entrega final.

## Antes de subir

1. Abrí `index.html`.
2. Buscá `TU-USUARIO/TU-REPOSITORIO`.
3. Reemplazalo por el usuario y repositorio reales de GitHub. Ejemplo:
   - `carolina-dev/blog-tecnico-mundial-alfajores`
4. Guardá el archivo.

> No publiques contraseñas, tokens, IPs internas, datos personales ni enlaces privados.

## Publicación en GitHub Pages

1. Creá un repositorio público con un nombre como `blog-tecnico-mundial-alfajores`.
2. Subí `index.html`, `styles.css`, `README.md` y `CHECKLIST-ENTREGA.md` a la rama `main`.
3. En GitHub abrí **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná la rama **main** y la carpeta **/(root)**.
6. Tocá **Save**.
7. Cuando termine el deploy, GitHub mostrará la URL pública del sitio.

## Publicación desde PowerShell

Ubicada dentro de la carpeta del blog, ejecutá estos comandos después de crear el repositorio vacío en GitHub:

```powershell
git init
git add .
git commit -m "feat: publicar entrada técnica sobre carrito persistente"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/blog-tecnico-mundial-alfajores.git
git push -u origin main
```

## Control de versiones recomendado

Para que la entrega tenga evidencia clara, podés hacer estos commits separados:

```powershell
git add index.html styles.css
git commit -m "feat: crear estructura inicial del blog técnico"

git add index.html
git commit -m "docs: documentar post-mortem y aprendizajes"

git add README.md CHECKLIST-ENTREGA.md
git commit -m "docs: agregar instrucciones y checklist de entrega"

git push
```

Al terminar, usá en la entrega:

- Blog: `https://TU-USUARIO.github.io/blog-tecnico-mundial-alfajores/`
- Repositorio: `https://github.com/TU-USUARIO/blog-tecnico-mundial-alfajores`
- Commits: `https://github.com/TU-USUARIO/blog-tecnico-mundial-alfajores/commits/main`
