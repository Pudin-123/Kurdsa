# KURD S.A. — sitio web

Sitio institucional estático para KURD S.A., desarrollado con HTML, CSS y JavaScript sin dependencias externas.

## Contenido

- `index.html`: página principal y asistente para preparar consultas de presupuesto.
- `productos.html`: catálogo con filtros y ordenamiento.
- `nosotros.html`: información institucional.
- `kurd-logo.png`: logotipo utilizado por el sitio.

## Vista previa local

Desde esta carpeta, iniciá un servidor local:

```powershell
py -m http.server 8000
```

Después abrí <http://localhost:8000>.

También podés iniciar la tarea **Servir sitio Kurdsa** desde Visual Studio Code.

## Publicar con GitHub Pages

1. Subí los archivos del proyecto a la raíz de un repositorio de GitHub.
2. En el repositorio, abrí **Settings → Pages**.
3. En **Build and deployment**, elegí **Deploy from a branch**, seleccioná `main` y la carpeta `/(root)`, y guardá.
4. GitHub Pages publicará el sitio en la URL que muestre esa pantalla.

No hace falta compilar ni instalar dependencias. El sitio usa rutas relativas para que las páginas y el logotipo funcionen desde GitHub Pages.

## Formulario de presupuesto

El formulario funciona enteramente en el navegador: permite revisar la consulta, descargar una copia y preparar un borrador de correo. No envía ni almacena datos en un servidor. El borrador no tiene destinatario configurado; quien lo use debe agregar la dirección de KURD S.A.

## Derechos de uso

Este repositorio no incluye una licencia de reutilización. Antes de publicarlo, confirmá que tenés autorización para compartir el sitio y el logotipo de KURD S.A. Sin una licencia explícita, no se concede permiso para reutilizar el código o los recursos.
