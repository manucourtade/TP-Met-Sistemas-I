# Sistema de Gestión Veterinaria — TP Metodología de Sistemas I

## De qué va el TP

Trabajo práctico grupal de la materia Metodología de Sistemas I. Consiste en elegir un sistema del mundo real y, a lo largo de varias consignas, aplicar el proceso de relevamiento y análisis: definir el dominio y los objetivos, levantar requerimientos hablando con un "cliente" (un agente de IA sin conocimientos técnicos), armar historias de usuario y casos de uso, definir el alcance del MVP, modelar diagramas (casos de uso y clases) y diseñar pruebas.

## Dominio elegido

Un sistema de gestión para una veterinaria: turnos, fichas clínicas de las mascotas, datos de los clientes (dueños/responsables) y diagnósticos cargados por los veterinarios.

## Por qué este prototipo

Una de las consignas pide un prototipo simple de las interfaces gráficas esperadas del sistema, sin necesidad de aplicar buenas prácticas de UI/UX a fondo. Este prototipo (HTML/CSS, responsive) muestra las 4 pantallas clave para cubrir esa consigna:

- **Login** de empleado
- **Turnos** del día con estado (pendiente / en curso / atendido)
- **Ficha de cliente y mascota** con historial
- **Registro de diagnóstico** por turno

Sirve como base visual para validar el flujo con el "cliente" y va a seguir ajustándose a medida que aparezcan nuevos requerimientos en la etapa de relevamiento.
