# Plan de desarrollo

**Proyecto:** Open Language Learning  
**Versión:** 1.0  
**Estado:** propuesta inicial; actualizar a medida que se pruebe el proyecto.

## Etapa 1 — Definición y organización
- [x] Crear repositorio público.
- [x] Incluir README y licencia.
- [ ] Acordar requisitos y criterios de aceptación.
- [ ] Registrar decisiones técnicas.
- [ ] Crear lista inicial de tareas.

**Salida:** requisitos claros antes de programar.

## Etapa 2 — Estructura técnica
- [ ] Elegir tecnologías web estándar.
- [ ] Separar interfaz, contenido, evaluación, almacenamiento y voz.
- [ ] Definir formato de ejercicios, idioma y nivel.
- [ ] Añadir instrucciones para ejecutar y probar el proyecto.

**Salida:** base pequeña, comprensible y mantenible.

## Etapa 3 — Primera experiencia de aprendizaje
- [ ] Empezar con inglés.
- [ ] Añadir ejercicios de texto y explicaciones en español.
- [ ] Crear evaluación inicial breve.
- [ ] Ofrecer sesiones de 1, 3 y 5 minutos.
- [ ] Explicar correcciones y evitar aprobar una frase solo porque contiene una palabra clave.

## Etapa 4 — Progreso local
- [ ] Guardar preferencias y progreso en el dispositivo.
- [ ] Manejar errores de almacenamiento.
- [ ] Verificar que respuestas, progreso y preferencias no se envíen a servidores.
- [ ] Informar claramente si no se pudo guardar el avance.

## Etapa 5 — Motor de aprendizaje
- [ ] Registrar intentos por tema y tipo de error.
- [ ] Distinguir errores aislados de dificultades recurrentes.
- [ ] Repasar con ejemplos diferentes.
- [ ] Aplicar repaso espaciado.
- [ ] Tratar el dominio como una estimación revisable.
- [ ] No castigar al usuario por saltarse días de práctica.

## Etapa 6 — PWA y modo sin conexión
- [ ] Añadir manifiesto web.
- [ ] Implementar service worker y una estrategia clara de actualización.
- [ ] Mantener disponibles recursos básicos ya descargados.
- [ ] Comprobar que una actualización no borre el progreso.

## Etapa 7 — Copias de seguridad
- [ ] Exportación manual.
- [ ] Importación manual y validación de archivos.
- [ ] Ofrecer elección entre restaurar una copia o empezar de cero.
- [ ] Probar recuperación tras borrar datos del sitio y reinstalar.
- [ ] Investigar avisos de copia semanal, quincenal y mensual sin prometer tareas en segundo plano que la plataforma no garantice.

## Etapa 8 — Audio y recordatorios
- [ ] Reproducir voz cuando haya síntesis disponible.
- [ ] Usar reconocimiento de voz solo donde sea compatible.
- [ ] Permitir continuar por texto si la voz falla.
- [ ] Probar permisos y comportamiento de notificaciones antes de anunciarlas como funcionales.

## Etapa 9 — Pruebas y publicación
- [ ] Probar en Android 10 con Chrome.
- [ ] Repetir pruebas en Brave.
- [ ] Probar modo sin conexión, persistencia, exportación e importación.
- [ ] Publicar una versión de prueba por HTTPS.
- [ ] Documentar limitaciones conocidas.

## Criterios de aceptación iniciales

La primera versión no estará lista hasta que:
1. los ejercicios básicos funcionen sin conexión después de descargar los recursos;
2. el progreso se guarde localmente y no se envíe a un servidor;
3. las correcciones expliquen sus criterios y limitaciones;
4. un tema no se marque dominado por un solo acierto;
5. exportación e importación se hayan probado;
6. la actualización PWA no borre el progreso;
7. voz y notificaciones se describan según su compatibilidad real;
8. exista una lista de limitaciones conocidas.

**Regla de trabajo:** priorizar una función pequeña, probada y documentada antes que muchas funciones incompletas.
