# Pérgolas y Herrería García

Sitio web corporativo estático para portafolio y solicitudes de cotización de **Pérgolas y Herrería García, con base en Ciudad de México (CDMX), México**.

## Qué contiene

- `index.html`: página comercial responsive, portada conceptual hiperrealista, siete familias de servicios con imágenes identificadas, nueve fotografías auténticas del taller, filtros, visor ampliado y generador de cotizaciones.
- `catalogo.html`: catálogo comercial de siete categorías, detalles y posibilidades de servicio, galería real separada y botón **Imprimir / Guardar PDF** (desde el navegador).
- `assets/catalogo/*.jpg`: siete imágenes fotorrealistas de referencia conceptual (pérgola, techumbre, portón, barandal, escalera, celosía y taller). **No deben anunciarse como obras realizadas.**
- `assets/portada-institucional.svg`: portada publicitaria horizontal 1200 × 630 con fotografía de referencia incrustada.
- `assets/ficha-servicios.svg`: gráfica vertical de servicios 1080 × 1350 con fotografía de referencia incrustada.
- `assets/garcia-mark.svg`: emblema vectorial original usado como logotipo y favicon.
- `assets/garcia-cover.svg`: imagen institucional de portada para compartir y campañas.
- Nueve fotografías JPEG originales aportadas al repositorio, conservadas con sus nombres actuales.

## Activar GitHub Pages

En **Settings → Pages → Build and deployment**, seleccionar **Deploy from a branch**; en **Branch**, escoger `main` y `/(root)`, y guardar.

URL prevista: https://fundacionecopiensaevolution.github.io/pergolas-y-herreria-garcia/

La publicación depende de la configuración del repositorio y puede requerir habilitar GitHub Pages manualmente.

**Direcciones tras activar Pages:**
- Portada: https://fundacionecopiensaevolution.github.io/pergolas-y-herreria-garcia/
- Catálogo: https://fundacionecopiensaevolution.github.io/pergolas-y-herreria-garcia/catalogo.html

Para revisar cambios, probar la galería, los siete enlaces de servicio y las imágenes en móvil y escritorio.

## Habilitar WhatsApp comercial

El proyecto **no incluye un número inventado**. Al recibir el número real del taller, abrir `index.html`, ubicar:

```js
const WHATSAPP_NUMBER = "";
```

y colocar el número en formato internacional sin `+` ni espacios, con el prefijo de México `52` seguido de los **10 dígitos reales** del teléfono del negocio, por ejemplo `52XXXXXXXXXX` (solo indica formato, no es un número funcional).

Antes de vincularlo, el formulario permite preparar y copiar un mensaje, o compartirlo abriendo WhatsApp sin destinatario predefinido. No se almacenan datos personales y no hay servidor de formularios.

## Actualizar fotos y textos

El álbum aparece en el arreglo `photos` usado para generar los elementos de la página. Las nueve fotos actuales se referencian por rutas relativas con codificación URL para conservar nombres originales. Mantener la correspondencia entre cada foto, su descripción y su proyecto.

## Guía visual

- Grafito: `#171b1d`
- Cobre: `#b9824f`
- Dorado suave: `#e1b580`
- Marfil: `#f7f5f0`

Diseño original para Pérgolas y Herrería García. **Ubicación confirmada: Ciudad de México (CDMX), México**. Dirección exacta, alcaldía de la sede, teléfono comercial, cobertura fuera de CDMX, trayectoria, certificaciones y garantías permanecen sin declarar hasta su confirmación.

## Política de imágenes y alcance del catálogo

Las nueve fotografías subidas originalmente por el cliente se mantienen en **Obras reales**. Las siete fotografías fotorrealistas adicionales y las dos portadas son **propuestas visuales generadas**. Están etiquetadas como ilustrativas y nunca se presentan como proyectos ejecutados.

Las siete familias de servicios son líneas que se pueden **consultar al taller**; disponibilidad, medidas, presupuestos, espesores, cálculo estructural, fijaciones, garantías, tiempos de entrega y cobertura de instalación se determinan con el negocio para cada caso. No se promete cobertura en toda el área metropolitana sin confirmar.

Datos pendientes para convertir la web en canal directo de clientes: número real de WhatsApp mexicano, dirección o alcaldía del taller, horarios, correo comercial si existe y zona efectiva de atención. No se publica ningún teléfono de ejemplo.
