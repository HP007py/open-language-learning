# Registro de decisiones

Este documento registra decisiones de producto y sus motivos. Pueden revisarse cuando haya nuevas pruebas.

## D-001 — Proyecto abierto
**Estado:** aceptada  
**Decisión:** desarrollar en un repositorio público.  
**Motivo:** facilitar aprendizaje, reutilización, revisión y contribuciones.  
**Consecuencia:** no incluir secretos, datos personales ni copias de seguridad privadas.

## D-002 — Privacidad local por defecto
**Estado:** requisito aceptado  
**Decisión:** respuestas, progreso y preferencias permanecen en el dispositivo.  
**Motivo:** evitar recopilar datos personales de aprendizaje.  
**Consecuencia:** sin sincronización automática en la primera versión; los datos locales pueden borrarse, por lo que se necesitan copias manuales.

## D-003 — Empezar por inglés y diseñar para varios idiomas
**Estado:** aceptada  
**Decisión:** implementar primero inglés y separar el contenido de la lógica.  
**Motivo:** reducir el alcance inicial sin cerrar la posibilidad de crecer.  
**Consecuencia:** cada idioma tendrá contenido y metadatos propios.

## D-004 — Sesiones cortas
**Estado:** aceptada  
**Decisión:** un minuto por defecto, con opciones de tres y cinco minutos.  
**Motivo:** facilitar prácticas frecuentes.

## D-005 — Explicaciones en español
**Estado:** aceptada para la primera versión  
**Decisión:** explicaciones y ayudas en español; ejercicios en el idioma objetivo.  
**Motivo:** reducir la fricción para hispanohablantes.

## D-006 — El aprendizaje requiere evidencia acumulada
**Estado:** requisito aceptado  
**Decisión:** no declarar dominado un tema tras una sola respuesta correcta.  
**Motivo:** distinguir aciertos casuales de aprendizaje consolidado.  
**Consecuencia:** usar varios intentos, ejemplos distintos y repaso espaciado.

## D-007 — No depender de IA remota para ejercicios básicos
**Estado:** principio inicial aceptado  
**Decisión:** la práctica básica deberá funcionar sin conexión a un servicio de IA.  
**Motivo:** favorecer privacidad y disponibilidad.  
**Consecuencia:** las reglas iniciales serán explícitas y tendrán límites documentados. Una futura IA remota sería opcional y requeriría revisar privacidad.

## D-008 — Voz opcional
**Estado:** aceptada  
**Decisión:** texto como alternativa básica; audio y reconocimiento de voz según compatibilidad.  
**Motivo:** la disponibilidad varía entre dispositivos y navegadores.  
**Consecuencia:** siempre debe ser posible continuar por texto.

## D-009 — Copias de seguridad bajo control del usuario
**Estado:** objetivo aceptado  
**Decisión:** exportación e importación manuales, con avisos opcionales para recordar copias.  
**Motivo:** recuperar datos sin enviarlos a un servidor.  
**Consecuencia:** probar restauración tras borrar datos y reinstalar; no prometer guardado automático en segundo plano sin soporte comprobado.

## D-010 — Recordatorios sujetos a pruebas
**Estado:** pendiente de validación técnica  
**Decisión provisional:** recordatorios opcionales, con intervalo inicial sugerido de tres horas.  
**Motivo:** fomentar práctica frecuente sin obligar al usuario.  
**Consecuencia:** comprobar permisos y comportamiento real antes de anunciar esta función como disponible.

## D-011 — Primera plataforma de prueba
**Estado:** aceptada como plan  
**Decisión:** comenzar en Android 10 con Chrome y Brave.  
**Motivo:** validar en un teléfono real y comparar navegadores.  
**Consecuencia:** no asumir que los navegadores comparten datos locales.

## D-012 — La interfaz no demuestra que una función exista
**Estado:** aceptada  
**Decisión:** documentar por separado el estado visual y el funcional.  
**Motivo:** evitar que un prototipo prometa capacidades incompletas.  
**Consecuencia:** cada función requiere una prueba verificable antes de considerarse lista.
