# Reglas del Equipo

## 1. Flujo de trabajo (Workflow)
- Toda tarea se trabaja en una rama nueva, nunca directo sobre `main`.
- Nombra las ramas con el formato: `tipo/descripcion-corta`
  - `feat/` → nueva funcionalidad
  - `fix/` → corrección de errores
  - `docs/` → documentación
  - `refactor/` → mejoras internas sin cambiar comportamiento
  - `test/` → pruebas

## 2. Commits
- Usa mensajes claros y en tiempo presente: `docs: add team rules guide`
- Un commit debe representar un cambio lógico, no mezclar varias cosas distintas.
- Evita mensajes genéricos como `cambios` o `fix`.

## 3. Pull Requests
- Todo cambio se sube a través de un Pull Request, nunca push directo a `main`.
- El PR debe tener:
  - Título claro y descriptivo
  - Breve descripción de qué cambia y por qué
- Se requiere al menos **1 revisión aprobada** antes de hacer merge.
- Quien abre el PR no se aprueba a sí mismo.

## 4. Revisión de código (Code Review)
- Revisa el código en un plazo máximo de 24-48 horas.
- Los comentarios deben ser constructivos y específicos.
- Si hay desacuerdo, se discute en el PR o en una llamada rápida, no se ignora.

## 5. Merge
- Usa `Squash and merge` para mantener el historial limpio (o el método que defina el equipo).
- Elimina la rama después de hacer merge.
- Nunca hagas `force push` sobre ramas compartidas (`main`, `develop`).

## 6. Comunicación
- Reporta bloqueos o dudas lo antes posible en el canal del equipo.
- Actualiza el estado de tus tareas regularmente (tablero/Issues).

## 7. Reuniones
- Horario de daily/standup: 6:00 pm
- Duración máxima: 15 minutos.
- Si no puedes asistir, avisa con anticipación.