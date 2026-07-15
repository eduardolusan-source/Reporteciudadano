# Reporte ciudadano y ordenamiento territorial — Valle de Concá · Arroyo Seco

Paquete web para la reunión interinstitucional del 17 de julio de 2026 (Campus Concá, UAQ). Propuesta de estructura del mecanismo de reporte ciudadano de cambios irregulares de uso de suelo, con captura de acuerdos integrada y sincronizada a una hoja de cálculo de Google.

## Contenido

| Archivo | Pieza |
|---|---|
| `index.html` | Página principal: articula las cinco piezas del mecanismo |
| `teoria_del_cambio.html` | Pirámide interactiva: meta, cuatro líneas estratégicas y supuestos críticos |
| `reporte_formulario_anonimo.html` | Formulario web de reporte anónimo, mapa de zonificación y documentos del PMDU |
| `reporte_whatsapp.html` | Canal alternativo por WhatsApp (propuesta a discutir) |
| `consulta_zonificacion.html` | "¿Esto se puede aquí?": qué sí / qué no por zona y trámite de licencia |
| `infografia_pmdu.html` | Infografía: por qué respetar el programa de desarrollo urbano |
| `plan_pilotaje.html` | Tablero de trabajo de la mesa: tareas, responsables, productos y fechas (enlazado discretamente al pie de la página principal) |

## Captura de acuerdos en la reunión

- Cada sección tiene un botón **Comentar** (con campo opcional de quién comenta).
- Los comentarios se guardan en el navegador y **se envían automáticamente a la hoja de cálculo de Google** conectada (pestaña "Comentarios", con columna de página). Si no hay internet, quedan en cola y se reintentan solos cada minuto; el indicador de la barra superior muestra "hoja sincronizada" o cuántos faltan por enviar.
- **Exportar acuerdos** descarga además un archivo `.md` como respaldo local, por página.
- En el tablero de pilotaje, **Enviar plan a la hoja** manda una instantánea completa del plan (cada envío queda fechado); **Exportar plan acordado** genera la minuta en `.md`.

## Publicación en GitHub Pages

Subir la carpeta a un repositorio y activar Pages (Settings → Pages → rama principal, carpeta raíz). `index.html` queda como portada automáticamente. La sincronización con la hoja funciona igual publicada o abierta localmente.

**Nota:** si varias personas abren las páginas, todos los comentarios llegan a la misma hoja (cada quien ve localmente solo los suyos). Para la reunión, lo más ordenado sigue siendo capturar desde el equipo que proyecta.

## Pendientes marcados en las propias páginas

- Número institucional del canal WhatsApp y quién lo administra (por definir en la mesa)
- Botones de mapa y documentos aún sin destino (KMZ, PDFs del PMDU)
- Usos por zona de la consulta de zonificación: ejemplos ilustrativos por validar contra el PMDU
- Enlaces del trámite de licencia: por definir con el Municipio
- Conexión del formulario de reporte al sistema real de folios y alertas

---
Proceso interinstitucional: Municipio de Arroyo Seco · CONANP · PROFEPA · SEDESU · UAQ (Laboratorio de Desarrollo Rural, FCN).
