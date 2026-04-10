# Working days configuration (prototype)

Página estática de configuración de días laborables y horario (tema PrimeNG vía CDN). Sin build ni dependencias locales.

## Vista local

```bash
python3 -m http.server 8080
```

Abre: http://localhost:8080/ (redirige a `working-days-config.html`) o directamente http://localhost:8080/working-days-config.html

## Publicar en GitHub

1. Crea un repositorio vacío en GitHub (sin README si ya tienes uno aquí).
2. En esta carpeta:

   ```bash
   git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
   git branch -M main
   git push -u origin main
   ```

## GitHub Pages (opcional)

En el repo: **Settings → Pages → Build and deployment → Branch**: `main`, carpeta `/ (root)`. La URL raíz servirá `index.html`, que enlaza al prototipo.
