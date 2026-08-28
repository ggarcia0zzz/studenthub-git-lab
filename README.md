# StudentHub

StudentHub es una plataforma para gestionar servicios académicos universitarios.

El proyecto será desarrollado colaborativamente utilizando Git y GitHub.

## Funcionalidades

- Gestión de estudiantes
- Gestión de cursos

## Equipo

- Developer A
- Developer B

## Preguntas de reflexión

### 1. ¿Cuál es la diferencia entre `git add` y `git commit`?

**Gabriela:**

El git add prepara los cambios que desea incluir en el siguiente commit, mientras git commit crea el nuevo commit con esos cambios.

**Juan David**

Con add preparo los cambios para guardarlos, con commit los guardo de verdad en el historial.

### 2. ¿Cuál es la diferencia entre `git push` y `git pull`?

**Gabriela**

Git push envia archivos del repositorio local al repositorio remoto, y el git pull trae una copia del repositorio remoto y la copia en el repositorio local y directorio.

**Juan David**

Con pull traigo los cambios del remoto a mi computador, con push subo los míos al remoto.

### 3. ¿Cuál es la diferencia entre un repositorio local y uno remoto?

**Gabriela**

La diferencia es que el remoto es el que almacena nuestra información en la nube cuando nosotros le damos commit, mientras que el repositorio local es donde uno va guardando todos los cambios sin haber hecho el commit.

**Juan David**

El repositorio local está en mi computador, el remoto está en un server como GitHub donde comparto el código con el equipo.

### 4. ¿Qué problema resuelve una rama?

**Gabriela**

Evita que se suban cambios a producción o a la rama principal que estén a medias o con errores.

**Juan David**

Me deja trabajar en mi propia versión sin romper o dañar lo que ya funciona en main.

### 5. ¿Qué diferencia existe entre `git merge` y `git rebase`?

**Gabriela**

La diferencia entre estos dos es que git merge deberia ser usado para subir cambios y nuevas features a la rama principal y git rebase deberia usarse cuando se trata de integrar ramas secundarias.

**Juan David**

Con merge junto dos ramas y se crea un commit extra que marca esa unión. Con rebase reacomodo mis commits arriba de los últimos cambios y dejo el historial más limpio.

### 6. ¿Por qué ocurre un conflicto?

**Gabriela**

Un conflicto en ocurre cuando el sistema no puede determinar automáticamente qué versión de un archivo conservar.

**Juan David**

Ocurre cuando yo y otra persona cambiamos la misma parte de un archivo y Git no sabe cuál versión dejar.

### 7. ¿Quién debe decidir cómo resolver un conflicto?

**Gabriela**

El desarrollador o el equipo que conoce el código y los cambios involucrados.

**Juan David**

La persona que está haciendo el merge o rebase, revisando ambas versiones y decidiendo qué dejar.

### 8. ¿Qué problema resuelve un Pull Request?

**Gabriela**

Resuelven problemas como no permitir que al implementarse cambios estos tengan erores, problemas de seguridad, entre otros, gracias a que este ayuda a identificarlos.

**Juan David**

Evito que el código llegue a main sin que nadie lo revise antes.

### 9. ¿Por qué es recomendable revisar un Pull Request antes de integrarlo?

**Gabriela**

Por como se habia dicho anteriormente, estos ayudan a poder identificar errores e indicarlos.

**Juan David**

Para ver si hay errores o cosas mal hechas antes de que afecten a todo el equipo.

### 10. ¿Qué ventaja tiene trabajar en una rama en lugar de modificar directamente `main`?

**Gabriela**

Al hacer esto es que cuando desarrollamos cambios evitamos que en el main se afecte lo que esta ahi con cambios incompletos o que tengan errores.

**Juan David**

La ventaja es que si algo sale mal o no funciona, no daño el codigo main, solo la rama que estaba usando en ese momento.


