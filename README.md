# Universo de Partículas - Control por Gestos

Proyecto web preparado para publicarse con **GitHub Pages**.

## Publicación

1. Crea un repositorio nuevo en GitHub.
2. Sube los archivos de esta carpeta a la raíz del repositorio.
3. En GitHub, abre **Settings > Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige la rama `main` y la carpeta `/ (root)`.
6. Guarda los cambios. GitHub mostrará la URL pública cuando termine el despliegue.

## Importante

- La aplicación necesita acceso a la cámara.
- GitHub Pages usa HTTPS, requisito adecuado para `navigator.mediaDevices.getUserMedia()`.
- Se recomienda usar Chrome o Edge.
- El proyecto carga Three.js y MediaPipe desde CDN, por lo que requiere conexión a Internet.
