SANDINO LOGÍSTICA - ARCHIVOS INICIALES

Este proyecto está preparado para publicarse como GitHub Pages desde la raíz del repositorio.

Archivos:
- index.html: página inicial
- manifest.json: manifiesto PWA sin referencias a iconos
- style.css: estilos
- 404.html: página de error

PUBLICACIÓN:
1. Crear un repositorio nuevo en GitHub.
2. Subir todos estos archivos directamente a la raíz del repositorio (no dentro de otra carpeta).
3. En Settings > Pages, seleccionar Deploy from a branch.
4. Seleccionar Branch: main y Folder: /(root). Guardar.
5. Esperar unos minutos y abrir la URL de GitHub Pages.

IMPORTANTE:
El manifest no incluye iconos, por lo que PWABuilder puede seguir advirtiendo que faltan iconos para empaquetar o distribuir en tiendas. Primero verificamos que la página y el manifest se carguen. Luego podemos agregar iconos si el empaquetado los exige.
