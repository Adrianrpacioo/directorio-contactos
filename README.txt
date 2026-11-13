DIRECTORIO PERSONAL - PWA

CONTENIDO
- index.html, styles.css, app.js: aplicación.
- manifest.webmanifest y sw.js: instalación y funcionamiento offline.
- iconos PNG: iconos de la PWA.

INSTALACIÓN EN IPHONE
1. Publica el contenido de esta carpeta en un alojamiento HTTPS (por ejemplo, GitHub Pages).
2. Abre la URL en Safari en el iPhone.
3. Pulsa Compartir > Añadir a pantalla de inicio.
4. Abre la aplicación desde el nuevo icono.

IMPORTAR CONTACTOS
En Contactos de iPhone, abre una ficha > Compartir contacto > Guardar en Archivos.
Después, en la PWA, elige el archivo .vcf.
Para varios contactos, puedes seleccionar/exportar un archivo VCF múltiple si tu método de exportación lo permite.

PRIVACIDAD
Los registros se guardan en localStorage del navegador de ese dispositivo. No hay cuenta, servidor ni sincronización.
Exporta copias de seguridad periódicamente desde el botón de la esquina superior derecha.
Borrar los datos del sitio o del navegador puede eliminar los contactos guardados. La copia JSON permite recuperarlos.

LIMITACIONES
- La PWA no accede directamente a toda la agenda de iOS: importa tarjetas VCF.
- Los datos no se sincronizan automáticamente entre dispositivos.
- La primera carga requiere conexión; después el service worker permite abrir la app sin conexión.
- Para máxima privacidad, protege el iPhone con código/Face ID y guarda las copias en un lugar seguro.

AVISO DE PROTECCIÓN DE DATOS
La ideología política es una categoría especial de datos personales bajo el RGPD. Registrar opiniones políticas de otras personas puede requerir una excepción específica del artículo 9 y una base jurídica del artículo 6, además de cumplir los principios de minimización, transparencia y seguridad. Esta herramienta no determina por sí sola que el tratamiento sea lícito.
