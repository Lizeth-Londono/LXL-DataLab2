# LXL Interview Lab — Aprende, practica y demuestra

Aplicación **estática, responsive y gratuita** para preparar entrevistas Junior en desarrollo de software. Desarrollada con HTML, CSS y JavaScript modular, sin backend ni dependencias externas.

## Empezar

1. Descomprime el ZIP.
2. Sirve el directorio con un servidor local (recomendado para módulos JavaScript): `python -m http.server 8000`.
3. Abre `http://localhost:8000` en Chrome o Edge.
4. Para GitHub Pages, sube `index.html`, `assets/` y `js/` directamente a la raíz del repositorio.
5. En **Settings → Pages**, selecciona **Deploy from a branch**, rama `main` y carpeta `/(root)`. Espera la publicación de GitHub y abre la URL que indique Pages.

> Abrir `index.html` directamente con `file://` puede bloquear importaciones JavaScript. Usa un servidor local o GitHub Pages.

## Qué incluye

- Dashboard y plan intensivo de ocho sesiones.
- Contenidos basados en el CV facilitado para HuellaVet, Planificador de Tareas, trayectoria de telecomunicaciones y formación de Generation Colombia.
- Banco de preguntas (RR. HH., técnica, proyectos, IA), respuestas orientativas y autoevaluación transparente.
- Lecciones con síntesis de voz en español, selección de voz disponible, velocidades y repetición 1/2/3/5/10.
- Reconocimiento de voz opcional cuando el navegador lo permita. También puedes escribir tus respuestas.
- Tarjetas para repetir, pruebas de selección múltiple con opciones mezcladas, ordenar pasos.
- Laboratorio de interpretación de código y explicaciones con pistas. **El código no se ejecuta**.
- Progreso local, marcadores de repaso y exportación/importación JSON.

## Límites y protección de datos

- No se envían respuestas a ningún servidor propio. Se guardan en `localStorage` solo tras guardarlas expresamente. La configuración y los resultados de ejercicios también se guardan en el navegador.
- La lectura en voz alta depende de la plataforma y las voces instaladas.
- El reconocimiento de voz puede utilizar servicios del proveedor del navegador. Actívalo solo si lo deseas; no introduzcas secretos o información privada de terceros.
- No se almacena audio. No hay reconocimiento ni retroalimentación generativa mediante API; la autoevaluación usa una rúbrica visible.
- El simulacro «Coupa» es **orientativo**, no representa preguntas oficiales. La invitación conocida anuncia un encuentro virtual para practicar entrevistas y recibir retroalimentación.
- Los proyectos se basan en la hoja de vida facilitada; antes de una entrevista, verifica las versiones actuales y los repositorios de los proyectos.
- El laboratorio de código es para razonar y explicar. Prueba el código por separado en herramientas adecuadas.

## Organización

```
index.html            Página principal
assets/styles.css     Diseño responsive
js/content.js         Preguntas, proyectos, retos y respuestas de ejemplo
js/app.js             Navegación, voz, juegos, simulación y persistencia
README.md             Este documento
```

## Personalización

Puedes modificar las preguntas de `js/content.js` (arrays `questions`, `quiz`, `labs`, etc.) sin cambiar el motor de la app. Usa únicamente información que puedas respaldar con experiencia, proyectos o documentos.

## Verificación recomendada

1. Abre todas las secciones desde navegación de escritorio y móvil.
2. Contesta una pregunta, comprueba y avanza; prueba también el modo de ordenar pasos.
3. Guarda una respuesta, recarga, comprueba persistencia, exporta e importa JSON.
4. Prueba narración, pausa y repetición con el navegador de destino.
5. Prueba micrófono solo si autorizas el reconocimiento.

© LXL — CODE × LIHEN. Proyecto de práctica personal.