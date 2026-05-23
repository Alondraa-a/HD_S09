## Caso 10: El equipo necesita integrar funcionalidades desarrolladas por dos subgrupos que nunca han trabajado juntos.

### Propuesta de Solución en Git:
1. **Definición de Contratos de API y Estructuras:** Antes de intentar fusionar los códigos, ambos subgrupos deben documentar las interfaces, rutas y estructuras de datos comunes en la raíz del repositorio para asegurar la compatibilidad.
2. **Uso de Ramas de Integración Común (Develop):** En lugar de subir los cambios directamente a `main`, se configura una rama intermedia llamada `develop`. Cada subgrupo sube sus funcionalidades a esta rama mediante **Pull Requests (PR)** independientes.
3. **Revisiones de Código Cruzadas (Code Reviews):** Establecer como regla obligatoria que al menos un miembro del Subgrupo A revise el Pull Request del Subgrupo B (y viceversa). Esto garantiza que se detecten y resuelvan posibles conflictos de código o lógica antes de consolidar la versión final en la rama principal (`main`).