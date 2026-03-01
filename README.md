# Studio Aberrante - Generador de Propuestas

Proyecto estático listo para publicar en GitHub Pages.

## Estructura

- `index.html`: aplicación principal.

## Publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub (por ejemplo: `studio-aberrante-propuestas`).
2. Desde esta carpeta, ejecutar:

```bash
git init
git add .
git commit -m "Initial version - generador de propuestas"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

3. En GitHub:
- Ir a `Settings` > `Pages`.
- En `Build and deployment`, elegir:
  - `Source`: `Deploy from a branch`
  - `Branch`: `main` y carpeta `/ (root)`
- Guardar.

4. URL final:
- `https://TU_USUARIO.github.io/TU_REPO/`
