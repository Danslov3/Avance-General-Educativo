# AulaNova EVA

Interfaz inicial de un Entorno Virtual de Aprendizaje con estética pixel-art moderna y paleta crema, beige, arena y terracota.

## Vista incluida
- Panel de inicio y navegación.
- Catálogo de 15 asignaturas con búsqueda y filtros.
- Rutas de tres unidades por asignatura.
- Evaluación de práctica y registro de resultados.
- Seguimiento local del progreso.
- Secciones de recursos y gestión académica.

## Estado y limitaciones
Esta publicación es un prototipo front-end de una sola página. El progreso y las notas se guardan en el almacenamiento local del navegador. No incluye todavía autenticación real, perfiles multiusuario, permisos de docente/administrador, base de datos compartida, materiales PDF/vídeo completos ni diplomas institucionales.

La integración prevista con Supabase requiere configurar Auth, base de datos y políticas Row Level Security (RLS) antes de utilizar datos reales.

## Ejecutar localmente
Abre `index.html` en un navegador moderno. Para publicar con GitHub Pages, configura Pages para desplegar desde la rama `main` y la carpeta raíz.
