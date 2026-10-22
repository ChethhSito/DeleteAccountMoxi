# Páginas públicas de MotoX

Este repositorio contiene páginas HTML estáticas para la ficha de MotoX en Google Play:

- index.html: portada sencilla con enlaces a las dos páginas.
- privacidad.html: política de privacidad.
- eliminar-cuenta.html: instrucciones para solicitar la eliminación de una cuenta sin iniciar sesión.
- style.css: presentación compartida, adaptable a móvil.

## Por qué existe este sitio

Google Play solicita una URL pública para la política de privacidad y, cuando la app permite crear una cuenta, un recurso web desde el que se pueda pedir su eliminación aunque la app ya no esté instalada. Estas páginas cubren la parte informativa y ofrecen el correo contacto@nosplanet.org como canal de solicitud. El enlace de correo no es un formulario ni ejecuta un borrado automático.

## Publicación con GitHub Pages

1. Revisar y aprobar el contenido con NOS PLANET SAC. Confirmar que contacto@nosplanet.org existe, recibe mensajes y tiene un responsable que atenderá solicitudes.
2. En este repositorio, abrir Settings > Pages. En Build and deployment elegir Deploy from a branch, seleccionar main y la carpeta / (root), y guardar.
3. Esperar a que Pages indique la URL publicada. Si se utiliza el dominio estándar, las páginas deberían quedar en:
   - https://chethhsito.github.io/DeleteAccountMoxi/privacidad.html
   - https://chethhsito.github.io/DeleteAccountMoxi/eliminar-cuenta.html
4. Abrir ambas URL desde una ventana privada y desde un teléfono. Verificar que carguen sin cuenta, que los enlaces funcionen y que el correo de solicitud se pueda enviar.
5. Registrar la URL de privacidad en Política y programas > Contenido de la app > Política de privacidad. Registrar la URL de eliminación en las preguntas de eliminación de datos de Seguridad de los datos. Los nombres de los menús pueden variar por idioma.
6. Hacer una solicitud de prueba con una cuenta de ensayo. Confirmar recepción, verificación de identidad, gestión del borrado y respuesta al solicitante.

## Alcance y pendientes

No hay API, formulario conectado ni lógica de borrado en este repositorio. El proceso por correo debe ser atendido por NOS PLANET SAC. El borrado dentro de la aplicación MotoX usa una función de Firebase llamada delete_my_account; desplegarla y probarla es un trabajo separado antes de publicar la app.

La política web debe coincidir con el comportamiento de la versión final de la app y con el formulario de Seguridad de los datos. Revisar especialmente los permisos de ubicación, los proveedores usados y cualquier plazo legal de retención antes de enviar la app a revisión. No se ha verificado desde este repositorio que el sitio esté publicado ni que el correo sea operativo.
