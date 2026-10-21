# Monkeytools — Makako Team

Página web estática de acceso a tres herramientas:

- Análisis IP: https://ip.monkeytools.es/
- Análisis Dominios: https://dominio.monkeytools.es/
- Hashes: https://hash.monkeytools.es/

## Publicación con GitHub Pages

1. Crea un repositorio público en GitHub (por ejemplo, `monkeytools`).
2. Sube `index.html`, `styles.css` y la carpeta `assets/` **manteniendo la estructura**.
3. En el repositorio, ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige `main`, carpeta `/ (root)` y pulsa **Save**.
6. GitHub Pages publicará la web en `https://TU-USUARIO.github.io/monkeytools/` (si usas ese nombre de repositorio).

Si quieres utilizar `monkeytools.es`, configura primero ese dominio en GitHub Pages (Settings → Pages → Custom domain), consulta los registros DNS que GitHub indique para tu caso y añádelos en DonDominio. **No elimines los DNS de los subdominios `ip`, `dominio` y `hash`** porque son servicios independientes.

La web es estática: no requiere instalar dependencias ni compilar nada.
