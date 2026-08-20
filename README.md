# Presupuesto PWA V3

Aplicación PWA 100% offline.

## Incluye
- IndexedDB para almacenamiento local de los datos.
- Búsqueda por descripción/categoría.
- Edición y eliminación de movimientos.
- PIN local de 4 a 8 dígitos.
- Copias de seguridad JSON manuales y recordatorio automático semanal.
- Restauración de copias.
- CSV del mes.
- Service Worker y PWA instalable.
- Sin CDN, API, servidor ni conexión necesaria para operar.



## Importante sobre el PIN
El PIN protege la interfaz de la aplicación. Los datos permanecen en IndexedDB y **no están cifrados**.

## Copias automáticas
El navegador no permite que una PWA normal descargue archivos automáticamente cada semana sin interacción del usuario. V3 guarda la fecha de la última copia y muestra un aviso cuando corresponde. La copia se crea al pulsar `Copia ahora`.
