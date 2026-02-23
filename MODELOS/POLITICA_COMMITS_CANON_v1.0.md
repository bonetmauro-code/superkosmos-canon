# POLÍTICA DE COMMITS CANON v1.0

Estado: VIGENTE  
Versión: 1.0.0  

## Formato obligatorio

<tipo>: <descripción breve>

### Tipos permitidos

- feat: nueva funcionalidad
- fix: corrección
- chore: tareas estructurales
- docs: documentación
- refactor: mejora interna sin cambio funcional
- audit: revisión o validación formal
- evidence: incorporación de evidencia verificable

## Reglas

1. Un commit = una intención clara.
2. No commits genéricos ("update", "changes").
3. Toda modificación relevante debe estar reflejada en CHANGELOG.
4. Si hay evidencia asociada → incluir referencia en el mensaje.
5. Cambios estructurales mayores → requieren nueva tag semántica.

## Ejemplo correcto

feat: add MODELO_BITACORA_CANON v1.1  
chore: initialize HASH directory  
audit: validate structure before v0.1.0 release
