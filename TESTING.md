# Plan de pruebas

**Objetivo:** verificar el funcionamiento real y documentar límites y errores reproducibles.

## Reglas generales
- Usar datos de prueba, nunca información privada real.
- Anotar dispositivo, sistema, navegador y versión de la aplicación.
- Registrar pasos concretos para reproducir errores.
- No aprobar una prueba solo porque la interfaz se ve bien.
- Antes de borrar datos, comprobar que cualquier información importante esté respaldada.

## Matriz inicial

| ID | Área | Prueba | Resultado esperado |
|---|---|---|---|
| T-001 | Inicio | Abrir por primera vez | Se muestra la práctica sin errores |
| T-002 | Ejercicio | Enviar respuesta vacía | Se solicita una respuesta sin bloquear la app |
| T-003 | Corrección | Enviar frase correcta y relevante | La evaluación explica por qué cumple |
| T-004 | Corrección | Usar un verbo en pasado en una frase incorrecta | No se aprueba toda la frase solo por detectar una palabra |
| T-005 | Aprendizaje | Acertar una vez un tema nuevo | No se declara dominio definitivo |
| T-006 | Repaso | Fallar y probar otro ejemplo | Se ofrece ayuda y un ejemplo diferente |
| T-007 | Preferencias | Cambiar duración y modalidad | La selección se refleja correctamente |
| T-008 | Persistencia | Cerrar y reabrir el navegador | Se conservan datos mientras el almacenamiento siga disponible |
| T-009 | Privacidad | Revisar solicitudes de red durante el uso | No se envían respuestas, progreso ni preferencias personales |
| T-010 | PWA | Instalar desde navegador compatible | La instalación se ofrece cuando la plataforma lo permite |
| T-011 | Sin conexión | Desconectar después de cargar recursos | Funciones básicas y recursos descargados siguen disponibles |
| T-012 | Actualización | Publicar actualización de prueba | No se borra el progreso local |
| T-013 | Exportación | Exportar progreso de prueba | Se genera un archivo válido |
| T-014 | Importación | Importar copia válida | Se restaura el progreso de prueba |
| T-015 | Importación | Importar archivo inválido | Se informa el error y no se corrompen los datos actuales |
| T-016 | Recuperación | Borrar datos del sitio y restaurar copia | La recuperación funciona según las instrucciones |
| T-017 | Voz | Navegador sin reconocimiento de voz | Se informa la limitación y se puede seguir por texto |
| T-018 | Audio | Reproducir pregunta con voz disponible | Se escucha la frase cuando el dispositivo dispone de la voz |
| T-019 | Recordatorios | Probar permisos y segundo plano | Se documenta el resultado real sin promesas no verificadas |
| T-020 | Navegadores | Repetir en Chrome y Brave | Se documentan diferencias y fallos |

## Dispositivos iniciales
- Teléfono: Huawei P30 Lite.
- Sistema operativo: Android 10.
- Navegadores iniciales: Chrome y Brave.
- Equipo de escritorio: Firefox para revisión complementaria.

Anotar las versiones exactas en cada prueba.

## Plantilla para registrar una prueba
- **ID:**
- **Fecha:**
- **Versión o commit:**
- **Dispositivo y sistema:**
- **Navegador y versión:**
- **Pasos realizados:**
- **Resultado esperado:**
- **Resultado observado:**
- **Estado:** pendiente / aprobada / fallida / bloqueada
- **Notas o captura sin datos personales:**

## Prioridades antes de publicar
1. Verificar que el progreso no se envía a servidores.
2. Comprobar persistencia tras cerrar y reabrir.
3. Probar exportación e importación.
4. Probar el modo sin conexión.
5. Evitar falsos positivos evidentes en la corrección.
6. Documentar voz y notificaciones según cada navegador.

## Limitaciones que deben comunicarse
- El almacenamiento local puede borrarse por el usuario, el navegador o el sistema.
- Los datos locales no se comparten automáticamente entre Chrome y Brave ni entre dispositivos.
- Síntesis y reconocimiento de voz dependen del dispositivo y del navegador; algunas funciones pueden requerir conexión.
- Los recordatorios fiables en segundo plano no están garantizados en todos los entornos PWA.
- Las reglas de corrección iniciales tienen límites y no equivalen a una comprensión completa del idioma.
