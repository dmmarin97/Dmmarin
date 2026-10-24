# Seguridad & Talento

Landing page estática para servicios de asesoría en seguridad y salud en el trabajo (SG-SST) y gestión humana en Santiago de Cali, Colombia.

## Archivos

- `index.html`: página, estilos y JavaScript.
- `assets/`: logotipo y fotografías que usa la página. Los nombres están en minúsculas y sin tildes para evitar problemas de rutas al publicar.
- `.nojekyll`: indica a GitHub Pages que publique los archivos estáticos tal como están.

No se requiere instalar dependencias ni ejecutar un proceso de compilación.

## Publicar en GitHub Pages

1. Sube `index.html`, `README.md` y la carpeta completa `assets/` a la raíz del repositorio. La carpeta debe conservar ese nombre y contener `logo.png`, `hero.jpeg`, `trabajo.jpg`, `asesoria.jpg`, `verificacion.jpg` y `gestion.jpg`.
2. En el repositorio, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Selecciona la rama donde subiste el sitio y la carpeta **/(root)**; pulsa **Save**.
5. Espera a que termine la publicación y abre la URL que muestra GitHub Pages en esa misma sección.

No subas solo `index.html`: el logotipo y las fotografías son archivos independientes que deben estar en `assets/` en la misma rama que la página. Si usas Git, desde la carpeta del sitio ejecuta `git add index.html README.md .nojekyll assets` y luego confirma y publica esos cambios en la rama seleccionada en Pages.

## Formulario de contacto

El formulario valida los campos y muestra una confirmación en el navegador, pero una página estática en GitHub Pages no puede enviar ni almacenar mensajes por sí sola. Antes de recibir consultas, conecta el formulario a un servicio de formularios o a un backend y actualiza el mensaje de confirmación para reflejar el envío real.
