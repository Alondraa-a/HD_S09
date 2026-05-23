## Caso 6: El cliente cambia los requerimientos a mitad del sprint, causando confusión en el equipo.

### Propuesta de Solución en Git:
1. **Uso Riguroso de Git Tags y Versiones:** Al iniciar cada Sprint, se debe marcar el estado de los requerimientos aprobados con un Tag (ej. `v1.0-sprint-req`). 
2. **Aislamiento en Ramas Feature:** Si el cliente exige un cambio drástico e inmediato, este no se toca en las ramas activas del sprint. Se abre una rama de diseño independiente (`feature-change-req`) para evaluar el impacto técnico y reestimar las tareas en el tablero de Git sin detener el trabajo actual del equipo.
3. **Historial como Respaldo de Negociación:** El historial de commits sirve como bitácora clara frente al cliente para demostrar qué características ya estaban desarrolladas y el costo en tiempo que implicará revertir o modificar esos commits.