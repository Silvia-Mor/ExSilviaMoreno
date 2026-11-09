# Hoja de consulta — Git (validación UP1)

| Comando | Finalidad |
|---|---|
| `git clone URL` | Clonar un repositorio |
| `git status` | Comprobar estado |
| `git log --oneline --graph --all` | Ver historial y ramas |
| `git branch -a` | Listar ramas locales y remotas |
| `git switch NOMBRE` | Cambiar a una rama local |
| `git switch -c NOMBRE --track origin/NOMBRE` | Crear rama local siguiendo una remota |
| `git switch main` | Volver a main |
| `git merge NOMBRE` | Integrar una rama en la actual |
| `git add ARCHIVO` | Preparar cambios |
| `git add .` | Preparar todos los cambios |
| `git commit -m "mensaje"` | Registrar un commit |
| `git remote -v` | Ver remotos |
| `git remote set-url origin URL` | Cambiar la dirección del remoto |
| `git push -u origin main` | Publicar main y configurar seguimiento |
| `git push origin NOMBRE` | Publicar otra rama |
| `git fetch origin` | Actualizar referencias remotas |

**Notas:** `git merge` se ejecuta desde la rama receptora. `git clone` suele crear solo una rama local, aunque las demás aparezcan como remotas. Para publicar en GitHub, usa la URL de tu repositorio propio, no la del docente.
