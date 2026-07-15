# StockÁgil Pro

Proyecto listo para GitHub Pages.

## Publicación

1. Cree un repositorio en GitHub.
2. Suba **todo el contenido**, incluida la carpeta `assets`.
3. Entre a **Settings → Pages**.
4. Seleccione **Deploy from a branch**.
5. Elija `main` y `/ (root)`.
6. Pulse **Save**.

## Estructura

```text
StockAgil_GitHub_Pages/
├── index.html
├── 404.html
├── .nojekyll
├── README.md
└── assets/
    ├── css/
    │   └── styles.css
    └── js/
        └── app.js
```

## Accesos

- Administrador: `admin` / `admin123`
- Cajero: `cajero` / `caja123`
- Bodega: `bodega` / `bodega123`
- Supervisor: `supervisor` / `super123`

## Nota técnica

La aplicación usa `localStorage`. Cada navegador conserva sus propios datos; GitHub Pages no comparte información entre dispositivos ni usuarios. Para sincronización real hace falta backend y base de datos.
