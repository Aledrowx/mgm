# MGM Perú — sitio web para GitHub

Versión estática del diseño aprobado. Incluye las once páginas, los carruseles,
las tarjetas interactivas del equipo, las reseñas y los formularios por WhatsApp.
El HTML, los estilos, la lógica y las imágenes están en archivos separados.

Abre `index.html` en un navegador para probarlo. No requiere instalar paquetes,
compilar el proyecto, WordPress ni una conexión para mostrar el diseño.

## Estructura

| Archivo o carpeta | Contenido |
| --- | --- |
| `index.html` | Inicio |
| `nosotros.html` | Quiénes somos, misión, visión, equipo y valores |
| `servicios.html` | Cinco servicios, carrusel del proceso y preguntas |
| `resenas.html` | Siete empresas y sus reseñas |
| `contacto.html` | Canales de contacto, formulario y ubicación |
| `agenda.html` | Solicitud de asesoría |
| `servicios/gestion-contable.html` | Detalle de gestión contable |
| `servicios/asesoria-y-auditoria-tributaria.html` | Detalle de asesoría tributaria |
| `servicios/gestion-de-nominas.html` | Detalle de nóminas |
| `servicios/asesoria-legal.html` | Detalle de asesoría legal |
| `servicios/creacion-de-empresa-ruc-20.html` | Detalle de constitución de empresas |
| `assets/css/estilos.css` | Colores, fuentes, diseños y adaptación móvil |
| `assets/js/config.js` | WhatsApp, URL opcional de citas y campañas |
| `assets/js/app.js` | Menús, carruseles, perfiles, reseñas y formularios |
| `assets/img/marca/` | Logotipos MGM |
| `assets/img/equipo/` | Roberto y fotografía provisional del equipo |
| `assets/img/servicios/` | Fotografías de los servicios |
| `assets/img/oficina/` | Fotografías de oficina y asesoría |
| `assets/img/resenas/` | Fotografías referenciales de las reseñas |
| `assets/img/mapa/` | Mapa referencial |
| `assets/fonts/` | Fuente Inter y su licencia |
| `docs/` | Instrucciones, recursos y comprobación local |
| `SUBIR_A_GITHUB.txt` | Pasos rápidos para subir y publicar |

## Subir el proyecto

1. Extrae el ZIP.
2. Abre tu repositorio en GitHub y entra en **Add file → Upload files**.
3. Arrastra el contenido extraído, conservando las carpetas.
4. Comprueba que `index.html` esté en la raíz del repositorio, junto a `assets/`.
5. Guarda el cambio con un mensaje como `Añadir diseño de MGM Perú`.

Sube los archivos extraídos. GitHub Pages no descomprime un ZIP para servirlo
como página. Si tu repositorio ya contiene una web, este contenido sustituirá
los archivos que tengan el mismo nombre al guardar tus cambios.

## Activar GitHub Pages

En **Settings → Pages → Build and deployment**, elige **Deploy from a branch**.
Selecciona la rama donde subiste los archivos (normalmente `main`) y la carpeta
**/(root)**. Guarda. GitHub mostrará la dirección publicada cuando termine.

Los enlaces y recursos son relativos: funcionan tanto en la raíz de un dominio
como bajo la carpeta de un repositorio, sin poner su nombre dentro del código.

Más detalle: [Guía de GitHub Pages](docs/GITHUB_PAGES.md).

## Editar

Los textos se cambian en el HTML de cada página. Los colores y las medidas se
cambian en `assets/css/estilos.css`. La configuración pública se cambia en
`assets/js/config.js`. Consulta [la guía de edición](docs/EDICION.md).

Los siete logos y testimonios, y dos perfiles, siguen esperando el contenido
real. Las imágenes de oficina, servicios y reseñas son referenciales. La foto
de Roberto y los logotipos MGM proceden del sitio original.

Los formularios preparan mensajes para enviarlos por WhatsApp. Una solicitud
de cita requiere que MGM confirme la disponibilidad; esta versión no crea
reservas ni registros de clientes en un servidor.

La etiqueta `noindex,nofollow` se conserva porque esta entrega es una vista
previa. Si decides convertir GitHub Pages en el sitio definitivo, revisa esa
etiqueta, los datos finales y la configuración SEO del dominio que publiques.

Las plantillas e instrucciones para instalarlo en Odoo están en el paquete
`MGM_Rebranding_Odoo.zip` entregado por separado.
