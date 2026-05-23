## Caso 10: Integración de funcionalidades desarrolladas por dos subgrupos que nunca han trabajado juntos.

### Propuesta de Solución en Git:
1. **Definición de Contratos de API:** Antes de programar, ambos subgrupos deben acordar y documentar en el repositorio las interfaces, rutas y estructuras de datos comunes.
2. **Uso de Ramas de Integración:** Configurar una rama intermedia (por ejemplo, `develop`). Cada subgrupo subirá sus cambios a esta rama mediante **Pull Requests (PR)**.
3. **Revisiones de Código Cruzadas (Code Reviews):** Establecer como regla obligatoria que un miembro del Subgrupo A revise el Pull Request del Subgrupo B (y viceversa) para garantizar la compatibilidad antes de fusionar el código a la rama principal (`main`).