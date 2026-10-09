# Nexo Eventos — sitio gratuito

Sitio estático, adaptable a celular, sin cuotas mensuales ni backend. Incluye catálogo de servicios y formulario para preparar una solicitud de cotización.

## Publicar gratis en GitHub Pages

1. Abre https://github.com/new y crea un repositorio público llamado `nexo-eventos`.
2. Sube el archivo `index.html` a la raíz del repositorio (Add file > Upload files > Commit changes).
3. Ve a **Settings > Pages** y selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)** y guarda.
4. Después de desplegar, la dirección será `https://TU-USUARIO.github.io/nexo-eventos/`.

## Antes de compartir la página

- En `index.html`, sustituye `const WHATSAPP_NUMBER = '';` por tu número comercial en formato internacional (ejemplo: `const WHATSAPP_NUMBER = '525512345678';`). Esto activa el botón de WhatsApp para enviar una solicitud precargada.
- El formulario **no envía ni almacena solicitudes por sí solo**; genera un texto para copiar o compartir. Para recibir consultas automáticamente hay que agregar integración de formularios, correo o backend.
- Las fotografías se cargan de Unsplash y las tipografías de Google Fonts; requieren internet. Confirma licencias y sustituye por imágenes propias para la versión definitiva.
- Los textos, el nombre comercial y los servicios son editables en `index.html`.
- No se incluye pago en línea ni precios inventados; la cotización queda sujeta a proveedores reales.

## Desarrollo

Abre `index.html` en un navegador. No hace falta instalar dependencias.
