# Contributing to StudentHub

Gracias por colaborar en StudentHub. Esta guía resume cómo trabajamos con Git y GitHub en el proyecto.

## Flujo de trabajo

1. Actualizar `main` antes de empezar:
```bash
   git checkout main
   git pull origin main
```
2. Crear una rama descriptiva:
```bash
   git checkout -b tipo/nombre-descriptivo
```
3. Hacer cambios pequeños y commits claros, revisando siempre antes de confirmar:
```bash
   git status
   git diff
```
4. Publicar la rama:
```bash
   git push -u origin nombre-de-la-rama
```
5. Abrir un Pull Request hacia `main` y esperar revisión.
6. Corregir lo que pida la revisión (si aplica) y volver a hacer push a la misma rama.
7. Una vez aprobado, integrar el Pull Request a `main`.

## Convención de commits

Usamos un prefijo corto que indica el tipo de cambio:

- `feat:` — nueva funcionalidad
- `docs:` — cambios de documentación
- `fix:` — corrección de errores
- `refactor:` — cambios internos que no alteran el comportamiento

Ejemplo: `feat: document student profile`

## Ramas

- `main` siempre debe quedar estable y funcional.
- Ninguna persona hace commits directos a `main`; todo cambio pasa por una rama y un Pull Request.
- El nombre de la rama debe reflejar lo que hace: `feature/...` para funcionalidades, `docs/...` para documentación, `fix/...` para correcciones.

## Revisión de Pull Requests

- Al menos una persona del equipo revisa antes de aprobar.
- Si se solicitan cambios, quien abrió el PR corrige y actualiza la misma rama (no crea una nueva).
- Solo se hace merge cuando el PR está aprobado.