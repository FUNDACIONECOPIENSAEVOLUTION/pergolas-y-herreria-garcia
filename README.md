# Pérgolas y Herrería García

Sitio web corporativo estático para portafolio y solicitudes de cotización.

## Qué contiene

- `index.html`: página comercial responsive, servicios, nueve fotografías originales, filtros, visor ampliado y generador de cotizaciones.
- `assets/garcia-mark.svg`: emblema vectorial original usado como logotipo y favicon.
- `assets/garcia-cover.svg`: imagen institucional de portada para compartir y campañas.
- Nueve fotografías JPEG originales aportadas al repositorio, conservadas con sus nombres actuales.

## Activar GitHub Pages

En **Settings → Pages → Build and deployment**, seleccionar **Deploy from a branch**; en **Branch**, escoger `main` y `/(root)`, y guardar.

URL prevista: https://fundacionecopiensaevolution.github.io/pergolas-y-herreria-garcia/

La publicación depende de la configuración del repositorio y puede requerir habilitar GitHub Pages manualmente.

## Habilitar WhatsApp comercial

El proyecto **no incluye un número inventado**. Al recibir el número real del taller, abrir `index.html`, ubicar:

```js
const WHATSAPP_NUMBER = "";
```

y colocar el número en formato internacional sin `+` ni espacios, por ejemplo `57XXXXXXXXXX` (solo indica formato, no es un número funcional).

Antes de vincularlo, el formulario permite preparar y copiar un mensaje, o compartirlo abriendo WhatsApp sin destinatario predefinido. No se almacenan datos personales y no hay servidor de formularios.

## Actualizar fotos y textos

El álbum aparece en el arreglo `photos` usado para generar los elementos de la página. Las nueve fotos actuales se referencian por rutas relativas con codificación URL para conservar nombres originales. Mantener la correspondencia entre cada foto, su descripción y su proyecto.

## Guía visual

- Grafito: `#171b1d`
- Cobre: `#b9824f`
- Dorado suave: `#e1b580`
- Marfil: `#f7f5f0`

Diseño original para Pérgolas y Herrería García. No se declara ubicación, teléfono, trayectoria, certificaciones ni garantías que no hayan sido confirmadas por el negocio.
