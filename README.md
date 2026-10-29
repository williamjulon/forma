# Forma · Miniapp de entrenamiento

## Publicación en Vercel

1. Descomprime el ZIP.
2. En Vercel crea un proyecto y sube la carpeta `curva-fit`, o importa un repositorio GitHub con estos archivos en la raíz.
3. No necesitas dependencias, Node, frameworks ni base de datos. El archivo principal es `index.html`.
4. Accede a tu dominio HTTPS de Vercel. Puedes instalar la app desde el navegador si se ofrece la opción de instalar aplicación.

## Guardado

- **Registros personales:** `localStorage`, único por dominio + navegador + dispositivo. Se conserva después de cerrar la pestaña, pero puede perderse si borras los datos del sitio, navegas en incógnito, cambias de navegador o reinstalas el dispositivo.
- **Funcionalidad offline:** `sw.js` precachea HTML, SVG, manifiesto. Las ilustraciones de ejercicio/comidas son SVG integrados en el HTML. Hay fuentes opcionales de Google Fonts; sin conexión usa fuentes del sistema.
- **Respaldo:** en Ajustes > Exportar respaldo JSON. Guarda copias periódicas. Restaurar mediante Ajustes > Importar respaldo.
- **No es una nube sincronizada**. Para compartir registros entre móviles o guardar en servidor necesitarás añadir una base de datos (p.ej. Supabase o Firebase).

## Contenido

Plan base: mujer adulta principiante, 26 años, 62 kg, 160 cm; hipertrofia de glúteos y piernas y recomposición corporal. Lunes cuádriceps/glúteos; martes espalda/bíceps; miércoles core; jueves empuje; viernes femorales/glúteos; sábado zumba; domingo recuperación.

El plan y sus valores son orientativos, no una prescripción individualizada. Entrena con técnica segura y adapta las cargas y el volumen a tu recuperación. Las ilustraciones son esquemáticas y no reemplazan un tutorial técnico.
