# Comandos Git

1. `git init`
Inicializa un nuevo repositorio Git en la carpeta actual (crea la carpeta oculta `.git/`).

2. `git add .`
Añade **todos los archivos modificados o nuevos** al área de *staging* (preparados para el commit).

3. `git reset .`
Quita los archivos del *staging area* (no borra cambios, solo deshace el `git add`).

4. `git commit`
Guarda los cambios en el repositorio con un mensaje de confirmación  
(si no se pasa `-m`, abre el editor para escribir el mensaje).

5. `git checkout -- .`
Descarta todos los cambios locales en los archivos, devolviéndolos al último commit.

6. `git log`
Muestra el historial de commits (autor, fecha, mensaje, hash).

7. `git commit --amend`
Modifica el último commit (mensaje o archivos incluidos).

8. `git checkout -b rama-heroes`
Crea una nueva rama llamada `rama-heroes` y se cambia a ella.

9. `git checkout master`
Cambia a la rama `master` (o `main`, dependiendo del repositorio).

10. `git branch -d rama-heroes`
Elimina la rama `rama-heroes` (solo si ya fue fusionada).

11. `git push`
Envía los commits locales al repositorio remoto (por defecto al `origin` y rama actual).

12. `git commit -am "mensaje"`
Hace `git add` y `git commit` en un solo paso,  
**pero solo para archivos ya versionados** (no incluye archivos nuevos).